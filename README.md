# 💼 My Profile Page

This is my simple personal profile web application built using **Flask** (Python), along with **HTML**, **CSS**, and **JavaScript**. It allows users to view a basic profile, see a photo, and submit a contact form.


---

## ✨ Features

- 📷 Displays a welcome message and personal photo
- 👩‍🎓 Shows a short introduction
- 📨 Contact form for visitors (Name, Email, Message)
- 🟢 JavaScript-powered "Say Hello" alert button
- 🎨 Neatly styled using custom CSS
- 🐳 Docker support included for easy deployment

---

## 🛠 Technologies Used

- Python 3
- Flask
- HTML5 / CSS3
- JavaScript
- Docker 

---

## 📁 Project Structure
my_profile/
├── app.py # Main Flask app
├── requirements.txt # Python dependencies
├── Dockerfile # For container deployment
├── static/
│ ├── 41642655-8953-44bc-9d6e-905d79b2a9af.jpg # Profile image
│ └── e6981655-a76d-4cf4-aae0-1498055e1a79.png # Screenshot

# Run with Docker

Build the image
docker build -t my_profile .

## Run the container
docker run -d -p 5000:5000 my_profile

