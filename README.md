# 🧮 Simple Calculator Web App

<div align="center">

🎉 A lightweight and responsive **Calculator Web Application**  
💻 Built using **HTML, CSS & JavaScript**  
🐳 Containerized using **Docker & Nginx**  
🚀 Designed for fast and reliable web deployment  

</div>

---

## ✨ Features
✔ User-friendly & clean UI  
✔ Supports +, −, ×, ÷ operations  
✔ Clear button (C) and backspace (⌫) functionality  
✔ Fully responsive layout  
✔ Deployed using Docker

---

## 📁 Project Structure
├── index.html

├── style.css

├── script.js

└── Dockerfile

---

## 🐳 Docker Deployment

### 🔹 Build Docker Image
```bash
docker build -t calculator-app .
```
🔹 Run Container
```
docker run -d -p 80:80 calculator-app
```
🔹 Access Application
```
http://localhost
```
📦 Dockerfile Used
```
FROM nginx:alpine

RUN rm -rf /usr/share/nginx/html/*

WORKDIR /usr/share/nginx/html

COPY . .

EXPOSE 80
```
📸 App Screenshot

![App Screenshot](https://github.com/user-attachments/assets/383f9513-dc55-4c66-9fe2-57567dd376ff)

🚧 Future Enhancements

- Add theme mode (Dark / Light)

- Add percent (%) & square root operations

- Add keyboard input support

👨‍💻 Author

💡 Developed by Shaik Nagul Babu

If you like this project, don’t forget to ⭐ the repo!

<div align="center">
🔥 Thank you for visiting this repository!
  
💬 Suggestions & contributions are always welcome

</div>
