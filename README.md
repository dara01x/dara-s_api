# Wild Horizons API

A dataset API for the planet's most interesting places.

## Endpoints

- `GET /api` - Get all destinations (supports query parameters for filtering)
- `GET /api/continent/{continent}` - Get destinations by continent
- `GET /api/country/{country}` - Get destinations by country

## Query Parameters

- `name` - Filter by destination name
- `location` - Filter by location
- `country` - Filter by country
- `continent` - Filter by continent
- `is_open_to_public` - Filter by public accessibility (true/false)

## Example Usage

```
GET /api?continent=Europe&is_open_to_public=true
GET /api/continent/Asia
GET /api/country/USA
```

## Live API

This API is deployed on Vercel. Once you share your deployment URL, you can test these endpoints:

- `GET /api` - Get all destinations
- `GET /api/continent/{continent}` - Get destinations by continent  
- `GET /api/country/{country}` - Get destinations by country

## Deployment

This API is deployed using Vercel for free hosting with automatic deployments from GitHub.
