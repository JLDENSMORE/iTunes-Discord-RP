# iTunes Rich Presence for Discord
This is an application that lets you have a personalized Discord status based on what you're listening to on iTunes. The status will show the song name, artist, album name, time elapsed since the track started playing and index of the track in the album. Additionally, an image with a "playing" or "paused" button will be shown in case the track is playing or paused. For some examples, see the [screenshots](#screenshots).

## Features
* Simple to use.
* No in-app login required.
* Lightweight (~1.5MB jar file).
* Same jar file works on both MacOS and Windows.
* Ugly UI.

## Requirements
* **MacOS** / **Windows**.
* A Java Runtime Environment (**JRE**), minimum version: **8**.
* iTunes and Discord applications.
* For Windows users, the application should work for iTunes version 4.7 or later.

## Usage
* Download the *jar* package containing the application and its dependencies [here](https://github.com/kevinmussi/iTunes-Discord-RP/releases/download/v1.0/iTunesDiscordRP-1.0.jar).
* Double click on it (or launch it from the Terminal with `java -jar /path/to/jar`).
* Done!

## Screenshots
### Status preview
![alt](screenshots/status-preview1.png)

### Status while playing
![alt](screenshots/status-playing.png)

### Status while paused
![alt](screenshots/status-paused.png)

### Status with long names
![alt](screenshots/status-playing-shortened.png)

## To-dos
* Javadocs.
* Unit tests.
* Spotify integration (easy but rather useless).
* Command line only interface.
* Translation to native language (Objective-C/Swift).

## Acknowledgements
* [DiscordIPC](https://github.com/jagrosh/DiscordIPC) by @jagrosh.

## Disclaimer
iTunes is a trademark of Apple Inc., registered in the U.S. and other countries.\
This application has not been authorized, sponsored, or otherwise approved by Apple Inc.
