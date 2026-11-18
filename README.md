# GoRide – React Ride Hailing App

Full-featured ride-hailing frontend built with **React + Vite + React Router + Bootstrap 5 + Leaflet**.

## Features

- Login / Register / Logout / Profile
- Book ride (login required)
- Real place search (OpenStreetMap Nominatim)
- Real distance & route (OSRM)
- Local vs Inter-state detection + dynamic pricing
- Vehicle types: Bike, Auto, Car
- Full ride flow:
  1. Searching for rider
  2. Rider assigned + notification
  3. Rider arriving → OTP shown
  4. Enter OTP → ride starts
  5. Reach destination → Payment (UPI / Card / Cash)
  6. Success → saved in My Rides
- Notifications center
- My Rides history with stats (Bike/Auto/Car, intercity, total spent)
- Interactive map

## Quick Start

```bash
cd GoRide-React
npm install
npm run dev
```

Open http://localhost:5173

## Demo Login

```
Email:    demo@goride.com
Password: Demo@123
```

## Example locations to try

- Pickup: `MG Road, Bangalore`
- Drop: `Electronic City, Bangalore`  (local)
- Or inter-state: `Bangalore` → `Chennai` / `Hyderabad`

## Tech

- React 18, Vite 5, React Router 6
- Bootstrap 5 + Icons
- Leaflet + React-Leaflet
- Nominatim + OSRM (public APIs)
- localStorage only (no backend)

This is a **frontend demo**. Payments and OTP are simulated.
