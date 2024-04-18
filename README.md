# PWA-web-app-by-Enna
# Overview
This project aims to create a robust text editor application that operates directly within the browser while meeting the standards of a Progressive Web Application (PWA). The text editor will offer seamless functionality for creating, editing, and accessing notes or code snippets, even in offline mode. Leveraging data persistence techniques, such as IndexedDB integration, ensures reliable storage and retrieval of data.

# Features
Offline Functionality: Users can create and access notes or code snippets without an internet connection.

IndexedDB Integration: Utilizes the idb package to store and retrieve data locally, ensuring efficiency and reliability.

Client-Server Architecture: Follows a client-server folder structure, with the backend serving the client.

Webpack Bundling: JavaScript files are bundled using webpack, optimizing performance and facilitating smooth operation.

Next-Gen JavaScript Support: Supports modern JavaScript features for compatibility and seamless functionality.

Installable: Users can install the web application as an icon on their desktop for convenient access.

Service Worker Integration: Registers a service worker for efficient caching of static assets and subsequent pages.

Render Deployment: Deployable to Render using proper build scripts for a webpack application.

# Usage
To run the application:

Clone the repository to your local machine.
Navigate to the root directory and run npm install to install dependencies.
Run npm run start to start the application.
Access the application in your browser and enjoy the seamless editing experience.
Deployment
This application is deployable to Render using the provided Render Deployment Guide. Ensure that the .npmrc file is included in the starter code for proper deployment.

# User Story and Acceptance Criteria
## User Story:
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use

# Acceptance Criteria:

The application should have a client-server folder structure.
Running npm run start should start up the backend and serve the client.
JavaScript files should be bundled using webpack.
Webpack plugins should generate HTML files, service workers, and a manifest file.
The application should function seamlessly with next-gen JavaScript.
IndexedDB should immediately create a database storage upon opening the text editor.
Content entered in the text editor should be saved with IndexedDB when clicking off the DOM window.
Content in the text editor should be retrieved from IndexedDB upon reopening the text editor.
Users should be able to install the web application as an icon on their desktop.
The web application should have a registered service worker using workbox.
Static assets should be pre-cached upon loading, along with subsequent pages and static assets.
Proper build scripts for a webpack application should be included for deployment to Render.
## Conclusion
This project showcases proficiency in web development, data persistence techniques, and Progressive Web Application (PWA) principles. By delivering a reliable and accessible text editor that meets PWA criteria, it demonstrates the ability to create efficient and user-friendly web applications.
## live application
My application deployed on Render https://pwa-web-app-by-enna.onrender.com/

