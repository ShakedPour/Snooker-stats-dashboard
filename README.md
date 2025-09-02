# Snooker Stats Dashboard 🎱

A web application to record and analyze snooker games between friends or solo practice sessions.  
The system tracks players stats such as average points per game, number of wins, and highest break, and displays them in a leaderboard and detailed player pages.  

This project is built as part of my personal learning journey in DevOps and Cloud Engineering, and also serves as a portfolio project.


## Features ✨
- Add a match between one or two players (name, score, highest break, date).
- Automatic update of player statistics:
  - Matches played
  - Wins
  - Average score per game
  - Highest break
- Dynamic Leaderboard sorted by:
  - Average score
  - Number of wins
  - Highest break
- Player details page:
  - List of all matches with dates and scores
  - Summary of stats
- CI/CD Pipeline with GitHub Actions → Docker Hub → AWS deployment.
- Cloud deployment on AWS (EC2/ECS).


## Architecture 🏗️
- **Flask API** for match entry and stats retrieval.  
- **Redis** for storing players, matches, and leaderboards.  
- **Simple UI** (HTML templates) for Leaderboard and player pages.  
- **CI/CD** with GitHub Actions for automated tests and container builds.  
- **Deployment** to AWS cloud.  

## Roadmap 🛣️
- [ ] MVP: record matches and update stats  
- [ ] Leaderboard UI (average, wins, high break)  
- [ ] Player detail page with history and stats  
- [ ] Unit tests with pytest  
- [ ] GitHub Actions CI/CD pipeline  
- [ ] Docker Hub integration  
- [ ] AWS deployment  
- [ ] Data visualization with Plotly/Grafana  
- [ ] Authentication & multi-user support  

---

## What I Am Learning 📚
Through this project, I am practicing:
- Building REST APIs with Flask  
- Using Redis as a data store  
- Writing and running automated tests  
- Creating CI/CD pipelines with GitHub Actions  
- Containerization with Docker & Docker Compose  
- Deploying apps to AWS cloud infrastructure  
