# 1. Clone or navigate to your repo
git clone https://github.com/YOUR_USERNAME/prodev-mobile-setup.git
cd prodev-mobile-setup

# 2. Create the task directory
mkdir prodev-mobile-app-0x00
cd prodev-mobile-app-0x00

# 3. Create the app-example directory
mkdir app-example
cd app-example

# 4. Initialize Expo project
npx create-expo-app@latest .

# 5. Test your app
npx expo start

# 6. Make your code changes in app/(tabs)/index.tsx
# Change "Welcome!" to "First App Created"

# 7. Reset the project
npm run reset-project

# 8. Go back to create README
cd ..  # Back to prodev-mobile-app-0x00
touch README.md

# 9. Edit README.md with your documentation

# 10. Commit everything
git add .
git commit -m "Complete Task 1: First Mobile App"
git push origin main
```

---

## ✅ Files to Submit

The grading system will look for these **specific files** in your repo:

1. **`prodev-mobile-setup/prodev-mobile-app-0x00/README.md`**
   - Your documentation

2. **`prodev-mobile-setup/prodev-mobile-app-0x00/app-example/app/(tabs)/index.tsx`**
   - Modified home screen with "First App Created"

3. **`prodev-mobile-setup/prodev-mobile-app-0x00/app-example/constants/Colors.tsx`**
   - Color constants (automatically created by Expo)

4. **`prodev-mobile-setup/prodev-mobile-app-0x00/app-example/`**
   - The entire app directory with all Expo files

---

## 💡 Why This Structure?

- **`prodev-mobile-setup`** = Your main repository for all mobile tasks
- **`prodev-mobile-app-0x00`** = Directory for THIS specific task (Task 0x00)
- **`app-example`** = Your actual Expo application code
- **`README.md`** = Documentation at the task level (not inside app-example)

This structure allows you to have **multiple tasks** in the same repository:
```
prodev-mobile-setup/
├── prodev-mobile-app-0x00/    # Task 1
├── prodev-mobile-app-0x01/    # Task 2 (future)
└── prodev-mobile-app-0x02/    # Task 3 (future)
```

---

## 🚨 Common Mistakes to Avoid

❌ **Don't do this:**
```
prodev-mobile-setup/
└── app-example/               # Wrong! Missing task directory
    └── README.md
```

❌ **Don't do this:**
```
prodev-mobile-setup/
└── README.md                  # Wrong! README in wrong location
└── app-example/
```

✅ **Correct structure:**
```
prodev-mobile-setup/
└── prodev-mobile-app-0x00/
    ├── README.md
    └── app-example/