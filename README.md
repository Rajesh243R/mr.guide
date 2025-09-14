# Incredible India Tours App

This is a comprehensive single-page web application designed to help users explore India’s diverse destinations, plan trips, and manage bookings. Built with HTML, Tailwind CSS, and vanilla JavaScript, it features location selection, destination details, trip planning, hotel booking, map integration, and offline/PWA capabilities.

---

## Features

- **Location Selection:** Choose your state and city to personalize experience.
- **User Authentication:** Login and register to manage bookings.
- **Home Dashboard:** Highlights destinations, stats, and regional exploration.
- **Destination Details:** Rich info about famous places with attractions, cuisine, tips.
- **Trip Planning:** Select travel modes, durations, hotels, and customize trips.
- **Booking Management:** View, modify, and track bookings with real-time updates.
- **Interactive Map:** Visualize trips and destinations on an SVG map of India.
- **Offline & PWA Support:** Install as app, offline caching, notifications.
- **Responsive Design:** Mobile-friendly with Tailwind CSS.

---

## Getting Started

### Usage

Open `index.html` in your web browser. The app supports desktop and mobile devices.

### Installation & PWA

- To install as a Progressive Web App, click the install prompt or follow browser instructions.
- Offline support is enabled via Service Worker registration.

---

## Features Breakdown

### Location & Preferences
- Select your state and city to get personalized suggestions.
- Location stored in `userLocation`.

### User Authentication
- Simple login/register system stored in session.
- Login required for booking features.

### Destination Exploration
- Browse destinations by region.
- View detailed info, attractions, food, tips.

### Trip Planning
- Choose travel mode (flight, train, bus, own).
- Select duration (fixed or custom dates).
- Pick hotels from categorized options.
- View cost breakdown.

### Bookings & Management
- Book trips, view confirmation.
- Manage bookings, see statuses.
- Real-time updates every 30 seconds.
- Map view of bookings with SVG markers.

### Map & Navigation
- SVG map of India with interactive region markers.
- View region bookings, explore on Google Maps.

### Notifications & Offline
- Browser notifications for updates.
- Offline caching with Service Worker.
- PWA installation prompt.

---

## Customization & Extensibility

The code is modular, with data structures for places, hotels, costs, and itineraries. You can extend destinations, add new hotels, or customize trip options as needed.

---

## License

This project is for educational and planning demonstration purposes. Feel free to customize and deploy.

---

## Contact

For questions or support, contact: support@indiatours.com

---

## Note

This is a full static prototype. For production, integrate with backend services for user data, bookings, payments, and real-time updates.

---

Enjoy exploring India with the Incredible India Tours App!
