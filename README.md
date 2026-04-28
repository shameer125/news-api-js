# 📰 News App

A simple and responsive **News Web Application** built using **HTML, CSS, and JavaScript** that fetches real-time news using the NewsAPI.

---

## 🚀 Features

* 🔍 Search news by keyword
* 🌍 Fetch top headlines (default view)
* 🖼️ Display news with image, title, and description
* 🔗 Click on any article to read full news
* ⚡ Fast and lightweight (Vanilla JavaScript)
* 📱 Responsive UI design

---

## 🛠️ Tech Stack

* HTML5
* CSS3
* JavaScript (ES6+)
* REST API (NewsAPI)

---

## 📂 Project Structure

```
📁 news-app
│── index.html
│── style.css
│── script.js
```

---

## 🔑 API Setup

This project uses **NewsAPI** to fetch news data.

1. Go to: https://newsapi.org
2. Create a free account
3. Generate your API key
4. Replace the API key in your `script.js` file:

```js
const apikey = "YOUR_API_KEY_HERE";
```

---

## ▶️ How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/news-app.git
```

2. Navigate to the project folder:

```bash
cd news-app
```

3. Open `index.html` in your browser

---

## ⚠️ Important Notes

* API key is exposed in frontend → not secure for production
* Some articles may not have images or descriptions
* Free API plan has request limits

---

## 📸 Preview

* Displays latest headlines on load
* Search functionality for custom topics
* Clean card-based layout for articles

---

## 🔮 Future Improvements

* 🔐 Add backend to secure API key (Node.js)
* 🎨 Improve UI with animations and modern design
* 🌙 Dark mode support
* 📄 Pagination / infinite scroll
* ❤️ Save favorite articles

---

## 🙌 Acknowledgements

* Powered by NewsAPI

---

## 📄 License

This project is open-source and free to use.
