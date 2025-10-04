# Find My Café

A **Next.js + React Leaflet** web app that helps users find nearby cafés. Users can see cafés on the map, view their distance from their location, get addresses, open them in Google Maps, and search for cafés in any city.

---

## 🌟 Features

- **Geolocation-based café search**: Detects the user's current location and shows nearby cafés.
- **Custom map markers**: Different icons for user and cafés.
- **Distance calculation**: Shows distance from user to each café in meters or kilometers.
- **Popups with info**: Displays café name, address, distance, and a link to Google Maps.
- **City search**: Jump to any city and see cafés in that area.
- **Interactive map**: Zoomable and pannable using OpenStreetMap tiles.
- **SSR-safe**: Leaflet dynamically loaded to avoid server-side rendering issues in Next.js.

---

## 🛠 Tech Stack

- **Frontend**: Next.js, React, TypeScript, Tailwind CSS
- **Map & Geolocation**: Leaflet, React-Leaflet
- **Data Source**: OpenStreetMap (Overpass API for cafés), Nominatim API for geocoding
- **Icons**: Custom PNG markers for user and cafés

---

## 🚀 Installation

1. Clone the repo:

```bash
git clone https://github.com/your-username/find-my-cafe.git
cd find-my-cafe
