# Bonnekes Dashboard

Een Next.js dashboard voor het beheren van bonnen, gebruikers en rapportages. Dit project gebruikt Supabase voor authenticatie en gegevensbeheer, en `recharts` voor grafieken.

## Installatie

1. **Kloon de repository:**
   ```sh
   git clone https://github.com/YoungGlobal/bonnekes-dashboard.git
   cd bonnekes-dashboard
   ```

2. **Installeer dependencies:**
   ```sh
   npm install
   ```

3. **Maak een `.env.local` bestand aan en voeg je Supabase gegevens toe:**
   ```env
   NEXT_PUBLIC_SUPABASE_URL=https://xyz.supabase.co
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your-anon-key
   ```

4. **Start de development server:**
   ```sh
   npm run dev
   ```

5. **Open [http://localhost:3000](http://localhost:3000) in je browser om het dashboard te bekijken.**

## Functionaliteiten

- **Overzicht van bonnen**
- **Automatische categorisatie van bonnen**
- **Grafieken en rapportages**

## Stack

- **Frontend:** Next.js
- **Backend:** Supabase
- **Grafieken:** recharts
