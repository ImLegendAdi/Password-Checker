<p align="center">
  <img src="https://d3v55qvjb2v012.cloudfront.net/gxnf/2025/08/04/01/12/cTjfVlnI5o3/sc.webp?srcid=cTjfVlnI5o3&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9kM3Y1NXF2amIydjAxMi5jbG91ZGZyb250Lm5ldC9neG5mLzIwMjUvMDgvMDQvMDEvMTIvY1RqZlZsbkk1bzMvc2Mud2VicD9zcmNpZD1jVGpmVmxuSTVvMyIsIkNvbmRpdGlvbiI6eyJEYXRlTGVzc1RoYW4iOnsiQVdTOkVwb2NoVGltZSI6MTc1NDMxNTAxNX19fV19&Signature=VI9au8zG~kgcBNzUaEEtIkX3Ry2Q4CRAMKvJf9l9Gpx1D-HVYfZTsNPqWHkzdbwjITlz~Z7j0TUffJZNvQFVphMe3k1gj1LTWrbBJvBi8RVNpg6Ml5xGNI8DcOvowDEpDA0bGMPHCTl9I5IPTbboWRYaHNDy30NoQhNmItRIyKg_&Key-Pair-Id=APKAI4E2RN57D46ONMEQ" 
       width="400" alt="Password Checker Demo Preview" />
</p>

# 🔒 Password Strength Checker Browser Extension

A lightweight Browser Extension that automatically evaluates password strength on web forms and suggests strong, secure passwords in real-time.

⚡ Built by [3L173 H4CK3R 1337 (@ImLegendAdi)](https://github.com/ImLegendAdi)

---

## 🚀 Features

- 🛡️ **Real-time Password Strength Checker**
- ⚠️ Displays visual warnings for weak passwords
- 💡 Suggests strong passwords containing:
  - Uppercase
  - Lowercase
  - Numbers
  - Special Characters (e.g. @, #, %)
- 📦 Fully offline — No data collected, 100% privacy-focused

---

## 📂 Project Structure

password-checker-extension/
├── manifest.json

├── popup.html

├── style.css

├── content.js

├── icons/

│ ├── icon16.png

│ ├── icon48.png

│ └── icon128.png

└── README.md

---

## 🛠️ Installation Steps

### 1. Clone the repository:
    ```bash
    git clone https://github.com/ImLegendAdi/Password-Checker.git ```
    
2. Go to `chrome://extensions` in your browser.
3. Enable **Developer Mode** (top right corner).
4. Click **Load unpacked**.
5. Select the **project folder**.
6. ✅ Done! The extension icon will appear in the toolbar.

### 2. Sideloading (Manual Install — Developer Mode)

If you don’t want to publish on AMO but still want to install it “semi-permanently”:

    Place your extension folder (unzipped) into:

        Windows: C:\Program Files\Mozilla Firefox\browser\extensions\

        Or place .xpi file there.

    Restart Firefox.

    It will install automatically but will still be flagged as an unverified extension unless signed.

    You can bypass some warnings by using Firefox Developer Edition and setting:

        Go to about:config

        Set xpinstall.signatures.required to false.

### 3. Best Workflow For You (Developer Mode, No Publishing)

    Use Firefox Developer Edition.

    Disable signature requirement:

        Go to about:config

        Set:

            xpinstall.signatures.required → false

            extensions.install.requireBuiltInCerts → false

    Load your unpacked extension manually via about:debugging#/runtime/this-firefox.

    It will stay loaded across sessions unless removed manually.
    
---

## 🧪 How It Works
- Listens to all password field inputs.
- Calculates strength based on length and character variety.
- Suggests a strong random password if the entered password is weak.
- It suggests 25 chars of strong password

---

## 🧑‍💻 Author
- **3L173 H4CK3R 1337 (@ImLegendAdi)**
  - [GitHub](https://github.com/ImLegendAdi)
  - [LinkedIn](https://linkedin.com/in/ImLegendAdi)

---

## 💡 Contributions
PRs are welcome! Feel free to fork this project, enhance it, or suggest new features via issues.

---

## ⭐ Support & Share
If you like this project, give it a ⭐ on GitHub and share it!

