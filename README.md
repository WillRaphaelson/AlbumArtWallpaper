# AlbumArtWallpaper
Set album art of currently playing song on spotify as your Desktop Wallpaper.

# Installation:
Clone the repo, and `pip install -r requirements.txt`

# Usage:

First open a developer aaccount on Spotify. Create a new project, then get client-id and secret to add to a config.py file. In settings menu of your project add a redirect-uri (http://localhost/callback can also be used). 
        
Then `python3 AlbumArtWallpaper.py`

# Limitations:
Works for a linux and Mac, need to add support for Windows.
