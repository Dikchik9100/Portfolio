# Online Parking Lot System

A simple MVP (Minimum Viable Product) for an online parking lot management system built with Flask.

## Features

- User registration and login
- View available parking spots
- Book a parking spot
- View booking history
- Admin dashboard for managing spots and bookings

## Local Development Setup

1. Clone the repository
2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Create a `.env` file with the following variables:
   ```
   SECRET_KEY=your-secret-key-here
   DATABASE_URL=sqlite:///parking.db
   ```
5. Run the application:
   ```bash
   python app.py
   ```
6. Access the application at `http://localhost:5000`

## Deployment

This application is configured for deployment on Render.com. The deployment process is automated through GitHub integration.

## Environment Variables

- `SECRET_KEY`: Flask secret key for session management
- `DATABASE_URL`: Database connection URL (automatically provided by Render)
