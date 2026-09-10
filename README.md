Quote Generator

A lightweight web application that displays a random quote and allows users to share it directly on Twitter.

Live Demo: quote-generator-rosy-six.vercel.app

Overview

Quote Generator is a minimal, dependency-free web app built with plain HTML, CSS, and JavaScript. It retrieves a random quote from a public API on page load and on demand, and provides a one-click option to share the current quote on Twitter.

Features
Fetches a random quote with its author on each request
One-click sharing of the current quote to Twitter
Loading state feedback while a new quote is being fetched
Error handling for failed API requests
No external frameworks or build tools required
Tech Stack
HTML5 — structure
CSS3 — styling
JavaScript (Vanilla) — logic and API calls
DummyJSON Quotes API — quote data source
How It Works
On page load, the application automatically fetches a random quote from the DummyJSON API.
Clicking New Quote disables the button, displays a loading state, fetches a new quote, and updates the displayed text.
Clicking Tweet opens Twitter's intent URL pre-filled with the current quote and author.
Project Structure
Quote-generator/
 index.html      # Markup + inline JavaScript logic
 style.css        # Styling
 .vscode/         # Editor settings
Getting Started
Prerequisites

Just a modern web browser — no installations or dependencies required.

Run Locally
Clone the repository
bash
   git clone https://github.com/ChilukaBinay/Quote-generator.git
Navigate into the project folder
bash
   cd Quote-generator
Open index.html in your browser (or use a tool like the Live Server VS Code extension for auto-reload)
Deployment

This project is deployed on Vercel and can be accessed at: quote-generator-rosy-six.vercel.app

Author

Chiluka Binay GitHub: @ChilukaBinay

License

This project is open source and available for anyone to use and modify.
