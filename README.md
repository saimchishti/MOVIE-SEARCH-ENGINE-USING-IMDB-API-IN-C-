# Movie Search Engine using IMDB API in C++

This project is a **fully functioning Movie Search Engine**, combining a **C++ backend** for processing movie data via the **IMDB API** and a **web front-end** built with HTML. The search engine allows users to query movie details such as title, rating, and year.

## Features
- **IMDB API Integration**: Fetch movie details including title, rating, year, plot, and more.
- **C++ Backend**: Handles all API requests using **CURL** and processes the data using **JSON**.
- **SFML for UI (C++ Application)**: Provides a graphical user interface for the backend application.
- **HTML Frontend**: User-friendly webpage to input movie titles and display the fetched data.
- **Ubuntu Platform**: Developed and tested on **Ubuntu**.

## Technologies and Libraries Used

### Backend:
- **C++**: Core language for the backend logic.
- **CURL**: For making HTTP requests to the IMDB API.
- **JSONCPP**: To parse and process JSON data returned by the API.
- **SFML**: Simple and Fast Multimedia Library (SFML) used for graphical display in the C++ application.

### Frontend:
- **HTML/CSS**: For building the movie search interface on the web.
- **JavaScript**: (Optional) To interact with the backend and dynamically display results.

### Required Libraries
- **libcurl**: Handles API requests.
- **jsoncpp**: Processes JSON responses.
- **SFML**: For the graphical user interface.

## Installing Dependencies

### 1. Install CURL
```bash
sudo apt update
sudo apt install libcurl4-openssl-dev
