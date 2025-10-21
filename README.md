# Workout Tracker App -- Mapty

## Overview

**Mapty** is a web application that allows users to log their workouts (running and cycling) directly on a map. The app provides a visual representation of workouts, keeps track of important statistics, and saves the data in the browser's local storage for persistent tracking.

This project demonstrates practical use of modern JavaScript techniques, object-oriented programming (OOP), and browser APIs such as Geolocation and Local Storage

---

## Features

- **Add Workouts:** Log running or cycling workouts with distance, duration, cadence (running), and elevation gain (cycling).
- **Map Integration:** Display workouts as markers on a map using **Leaflet.js**.
- **Dynamic Form Fields:** Form adapts based on workout type (running vs. cycling).
- **Workout List:** View all workouts in a list with details such as pace, speed, cadence, and elevation.
- **Local Storage:** Persist workouts across page reloads using **Local Storage**.
- **Interactive Map:** Click a workout in the list to pan and zoom to its location on the map.[Using leaflet API]
- **Reset Data:** Clear all workouts from storage and reload the app.

---

## Getting started

- Download the zip file and open the index.html file using google chrome
- Give permission to access location
- Click on the point on the map that you want to mark
- Add the activity for the point in form on the left and press enter
- If you want to locate a particular activity just click on it in the activity list you created .
- One you are done --> right click on the screen --> Click on inspect ---> Console ---> Type "app.reset()" ----> This will clear the data from the local storage and the application will get reset !!!!
