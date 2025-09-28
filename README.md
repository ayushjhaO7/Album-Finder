# Album Finder

A Spotify Album Finder built with React and Vite. Search for any artist and discover their albums.

## How to Run

1. **Install dependencies**
   ```bash
   npm install
   ```

2. **Set up Spotify API**
   - Create a `.env` file in the root directory
   - Add your Spotify credentials:
   ```
   VITE_CLIENT_ID=your_spotify_client_id
   VITE_CLIENT_SECRET=your_spotify_client_secret
   ```

3. **Start the app**
   ```bash
   npm run dev
   ```

4. **Open browser**
   - Go to `http://localhost:5173`

## Getting Spotify API Credentials

1. Go to [Spotify Developer Dashboard](https://developer.spotify.com/dashboard)
2. Create a new app
3. Copy your Client ID and Client Secret
4. Add them to your `.env` file

## Tech Stack

- React 18.2.0
- Vite 5.0.8
- Bootstrap 5.3.8
- Spotify Web API