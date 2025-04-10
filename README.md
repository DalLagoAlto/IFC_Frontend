# IFC Frontend

Dit is de frontend van het IFC-dashboard project. Hiermee kun je IFC-bestanden uploaden en validatieresultaten bekijken.

## Installatie

1. Navigeer naar de frontend-map:

```bash
cd frontend
```

2. Installeer de dependencies:

```bash
npm install
```

3. Start de ontwikkelserver:

```bash
npm run dev
```

Frontend draait standaard op `http://localhost:5173`.

## Omgevingsvariabelen

Zorg ervoor dat je een `.env` bestand hebt in de root van het project met daarin:

```env
VITE_API_URL=https://jouw-backend-url.up.railway.app
```