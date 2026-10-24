<div align="center">

# 👋 Vue Hello World

**A Vue 3 playground with the Composition API, Pinia and Axios**

![Vue.js](https://img.shields.io/badge/Vue-3-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![Pinia](https://img.shields.io/badge/Pinia-FFD859?style=for-the-badge&logo=pinia&logoColor=black)
![Cypress](https://img.shields.io/badge/Cypress-17202C?style=for-the-badge&logo=cypress&logoColor=white)

[📂 Source](src) · [🧩 Components](src/components) · [🗃️ Store](src/stores)

</div>

---

## 📖 Overview

A small **Vue 3** app for practicing the framework's core ideas. It manages a list of students fetched from an API, shares state through a **Pinia** store, and draws an animated bubble counter. It also includes **Cypress** for end-to-end tests and **SonarQube** settings for code quality checks.

## 🔄 How It Works

| Step | What happens |
|:---:|---|
| 1️⃣ | When the app mounts, it fetches users from JSONPlaceholder with **Axios** |
| 2️⃣ | Students can be added or removed, and a `computed` property keeps the count up to date |
| 3️⃣ | A `watch` and lifecycle hooks log what the component is doing |
| 4️⃣ | Clicking the button increments the Pinia counter, and `AnimatedCounter` adds a colored bubble |

## ✨ Highlights

| ⚛️ Reactivity | 🗃️ State & Data | 🧪 Tooling |
|---|---|---|
| `ref`, `reactive`, `computed`<br>`watch` and lifecycle hooks<br>`<script setup>` | Pinia store<br>Axios HTTP calls<br>Component props | Cypress E2E tests<br>ESLint<br>SonarQube settings |

## 🚀 Quick Start

```bash
git clone https://github.com/salimkaboura8/vue-hello-world.git
cd vue-hello-world

npm install
npm run serve
```

---

<div align="center">
Made with ❤️ by <a href="https://github.com/salimkaboura8">Salim Kaboura</a>
</div>
