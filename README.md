# practise-redux-tookit

# 📱 UserManagementApp

UserManagementApp is a React Native application that provides user authentication and basic user management features such as Login, Register, Profile, and Settings screens.

The app uses **Redux Toolkit**, **Redux Persist**, and **React Navigation** with token-based authentication logic.

---

## 🚀 Project Structure

```
UserManagementApp/
│
├── android/                  
├── ios/                      
├── src/
│   ├── assets/               
│   ├── components/           
│   ├── navigation/           
│   ├── redux/       
│   ├── screens/              
│   ├── types/                
│   └── utils/                
├── App.tsx                   
├── package.json              
└── README.md                 
```

---

## 📋 Prerequisites

- Node.js (>= 18)
- npm or yarn
- React Native CLI or Expo CLI
- Android Studio
- Xcode (macOS only)

Check versions:

```bash
node -v
npm -v
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/UserManagementApp.git
cd UserManagementApp
```

### 2️⃣ Install Dependencies

Using npm:

```bash
npm install
```

OR using yarn:

```bash
yarn install
```

---

### 3️⃣ Run Application

#### ▶️ Android

```bash
npx react-native run-android
```

#### ▶️ iOS

```bash
npx react-native run-ios
```

#### ▶️ Expo

```bash
npx expo start
```

---

## 🔐 Demo Credentials

```
Username: testuser
Email: test@example.com
Password: 123456
```

---

## 🔑 Authentication Flow

- App checks for stored token on splash screen.
- If token exists → Redirects to Home.
- If token does not exist → Redirects to Login.
- Token is stored using Redux Persist.

---

## 🧪 Running Tests

```bash
npm test
```

or

```bash
yarn test
```

---

## 📦 Built With

- React Native
- TypeScript
- Redux Toolkit
- Redux Persist
- React Navigation

---

## 📌 Features

- ✔️ User Login 
- ✔️ Token-based Authentication  
- ✔️ Redux State Management  
- ✔️ Persistent Login  
- ✔️ Profile Screen  (image picker )
   

---

## 👨‍💻 Author

**Darshan Chudsama**  
React Native Developer
