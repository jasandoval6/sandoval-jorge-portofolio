# 🎮 gamed. — Video Game Diary App

**Technologies:** Flutter, SQLite, IGDB API  
**Role:** Full-Stack Developer  
**Type:** Graduate & Personal Project  

## Overview
*gamed.* is a cross-platform mobile application designed to help users track video game reviews, ratings, and favorites in a personal diary format. 
The project emphasizes frontend-focused mobile development, intuitive navigation, and reliable local data persistence, while integrating third-party APIs for live game metadata.
The application was built to deliver a clean, accessible user experience and to demonstrate practical mobile software engineering concepts such as state management, API consumption, 
and offline data storage.

---

## Architecture Overview

- **UI Layer:** Flutter widgets (screens, dialogs, components)
- **Controllers:** Handle business logic and state coordination
- **Models:** Strongly-typed data models for games, users, and reviews
- **Database:** Local SQLite database using `sqflite`
- **Services:** External API integration for game search

---

## Key Features
- Search games via external API
- Diary-style game reviews with ratings
- Multi-category rating system (Graphics, Sound, Gameplay, Final)
- Favorites & custom lists
- Local persistence using SQLite (`sqflite`)
- Dark-mode focused UI design
- Bottom navigation with FAB-driven actions

---

## Engineering Focus
Frontend development • Mobile UI/UX • API integration • Local data persistence • User-centered design

## Why This Project Matters

gamed demonstrates real-world mobile development concepts including:
- Full CRUD workflows
- Persistent local storage
- API-driven search
- Modular architecture
- Production-style UI patterns

This project is representative of how I approach building maintainable, user-focused mobile applications.

---

## System Artifacts

### User Profile
Shows the main profile view with navigation tabs and top favorite games.

![User Profile](assets/gamed/gamed-user-profile.png)

---

### Search Games
Search results populated from an external game API with platform metadata.

![Search Games](assets/gamed/gamed-search-games.png)

---

### Game Details
Detailed view of a selected game, including supported platforms and diary entry access.

![Game Detail](assets/gamed/gamed-game-result.png)

---

### Rate & Review UI
Custom modal for rating games across multiple categories and adding comments.

![Game Review UI](assets/gamed/gamed-game-review-UI.png)

---

### Diary
Chronological diary entries showing completed reviews and ratings.

![Profile Diary](assets/gamed/gamed-profile-diary.png)

---

### Lists
User-curated lists for organizing liked and favorite games.

![User Lists](assets/gamed/gamed-user-lists.png)

---
*(Source code maintained in a private repository — details and walkthroughs available upon request.)*
