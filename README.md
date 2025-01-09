# Mapper

A Javascript project to demonstrate core and advanced JS concepts with basic HTML, CSS.

## Description

This project implements fundamentals of HTML, CSS and modern JavaScript. It also covers advanced features of JS such as OOP, DOM manipulation, EventHandlers and much more.

## Installation

To install this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/kondlekar-yash/Mapper.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Mapper
   ```
3. Install node
   ```bash
    npm install -g npm
   ```
4. Install node live server
   ```bash
    npm install -g live-server
   ```
5. Run project using:
   ```bash
    live-server --browser='google chrome'
   ```

## Overview

User Stories:

1. As a user, I want to log my running workouts with location, distance, time, pace and steps/minute, so I can log all my running
2. As a user, I want to log my cycling workouts with location, distance, time, speed and elevation gain, so I can keep logs of all my cycling
3. As a user, I want to see all my workouts at a glance, so I can easily track my progress.
4. As a user, I also want to see all my workouts on Map, so I can easily check where I work out the most.
5. As a user, I want to see all my workouts when I leave the app and comeback later, so that I can keep using the app overtime.

Features(as per user stories):

- Map, where user clicks to add new workout (to get location coordinates)
- Geolocation to display map at current location(more user friendly)
- Form to input distance, time, pace, steps/minute
- Form to input distance, time, speed, elevation gain
- Display all workouts in a list
- Display workouts on the map
- Data persistence, for now use local storage to store workout data and on reload get the
  stored data
- Move map to workout location on click

To-Do features:
1- Edit a workout
2- Delete a workout
3- Delete all workouts
4- Sort workouts by certain field (eg distance)
5- Rebuild running and cycling obj from local storage
6- Better error/confirmation messages
7- Geocode and display the actual location from coordinates using 3rd party api (using async await/ promises)
8- Display weather on that location

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
