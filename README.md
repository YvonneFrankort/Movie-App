# 🎬 Movie App
A full-stack movie discovery platform built as a 4-person team project using React, Node.js/Express, PostgreSQL, and The Movie Database (TMDb) API.<br>

The application allows users to search movies and series, explore detailed information, read and write reviews, and manage personal favorites.

---

## 📖 Overview
This application allows users to:

- search movies and series using multiple criteria with basic and advanced filters  
- view detailed movie information  
- browse movies currently in Finnish cinemas  
- create and manage groups  
- write and read reviews with ratings  
- maintain personal favorites  
- earn points and credits through activity (reviews and ratings)  
- purchase items in an in-app shop using earned credits  
- manage a user profile with profile picture, display name, and purchased items  
- share lists publicly

The UI is fully responsive and adapts smoothly across devices.

---

## 👥 My Contribution

I was responsible for frontend development and API-driven user features in the application.

- Implemented movie search functionality (basic and advanced filtering) using TMDb API data
- Built movie detail views and reusable UI components
- Developed the “Now in Cinemas” feature for displaying current releases
- Created the review system with star ratings and comments
- Implemented the personal favorites feature, including partial backend integration for data persistence

---

## 🚀 Features

### 🔍 Search & Discovery
- Search by title, genre, year  
- Movie details with metadata  
- Now in Theaters (Finland)  
- TMDb API integration for real-time data    

### 👥 Groups
- Create groups with custom names  
- Public group listing  
- Join requests (approve/reject)  
- Remove members or leave groups  
- Add movies to group pages  

### ⭐ User Interaction
- Reviews with star ratings and comments
- Favorites system for saved movies 
- Public sharing via URL  

### 🔐 Authentication & Permissions

The application implements role-based access control and feature restrictions based on user authentication state.

- Guests can browse basic movie search, in cinemas listings, and view movie details
- Logged-in users can access advanced search features, write reviews, and rate movies
- Reviews and ratings are publicly visible but can only be created by authenticated users
- Groups are restricted to logged-in users only
- Group management includes role-based permissions:
  - Only group creators can dissolve groups
  - Only admins can approve or remove members
- Favorites and watchlists are private per user but can be shared within groups

---

## 🎞 Demo GIF

https://github.com/user-attachments/assets/0af321c3-3f70-4c11-b658-fb10eeed9b1e

![Demo](screenshots/demo.gif)

---

## 📸 Screenshots

### Home Page & Movie Search
| Home Page | Movie Search |
|-----------|--------|
| <img width="350" alt="homepage2" src="https://github.com/user-attachments/assets/6bc3a6cd-9bf6-4bd3-b216-45b235bee51d" /> | <img width="350" alt="advanced_search2" src="https://github.com/user-attachments/assets/a3e9bae2-450c-4e17-b28b-2af0a746f021" /> |

### Groups & Profile
| Groups | Profile |
|-----------|--------|
| <img width="350" alt="groups" src="https://github.com/user-attachments/assets/caae99d3-be64-48dd-a71d-675534dac46b" /> | <img width="350" alt="profile" src="https://github.com/user-attachments/assets/9b85c50a-4c5f-45c5-96f5-4750d616fd3d" /> |

### In Cinemas & Shop
| In Cinemas | Shop |
|-----------|--------|
| <img width="350" alt="in_cinemas" src="https://github.com/user-attachments/assets/11117120-8330-48e8-b6ca-dfb82fa6d302" /> | <img width="350" alt="shop" src="https://github.com/user-attachments/assets/367ed157-2cce-4502-bc27-c45072c85a8e" /> |

### Movie Details & Reviews
| Movie Details | Reviews |
|-----------|--------|
| <img width="350" alt="details" src="https://github.com/user-attachments/assets/454be5fd-9159-4bfc-8bbe-4668045a2376" /> | <img width="350" alt="reviews" src="https://github.com/user-attachments/assets/e07d0cb7-6379-4684-ad94-701930777837" />|

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

## 🧪 Testing
The backend includes automated unit tests using **Jest**.

### Test Coverage Includes:
- Authentication flows  
- Review functionality  
- Core API endpoints  

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

This project strengthened my experience in building a full-stack application in a team environment.

- Developing frontend features in React with API-driven data flow
- Working with external APIs (TMDb) and handling asynchronous data
- Designing and implementing user interaction features such as search, filtering, and reviews
- Collaborating in a team using Git workflows and shared code structure
- Understanding backend integration points such as authentication and data persistence
- Working with Docker-based development environments and testing practices (Jest)
