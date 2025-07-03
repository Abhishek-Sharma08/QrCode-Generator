# 📦 QR Code Generator

A simple and responsive QR Code generator web app built using HTML, CSS, and JavaScript. Enter any text or URL, click a button, and get a QR code instantly using the QuickChart API.


---

## 🛠️ Features

- ✅ Generates QR codes for any text or URL  
- ✅ Smooth transition effect when QR code is displayed  
- ✅ Shake animation for empty input errors  
- ✅ Mobile-friendly and responsive design  
- ✅ Lightweight – no external libraries used  

---

## 📂 Project Structure

```
├── index.html       # Main HTML file
├── style.css        # Styling and animations
└── script.js        # QR generation logic
```



## 🔧 How It Works

- User inputs text or a URL.
- Clicking the **"Generate QRCode"** button triggers a call to:

  ```
  https://quickchart.io/qr?text=YOUR_TEXT
  ```

- The image is dynamically updated and displayed with a transition.
- If the input is empty, an error shake animation is shown.

---

## 💻 How to Run Locally

1. Clone the repository or download the files.
2. Open `index.html` in any modern web browser.
3. Type text/URL and click **Generate QRCode**.

---

## 📄 Technologies Used

- **HTML5**
- **CSS3**
- **Vanilla JavaScript**
- **[QuickChart.io](https://quickchart.io/)** – for generating QR codes



## 📃 License

This project is open-source and free to use.
