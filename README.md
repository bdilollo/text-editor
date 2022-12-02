# Text Editor


[![](https://img.shields.io/static/v1?label=License&message=MIT&color=<yellow>)](https://opensource.org/licenses/MIT)


## Description
This repo contains an application that functions as a text editor. It utilizes webpack to configure a progressive web application, bundling and serving an optimized codebase while also offering the possibility to install and use offline. A service worker precaches assets and retrieves them upon page load, and indexedDB is used to store persistent data on the browser.

---

## Installation
The repo contains a package.json with the necessary dependencies. Run ```npm install``` in terminal to install dependencies. It also has several scripts  Run ```npm start``` to run the build on the client side and launch the server, then navigate to the appropriate URL to use the application.

---

## Usage
Simply type into the text editor--the application will store the contents. Navigate away from the page and come back later to resume--the content will persist. Click the 'Install' button in the top-left corner to install the application, then use it on or offline.

---

## Technologies Used
- Node.js
- Webpack
- IndexedDB
- Babel
- Express

---

## Contact
[LinkedIn](https://www.linkedin.com/in/bradley-dilollo/)  
[GitHub](https://github.com/bdilollo)