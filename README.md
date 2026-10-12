# React Video Player

A YouTube video player built with React.
Videos are loaded from a local data file and grouped into playlists (songs, conferences, trailers) that can be switched from the sidebar.

**Live demo:** <https://video-player.davidebalice.dev/>

![Screenshot](https://www.aroundweb.it/screenshot/video.jpg)

## Features

- Embedded YouTube player
- Multiple playlists with a playlist selector
- Video list with thumbnails and active video highlight
- Video data managed from a single file (`src/data/video.jsx`)
- Responsive layout

## Tech stack

- [React 18](https://react.dev/)
- [Vite](https://vite.dev/)
- [Tailwind CSS 4](https://tailwindcss.com/)
- [React Icons](https://react-icons.github.io/react-icons/)

## Getting started

### Requirements

- Node.js 20 or later
- npm

### Installation

```bash
git clone https://github.com/davidebalice/video-player.git
cd video-player
npm install
```

### Available scripts

| Command           | Description                              |
| ----------------- | ---------------------------------------- |
| `npm run dev`     | Start the development server on port 3000 |
| `npm run build`   | Create a production build in `dist/`     |
| `npm run preview` | Preview the production build locally     |

## Adding videos

Edit `src/data/video.jsx`: add playlists to the `playlist` array and videos to the `video` array, using the YouTube embed URL and the `idPlaylist` of the playlist the video belongs to.

## Author

**Davide Balice** – [davidebalice.dev](https://www.davidebalice.dev)
