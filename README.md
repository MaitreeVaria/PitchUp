# PitchUp 

PitchUp is an innovative recruitment platform that revolutionizes the hiring process by connecting talent with opportunities through dynamic video pitches and intuitive matchmaking algorithms.

Check out a walkthrough of the app on YouTube: [App Demo](https://www.youtube.com/watch?v=78MGDB0GqlE)

## Features

- **Video Pitches**: Candidates can showcase their skills and personality through short, engaging video introductions.
- **AI-Driven Matching**: Advanced algorithms match candidates with suitable job opportunities based on skills, experience, and preferences.
- **Swipe-Based Interface**: Intuitive swipe functionality for both recruiters and candidates to express interest.
- **Real-Time Notifications**: Instant updates on matches and new opportunities.
- **Detailed Profiles**: Comprehensive candidate and job profiles for informed decision-making.
- **In-App Messaging**: Seamless communication between matched candidates and recruiters.

## Technology Stack

- **Frontend**: React Native
- **Backend**: FastAPI
- **Databases**: 
  - MongoDB (User authentication)
  - Neo4j (Candidate profiles and relationships)
- **Video Storage**: Google Cloud Storage
- **Machine Learning**: TensorFlow, Keras, PyTorch

## System Architecture
![System Architecture](https://github.com/MaitreeVaria/PitchUp/blob/4acfda773c2112ffdd7e8875faac0da3a760d96d/Images/system_architecture.png?raw=true)


## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/MaitreeVaria/PitchUp.git
   ```

2. Install dependencies:
   ```
   cd PitchUp
   npm install
   ```

3. Set up environment variables (refer to `.env.example` if available).

4. Run the application:
   ```
   npm start
   ```
## Screen Flow
![System Architecture](https://github.com/MaitreeVaria/PitchUp/blob/6fa09a2085335991c1779ae91e63c0bd550b5526/Images/screen_flow.png?raw=true)

## Project Structure

The project consists of several key components:

- **Frontend**: React Native application with screens for user authentication, profile creation, job listings, and matching.
- **Backend**: FastAPI server handling API requests, database interactions, and matchmaking algorithms.
- **Databases**: MongoDB for user authentication and Neo4j for storing candidate profiles and relationships.
- **Machine Learning**: Collaborative filtering algorithms for personalized recommendations.

---

PitchUp - Redefining Recruitment for the Digital Age
