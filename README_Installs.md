SETUP

1. npx create-expo-app@latest ./
2. Rename app.json 'scheme' to 'restate'
3. npm run reset-project
4. Remove 'app-example' folder
5. Run 'npx expo install nativewind tailwindcss react-native-reanimated react-native-safe-area-context'
6. Run 'npx pod-install'
7. Run 'npx tailwindcss init'
8. Modify the tailwind.config.js file
9. Create 'global.css' in the app folder and modify it
10. Create 'babel.config.js' in the root and modify it
11. Run 'npx expo customize metro.config.js' and modify it
12. Create 'nativewind-env.d.ts' in the root and modify it
13. Update tailwind.config.js and metro.config.js so CSS is imported correctly

STYLES

1. Add all the assets and constants
2. Update app.json
3. Update \_layout.tsx in app
4. Update tailwind.config.js
5. Create 'image.d.ts' in the root and modify it
