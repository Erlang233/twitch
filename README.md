# Twitch Resource Search and Recommendation Application

This is a full-stack Spring Boot application that allows users to search Twitch resources and receive tailored recommendations based on their favorite game collections. The application integrates with Twitch API, stores data in a MySQL database, and is deployed on AWS App Runner for scalable and efficient performance.

## Features

- **Search Twitch Resources**: Users can search for Twitch resources such as streams and games.
- **Tailored Recommendations**: The application provides content-based recommendations based on the user's favorite game collections.
- **User Authentication**: Integrated with Spring Security for secure user registration and login.
- **Real-Time Data**: Uses OpenFeign to retrieve real-time data from Twitch API.
- **Scalable Deployment**: Deployed on AWS App Runner with Auto Scaling, Serverless Architecture, Concurrent Request handling, and Load Balancing.

## Technologies Used

- **Backend**: Spring Boot, Spring Data JDBC, Spring Security
- **Frontend**: (Specify if you used any frontend technologies like HTML, CSS, JavaScript)
- **Database**: MySQL hosted on AWS RDS
- **API Integration**: OpenFeign HTTP client for Twitch API
- **Deployment**: AWS App Runner

## Setup Instructions

### Prerequisites

- Java 11 or higher
- Maven 3.6.0 or higher
- MySQL database (locally or hosted on AWS RDS)
- AWS account for deployment (if you want to deploy using AWS App Runner)

### Clone the Repository

```bash
git clone https://github.com/yourusername/twitch-resource-recommendation.git
cd twitch-resource-recommendation
