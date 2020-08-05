# PWA Budget Tracker
BootCampSpot Web Development - Week 13 Homework

## Notes on PWA
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Progressive Web Apps are web apps that use emerging web browser
APIs and features along with traditional progressive enhancement strategy to bring a native app-like
user experience to cross-platform web applications like those on mobile phones or tablets. To
implement these strategies, the web application must be served over a secure network (HTTPS), a
service worker must be used to allow offline functionality through asset caching, and a manifest file
is needed to transform the app into an app like format.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Furthermore, a brower database, indexedDB, must be used to store 
data from offline network requests, so that the online network database, Mongo, can be updated once
the app gains a network connection.

## Motive & Action
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In order for the app to work offline, the necessary files will be
cached in the Manifest File so that assets can be loaded from the cache. Also, the service worker will
be set up to store data and data from resulting offline network requests by detecting if there is a 
network connection or not. When there is a connection, the data will be updated on the server's 
database, subsequently using the online API while online.

## Installation
Install `node.js` and run `npm install` to install the necessary node packages.

* Installs:
    - express node package
    - morgan node package
    - mongoose node package
    - compression node package
    - lite-server node package

## Usage
* For local development:
    - Install MongoDB.
    - Run `node server.js` to start the server.
    - Open a web browser and navigate to localhost:3000.
* For use:
    - https://rocky-journey-53934.herokuapp.com/

## Questions
Contact: kevin1choi@gmail.com
