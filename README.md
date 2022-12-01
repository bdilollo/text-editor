# text-editor

GIVEN a text editor web application

<!-- WHEN I open my application in my editor
THEN I should see a client server folder structure -->

WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
<!-- use concurrently and add script in package.json -->

WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
<!-- create webpack.config.js -->

WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
<!-- modify webpack.config.js (need to refresh on how) -->

WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
<!-- add babel to webpack.config.js -->

WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
<!-- need to refresh on IndexedDB -->

WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
<!-- again, need to refresh on IndexedDB, but should use those chained methods from activity -->

WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
<!-- need IndexedDB refresh -->

WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
<!-- need manifest.json - generated in webpack.config? -->

WHEN I load my web application
THEN I should have a registered service worker using workbox
<!-- register service worker -->

WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
<!-- modify webpack.config.js for service worker -->

WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application