# NewsMag - React News App

NewsMag is a React-based news web application that fetches and displays the latest headlines using the [NewsAPI](https://newsapi.org/). Users can browse news articles across different categories like Technology, Business, Health, Sports, and Entertainment.

## Features

- Fetches real-time news articles from NewsAPI
- Responsive Bootstrap-based UI
- Category-based news filtering
- Dynamic updates without page reload

## Installation and Setup

### Prerequisites
Make sure you have the following installed:
- [Node.js](https://nodejs.org/) (latest LTS recommended)
- npm or yarn

### Clone the Repository
```sh
git clone https://github.com/Remmy4873/news-app

cd news-site
```

### Install Dependencies
```sh
npm install
```

### Set Up API Key
1. Create a `.env` file in the root directory.
2. Add the following line to the file:
   ```sh
   VITE_API_KEY=your_newsapi_key_here
   ```
   Replace `your_newsapi_key_here` with your actual API key from [NewsAPI](https://newsapi.org/).

### Run the Development Server
```sh
npm run dev
```
This will start the application, and you can view it in the browser at `http://localhost:5173/` (or whichever port is assigned).

## Project Structure
```
news-site/
├── src/
│   ├── components/
│   │   ├── Navbar.js
│   │   ├── NewsBoard.js
│   │   ├── NewsItem.js
│   ├── App.js
│   ├── main.js
├── public/
├── .env
├── package.json
├── README.md
```

## Deployment
To build the app for production:
```sh
npm run build
```

You can deploy the `dist/` folder to any static hosting service like Vercel, Netlify, or GitHub Pages.

## License
This project is licensed under the MIT License.

---
Feel free to contribute, suggest improvements, or report issues!

