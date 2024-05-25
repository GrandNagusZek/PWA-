# PWA-

## Description

This project is a Progressive Web App (PWA) text editor that runs in the browser. It is designed as a single-page application (SPA), ensuring a seamless offline experience and data persistence through various techniques. The application uses IndexedDB for data storage, facilitated by the idb package, providing robust methods for data management. This project aims to demonstrate the capabilities of PWAs and IndexedDB in creating reliable, offline-capable web applications.

## Features

* Progressive Web App: Installable and offline-capable application.
* Single-Page Application: Seamless user experience without page reloads.
* IndexedDB: Data persistence using the idb package, a lightweight wrapper around the IndexedDB API.
* Offline Functionality: Full functionality even when the user is offline.
* Data Redundancy: Multiple data persistence techniques to ensure reliability across different browsers.

## Technologies Used

* JavaScript: Core programming language.
* HTML/CSS: Markup and styling.
* Webpack: Module bundler.
* Babel: JavaScript compiler.
* idb: Lightweight wrapper for IndexedDB.
* Service Worker: Offline capability and caching.
* Workbox: Library for service worker and caching strategies.


## Installation

1. Clone the repository: https://github.com/GrandNagusZek/PWA-.git

2. Install dependencies: npm install

3. Build the project: npm run build

4. Start the development server: npm start

5. Open the application: 
    * Navigate to 'http://localhost:3000' in your browser.


## Usage 

* Writing and Editing: Use the text editor to write and edit text. Your changes will be automatically saved using IndexedDB.
* Offline Access: The app will function offline, allowing you to continue editing without an internet connection.
* Installation: Install the PWA on your device for a native app-like experience.


## Contributing

Contributions are welcome! Please fork the repository and use a feature branch. Pull requests are warmly welcome.


## License

This project is open source and available under the MIT License.