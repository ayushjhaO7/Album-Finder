A Spotify Album Finder built with React and Vite. Search for any artist and discover their albums.

# How to Run

A beautiful and interactive Spotify Album Finder built with React and Vite. 
Search for any artist and discover their complete discography with stunning visual effects and modern UI design.

React 18.2.0
Vite 5.0.8
Bootstrap 5.3.8

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

   ### Getting Spotify API Credentials

   1. Go to [Spotify Developer Dashboard](https://developer.spotify.com/dashboard)
   2. Create a new app
   3. Copy your Client ID and Client Secret
   4. Add them to your `.env` file

3. **Start the app**
   ```bash
   npm run dev
   ```

4. **Open browser**
   - Go to `http://localhost:5173`



## Tech Stack

- **React:** 18.2.0
- **Vite:** 5.0.8
- **Bootstrap:** 5.3.8
- **Spotify Web API**
- **Frontend Framework:** React 18.2.0
- **Build Tool:** Vite 5.0.8
- **UI Library:** React Bootstrap 2.10.10
- **Styling:** CSS3 with modern animations
- **API:** Spotify Web API
- **Package Manager:** npm

## 🎨 Project Structure

```
Album-Finder/
├── public/
│   ├── codedex-bot-logo.gif
│   └── vite.svg
├── src/
│   ├── assets/
│   │   └── react.svg
│   ├── App.css
│   ├── App.jsx          # Main application component
│   ├── index.css        # Global styles
│   └── main.jsx         # Application entry point
├── .env                 # Environment variables (create this)
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## 🔧 Configuration

### Environment Variables

Create a `.env` file in the root directory with the following variables:

```env
# Spotify API Credentials
VITE_CLIENT_ID=your_spotify_client_id
VITE_CLIENT_SECRET=your_spotify_client_secret
```

**Important:** Never commit your `.env` file to version control!

### Vite Configuration

The project uses Vite for fast development and building. Configuration can be found in `vite.config.js`.

## 🎵 How to Use

1. **Search for an Artist**
   - Type any artist name in the search bar
   - Press Enter or click the Search button

2. **Explore Albums**
   - Browse through the artist's discography
   - View album covers and release dates
   - Click "Album Link" to open in Spotify

3. **Enjoy the Experience**
   - Experience smooth animations and transitions
   - Enjoy the modern, responsive design



**Happy Music Discovery! 🎵✨**
