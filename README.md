# Anime-no-Kura

Anime Vault is a web application that allows users to explore and discover their anime details. The application fetches anime data from the Shikimori API and displays it in a user-friendly interface.

## Features

- Display a list of popular anime
- Infinite scrolling to load more anime as the user scrolls down
- Detailed anime cards with images, titles, and additional information
- Responsive design for mobile and desktop views

## Technologies Used

- React
- Next.js
- Tailwind CSS
- Shikimori API
- Intersection Observer API

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Dakshesh1234/Anime-no-Kura.git
```

2. Navigate to the project directory:

```bash
cd anime-vault
```

3. Install the dependencies:

```bash
npm install
```

## Usage

1. Start the development server:

```bash
npm run dev
```

2. Open your browser and visit `http://localhost:3000` to see the application in action.

## Project Structure

- `pages/`: Contains the main pages of the application
- `components/`: Contains the UI components used throughout the application
- `styles/`: Contains the global CSS files
- `lib/`: Contains utility functions
- `public/`: Contains static assets such as images

## Components

### AnimeCard

Displays individual anime details including the image, title, type, number of episodes, and score.

### LoadMore

Handles infinite scrolling and fetching additional anime data when the user scrolls to the bottom of the page.

### Badge

A reusable component to display different types of badges.

### Card

A reusable card component to display content in a card format.

## API

This application uses the Shikimori API to fetch anime data. 

## Contributing

1. Fork the repository.
2. Create a new branch:

```bash
git checkout -b feature-branch
```

3. Make your changes and commit them:

```bash
git commit -m 'Add some feature'
```

4. Push to the branch:

```bash
git push origin feature-branch
```

## Acknowledgements

- [Shikimori API](https://shikimori.one/api/doc)
- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Lucide Icons](https://lucide.dev/)

---

Feel free to customize this README file further based on your project's specific details and requirements.
