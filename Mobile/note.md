# Big > [!NOTE]
> to init in react native the command is:
  "npx @react-native-community/cli init fileName"

> to run in android, the command is:
  "npm run android"

> MASALAHH HYPRLAND LAGI SYBAALLL
  Ijin sehari dulu hiks

> to init in react native using latest version:
   "npx @react-native-community@latest init fileName" 

### fyi dari sini untuk bisa akses lewat web (tanpa harus pake hp)

> to make webview in react native use:
   "npm install react react-dom@19.2.0 --legacy-peer-deps"

> intall web runtime 
   "npm install react-native-web --legacy-peer-deps"

> install expo 
   "npm install expo"

> run using this command:
   "npx expo start --web" and then the link will be opened

> in the file "App.tsx", change the import 
 from:
  import { NewAppScreen } from '@react-native/new-app-screen';
  import { StatusBar, StyleSheet, useColorScheme, View } from 'react-native';
  import {
    SafeAreaProvider,
    useSafeAreaInsets,
   } from 'react-native-safe-area-context';

 to:
  import React from 'react';
  import { Text, View, StyleSheet } from 'react-native';


> in the root folder, add a file with name "index.web.js" and fill it with:
`
  import { registerRootComponent } from 'expo';
  import App from './App';

  registerRootComponent(App);
`
and then you must to restart 'npx expo start --web'

