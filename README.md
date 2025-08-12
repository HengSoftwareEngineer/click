# 🖱️ Click.exe - Click

📢 Click is a simple tool desktop app to quickly scaffold popular frontend projects like **Next.js**, **React + Vite**, and **Vue + Vite**, with options for **TypeScript**, **ESLint**, **Tailwind CSS**, and more.

---

## 🚨 If Not Found

> Before running Click.exe, if you haven’t installed or configured the following tools on your system, don’t worry — Click.exe can automatically install and set them up for you.
  However, if you prefer to install them manually, please follow the instructions above.

- **[Node.js](https://nodejs.org/)** and **`npm`** — must be accessible from your system PATH.
   
   *To check versions, run:* 
   `node --version`
   `npm --version`
> Currently supports only **`npm`**. More package managers will be added in the future.


- **[Flutter SDK](https://docs.flutter.dev/get-started/install)** — must be installed and added to your system PATH. 
   ➡ *Example Flutter SDK PATH: `C:\src\flutter\bin`*
  
   *To check versions, run:* 
   `flutter --version`

---

## 🔥 Requirements

- **[Visual Studio Code](https://code.visualstudio.com/)** — added to PATH with the `code` command available.
   *To check versions, run:*
   `code --version`
  ⚠️ Missing or misconfigured tools may cause errors during usage.


> If any of the above are missing or incorrectly set up, you may encounter errors during use.

---

### ⬇⬇⬇ Steps to Install

1. **Locate the `setup` folder** in this project.  
2. **Run `clicksetup-2.0.0.exe`** to install the application.  
3. If Windows Defender or another antivirus flags the file:  
   - This is a **false positive** caused by the app not being code-signed or registered with Microsoft.  
   - It is safe to proceed — simply choose **"More info" → "Run anyway"**.  
   - You can also verify the installer’s source files in the [`\setup\ui`](./setup/ui) folder before proceeding.


---

## 📦 Features

- Create **Next.js** projects with options for TypeScript, ESLint, Tailwind CSS, and App Router.
- Create **React + Vite** or **Vue + Vite** projects with TypeScript support.
- Create **Flutter App** projects. 🔥
- Automatically runs `npm install` and installs `tailwindcss @tailwindcss/vite` for Vite projects. 🔥
- Automatically configures `vite.config.ts` or `vite.config.js`. 🔥
- Automatically imports `@import "tailwindcss";` in CSS files for both React and Vue. 🔥
- Automatically installs **Node.js** if not found. 🔥
- Automatically installs **Flutter SDK** if not found. 🔥
- Opens the created project in **Visual Studio Code**.
- User-friendly GUI with progress logs and real-time feedback.

---

## 🌈 How to Use

1. **Set Project Name**  
   Enter your desired project name (e.g., `my_first_app`).

2. **Select Target Directory**  
   Choose where you want the project folder to be created.

3. **Select Framework / Template**  
   - Next.js  
   - React + Vite  
   - Vue + Vite  
   - Flutter 🔥

4. **Configure Options**  
   - **Next.js:** Toggle TypeScript, ESLint, Tailwind CSS, use `/src` directory, and enable App Router.  
   - **React + Vite / Vue + Vite:** Option to enable TypeScript.

5. **Create Project**  
   Click the **Create Project** button. The tool will scaffold your project, install dependencies, and open it in Visual Studio Code.

6. **Monitor Progress**  
   View real-time logs and progress updates in the log window.

---

## ⚡ Troubleshooting

- If the project folder already exists, you will be prompted to choose another name.
- Ensure `npx`, `npm`, and `code` commands are accessible.
- Check the log for any errors during project creation.
> **Important:** When creating a Flutter project, use underscores (_) in the project name (e.g., my_first_app) instead of spaces or hyphens.

---

## 📄 License

See the [LICENSE.md](LICENSE.md) file for details.

---

**Created by:** Mai Bunheng | [maibunheng.site](https://www.maibunheng.site)
