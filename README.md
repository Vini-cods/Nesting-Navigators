# 📱 Nesting Navigators

[![React Native](https://img.shields.io/badge/React_Native-2025-blueviolet?logo=react)](https://reactnative.dev/)
[![Expo](https://img.shields.io/badge/Expo-49.0.6-000000?logo=expo)](https://expo.dev/)
[![Navigation](https://img.shields.io/badge/@react--navigation%2Fstack-v6.x-blue?logo=reactrouter)](https://reactnavigation.org/)

> A practical guide to implementing **nested navigation** using React Native and React Navigation.

---

## 📌 About

This project demonstrates how to structure an app using **nested navigators** with React Navigation. It integrates both `Stack Navigator` and `Bottom Tab Navigator` to create an organized flow between screens — perfect for apps with internal menus or section-based layouts.

---

## 🚀 Features

- Stack and Bottom Tab navigators  
- Styled and customized tab bar  
- Internal navigation with icons and badges  
- Data sharing between screens using state and props  
- Clean and modular file structure  

---

## ⚙️ Installation
Create the project:

npx create-expo-app nesting -t
Install dependencies:

npx expo install react-native-web react-dom @expo/metro-runtime expo-status-bar react-native-gesture-handler

npm install @react-navigation/stack @react-navigation/native @react-navigation/bottom-tabs react-native-screens react-native-safe-area-context

---

## 🎨 Customization

- Icons provided by [Ionicons](https://icons.expo.fyi/Index)  
- Styled tab bar with `tabBarStyle`, `tabBarIcon`, and `tabBarBadge`  
- Visual feedback with input shadows and elevated elements  

---

## 🔄 Navigation Flow

- The **Stack Navigator** handles primary navigation (`index`, `rotaInterna`)  
- The **Bottom Tab Navigator** handles nested screens (`tela1`, `tela2`, `tela3`)  
- Data from `tela1` is passed to `tela3` via shared state in `rotaInterna.js`  

---

## 📚 Documentation

- [React Navigation Docs](https://reactnavigation.org/docs/getting-started)  
- [Expo Docs](https://docs.ex
- [Ionicons Gallery](https://icons.expo.fyi/Index)  
