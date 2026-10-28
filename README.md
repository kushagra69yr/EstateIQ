# EstateIQ — Real Estate, Intelligently

EstateIQ is a responsive real-estate discovery and property comparison **portfolio demo**. It is built with plain HTML, CSS, and JavaScript so it can be hosted as a static GitHub Pages website.

## Features
- Search demo properties by city/neighbourhood
- Filter by property type, budget, and bedroom count
- Save/unsave favourites during the current browser session
- Select up to three properties and compare their displayed features
- Explore an illustrative property price estimate using property details
- Responsive layout for desktop and mobile

## Live demo
Once GitHub Pages is enabled for this repository, the expected URL is:

https://kushagra69yr.github.io/EstateIQ/

## Run locally
Open `index.html` in a browser. Internet access is needed for the Unsplash property photography.

## Important limitations
- The property listings and their prices are sample/demo data, not verified live listings.
- Favourites are stored only in page memory and reset when the page is refreshed.
- The price estimator is a transparent rule-based illustration. It is **not a trained machine-learning model**, not a professional valuation, and not financial advice.
- This repository currently has no database, authentication, real-estate API, or deployed backend.

## Suggested next steps
1. Add a backend API (for example, FastAPI) and a database (for example, PostgreSQL).
2. Replace sample listings with a trusted, licensed data source.
3. Train and evaluate a model using reliable local property-sale data before describing the estimator as ML.
4. Add automated tests, accessibility checks, and error handling.
5. Add privacy-conscious authentication and persistent favourites if needed.

## Tech stack
- HTML5
- CSS3
- Vanilla JavaScript
- Unsplash image URLs for demo photography
