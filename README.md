🎬 Movie Web App

A full‑stack movie discovery platform built with React, Node.js/Express, PostgreSQL, and Docker.
The app integrates with The Movie Database (TMDb) API to deliver real‑time movie data and offers social features like groups, reviews, and favorites.


📖 Overview
This application allows users to:

- search movies and series using multiple criteria

- browse what’s currently in Finnish cinemas

- create and manage groups

- write and read reviews

- maintain personal favorites

- share lists publicly

The UI is fully responsive and adapts smoothly across devices.
<br>
<br>
🚀 Features
<br>
🔍 Movie & Series Search
Search by title, genre, year

- View detailed movie information

- “Now in Theaters (Finland)” section

- Search available without login

👤 User Accounts
- Registration with password validation

- Login & logout

- Account deletion (removes all user‑generated data)

👥 Groups
- Create groups with custom names

- Public group listing

- Join requests (approve/reject)

- Remove members or leave groups

- Add movies to group pages

⭐ Reviews & Favorites
- Post reviews with text + star rating

- Browse reviews without login

- Personal favorites list

- Public sharing via URL

✨ Optional Enhancements
- Shop integration

- Custom lists

- Dynamic background changes based on genre

🧪 Testing
The backend includes automated unit tests using Jest.

Test Coverage Includes:
- User registration

- Login & logout

- Account deletion

- Browsing reviews

- Positive & negative test cases

🐳 Docker Support
The project includes Docker configuration for containerized development and deployment.

Run with Docker Compose:
docker-compose up --build

This starts:

- backend (Node.js/Express)

- database (PostgreSQL)

- frontend (React)

All services run in isolated containers for consistent environments.

▶️ Running Locally (without Docker)
Backend:
cd moovie/server
npm install
npm start

Frontend:
cd moovie/client
npm install
npm start

🧰 Tech Stack
- Frontend: React

- Backend: Node.js, Express

- Database: PostgreSQL

- API: TMDb

- DevOps: Docker, Railway

- Testing: Jest

📚 Documentation
The repository includes additional documentation:

- Database class diagram

- UI design

- REST API documentation

- Backlog management

- Version control practices

- Project management notes

🌐 Demo
The project was previously deployed on a temporary hosting service.
The trial period has ended, so the live demo is no longer available.

Screenshots and a short demo GIF will be added soon.

👥 Team
Developed collaboratively by:

Pilar Murcia Pozuelo

Yvonne Frankort

Petteri Pätsi

Markku Putaala

💡 What I Learned
This project strengthened my skills in:

- full‑stack development

- API integration

- database design

- authentication & authorization

- writing automated tests

- Docker & containerized workflows

- collaborative Git practices

- project planning and documentationSwagger returns the response body, headers, and status code.
