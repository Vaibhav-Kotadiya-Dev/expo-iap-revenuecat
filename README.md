## 📦 Installation

1. **Clone the repository**

   ```bash
   https://github.com/Vaibhav-Kotadiya-Dev/expo-iap-revenuecat.git
   cd expo-iap-revenuecat
   ```

2. **Install dependencies**

   ```bash
   bun install
   ```

3. **Configure RevenueCat**
   - Create a RevenueCat account at [revenuecat.com](https://www.revenuecat.com)
   - Set up your iOS and Android apps in the RevenueCat dashboard
   - Update the API keys in `app/_layout.tsx`:
     ```typescript
     const REVENUE_CAT_IOS_KEY = "your-ios-key";
     const REVENUE_CAT_ANDROID_KEY = "your-android-key";
     ```

## 🚀 Development

### Run on iOS Simulator

```bash
bun run ios
```

### Run on Android Emulator

```bash
bun run android
```

### Start Expo Development Server

```bash
bun start
```

## 📱 Building for Production

This project is configured with [EAS Build](https://docs.expo.dev/build/introduction/) for creating production builds.

### Build for iOS

```bash
eas build --platform ios
```

### Build for Android

```bash
eas build --platform android
```


## 📚 Resources

- [Expo Documentation](https://docs.expo.dev/)
- [RevenueCat Documentation](https://docs.revenuecat.com/)
- [React Native Documentation](https://reactnative.dev/docs/getting-started)
- [Bun Documentation](https://bun.sh/docs)
