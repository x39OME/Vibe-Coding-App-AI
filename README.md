# Vibe Coding App AI

## What did we use in the project?
### 1- [Expo SDK 55](https://docs.expo.dev/get-started/create-a-project/)
### 2- [Claude Code](https://claude.com/product/claude-code)
### 3- [Expo/skills](https://github.com/expo/skills)
### 4 [Dev Expo skills](https://expo.dev/expo-skills)


## Getting Started Expo Applaction

- Create New Expo Applaction
```
npx create-expo-app@latest --template default@sdk-56
```
- install claude code
- Windows
```
- Administrator power shell
irm https://claude.ai/install.ps1 | iex
```
- Mac / Linux
```
curl -fsSL https://claude.ai/install.sh | bash
```

- npx expo start
- npm run android
- npm run ios
- claude Opus 4.7
- gemini-2.5-flash

  
## Claude Code
### Expo Skills/Plugins

- Add the marketplace:
```
/plugin marketplace add expo/skills
```

- Install the plugin:
```
/plugin install expo
 ```

### Claude Code & Claude App Desktop:

1. Claude الأمر الأول: تثبيت أداة المطورين (Claude Code) عبر Node.js
```
npm install -g @anthropic-ai/claude-code
```
```
- ماذا يثبت؟ يقوم بتثبيت أداة اسمها Claude Code. وهي أداة مخصصة للمبرمجين والمطورين تعمل داخل شاشة الأوامر (Terminal/Console). تتيح للذكاء الاصطناعي الدخول لملفات مشروعك البرمجي، التعديل على الكود، فحص الأخطاء، وتشغيل الاختبارات مباشرة
- المتطلبات: لن يعمل هذا الأمر إطلاقاُ إلا إذا كنت قد قمت بتثبيت بيئة Node.js مسبقاً على جهازك، لأن الأمر يستخدم مدير الحزم npm التابع لها.
- الرمز -g: يعني تثبيت الأداة بشكل عالمي (Global) على جهازك لتستطيع استدعاءها من أي مجلد برمجيات.
```
2. Claude App الأمر الثاني: تثبيت تطبيق كلود العادي للويندوز (Claude Desktop App)
```
irm https://claude.ai/install.ps1 | iex
```
```
- ماذا يثبت؟ يقوم بتثبيت تطبيق Claude الرسمي لواجهات الويندوز (Claude Desktop). وهو البرنامج العادي الذي تفتحه لتجده واجهة رسومية جميلة (مثل شكل الموقع) لتتحدث مع كلود، ترفع له ملفات، وتسأله بشكل طبيعي.
- المتطلبات: لا يتطلب أي برامج مسبقة مثل Node.js، هو فقط سكربت مخصص لنظام ويندوز (PowerShell) يقوم بتحميل ملف التثبيت المباشر للبرنامج وتشغيله فوراً.
```

## Prerequisites

- [Node.js](https://nodejs.org/en) (LTS recommended)
- [Expo CLI](https://docs.expo.dev/get-started/set-up-your-environment/)
- iOS Simulator (macOS) or Android Emulator, or a physical device with [Expo Go](https://expo.dev/go)


### Prompt
```
1 > Set up three tabs for the app:
        * Home
        * Favorites
        * Settings  On the home screen, I want:
        * a text input where I can type what I want to cook
        * filter chips underneath for things like vegan, keto, gluten-free, dairy-free, and so on
        * below that, add a big green "Generate Recipe" button
        * two smaller buttons side by side
        * one of them will say "Surprise Me"
        * the "Scan Ingredients" button  Set up the types storage we will need for saving recipes and preferences later.

 2 > Hook up the Gemini API so I can actually generate recipes when I type something like "butter chicken" and tap "generate".
            It should call Gemini, get back the full recipe, and take me to the detailed screen showing:

           * the title
           * a description
           * all the ingredients with amounts
           * a step-by-step instruction in a nice timeline layout
           * stats like prep time, cook time, servings, and calories  It should do the same thing but with a random recipe idea.

3 > Add AI image generation for the recipe. When I open a recipe that doesn't have a photo yet, it should automatically generate one in the background using Gemini and show it as a big image on the top of the recipe screen. While it's generating, show a loading spinner, and when the image is ready, fade it in smoothly. Save the image so that it also shows up on the recipe cards elsewhere in the application.

4> Add the ability to save recipes as favorites and share them.

    Make the hot button in the recipe details page functional so that I can tap it and save or unsave the recipe.

    Add a share button that sends the recipe as a nice formatted text.

    Generate and add a regenerate button to get the different version of the same recipe.

    Build out the favorites tab with cards showing the image, title, cuisine, and the cook time.

    Long press on the card should be able to delete that favorite recipe.

    Add a recent section in the home screen with the horizontal scrollable list of my last few generated recipes.

5 > Add a camera screen where I can take a photo of my ingredients and the AI figures what's in the picture. Show the        
  identified ingredients as little chips that I can tap and remove if they are wrong. Then let me generate a recipe from   
  whatever is left. Put a gallery button next to the shutter button so I can also pick a photo from my camera roll instead 
   of taking a new one. It should go through this thing. I'm going to use the same scanning flow when generating the       
  recipe and make sure it uses my dietary preferences and allergies from settings.
  Also
* Change the home icon to a fork and knife.                                                                                
                                                                                                                           
* When I generate a recipe, the images don't appear. Why? Please investigate the cause of the problem and let me know what 
   it is and how to fix it.                                                                                                
                                                                                                                           
                                                                                                                           
6> So when I click on the Generate Recipe button after getting all the ingredients from an image, it says "Expected double quote property name in JSON at position 437", and it shows an alert with this error. Can you find and fix this issue for me?
                                                                                                                           





7> Build these settings screens:

    I want a section for dietary defaults, like vegan keto, that automatically applies to every recipe I generate.

    Add a servings picker so I can set how many servings I usually want.

    Add an allergy section where I can type things like peanuts shellfish, and they will always be excluded from the recipes I put.

    I put a clear all button at the bottom to wipe the saved data as well.

    Then go through the whole application and add smooth animations when things appear on the screen and haptic feedbacks when I tap buttons or any toggles.










Okay, now I want to improve the app's appearance! Open the app completely and search for anything missing. Add it if needed, and if it requires an additional feature, add it. Also, improve the app's appearance to make it look professional. Add dark mode and add Arabic language support in the settings.

And don't forget to enable data saving if you restart the app in recent updates.  
```

# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

### Other setup steps

- To set up ESLint for linting, run `npx expo lint`, or follow our guide on ["Using ESLint and Prettier"](https://docs.expo.dev/guides/using-eslint/)
- If you'd like to set up unit testing, follow our guide on ["Unit Testing with Jest"](https://docs.expo.dev/develop/unit-testing/)
- Learn more about the TypeScript setup in this template in our guide on ["Using TypeScript"](https://docs.expo.dev/guides/typescript/)

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
