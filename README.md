# 📸 PixelFlow – Premium Image Hosting App

PixelFlow is a clean, modern, and fast image hosting web application built with **HTML, CSS, and JavaScript**. It allows users to upload images easily and instantly get **Direct image links**, **HTML embed codes**, and **Markdown links** using the **ImgBB API**.

---

## 🎥 Tutorial Video

Watch the complete setup and usage tutorial here:  
PASTE YOUR VIDEO LINK HERE

---

## About This Project

PixelFlow works by connecting directly to **ImgBB**, a free image hosting service. Images are uploaded from the browser and stored securely on ImgBB servers. Once uploaded, the app automatically generates different types of links that can be used on websites, blogs, forums, and Markdown files.

---

## ImgBB API Setup

To use this project, you must create a free ImgBB account and generate an API key.

Go to **https://imgbb.com** and sign up for a free account.  
After logging in, visit **https://api.imgbb.com** and generate your API key.  
Copy the API key for later use.

---

## How to Use PixelFlow

Download or clone this repository and open the `index.html` file in a code editor.  
Inside the JavaScript section, locate the line where the ImgBB API key is defined and replace the placeholder with your own API key.

```js
formData.append('key', 'YOUR_API_KEY_HERE');
```

Save the file and open `index.html` in your browser.  
You can now drag and drop images or click to upload them.  
After uploading, the app will display the direct link, HTML embed code, and Markdown link, which you can copy and use anywhere.

---

## Credits

PixelFlow is created as a lightweight and user-friendly image hosting solution.  
You are free to use, modify, and share this project for personal or educational purposes.
