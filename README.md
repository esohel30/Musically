# Musically - A Music Analysis application for song lovers!

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

##Images of the application 

<img width="1427" alt="Screen Shot 2024-01-15 at 8 01 22 PM" src="https://github.com/esohel30/Musically/assets/90656205/f60922ff-85ac-4050-b0cf-f0d169163e0f">
<img width="1427" alt="Screen Shot 2024-01-15 at 7 58 55 PM" src="https://github.com/esohel30/Musically/assets/90656205/b73be028-42f6-4776-b5ef-cbe2f84bf1a1">
<img width="1427" alt="Screen Shot 2024-01-15 at 7 59 51 PM" src="https://github.com/esohel30/Musically/assets/90656205/e371c478-a222-4acf-b7e8-3494bdcf2e22">
<img width="1427" alt="Screen Shot 2024-01-15 at 8 00 30 PM" src="https://github.com/esohel30/Musically/assets/90656205/b3639b7b-81fd-4beb-86d0-65b04c08b7ed">
<img width="1427" alt="Screen Shot 2024-01-15 at 7 58 30 PM" src="https://github.com/esohel30/Musically/assets/90656205/29ae6a49-9f1e-4e53-a8d7-bb182aceabbf">
<img width="1427" alt="Screen Shot 2024-01-15 at 7 59 07 PM" src="https://github.com/esohel30/Musically/assets/90656205/8b2f1841-7e3a-481e-9b5c-2c1d882d8596">

## Running the Application
- The application can be launched locally by running `python [filename].py`, and it will be hosted on `0.0.0.0` at port `5000`.

## Future Development
- Implementing OAuth for secure Spotify integration.
- Refining the lyric generation algorithm for enhanced output.
- Upgrading the UI/UX for a more engaging user interface.

## Conclusion
This Flask-based web application is a versatile platform for music enthusiasts. Its standout feature is the use of Markov chains for lyric generation, offering users a creative tool to explore and create music-inspired content.
