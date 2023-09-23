# startup
CS 260 project

## Description Deliverable

### Elevator Pitch

The best way to settle a quick decision with a friend is easily rock-paper-scissors. But what if you're online chatting with some friends and need to make a decision about who gets to play what role in an online game? This is where Janken Ketto comes into play. You pull out your phone or go to the website, look up your friend, and challenge them to a dual. Janken (じゃんけん) is the name of the rock-paper-scissors in Japanese and ketto (決闘) means dual.

### Key Features

- Real-time Janken duals!
- English and Japanese language settings
- Friend list to keep track of friends and challenge them quickly
- Friend list and win/loss count per friend persistently stored
- Account settings like username, password, and deleting account.

### Design

![Design Layout](<Design Export.png>)

### Technologies

This is how I will be incorporating the required technologies.

- **HTML** - The general structure of the application with 4 pages. Login/landing page, friend list & record, settings, and of course the dualing arena.
- **CSS** - Used for style to make the general layout look visually appealing.
- **JavaScripti** - Used to handle the game logic and interacting with the services.
- **Service** - Backend services will be used for the game logic as well as retrieving/submitting credentials.
- **DB** - Stores users and all their information like credentials and friend lists.
- **Login** - Handle registration, login, and account deletion. Can't proceed pass the login/landing page unless logged in.
- **WebSocket** - Rock-paper-scissor choices and results will be sent to dualing opponent.
- **React** - Will use the React web framework.
