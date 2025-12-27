# 🚀 Quick Start Guide

Get MusicStream up and running in minutes!

## Step 1: Open the Application

Simply double-click on `sporty.html` to open the main music player application in your default browser.

## Step 2: Access Admin Panel

Double-click on `sportyadmin.html` to access the admin panel for managing songs.

## Step 3: Add Your First Song (Optional)

If you want to add songs to the library:

1. Open `sportyadmin.html`
2. Fill in the song details:
   - Title
   - Artist
   - Genre
   - Duration (format: MM:SS)
   - MP3 file URL
   - Album image URL
3. Click "Simpan Lagu" to save

## Step 4: Start Listening

1. Go back to `sporty.html`
2. Browse the song grid or use the search bar
3. Click on any song to start playing
4. Use the player controls to manage playback

## Important Notes

### Firebase Configuration

The app comes with a default Firebase configuration. For production use:

1. Create your own Firebase project at https://console.firebase.google.com/
2. Enable Realtime Database
3. Copy your Firebase config
4. Replace the `firebaseConfig` object in both HTML files

### Sample URLs

For testing, you can use these sample URLs:

**MP3 Files:**
- Use direct links to MP3 files hosted on cloud storage
- Ensure CORS is enabled on the hosting server

**Images:**
- Use direct links to JPG/PNG images
- Recommended size: 800x800 pixels for album art

## Troubleshooting

**Songs not loading?**
- Check your internet connection
- Verify Firebase configuration
- Check browser console for errors

**Audio not playing?**
- Ensure MP3 URL is accessible
- Check browser's audio permissions
- Try a different browser

## Need Help?

Check the main [README.md](README.md) for detailed documentation.