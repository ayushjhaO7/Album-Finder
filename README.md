# Album Finder

<<<<<<< HEAD
A Spotify Album Finder built with React and Vite. Search for any artist and discover their albums.

## How to Run
=======
A beautiful and interactive Spotify Album Finder built with React and Vite. 
Search for any artist and discover their complete discography with stunning visual effects and modern UI design.

React 18.2.0
Vite 5.0.8
Bootstrap 5.3.8
>>>>>>> 9b4d37d7047748d60345709b10b63627973af2c4

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

<<<<<<< HEAD
- React 18.2.0
- Vite 5.0.8
- Bootstrap 5.3.8
- Spotify Web API
=======
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

## 🚨 Troubleshooting

### Common Issues

**App won't load albums:**
- Check that your Spotify API credentials are correctly set in `.env`
- Ensure your Spotify app is not in "Development Mode" if you want to use it publicly
- Verify your internet connection

**Build errors:**
- Make sure all dependencies are installed: `npm install`
- Check Node.js version (requires 16+)
- Clear node_modules and reinstall if needed

**Styling issues:**
- Ensure Bootstrap is properly imported
- Check browser console for CSS errors

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- [Spotify Web API](https://developer.spotify.com/documentation/web-api/) for music data
- [React](https://reactjs.org/) for the amazing framework
- [Vite](https://vitejs.dev/) for the lightning-fast build tool
- [Bootstrap](https://getbootstrap.com/) for the UI components

## 📞 Support

If you encounter any issues or have questions:

1. Check the [Troubleshooting](#-troubleshooting) section
2. Search existing [Issues](https://github.com/your-username/Album-Finder/issues)
3. Create a new issue with detailed information

---

**Happy Music Discovery! 🎵✨**
>>>>>>> 9b4d37d7047748d60345709b10b63627973af2c4
