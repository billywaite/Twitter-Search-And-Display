# Twitter-Search & Display

Twitter search &amp; display app built with Node, LokiJS, EJS templating, and Twitter's search API. The form uses jQuery to send an AJAX request to a node application, and this AJAX request is made to the api/results route and returns a JSON response. The front end javascript takes care of displaying the data.

## To deploy:
1. Clone to your machine.
2. Run NPM Install to install the node modules.
3. Register the app with Twitter to get API credentials here: https://apps.twitter.com/ - Store consumer key, consumer secret, access token key, and access token secret in the main directory in .env file.
4. Create db.json file in the main directory as well.
4. Run node main.js and visit localhost:8080