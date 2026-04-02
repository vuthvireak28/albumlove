# 💖 Wedding Album Website

A beautiful, mobile-friendly wedding album website with:

* 📸 Swipeable photo pages
* ➕ Add photos dynamically
* 🔐 Password unlock system
* 🎵 Background music

---

## ✨ Features

* 📱 **Mobile-first design** (perfect for phone view)
* 🖼️ **Elegant album layout** (like real wedding photo book)
* ➕ **Upload photos anytime**
* 🔐 **Password protection**
* 👁️ **Show / hide password toggle**
* 🎶 **Auto music play after unlock**

---

## 📁 Project Structure

```
project/
│── index.html
│── style.css
│── script.js
│── music.mp3
└── img/
    ├── img1.jpg
    ├── img2.jpg
    ├── img3.jpg
    └── ...
```

---

## 🚀 How to Use

### 1. Open Website

Just open:

```
index.html
```

---

### 2. Unlock Album

* Enter password:

```
170320
```

* Tap 👁 to show/hide password
* Click **Unlock 💖**

---

### 3. Add Photos

* Tap **+ Add Photos**
* Select images from your phone
* Photos will automatically create new album pages

---

## 🛠️ Customization

### 🔑 Change Password

In `script.js`:

```javascript
if(p === '170328')
```

---

### 🖼️ Add Default Images

Put your images inside `/img` folder and update:

```html
<img src="img/yourimage.jpg">
```

---

### 🎵 Change Music

Replace:

```
music.mp3
```

with your own file

---

## 📱 Mobile Experience

* Swipe left/right to view pages
* Tap to upload photos
* Smooth and responsive layout

---

## 💡 Future Upgrades

* 💾 Save photos permanently
* 📖 Real page flip animation
* ✨ Wedding-style fonts & effects
* 🔄 Drag & reorder album pages

---

## ❤️ Credits

Made with love 💕
Perfect for couples, memories, and special moments.

---

## 📌 Note

Photos uploaded are temporary (not saved after refresh).
Use backend or localStorage if you want permanent storage.

---

Enjoy your beautiful memory album 💖
