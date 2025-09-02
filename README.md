# WallpaperOfTheDay
This is a little project of mine that I made because I'm indecisive and don't want to constantly change my wallpaper!

It uses the wonderful work by [Jonah Lawrence](https://github.com/DenverCoder1), who has compiled a list of minimalist wallpapers.

This project works with Wallpaper Engine; however, I don't plan on publishing it there as I don't want to risk overwhelming the API he's built, as it's entirely free!

Some nice features:
- A default wallpaper is the first image loaded. You can customize this by replacing the file `defaultWallpaper.png` with any other image you want
- If the internet connection is not available to pull a wallpaper from the API, it keeps this one loaded to ensure you have something for a wallpaper
- In the background, the wallpaper will keep trying every 2 seconds to fetch the wallpaper
- There's a handy refresh button and status indicator just in case you don't quite like the current wallpaper