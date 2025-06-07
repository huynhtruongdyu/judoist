# 🥋 Judoist – A Todoist Clone in Blazor WebAssembly

> ✅ Task management, 100% offline-first. Built with **Blazor WASM**, **Dexie.js**, and **PWA support**.

**Judoist** is a lightweight, open-source task manager inspired by Todoist, designed to work **fully offline** and store all user data securely in the browser using **IndexedDB via Dexie.js**. It's built with **Blazor WebAssembly (WASM)** and supports **PWA (Progressive Web App)** features like offline usage, background sync, and installability.

---

## 🔧 Features

- ✅ **Add/Edit/Delete Tasks**
- ✅ **Mark Tasks as Completed**
- ✅ **Organize Tasks by Project or Category**
- ✅ **Offline Support** – All tasks are stored in the browser
- ✅ **PWA Ready** – Installable on desktop & mobile
- ✅ **Responsive UI** – Works on mobile and desktop
- ✅ **No Backend Required** – Fully client-side architecture

---

## ⚙️ Technical Stack

| Layer | Technology |
|-------|------------|
| **Frontend Framework** | [Blazor WebAssembly](https://dotnet.microsoft.com/apps/aspnet/web-apps/client)  |
| **State Management** | Component state + JS interop |
| **Storage** | [Dexie.js](https://dexie.org/)  (IndexedDB wrapper) |
| **Styling** | Tailwind CSS / Bootstrap / Custom CSS |
| **Offline Support** | PWA + Service Workers |
| **Deployment** | GitHub Pages / Netlify / Any static host |

---

## 📦 How It Works

All user data is stored **locally in the browser** using **IndexedDB**, managed via **Dexie.js**. This allows the app to function without any internet connection and avoids the need for a backend server or external database.

Thanks to **Blazor WebAssembly**, the entire app runs in the browser using C#, giving you a powerful development experience while maintaining the performance of native JavaScript apps.

The app also uses **PWA capabilities**, allowing users to:
- Install it on their home screen
- Use it offline
- Receive fast load times due to caching strategies

---

## 📸 Screenshots

_(You can add screenshots here if desired, e.g., of the task list, project view, etc.)_

---

## 🚀 Live Demo

🔗 [Live Demo on GitHub Pages](https://yourusername.github.io/judoist) 

---

## 🧰 Development Setup

### Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download) 
- IDE: Visual Studio, VS Code, or Rider

### Build and Run Locally

```bash
git clone https://github.com/huynhtruongdyu/judoist.git 
cd judoist
dotnet run