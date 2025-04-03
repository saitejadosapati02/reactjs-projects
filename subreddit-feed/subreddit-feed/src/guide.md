# 📬 Subreddit Feed

A simple React-based web app that lets users view and explore posts from any subreddit in real-time using Reddit’s public JSON API.

## 🚀 Features

- 🔎 Search for any subreddit dynamically

- 📄 Display subreddit post titles as clickable links

- 🎨 Simple and responsive UI with gradient styling

- ⚛️ Built using React functional components and hooks

## 🛠️ Technologies Used

- React (with Hooks: `useState`, `useEffect`)

- Reddit JSON API

- CSS for styling

## 🖥️ Usage

1. Clone the repository:

   git clone https://github.com/saitejadosapati02/subreddit-feed.git

   cd subreddit-feed

2. Install dependencies
   npm install

3. Start the development server
   npm start

4. Open in browser: Navigate to http://localhost:3000

## How It Works

-The app defaults to the webdev subreddit.

-Users can change the subreddit using the input field.

-On change, fetch() calls Reddit’s JSON API for the new subreddit and updates the feed.

-Each post links directly to its Reddit page.
