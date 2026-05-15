# Digital Clock - Multiple Time Zones

A beautiful, responsive web application that displays the current time in 12 different time zones around the world.

## Features

- ⏰ **Real-time Updates** - Clock updates every second
- 🌍 **12 Major Time Zones** - Displays time in major cities worldwide
- 📅 **Date & Day Information** - Shows full date and day of the week for each timezone
- 📱 **Fully Responsive** - Works perfectly on desktop, tablet, and mobile devices
- 🎨 **Modern UI** - Beautiful gradient background with smooth animations
- ✨ **Interactive Cards** - Hover effects and smooth transitions

## Time Zones Included

1. New York (America/New_York)
2. Los Angeles (America/Los_Angeles)
3. London (Europe/London)
4. Paris (Europe/Paris)
5. Dubai (Asia/Dubai)
6. Tokyo (Asia/Tokyo)
7. Sydney (Australia/Sydney)
8. Singapore (Asia/Singapore)
9. Mumbai (Asia/Kolkata)
10. São Paulo (America/Sao_Paulo)
11. Mexico City (America/Mexico_City)
12. Hong Kong (Asia/Hong_Kong)

## Files

- `index.html` - Main HTML structure
- `styles.css` - Styling and responsive design
- `script.js` - Clock functionality and time zone handling

## How to Use

1. Open `index.html` in any modern web browser
2. The clock will automatically display and update every second
3. All time zones are displayed simultaneously

## Adding More Time Zones

To add more time zones, simply add new entries to the `timeZones` array in `script.js`:

```javascript
const timeZones = [
    { name: 'City Name', timezone: 'Continent/City' },
    // ... more entries
];
```

## Browser Compatibility

Works in all modern browsers that support:
- ES6 JavaScript
- CSS Grid and Flexbox
- Intl.DateTimeFormat API

## License

Open source - feel free to use and modify as needed.