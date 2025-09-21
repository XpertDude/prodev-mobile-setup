Objective:
Set up your first mobile application using the Expo Router template. Document the scaffolding process and understand the file structure of a React Native application using Expo.

Instructions:
Navigate to Your Project Directory

Open your terminal and move to your parent project directory:

cd prodev-mobile-setup

Set Up Your Project

Initialize a new Expo project using the latest Expo Router template:

npx create-expo-app@latest .

Modify the Home Screen

Open app/(tabs)/index.tsx.
Locate the default text Welcome!.
Change it to ** First App Created**.
Run and Test Your Application

Start the Expo development server with:

npx expo start

For iOS Devices: Scan the QR code in the terminal using your phone’s Camera app.
For Android Devices: Scan the QR code using the Expo Go app.
Reset the Application

Run the reset command and observe its effects:

npm run reset-project

Document what happens when you reset the project in your README.md file.

Ensure your README.md includes

Steps you followed for scaffolding.
Observations from thereset-project command.