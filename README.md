# Mapty

Mapty is a JavaScript-based web application that allows users to log and visualize their workouts on an interactive map.  
It combines geolocation, local storage, and object-oriented programming concepts to demonstrate modern JavaScript in action.

---

## Overview

The Mapty app lets users:
1. View their current location on a map (using the Geolocation API)
2. Log new workouts (running or cycling) by clicking on the map
3. Store all workout data persistently using Local Storage
4. Display workout details both on the map and in a sidebar list
5. Automatically zoom to workout locations

It’s a fully client-side project — no backend, database, or external server is required.

---

## Features

- Geolocation API to detect and render the user’s current position on a map  
- Interactive map powered by **Leaflet.js**  
- Ability to add workouts (Running or Cycling) by clicking anywhere on the map  
- Input form for workout details: distance, duration, cadence, or elevation  
- Display of workouts as pins on the map and items in the workout list  
- Auto-centering and zooming to selected workouts  
- Persistent data storage in browser local storage  
- Object-Oriented JavaScript with ES6 classes and method chaining  
- Data validation and clear form interactions  

---

## Technologies Used

- **HTML5**, **CSS3**, and **Vanilla JavaScript (ES6+)**
- **Leaflet.js** for interactive maps
- **Geolocation API** for retrieving user’s location
- **LocalStorage API** for saving data persistently
- **Parcel** (optional) for bundling

---

## Project Structure

