# Spotify Clone for Android

## Overview

This Android application is a Spotify Clone that serves as a platform for music streaming. It’s designed as a personal project to practice and showcase Android development skills, particularly focusing on modern Android development techniques. The application features a sleek user interface allowing users to browse their favorite music, create playlists, and enjoy seamless music playback.

![Home Screen](https://github.com/x1991x/Spotify/blob/master/image/Spotify_home.PNG)
![Favorites Screen](https://github.com/x1991x/Spotify/blob/master/image/Spotify_favorite.PNG)
![Player Screen](https://github.com/x1991x/Spotify/blob/master/image/Spotify_play.PNG)

## Features

- **Home Screen**: Discover top mixes and recommendations tailored to your taste.
- **Favorites**: Save and manage your favorite tracks with ease.
- **Playlists**: Create and modify playlists to organize your music.
- **Playback Control**: Enjoy an interactive player bar with full control over your music playback.

## Architecture

Leveraging the Model-View-ViewModel (MVVM) architecture, the app ensures a robust, maintainable, and scalable codebase. Each screen is powered by its corresponding ViewModel, promoting a clear separation of concerns and easier management of the UI logic.

## Technologies

- **Kotlin**: The primary language for development, taking advantage of its conciseness and interoperability with Java.
- **Jetpack Compose**: Utilizing the latest UI toolkit for building natively and declaratively.
- **Kotlin Coroutines**: For managing background tasks efficiently and seamlessly.
- **Hilt**: For dependency injection, simplifying the provision of dependencies throughout the application.
- **Retrofit**: To fetch data from a mock server, showcasing network communication.
- **Room Database**: For caching data locally, ensuring a smooth offline experience.
- **Exoplayer**: For handling media playback, providing a rich media experience.

## Backend Integration

The application integrates with a [Spotify Backend](https://github.com/x1991x/Spotify_backend), which is built using the Ktor framework, a lightweight and scalable asynchronous server-side framework by JetBrains, suitable for creating web applications in Kotlin.

## Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/x1991x/Spotify.git
2. Open the project in Android Studio or your favorite IDE.
3. Build the project and run on an Android device or emulator.
