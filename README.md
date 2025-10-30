#  AdGenie – Generate Creative Ad Copy Instantly

AdGenie is a fun and simple web app that helps you generate creative, catchy ad copy for your products or ideas.
Just type in your product, click **Generate Copy**, and let AdGenie work its magic!

Built using **HTML**, **CSS**, and **JavaScript**, and deployed with **Firebase Hosting**, AdGenie delivers instant creative results right from your browser — no backend required.


## ✨ Features

* 🎨 Clean, Material Design–inspired interface
* ⚡ Generates unique and catchy ad copy instantly
* 💬 Dynamic creativity — every click gives a fresh result
* 🌐 Fully client-side (no server or API needed)
* 🚀 Deployed on Firebase for fast and secure access


## 🧱 Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Design:** Material Design Principles & Icons
* **Hosting:** Firebase


## 📁 Folder Structure

```
geniead/
│
├── index.html        # Main app page
├── main.css          # Styling
├── main.js           # JavaScript logic for generating ad copy
├── 404.html          # Custom error page
└── firebase.json     # Firebase hosting configuration
```



## ⚙️ Setup & Deployment

1. **Clone the repo**

   ```bash
   git clone https://github.com/<your-username>/geniead.git
   cd geniead
   ```

2. **Install Firebase CLI (if not already installed)**

   ```bash
   npm install -g firebase-tools
   firebase login
   ```

3. **Initialize Firebase Hosting**

   ```bash
   firebase init
   ```

   * Select **Hosting**
   * Choose **Use existing project**
   * Set `public` directory to `.`
   * Configure as single-page app: **No**

4. **Deploy**

   ```bash
   firebase deploy
   ```



## 💡 Example

**Input:**

> “Eco-friendly coffee mug”

**Generated Copy:**

> 💡 Introducing Eco-friendly coffee mug: changing the way the world thinks.



## 🚀 Live Demo

👉 https://geniead.web.app/


## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
