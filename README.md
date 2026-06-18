# AIFAB Flights

A single-page web app that generates one-way flight search deep links across major metasearch engines for any global route.

## Overview

Flight Link Generator builds a date-by-date table of live search URLs for a chosen origin and destination. Instead of manually constructing links on Google Flights, Kayak, Skyscanner, or Expedia, you configure the route once and get ready-to-open links for every day in your selected range.

## How It Works

1. **Configure the search** — Enter departure and destination airports as IATA codes (e.g. `BOS` → `BKK`), pick a starting date, and choose how many days to cover (7, 14, 30, or 31).
2. **Generate the table** — The app produces one row per departure date, showing the day of week and individual links to each metasearch site.
3. **Open searches** — Click a provider link for a specific date, or use **Open All** to launch every engine for that day in separate tabs.

## Supported Search Engines

- Google Flights
- Kayak
- Skyscanner
- Expedia

All generated links are one-way searches only.

## Popular Routes

Quick-select buttons are available for common destinations grouped by region:

- **Eastern Europe** — Warsaw, Prague, Budapest, Bucharest, and others
- **East Asia** — Tokyo, Seoul, Beijing, Hong Kong, Taipei, and others
- **Southeast Asia** — Bangkok, Singapore, Bali, Ho Chi Minh City, and others

Popular routes update dynamically based on the current departure airport.

## Tech Stack

Static HTML with vanilla JavaScript and Tailwind CSS (CDN). No backend or build step required.
