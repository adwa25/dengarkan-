# 🎵 MusicStream

A modern, responsive music streaming web application built with HTML, CSS, and JavaScript. Features a sleek dark theme, real-time audio playback, and Firebase integration for data management.

## ✨ Features

### Main Application (sporty.html)
- **Music Player**: Full-featured audio player with play/pause, next/previous, shuffle, and repeat controls
- **Progress Bar**: Interactive progress bar with seek functionality
- **Volume Control**: Adjustable volume slider
- **Playlist Management**: Browse and play songs from a dynamic grid
- **Genre Filtering**: Filter songs by genre (Pop, Rock, Jazz, Hip Hop)
- **Search Functionality**: Search songs by title, artist, or genre
- **Favorites System**: Save your favorite songs with local storage
- **Responsive Design**: Fully responsive layout for mobile, tablet, and desktop
- **Modern UI**: Dark theme inspired by Spotify with smooth animations

### Admin Panel (sportyadmin.html)
- **Song Management**: Add, edit, and delete songs
- **Live Preview**: Preview songs before publishing
- **Statistics Dashboard**: Real-time stats for total songs, plays, favorites, and users
- **Search & Filter**: Quick search through song database
- **Modal Confirmations**: Safe delete operations with confirmation dialogs
- **Form Validation**: Client-side validation for all inputs

## 🚀 Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Backend**: Firebase Realtime Database
- **Authentication**: Firebase Auth (integrated)
- **Icons**: Font Awesome 6.4.0
- **Fonts**: Google Fonts (Poppins)
- **Styling**: CSS Variables, Flexbox, Grid Layout

## 📁 Project Structure

```
musicstream/
├── sporty.html          # Main music player application
├── sportyadmin.html     # Admin panel for song management
├── style.css           # Main application styles
├── admin-style.css     # Admin panel styles
├── README.md           # Project documentation
└── .gitignore          # Git ignore rules
```

## 🛠️ Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/musicstream.git
cd musicstream
```

2. **Open the application**
Simply open `sporty.html` in your web browser to view the main application.

3. **Access Admin Panel**
Open `sportyadmin.html` in your web browser to access the admin panel.

## 🔧 Firebase Setup

The application uses Firebase for data storage. To set up your own Firebase instance:

1. Go to [Firebase Console](https://console.firebase.google.com/)
2. Create a new project
3. Enable Realtime Database
4. Create a web app and copy the Firebase configuration
5. Replace the `firebaseConfig` object in both HTML files with your credentials

## 📱 Usage

### For Users
- **Browse Songs**: Scroll through the song grid or use the search bar
- **Play Music**: Click on any song card to start playback
- **Control Playback**: Use the player controls for play/pause, next/previous
- **Adjust Volume**: Use the volume slider in the player header
- **Filter by Genre**: Click genre links in the sidebar
- **Add to Favorites**: Click the heart icon on song cards
- **View Favorites**: Click the "Favorit" button in the header

### For Admins
- **Add Songs**: Fill out the form in the admin panel to add new songs
- **Edit Songs**: Click the edit icon on any song in the table
- **Delete Songs**: Click the delete icon and confirm deletion
- **Preview Songs**: Click the play icon to preview songs
- **View Stats**: Check the dashboard for real-time statistics

## 🎨 Customization

### Colors
Edit the CSS variables in `style.css` or `admin-style.css`:
```css
:root {
    --primary: #1DB954;
    --primary-dark: #1AA34A;
    --dark: #121212;
    --light: #FFFFFF;
    /* ... more variables */
}
```

### Fonts
Change the font family in the CSS files:
```css
body {
    font-family: 'Your-Font', sans-serif;
}
```

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Features in Detail

### Music Player
- Audio visualization with album art
- Time display (current time / total duration)
- Progress bar with click-to-seek
- Shuffle and repeat modes
- Smooth transitions between songs

### Responsive Design
- Mobile-first approach
- Flexible grid layouts
- Touch-friendly controls
- Optimized for all screen sizes

### Data Management
- Real-time sync with Firebase
- Local storage for favorites
- Persistent user preferences
- Automatic data refreshing

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

Created with ❤️ by MusicStream Team

## 🙏 Acknowledgments

- Firebase for the backend services
- Font Awesome for the beautiful icons
- Google Fonts for the typography
- Unsplash for the placeholder images

## 📧 Contact

For support or questions, please open an issue on GitHub.

---

**Note**: Make sure to update the Firebase configuration with your own credentials before deploying to production.