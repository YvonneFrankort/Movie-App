# 🎬 Movie Web App
A full‑stack movie discovery platform built with **React**, **Node.js/Express**, **PostgreSQL**, and **Docker**.  
The app integrates with **The Movie Database (TMDb)** API to deliver real‑time movie data and offers social features like groups, reviews, and favorites.

---

## 📖 Overview
This application allows users to:

- **search movies and series** using multiple criteria  
- **browse what’s in Finnish cinemas**  
- **create and manage groups**  
- **write and read reviews**  
- **maintain personal favorites**  
- **share lists publicly**  

The UI is fully responsive and adapts smoothly across devices.

---

## 🚀 Features

### 🔍 Search & Discovery
- Search by title, genre, year  
- Movie details with metadata  
- Now in Theaters (Finland)  
- Search available without login  

### 👤 User Accounts
- Registration with password validation  
- Login & logout  
- Account deletion (removes all user data)  

### 👥 Groups
- Create groups with custom names  
- Public group listing  
- Join requests (approve/reject)  
- Remove members or leave groups  
- Add movies to group pages  

### ⭐ Reviews & Favorites
- Post reviews with text + star rating  
- Browse reviews without login  
- Personal favorites list  
- Public sharing via URL  

### ✨ Optional Enhancements
- Shop integration  
- Custom lists  
- Dynamic background changes based on genre  

---

## 📸 Screenshots
*(Add your images to `/screenshots` and update the paths)*

### Home Page
![Home](screenshots/homepage.png)
![Home](screenshots/homepage2.png)

### Search
![Search](screenshots/advanced_search.png)
![Search](screenshots/advanced_search2.png)
![Search](screenshots/advanced_search3.png)

### Movie Details
![Details](screenshots/details.png)

### Movie Reviews
![Reviews](screenshots/reviews.png)

### Groups
![Groups](screenshots/groups.png)

### Profile
![Profile](screenshots/profile.png)

### In Cinemas
![In Cinemas](screenshots/in_cinemas.png)

### Shop
![Shop](screenshots/shop.png)

---

## 🎞 Demo GIF
![Demo](screenshots/demo.gif)

---

## 🧪 Testing
The backend includes automated unit tests using **Jest**.

### Test Coverage Includes:
- User registration  
- Login & logout  
- Account deletion  
- Browsing reviews  
- Positive & negative test cases  

---

## 🐳 Docker Support
The project includes Docker configuration for containerized development and deployment.

### Run with Docker Compose
```
docker-compose up --build
```

This starts:

- Backend (Node.js/Express)  
- Database (PostgreSQL)  
- Frontend (React)  

---

## ▶️ Running Locally (without Docker)

### Backend
```
cd moovie/server
npm install
npm start
```

### Frontend
```
cd moovie/client
npm install
npm start
```

---

## 🧰 Tech Stack
- **React**  
- **Node.js / Express**  
- **PostgreSQL**  
- **TMDb API**  
- **Docker**  
- **Railway**  
- **Jest**  

---

## 📚 Documentation
The repository includes additional documentation:

- Database class diagram  
- UI design  
- REST API documentation  
- Backlog management  
- Version control practices  
- Project management notes  

---

## 🌐 Demo
The project was previously deployed on a temporary hosting service.  
The trial period has ended, so the live demo is no longer available.

Screenshots and a short demo GIF are provided above.

---

## 👥 Team
Developed collaboratively by:

- Pilar Murcia Pozuelo  
- **Yvonne Frankort**  
- Petteri Pätsi  
- Markku Putaala  

---

## 💡 What I Learned
This project strengthened my skills in:

- full‑stack development  
- API integration  
- database design  
- authentication & authorization  
- writing automated tests  
- Docker workflows  
- collaborative Git practices  
- project planning and documentation  
