
# TurboModules React Native Example

A basic example of integrating **Kotlin Native Modules** into a **React Native** app using **TurboModules + Codegen**.

This setup demonstrates how to create fast, type-safe native modules in Kotlin with modern React Native architecture.

---

## 🚀 Features

- TurboModules integration (JSI-based, no old JS bridge)
- Kotlin Native Module with `@ReactModule` and `@ReactMethod`
- Auto-generated TypeScript bindings via `react-native-codegen`
- Clean Gradle + Android setup

---

## 🛠️ Tech Stack

- React Native (New Architecture)
- Kotlin (for Android native code)
- TurboModules + Codegen
- TypeScript

---

## 📦 Setup

```bash
# Clone the repo
git clone git@github.com:Abhisheklearn12/turbomodules-reactnative.git

# Navigate to the project
cd turbomodules-reactnative

# Install JS dependencies
yarn install

# Generate native bindings
yarn codegen

# Run on Android
npx react-native run-android
