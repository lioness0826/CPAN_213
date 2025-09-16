# Environment Setup Documentation

## 1. System Specifications
- **Operating System**: Windows 11 (64-bit)
- **Processor**: Intel(R) Core(TM) Ultra 7 155H (3.80 GHz)
- **Memory (RAM)**: 32 GB
- **Storage**: 1TB SSD
- **Graphics**: Intel(R) Arc(TM) Graphics

## 2. Software Versions Installed
- **Node.js**: v20.17.0
- **npm**: 11.0.0
- **React Native CLI**: 0.81.4
- **Android Studio**: Android Studio Narwhal 3 Feature Drop | 2025.1.
- **Java JDK**: 23.0.1
- **VS Code**: 1.104.0

## 3. Setup Steps Followed
1. Installed Node.js from the official website.  Verified installation with `node -v` and `npm -v`.  
2. Installed React Native CLI using "npm install -g react-native-cli" and "npm install -g @react-native-community/cli" 
3. Installed Android Studio and configured SDK & Emulator.  
4. Set up environment variables using "setx ANDROID_HOME "%LOCALAPPDATA%\Android\Sdk"" and "setx PATH "%PATH%;%LOCALAPPDATA%\Android\Sdk\platform-tools""
5. Create Android Virtual Device.
6. Install vscode and extensions.
7. Environment verifications: run "npx @react-native-community/cli@latest init EnvironmentTest", "cd EnvironmentTest", "npx react-native run-android"
8. Make changes in app.tsx and see results.

## 4. Deviations from Lab Instructions
- Used "npx @react-native-community/cli@latest init EnvironmentTest" instead of npx react-native init EnvironmentTest to verify environment.
- Open android studio when run "npx react-native run-android"
  
## 5. Time Taken
- Installing Node.js and npm: 20 minutes  
- Setting up React Native project: 30 minutes  
- Installing Android Studio & SDK: 20 minutes  
- Configuring environment variables: 1 hour 
- Running first app on emulator: 1 hour  

**Total Time**: 3 hour 10 minutes

