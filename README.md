# FoodRoute - Backend API

## Application Database

**Application DB Connection String:** `postgresql://db_appdb_6a1717a7c3789abeb290aa29_user:Oqd%25%21H2%40MX696HH9v5oilFWg%40lNBD6KU@ep-broad-block-aqfm6yza.c-8.us-east-1.aws.neon.tech:5432/AppDB_6a1717a7c3789abeb290aa29?sslmode=require`

**Swagger API Tester URL:** /swagger

## Google APIs (Gemini, Maps, Speech-to-Text)

The backend can use a Google API key provided via the **GOOGLE_API_KEY** environment variable (set on Railway). Use it for Gemini LLM, Maps, and Speech-to-Text. Check **GET /api/google/status** and **GET /api/google/health** to verify the key is set and reachable.

## Recommended Tools

**Recommended SQL Editor tool (Free):** [pgAdmin](https://www.pgadmin.org/download/)

## Deployment

This backend is configured for Railway deployment using nixpacks.toml.
