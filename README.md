# Django Geolocation App with Google Maps

This application allows users to view and interact with Google Maps, search for locations, and save favorite places.

## Setup Instructions

1. Make sure you have Python 3.10 installed
2. Create and activate a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Create a `.env` file in the root directory and add your Google Maps API key:
   ```
   GOOGLE_MAPS_API_KEY=your_api_key_here
   ```
5. Run migrations:
   ```bash
   python manage.py migrate
   ```
6. Start the development server:
   ```bash
   python manage.py runserver
   ```

## Features

- Interactive Google Maps interface
- Location search functionality
- Save favorite locations
- Display current location
- Custom markers and info windows

## Note

You need to obtain a Google Maps API key from the Google Cloud Console and enable the following APIs:
- Maps JavaScript API
- Geocoding API
- Places API 