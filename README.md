# 🎵 Album Finder

A beautiful and interactive Spotify Album Finder built with React and Vite. Search for any artist and discover their complete discography with stunning visual effects and modern UI design.

![Album Finder Demo](https://img.shields.io/badge/React-18.2.0-blue) ![Vite](https://img.shields.io/badge/Vite-5.0.8-646CFF) ![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.8-7952B3)

## ✨ Features

- 🎨 **Stunning Visual Design** - Modern glassmorphism UI with animated backgrounds
- 🔍 **Artist Search** - Find any artist and explore their complete discography
- 🎵 **Album Discovery** - View album covers, release dates, and direct Spotify links
- 📱 **Responsive Design** - Works perfectly on desktop and mobile devices
- ⚡ **Fast Performance** - Built with Vite for lightning-fast development and builds
- 🎭 **Interactive Animations** - Smooth transitions and hover effects

## 🚀 Quick Start

### Prerequisites

- **Node.js** (version 16 or higher)
- **npm** or **yarn**
- **Spotify Developer Account** (for API access)

### Installation

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd Album-Finder
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up Spotify API credentials**
   
   Create a `.env` file in the root directory:
   ```bash
   # .env
   VITE_CLIENT_ID=your_spotify_client_id_here
   VITE_CLIENT_SECRET=your_spotify_client_secret_here
   ```

   **How to get Spotify API credentials:**
   - Go to [Spotify Developer Dashboard](https://developer.spotify.com/dashboard)
   - Click "Create App"
   - Fill in app details (name, description)
   - Copy your **Client ID** and **Client Secret**
   - Add them to your `.env` file

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   - Navigate to `http://localhost:5173`
   - Start searching for your favorite artists! 🎵

## 📋 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build |
| `npm run lint` | Run ESLint for code quality |

## 🛠️ Tech Stack

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