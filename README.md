# Airbnb Clone with Advanced Features

## Project Description
This project is a web application inspired by Airbnb, designed to provide users with a platform to book and list properties. Unlike the traditional Airbnb site, this platform introduces advanced search capabilities and community engagement features, such as user forums and real-time messaging, to enhance user interaction and usability.

---

## Features

### Core Features
- **User Authentication**: Secure signup, login, and logout functionalities using JWT.
- **Property Listings**: Hosts can add, edit, and delete property listings.
- **Booking System**: Guests can check availability, book properties, and manage reservations.
- **Payments Integration**: Secure payment handling using Stripe/PayPal.

### Advanced Features
- **Advanced Search**: Filters for property type, price range, and amenities with Elasticsearch integration.
- **Community Engagement**: User forums for discussions and real-time chat between hosts and guests using Socket.IO.
- **Reviews & Ratings**: Users can leave reviews and ratings for properties.
- **Gamification**: Reward system with badges and leaderboards for hosts and guests.

---

## Tech Stack

### Frontend
- **React**: User interface development.
- **Next.js**: Server-side rendering and routing.
- **Tailwind CSS**: Styling and design.

### Backend
- **Node.js**: Server-side development.
- **Express.js**: REST API creation.
- **Socket.IO**: Real-time messaging.

### Database
- **PostgreSQL**: Relational database for core application data.
- **MongoDB**: NoSQL database for chat logs.
- **Elasticsearch**: Advanced search and filtering.

### Other Tools
- **Stripe/PayPal**: Payment processing.
- **Docker**: Containerization.
- **AWS/Vercel**: Deployment.

---

## Usage

### Local Development
- Access the frontend at `http://localhost:3000`.
- The backend runs at `http://localhost:5000`.

### Testing
- Unit tests are written using Jest.
- Run tests with:
  ```bash
  npm test
  ```

---

## Deployment

### Steps
1. Build the application:
   ```bash
   npm run build
   ```
2. Deploy using Docker:
   ```bash
   docker-compose up --build
   ```

### Recommended Hosting Platforms
- AWS
- Vercel
- Heroku

---
## Contact

For questions or feedback, please contact:
- **Your Name**: nobuhlereitumetse@gmail.com
- [GitHub Repository](https://github.com/ReituTheCompSciGirlie/AirBnbProject)

