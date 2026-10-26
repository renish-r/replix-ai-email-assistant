# Replix - AI Email Assistant

**Replix** is an AI-powered Gmail assistant designed to help users quickly generate and edit email replies.  
It provides a seamless experience for Gmail users through a **browser extension** and a **web-based UI** for those who prefer not to install the extension.

---

## 🚀 Features

- ✨ Generate AI-based email replies with a single click  
- 🎯 Choose tones: **Professional**, **Casual**, **Friendly**, or **None**  
- 📝 Edit generated replies inline using the edit panel  
- 📩 Works directly in Gmail’s compose interface  
- 🌐 Web UI for users who don’t want to use the extension  

---

## 🔗 Demo & Links

- **Web UI:** [https://replix-web.vercel.app/](https://replix-web.vercel.app/)  
- **Chrome Extension:** [https://chromewebstore.google.com/detail/agcggljbfakfmaijbgkpkhccomofkdck?utm_source=item-share-c](https://chromewebstore.google.com/detail/agcggljbfakfmaijbgkpkhccomofkdck?utm_source=item-share-cb)  

---

## 🖼️ Screenshots

### Gmail Extension
![Compose Toolbar](https://github.com/Renish-R/replix-extension/blob/main/screenshots/gmail-toolbar.png)
*AI buttons integrated into Gmail compose toolbar.*

### Edit Feature
![Edit Panel](https://github.com/Renish-R/replix-extension/blob/main/screenshots/edit-panel.png)
*Inline edit panel for modifying AI-generated replies.*

### Web UI
![Web UI](https://github.com/Renish-R/replix-extension/blob/main/screenshots/web-ui.png)
*Replix Web interface for users who don't want the extension.*

### Web UI Edit
![Web UI](https://github.com/Renish-R/replix-extension/blob/main/screenshots/web-ui-edit.png)
*Replix Edit interface for users who use UI.*

---

## 🎥 Screen Recordings

### 🌐 Web UI – Working Demo
![Web UI Demo](https://raw.githubusercontent.com/renish-r/replix-extension/main/gif/ui.gif)

▶️ Full video: https://raw.githubusercontent.com/renish-r/replix-extension/main/capture/ui.mp4

### 📩 Gmail Extension – Working Demo
![Gmail Extension Demo](https://raw.githubusercontent.com/renish-r/replix-extension/main/gif/extension.gif)

▶️ Full video: https://raw.githubusercontent.com/renish-r/replix-extension/main/capture/extension.mp4

---

## 🧰 Tools & Technologies

**Frontend / Extension:**
- HTML, CSS, JavaScript (ES6+)
- Chrome Extension Manifest V3
- MutationObserver API for Gmail DOM changes

**Backend:**
- Java 21  
- Spring Boot 4.0 (Web & WebFlux)  
- Maven for build management  
- REST API endpoints:  
  - `/api/email/generate`  
  - `/api/email/edit`

**Deployment:**
- **Backend:** Render (Docker-based deployment)  
- **Frontend / Web UI:** Vercel  
- **Extension Hosting:** GitHub Pages  

**Other Tools:**
- Lombok for Java boilerplate reduction  
- Fetch API for communication between extension and backend  

---

## ⚙️ Installation

### Chrome Extension
1. Visit [GitHub Pages](https://renish-r.github.io/replix-extension/).  
2. Click **Download** -> **Un-zip** -> **Add to Chrome extension**.  
3. Open Gmail — the **“May i”** button appears in the compose toolbar.

### Web UI
1. Open [Replix Web](https://replix-web.vercel.app/).  
2. Enter your email content and select the desired tone(optional).  
3. Generate AI replies directly from your browser.

---

## 💡 Usage

1. Open Gmail and start composing a new email.  
2. Click **“May I”** to generate a reply.  
3. Select a tone for the email *(optional)*.  
4. Edit the reply using the **Edit** button if needed.  
5. Send the email as usual.

---

## 🌱 Future Improvements

- 🌍 Multi-language support for AI generation  
- 🔐 User authentication for personalized suggestions  
- 💼 Improve web UI for handling multiple emails  

---

## ❤️ Credits

Developed by [**Renish R**](https://github.com/Renish-R)
