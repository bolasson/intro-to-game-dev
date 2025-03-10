# Getting Started with Game Development

Welcome! This guide will help you set up the necessary tools for game development using Unity. By the end of these instructions, you’ll have Unity Hub, the latest LTS version of the Unity Editor, and Visual Studio Code installed on your system.

_Note: If you'd like a more in depth explanation of how to install the Unity Hub and Editor, check out Unity's own tutorial [here](https://learn.unity.com/pathway/unity-essentials/unit/editor-essentials/tutorial/unity-essentials-install-unity?version=6)._

---

## 1. Installing Unity Hub

**What is Unity Hub?**  
Unity Hub is a central management tool that allows you to install and manage different versions of the Unity Editor, organize your projects, and access various Unity services all in one place.

### Download & Install Instructions

- **Windows:**  
  Download the installer from [Unity Hub for Windows](https://public-cdn.cloud.unity3d.com/hub/prod/UnityHubSetup.exe). Once downloaded, run the installer and follow the on-screen instructions.

- **macOS:**  
  Download the DMG file from [Unity Hub for Mac](https://public-cdn.cloud.unity3d.com/hub/prod/UnityHubSetup.dmg). Open the DMG and drag the Unity Hub icon into your Applications folder.

- **Linux:**  
  Follow the official Unity documentation for installing Unity Hub on Linux:  
  [Install Unity Hub on Linux](https://docs.unity3d.com/hub/manual/InstallHub.html#install-hub-linux).


### Create a Unity ID and Sign In
After downloading the Unity Hub, it'll prompt you to sign in or create an account. You'll likely need to create a new account, and when prompted, select the personal plan ($0).

---

## 2. Installing the Unity Editor (Latest LTS Version)

**What is the Unity Editor?**  
The Unity Editor is the application used for creating your games. The Long-Term Support (LTS) version is recommended for beginners due to its stability and extended support.

### How to Install:

1. **Open Unity Hub:**  
   After installing Unity Hub, launch it from your system.

2. **Go to the Installs Tab:**  
   Click on the **Installs** tab in Unity Hub.

3. **Add a New Version:**  
   Click the **Install Editor** button. You’ll see a list of available Unity versions. Look for the latest LTS (Long-Term Support) release, which is usually marked with "Recommended version".
   You will be provided with a lot of modules you can download. For our projects, you will need to:
   -  Add the module associated with your Operating System (OS) under PLATFORMS.
       - **Windows:**
         Universal Windows Platform Build Support
       - **macOS:**
         Mac Build Support (Mono)
       - **Linux:**
         Linux Build Support (Mono)
   - Remove the module Microsoft Visual Studio Community 2022 under DEV TOOLS.
   Click **Install**.
   Move on to the next section while you wait for the download to finish.

---

## 3. Installing Visual Studio Code

**What is Visual Studio Code?**  
Visual Studio Code (VS Code) is an integrated development environment (IDE) developed by Microsoft. It’s a great tool for writing and debugging your C# code as you develop your games.

### Download & Install Instructions

Visit the [Visual Studio Code Download page](https://code.visualstudio.com/Download) and click the download link for your OS. Run the installer and follow the installation steps.

### After Installation

1. **Launch VS Code:**  
   Open Visual Studio Code once the installation is complete.

2. **Install the Required Extensions:**  
   Open the Extensions sidebar (Ctrl+Shift+X or Cmd+Shift+X) and install the **C#**, **C# Dev Kit**, and **Unity** extensions by Microsoft.

---

## Next Steps

Now that you have all the necessary tools installed, you can start the tutorials in this repo, or anywhere else!
