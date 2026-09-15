# 🎵 HITS OF Music

A simple and dynamic **music playlist website** built using **HTML, CSS, and JavaScript**. The website presents a collection of popular songs in a YouTube-inspired card layout.

Each music card displays the song thumbnail, title, artist/channel name, number of views, published time, and video duration.

## 🚀 Features

- 🎧 Dynamic music playlist
- 🖼️ YouTube-style music cards
- 🎵 Song title and artist information
- 👁️ Automatic view-count formatting
- 📅 Automatic calculation of published time
- ⏱️ Video duration display
- 🔗 Direct links to YouTube videos
- ➕ **Show More** functionality
- 🌙 Dark-themed user interface
- 📱 Clean and simple layout

The website initially displays five music cards, and clicking **Show More** loads three additional cards at a time.

## 🛠️ Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript**

HTML is used for the webpage structure, CSS handles the visual design, and JavaScript dynamically generates the music cards and provides the interactive functionality.

## 🎶 Playlist

The project contains songs from several artists, including:

- Jass Manak
- Young Stunners
- Talha Anjum
- Talhah Yunus
- aleemrk
- Taimour Baig
- AUR
- Faris Shafi
- Arijit Singh
- Umair

The song information is stored in a JavaScript array, allowing the playlist data to be easily modified or extended.

## ⚙️ Functionality

### Dynamic Music Cards

The `createCard()` function creates each music card dynamically using the provided song data.

Each card contains:

- Song thumbnail
- Video duration
- Song title
- Channel/artist name
- View count
- Published time
- YouTube URL

The generated card is then inserted into the webpage.

### 📊 View Count Calculator

The project converts large numerical view counts into an easier-to-read format.

For example:

```text
1,872,397,202 → 1.8B views
95,536,895    → 95M views
12,496,413    → 12M views
