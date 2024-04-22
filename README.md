# Leonid Filippov

## 📌 Profile
- Student at CTU FIT, passionate about space engineering and technology with a strong foundation in computer systems.
- Experienced in backend and frontend development, database management, and application architecture.
- Proficient in C, Python, JavaScript, SQL, and more.

## 🚀 Employment History
- Backend Developer at Freelance, Moscow (Jan 2021 - Aug 2021)
- Front-end Developer at Placeb2b, Moscow (Sep 2021 - Dec 2021)
- System Administrator at DaIITrans Group s.r.o, Prague (Jan 2022 - Mar 2022)
- Web Application Developer at HP Tronic, Prague (Jul 2022 - Present)

## 🎓 Education
- Higher Diploma in Programming in Computer Systems from the College of Space Engineering and Technology (2019 - 2021)
- Currently studying Software Engineering at Czech Technical University, Faculty of Information Technology

## 🌐 Languages
- Russian (Native)
- English (Intermediate)
- Czech (Intermediate)

## 💻 Skills
- `C` `C++` `Python` `JavaScript` `Java`
- `Git` `HTML & CSS` `SQL` `PostgreSQL` `Vue` `PHP`

## 🏅 Courses Completed
- C, C++, Python at Moscow School of Programmers (Sep 2016 - Jun 2018)
- Algorithms: Theory and Practice, Data Structures at Stepik (Nov 2019 - Dec 2019)
- Interactive SQL (Jun 2020 - Aug 2021)
- Java Course at HyperSkill (Jan 2023 - Mar 2023)
- Standard Linux Course, Cisco Networking Academy (Sep 2022 - Nov 2022)

## 🔗 Links
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Leonid%20Filippov-blue)](https://www.linkedin.com/in/leonid-filippov-6b99b7286/)

---

<p align="center">
  <img src="https://media.giphy.com/media/3oKIPnAiaMCws8nOsE/giphy.gif" alt="Greeting Animation" width="200"/>
</p>

<p align="center">
  <strong>You've scrolled down to the most interesting part - the description of my projects and a cat. 😺</strong>
</p>

---

## 📚 Projects

Below are some of the projects I've worked on. Click on the titles to see the repositories and read more about each project.

## 🏨 StayEz - Hotel Reservation System

[![StayEz](https://img.shields.io/badge/View_Project-StayEz-blue.svg?style=flat-square&logo=github)](https://github.com/OhOverLord/StayEz)

A concise university project aimed at delivering a hotel room reservation system crafted with Spring Boot. This application features a simple yet effective user interface for room bookings, backed by a solid Spring ecosystem.

### Tech Stack:
- Spring Boot
- Spring Data JPA
- Thymeleaf
- PostgreSQL
- Lombok
- Swagger/OpenAPI
- Docker

StayEz allows users to efficiently book hotel rooms, handling reservations with a robust backend and an intuitive front-end interface.

## 🖥️ StayEz Client

[![StayEz Client](https://img.shields.io/badge/View_Client-StayEz_Client-blue.svg?style=flat-square&logo=github)](https://github.com/OhOverLord/StayEz-client)

The StayEz Client provides a user interface for the hotel reservation system, enabling easy and efficient room bookings.

### Tech Stack:
- **Vue.js**: Front-end framework for building user interfaces
- **BootstrapVue**: For responsive and modern UI components
- **SweetAlert2**: For elegant alerts and popups
- **Vue Router**: For spa-like page navigation
- **Vite**: Modern frontend build tool enhancing the development experience
- **Docker**: Used to containerize and deploy the application

This setup ensures a responsive and intuitive booking experience.

## 🏰 Tower Attack

[![Tower Attack](https://img.shields.io/badge/View_Project-Tower_Attack-blue.svg?style=flat-square&logo=github)](https://github.com/OhOverLord/Tower-attack)

Tower Attack is a strategic game where the player sends waves of enemies through a maze with the goal of evading or destroying as many enemy defense towers as possible to conquer the base.

### Tech Stack:
- **C++**: Used for all game logic and performance-intensive tasks.

### Key Features:
- **Tower vs. Attacker Interaction**: Implements functionalities such as attacker destruction, breakthroughs, and tower destruction.
- **Multiple Effects**: Features at least three different effects for both towers (e.g., attack nearest unit, attack strongest, area slow) and attackers (e.g., invisibility, flying, increased resilience).
- **Score Counter and Victory Detection**: Tracks player performance and determines game outcome.
- **AI for Tower Placement**: AI algorithms strategically place towers to maximize defense.
- **Game Configuration from Files**: Configurable game elements (attackers, towers, maps) through external files.
- **Game Save and Load**: Ability to save and load gameplay states.

### Programming Principles:
- **Polymorphism**: Utilized in attacker effects and user interface elements, where different effects and screens share common methods.
- **Breadth-First Search (BFS) Algorithm**: Implemented to find the shortest path for enemies on the map, ensuring strategic gameplay and effective pathfinding.

This project exemplifies the application of advanced programming principles in a complex, interactive game environment.

## 🤖 TCPServer - Treasure Hunt Robot Control

[![TCPServer](https://img.shields.io/badge/View_Project-TCPServer-blue.svg?style=flat-square&logo=github)](https://github.com/OhOverLord/TCPServer)

TCPServer is a TCP server implemented in Python, designed to control robots as they navigate and search for treasure. The server receives coordinates from robots and instructs them on their next moves based on their current location and obstacles encountered.

### Tech Stack:
- **Python**: For server logic and handling TCP connections.
- **Socket Programming**: For TCP/IP communication.
- **Multi-threading**: To handle communication with multiple robots concurrently.

### Key Features:
- **Dynamic Command Handling**: Robots receive commands such as MOVE, TURN LEFT, TURN RIGHT, and GET MESSAGE based on their situation.
- **Error Handling**: Implements responses to various error conditions like SYNTAX ERROR and LOGIC ERROR.
- **Encryption and Security**: Uses a basic encryption mechanism for secure communication between the server and robots.
- **State Management**: Manages robot states and positions, providing commands based on the robot's current state and received data.

### Server Commands:
- `MOVE` - instructs the robot to move forward.
- `TURN LEFT`/`TURN RIGHT` - directs the robot to turn.
- `GET MESSAGE` - command to pick up a treasure if at the correct location.
- `LOGOUT` - disconnects the robot from the server.

The server architecture allows for scalable communication with multiple robots, ensuring robust handling of real-time data and commands.
