# Kartik Time and Location Project

## Project overview
A live clock that combines the current date, an interactive map, location search, draggable marker selection, WorldTimeAPI timezone lookup, and browser fallback time.

## Run in VS Code
1. Open `college-mini-project` in VS Code.
2. Open `kartik/digital-clock.html`.
3. Install Live Server.
4. Right-click the file and select **Open with Live Server**.
5. Search a place or select a location on the map.

No API key is required.

## Copy the project
1. Create a folder named `kartik`.
2. Create `digital-clock.html`.
3. Copy all code from the repository file.
4. Paste, save, and open it with Live Server.

## Technologies
- HTML for structure
- CSS for layout and responsive design
- JavaScript for clock and API logic
- Leaflet for the map
- OpenStreetMap for map tiles
- Nominatim for search and reverse geocoding
- WorldTimeAPI for timezone time

## APIs used
**Leaflet CDN:** loads the map library.
**OpenStreetMap:** supplies map tiles.
**Nominatim:** converts place names to coordinates and coordinates to addresses.
**WorldTimeAPI:** supplies timezone and location time. It is free and open and does not require an API key.

Example:
`https://worldtimeapi.org/api/timezone/Asia/Kolkata`

## How it works
1. Leaflet creates the map and marker.
2. Map click or drag events provide coordinates.
3. Nominatim reverse-geocoding finds the address.
4. Nominatim geocoding finds coordinates from a searched place.
5. The country and city help select an IANA timezone.
6. WorldTimeAPI returns timezone data.
7. `setInterval()` updates the clock every second.
8. Browser time formatting is used if the network API fails.

## Viva questions

**Q1. What is Leaflet?**
Leaflet is an open-source JavaScript library for interactive maps.

**Q2. What is Nominatim?**
Nominatim is an OpenStreetMap geocoding and reverse-geocoding service.

**Q3. What is geocoding?**
Converting a place name or address into latitude and longitude.

**Q4. What is reverse geocoding?**
Converting latitude and longitude into a readable address.

**Q5. What is WorldTimeAPI?**
It is a free open-source HTTP API that provides current time and timezone information.

**Q6. Does it need an API key?**
No. Kartik's project uses WorldTimeAPI without an API key.

**Q7. What is an IANA timezone?**
An IANA timezone is a timezone identifier such as `Asia/Kolkata` or `Europe/London`.

**Q8. What happens if WorldTimeAPI fails?**
The project uses browser timezone formatting as a fallback.

**Q9. What does `setInterval()` do?**
It runs the clock update function every 1000 milliseconds.

**Q10. What is CORS?**
CORS is a browser security mechanism that controls whether a website may read a response from another domain.
