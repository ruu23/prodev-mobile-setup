# 📱 Task 1: Create Your First Mobile App

A comprehensive guide to scaffolding, configuring, and testing your first Expo mobile application.

---

## 🚀 Scaffolding the Project

### Step 1: Navigate to Project Directory

```bash
cd prodev-mobile-setup
```

### Step 2: Initialize the Expo Project

Created a new Expo project using the latest Expo Router template:

```bash
npx create-expo-app@latest .
```

**Project Configuration:**
- Expo framework
- Expo Router
- TypeScript support
- Default folder structure for routing and tabs

---

## ✏️ Modifying the Home Screen

**File Location:** `app/(tabs)/index.tsx`

**Changes Made:**
- Located the default text: `Welcome!`
- Replaced with: `First App Created`

---

## 🧪 Running and Testing the Application

### Starting the Development Server

```bash
npx expo start
```

### Testing on Physical Devices

**Android Devices:**
- Scan the QR code using the **Expo Go** app

**iOS Devices:**
- Scan the QR code using the **Camera** app

**Result:** ✅ Application ran successfully and displayed the updated text: *First App Created*

---

## 🔄 Resetting the Project

### Command

```bash
npm run reset-project
```

### Observations

The reset process successfully:
- Removed example and demo files from the Expo template
- Reset the project to a clean baseline state
- Preserved core project files and structure

This step prepares the project for fresh development without leftover template content.

---

## ✨ Conclusion

Task 1 was completed successfully. The Expo project was scaffolded, the home screen was modified, the application was tested on a physical device, and the reset process was executed and documented as required.

---

**Next Steps:** Ready to build your next feature! 🎉