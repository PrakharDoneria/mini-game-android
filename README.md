
# Mini Game - Android Project

This project was exported from Karbon Sites and is ready to be built as an Android application using Capacitor.

## Prerequisites

1.  **Node.js and npm**: Make sure you have Node.js (which includes npm) installed.
2.  **Java Development Kit (JDK)**: You'll need a recent version of the JDK (e.g., OpenJDK 17).
3.  **Android Studio**: Download and install the latest version of Android Studio. Make sure to set up the Android SDK.
4.  **GitHub Account**: You need a GitHub account to host your code and run the build workflow.

## Local Build Steps

1.  **Unzip the Project**: Unzip this file into a new folder.
2.  **Open a Terminal**: Navigate into the unzipped folder.
3.  **Install Dependencies**: Run `npm install`.
4.  **Add Android Platform**: Run `npx cap add android`.
5.  **Open in Android Studio**: Run `npx cap open android`.
6.  **Build**: In Android Studio, go to **Build** > **Build Bundle(s) / APK(s)** > **Build APK(s)**.

## Cloud Build with GitHub Actions (Recommended)

This project includes a GitHub workflow to automatically build and release your app.

1.  **Create a GitHub Repository**: Create a new, empty repository on your GitHub account. Do NOT initialize it with a README.
2.  **Push Your Code**: In your terminal, inside the unzipped project folder, run the following commands:
    ```bash
    git init
    git add .
    git commit -m "Initial commit"
    git branch -M main
    git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git
    git push -u origin main
    ```
    (Replace `YOUR_USERNAME` and `YOUR_REPOSITORY_NAME` with your actual GitHub details).
3.  **Check Releases**: Once you push, the workflow will automatically start. Go to the "Releases" section of your GitHub repository to find your downloadable APK and AAB files.
    