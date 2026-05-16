# Creating a Unity Game that Gamifies Teaching

A 2D educational role-playing game (RPG) built with Unity and C# to make learning software engineering concepts more engaging through gameplay inspired by classic monster-battling games.

This project was developed as part of a university software engineering course. It combines gamification with academic content from modules such as Object-Oriented Design & Programming (OODP), Software Engineering (SE), and Software Systems Analysis & Design (SSAD). Players progress through worlds, battle trainers by answering quiz questions, compete on leaderboards, and teachers can create assignments for students.

---

## Project Overview

Traditional studying can be repetitive and disengaging. This project transforms revision into an interactive game where students answer multiple-choice questions to defeat enemies and unlock new sections.

The game supports two types of users:

### Students
- Explore worlds and complete Quest Mode
- Compete in timed PvP battles
- Join custom challenge rooms
- Track stars, points, and statistics
- View leaderboards

### Teachers
- Create assignments using custom question sets
- Share room IDs with students
- View student scores and statistics
- Manage the question bank

---

## Features

### Quest Mode
- Explore three worlds representing academic modules
- Progress through sections and defeat trainers
- Earn stars to unlock new sections

### Battle System
- Turn-based combat powered by quiz questions
- Choose Easy, Medium, or Hard questions
- Correct answers deal damage to opponents

### PvP Mode
- Timed battles with a 300-second limit
- Points awarded based on remaining time
- Highest scores are recorded to the leaderboard

### Custom Mode
- Create and join challenge rooms
- Build custom question sets from the question bank
- Scores are stored for later review

### Statistics and Leaderboards
- Track total stars and points
- Filter results by world and section
- Compare rankings with other players

### Assignment System
- Teachers create assignments as challenge rooms
- Students complete assignments asynchronously
- Teachers review student performance

### Question Bank Management
- Add and edit questions
- Organize by world, section, and difficulty

### Authentication
- Student and teacher registration
- Password reset
- Role-based access control

---

## Architecture

The application follows a three-tier architecture:

1. Client Tier – Unity UI and scene interactions
2. Logic Tier – Game mechanics and business logic
3. Data Tier – Firebase for authentication and persistent storage

This architecture improves maintainability, scalability, and extensibility.

---

## Technology Stack

- Unity
- C#
- Firebase Authentication
- Firebase Realtime Database

---

## Educational Content

The game organizes questions into three academic worlds:

- OODP – Object-Oriented Design & Programming
- SE – Software Engineering
- SSAD – Software Systems Analysis & Design

Each world contains multiple sections, trainers, and questions with Easy, Medium, and Hard difficulty levels.

---

## Getting Started

### Prerequisites

- Windows operating system

### Running the Game

1. Download the repository.
2. Navigate to the build folder.
3. Run the executable file (`SoftwareMon.exe` or the provided `.exe` file).
4. Create an account or log in to start playing.

No Unity installation is required to play the game.

---

## Core Modules

- Authentication System
- Quest Mode
- Battle System
- PvP Mode
- Custom Challenge Rooms
- Leaderboard
- Assignment Management
- Question Bank
- Statistics Dashboard

---

## Key Learning Outcomes

This project provided hands-on experience in:

- Game development with Unity
- Object-oriented programming in C#
- Firebase authentication and database design
- Educational software design
- Software architecture and design patterns
- Requirements engineering and testing
- Team-based software development

---

## Documentation

The project includes comprehensive software engineering artifacts such as:

- Software Requirements Specification (SRS)
- Use Case Diagrams
- Component Diagrams
- ER Diagrams
- Black-Box Test Cases

---

## Team Project

This project was developed collaboratively as part of a university software engineering course. My contributions included Unity development, C# programming, software design, and Firebase integration.

---

## Author

Jethro Phuah

- GitHub: https://github.com/JethroPhuah
