# Transaction Immo

A web-based real estate portfolio management platform for the Swiss Federal Office for Buildings and Logistics (Bundesamt für Bauten und Logistik - BBL). This platform enables visualization, filtering, and management of federal government properties available for sale across Switzerland.
- Deployed: [davras5.github.io/transaction-immo/](davras5.github.io/transaction-immo/)

<table>
  <tr>
    <td colspan="2" align="center">
      <img src="images/Preview1.jpg" width="90%"/>
    </td>
  </tr>
  <tr>
    <td><img src="images/Preview2.jpg" width="100%"/></td>
    <td><img src="images/Preview3.jpg" width="100%"/></td>
  </tr>
</table>

## Features

- **Three View Modes**: Gallery grid, sortable list table, and interactive Mapbox map
- **Advanced Filtering**: Multi-criteria filtering by priority, canton, property type, year, condition, and more
- **Property Details**: Comprehensive information including specifications, pricing, location ratings, milestone tracking, and document management
- **Real-time Search**: Instant text search across property titles and addresses
- **URL State Persistence**: Shareable filtered views via URL parameters
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices

## Tech Stack

- **Frontend**: Vanilla HTML5, CSS3, JavaScript (ES6+)
- **Mapping**: Mapbox GL JS v3.0.1
- **Icons**: Material Design Icons
- **Data**: JSON

Zero dependencies - no build process required.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/davras5/transaction-immo.git
   cd transaction-immo
   ```

2. Serve the files using any static file server:
   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js (npx)
   npx serve
   ```

3. Open `http://localhost:8000` in your browser

## Project Structure

```
transaction-immo/
├── index.html        # Complete SPA (HTML, CSS, JS embedded)
├── data.json         # Property data
├── switzerland.svg   # Map background asset
└── README.md
```

## License

All rights reserved.
