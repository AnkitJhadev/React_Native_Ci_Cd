# 🚀 React Native CI/CD Starter

A production-ready React Native project demonstrating how to set up **CI/CD pipelines for mobile apps**.

This repository is focused on automating:

* 🛠️ Build processes
* 🧪 Testing workflows
* 🚀 Deployment pipelines

---

## 📱 What This Project Covers

This project is not just a basic app — it demonstrates **real-world CI/CD practices** for React Native:

* ✅ Automated builds (Android & iOS)
* ✅ Code quality checks (ESLint, Prettier)
* ✅ CI pipelines (GitHub Actions)
* ✅ OTA updates (optional)
* ✅ Scalable project structure

---

## ⚙️ CI/CD Workflow Overview

### 🔁 Continuous Integration (CI)

* Runs on every push / pull request
* Linting & formatting checks
* Build validation
* (Optional) Unit tests

### 🚀 Continuous Deployment (CD)

* Auto build APK / IPA
* Deploy to:

  * Firebase App Distribution / TestFlight
  * Play Store (optional)

---

## 🛠️ Tech Stack

* React Native
* TypeScript
* GitHub Actions
* Fastlane (optional)
* Node.js

---

## 📂 Project Structure

```id="rnci02"
/src
  /components
  /screens
  /services
  /utils

/.github/workflows
  ci.yml        → CI pipeline
  cd.yml        → Deployment pipeline
```

---

## ⚡ Getting Started

### 1️⃣ Install Dependencies

```bash id="rnci03"
npm install
```

---

### 2️⃣ Start Metro

```bash id="rnci04"
npm start
```

---

### 3️⃣ Run App

```bash id="rnci05"
npm run android
# or
npm run ios
```

---

## 🔄 CI/CD Setup

### GitHub Actions

This project uses **GitHub Actions** for automation.

### Example Workflow

```yaml id="rnci06"
name: CI

on:
  push:
    branches: [main]

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - uses: actions/checkout@v3
      - name: Install dependencies
        run: npm install
      - name: Run lint
        run: npm run lint
```

---

## 🧪 What You’ll Learn

* How to automate React Native builds
* How to structure CI/CD pipelines
* How to prepare apps for production deployment
* How to integrate testing and linting

---

## 🔮 Roadmap

* [ ] Add Fastlane automation
* [ ] Add E2E testing (Detox)
* [ ] Add caching for faster builds
* [ ] Add environment-based configs

---

## 👨‍💻 Author

**Ankit Jha**

* React Native Developer
* Focused on scalable mobile apps & CI/CD

---

## ⭐ Support

If this helped you understand CI/CD in React Native, give it a ⭐

---

## 🔍 Keywords

react native ci cd, github actions react native, mobile app deployment, fastlane react native, automated builds mobile
