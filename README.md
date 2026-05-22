# Vibe Coding App AI

## What did we use in the project?
### 1- [Expo SDK 56](https://docs.expo.dev/get-started/create-a-project/)
### 2- [Claude App Desktop](https://claude.com/product/claude-code)
### 3- [Claude Code](https://code.claude.com/docs/en/agent-sdk/migration-guide) Sonnet 4.6
### 4- [Expo/skills](https://github.com/expo/skills)
### 5- [Dev Expo skills](https://expo.dev/expo-skills)

## Preview Final Project

-
-

<img src="./preview/" alt="app" />


## Getting Started Expo Applaction

### Create New Expo App
```
npx create-expo-app@latest --template default@sdk-56
```
### install claude code
```
npm install -g @anthropic-ai/claude-code
```
### install claude code App Desktop
  - Windows
  - Administrator power shell
```
irm https://claude.ai/install.ps1 | iex
```
  - Mac / Linux
```
curl -fsSL https://claude.ai/install.sh | bash
```

### Commands
- npx create-expo-app@latest --template default@sdk-56
- npm install -g @anthropic-ai/claude-code
- npx expo start
- claude
- /model Sonnet 4.6

  
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
