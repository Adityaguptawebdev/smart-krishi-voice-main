## Smart Krishi Voice

Local development

```sh
npm install
npm run dev
```

Environment variables

- VITE_OPENWEATHER_API_KEY: OpenWeather API key (frontend fallback)
- VITE_SUPABASE_URL, VITE_SUPABASE_PUBLISHABLE_KEY: Supabase client
- OPENWEATHER_API_KEY (Edge Functions secret): for `weather` and `weather-forecast`

Features

- Real-time sensor simulation with manual soil moisture control
- Current weather + 5-day forecast (geolocation first, city fallback)
- AI recommendations and chat assistant
