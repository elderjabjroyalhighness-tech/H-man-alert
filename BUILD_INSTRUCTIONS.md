# Human Alert - Complete Frontend Project

## This is the COMPLETE Expo/React Native frontend for Human Alert app.

### 📁 Project Structure
```
human-alert-frontend/
├── app/                    # Screens & Navigation
│   ├── (tabs)/            # Tab screens
│   │   ├── index.tsx      # Emergency button screen
│   │   ├── map.tsx        # Map view screen
│   │   └── alerts.tsx     # Alerts list screen
│   ├── alert-view.tsx     # Alert detail/responder view
│   └── _layout.tsx        # Root layout
├── src/
│   ├── components/        # UI components
│   ├── hooks/             # Custom hooks (location, notifications)
│   ├── services/          # API, socket, sound services
│   └── store/             # State management
├── assets/                # Images & fonts
├── app.json              # ✅ Expo configuration
├── package.json          # ✅ Dependencies
├── eas.json              # ✅ APK build configuration
└── tsconfig.json         # TypeScript config
```

### 🚀 Build APK Steps

1. **Upload to GitHub**
   - Create new repository
   - Upload ALL these files (keep folder structure)

2. **Create Expo Account**
   - Go to https://expo.dev/signup

3. **Connect & Build**
   - Go to expo.dev → Create project
   - Connect your GitHub repository
   - Go to Builds → Create Build
   - Select: Android → APK
   - Wait ~15 minutes
   - Download your APK!

### ⚙️ Key Configuration Files

**app.json** - App name, permissions, icons
**eas.json** - Configured for APK output (not AAB)
**package.json** - All dependencies listed

### 🔗 Backend URL
The app connects to: https://safe-radius.preview.emergentagent.com

### 📱 Features Included
- Emergency alert button
- Live map with directions
- Push notifications with sound
- Responder tracking
- 20-minute auto-end timer
- Smart radius (300m→600m→1km)
