# Music Enthusiast Web Application

## Introduction
This web application, designed for music lovers, integrates various functionalities including user authentication, music data access through the Spotify API, and a unique feature for lyric generation using Markov chains.

## Features

### User Authentication
- **Login/Signup:** Users can create an account or log in to access personalized features.
- **Logout:** Session-based logout functionality for security.
- **Profile Management:** Options for users to view and edit their profile, including password changes.

### Music Data Integration
- **Spotify API Usage:** Fetches data from Spotify for artist and song information.
- **Artist Search:** Allows users to search for artists and view their top tracks.
- **Song Data Analysis:** Provides detailed analysis of songs using Spotify's data.
- **Music Visualizer:** A feature for visualizing music data (implementation details not provided in the code).

### Lyric Generation Using Markov Chains
- **Innovative Text Generation:** Implements Markov chains to generate new lyrics. This probabilistic model considers the likelihood of each word's occurrence based on previous words, creating coherent and stylistically similar lyrics.
- **Customization:** Users can adjust settings like the number of lines and word similarity to influence the lyric generation process.
- **Lyric Mixing:** A feature to blend lyrics from two different songs, creating a unique composition.

## Technical Details
- **Database Handling:** Utilizes SQLite for managing user data and lyric content.
- **Flask Framework:** The application is built on Flask, offering a lightweight and flexible structure.
- **Secure Sessions:** Manages user sessions for both security and a tailored user experience.

## Security Considerations
- The application currently uses a hardcoded secret key, which is not recommended for production environments.

## Running the Application
- The application can be launched locally by running `python [filename].py`, and it will be hosted on `0.0.0.0` at port `5000`.

## Future Development
- Implementing OAuth for secure Spotify integration.
- Refining the lyric generation algorithm for enhanced output.
- Upgrading the UI/UX for a more engaging user interface.

## Conclusion
This Flask-based web application is a versatile platform for music enthusiasts. Its standout feature is the use of Markov chains for lyric generation, offering users a creative tool to explore and create music-inspired content.
