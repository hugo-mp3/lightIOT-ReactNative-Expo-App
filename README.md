Light Automation IoT App
A React Native mobile application designed for IoT light automation. This app allows users to control and monitor their lights remotely with a very simplistic interface.
This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

Features
🏡 Control IoT-enabled lights remotely.
📡 Real-time status updates from IoT devices.
📱 Cross-platform support (iOS and Android).
⚡ Built with Expo for rapid development and deployment.

Technologies Used
React Native: For creating a robust and responsive mobile interface.
Expo: To streamline development and provide easy access for collaborators.
ESP32: For IoT hardware communication (replace if your IoT device differs).

Setup and Installation
1. Prerequisites
Ensure you have the following installed on your machine:
Expo CLI (npm install -g expo-cli)
A mobile device with the Expo Go App.
2. Clone the Repository
git clone https://github.com/hugo-mp3/lightIOT-ReactNative-Expo-App.git
cd light-automation-iot-app
3. Install Dependencies
npm install
4. Configure Environment Variables
Create a .env file in the root directory and add the necessary variables (e.g., IoT device IP, API keys):
EXPO_PUBLIC_ESP32_IP=192.168.1.10
5. Start the Development Server
Run the app locally:
npx expo start
Scan the QR code using the Expo Go app on your mobile device to preview the app.
Publishing the App
Using Expo
Log in to Expo:
npx expo login
Publish the app:
eas update
The app will be available at the following URL:
https://expo.dev/accounts/yourusername/projects/light-automation-iot-app/updates
