# 🎬 Movie App
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

### Home Page
<img width="764" height="763" alt="homepage2" src="https://github.com/user-attachments/assets/6bc3a6cd-9bf6-4bd3-b216-45b235bee51d" />

<img width="764" height="763" alt="homepage2" src="https://github.com/user-attachments/assets/4a8ae51a-fae8-4e5d-afb7-5f63ad3c70d3" />


### Search
<img width="770" height="763" alt="advanced_search" src="https://github.com/user-attachments/assets/c3c068bf-2802-4451-afc6-b606dd602db0" />
<img width="772" height="763" alt="advanced_search2" src="https://github.com/user-attachments/assets/a3e9bae2-450c-4e17-b28b-2af0a746f021" />
<img width="770" height="761" alt="advanced_search3" src="https://github.com/user-attachments/assets/d906f1b0-39fc-4a00-98d8-76cea3c50be3" />

### Movie Details
<img width="939" height="334" alt="details" src="https://github.com/user-attachments/assets/454be5fd-9159-4bfc-8bbe-4668045a2376" />

### Movie Reviews
<img width="977" height="679" alt="reviews" src="https://github.com/user-attachments/assets/e07d0cb7-6379-4684-ad94-701930777837" />

### Groups
<img width="763" height="756" alt="groups" src="https://github.com/user-attachments/assets/caae99d3-be64-48dd-a71d-675534dac46b" />

### Profile
<img width="771" height="768" alt="profile" src="https://github.com/user-attachments/assets/9b85c50a-4c5f-45c5-96f5-4750d616fd3d" />

### In Cinemas
<img width="766" height="747" alt="in_cinemas" src="https://github.com/user-attachments/assets/11117120-8330-48e8-b6ca-dfb82fa6d302" />

### Shop
<img width="767" height="763" alt="shop" src="https://github.com/user-attachments/assets/367ed157-2cce-4502-bc27-c45072c85a8e" />

---

## 🎞 Demo GIF

https://github.com/user-attachments/assets/0af321c3-3f70-4c11-b658-fb10eeed9b1e

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
