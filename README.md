
# QuestComplete (Beta)

**QuestComplete** is a Vencord plugin that adds a **“Spoof”** button to the **Quests tab** in Discord, allowing you to complete quests without having to install or launch games/apps manually.

> If Quest asks to choose platform just choose `Desktop`

> ⚠️ This plugin is still **work in progress (WIP)**.

> Spoofing code adapted from [this gist](https://gist.github.com/aamiaa/204cd9d42013ded9faf646fae7f89fbb) by [aamiaa](https://gist.github.com/aamiaa).



## Installation Guide

### Requirements

Before installing, make sure you have:

* [Node.js](https://nodejs.org/) **v16 or higher**
* [Git](https://git-scm.com/)
* [pnpm](https://pnpm.io/) — install via: `npm install -g pnpm`

### 1. Clone Vencord

```bash
# Clone the Vencord repository
git clone https://github.com/Vendicated/Vencord.git
cd Vencord

# Install dependencies
pnpm install
```

### 2. Add the Plugin

1. Inside the `src` folder, create a new folder structure:

   ```
   src/userplugins/questComplete/
   ```

2. Download or copy the plugin file
   👉 [`index.tsx`](https://github.com/zaher-neon/vc-questComplete/blob/main/index.tsx)

3. Place the file inside the `questComplete` folder:

   ```
   src/userplugins/questComplete/index.tsx
   ```


### 3. Build and Inject

Run the following commands in the **root directory** of your Vencord clone:

```bash
pnpm build
pnpm inject
```




