# liri-node-app

LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.

### Before You Begin

1. Clone the repository.

2. Navigate to root folder and run `npm init` to initialize a package.json.

3. To retrieve the data that will power this app, you'll need to send requests to the Twitter, Spotify and OMDB APIs. Install these Node packages:

    * [Twitter](https://www.npmjs.com/package/twitter)
   
    * [Node-Spotify-API](https://www.npmjs.com/package/node-spotify-api)
   
    * [Request](https://www.npmjs.com/package/request)

    * [OMDB API](http://www.omdbapi.com)

    * [DotEnv](https://www.npmjs.com/package/dotenv) `npm i dotenv`

    * [Inquirer](https://www.npmjs.com/package/inquirer) - command line user interface. `npm i inquirer`


4. To run the app you need your own `.env`, replacing the values below with your own API keys (no quotes) once you have them. To get API keys, create developer accounts with Spotify and Twitter (and an accompanying Twitter user account to read tweets from). Then add keys into `.env` file.

```js

# Spotify API keys

SPOTIFY_ID=your-spotify-id
SPOTIFY_SECRET=your-spotify-secret

# Twitter API keys

TWITTER_CONSUMER_KEY=your-twitter-consumer-key
TWITTER_CONSUMER_SECRET=your-twitter-consumer-secret
TWITTER_ACCESS_TOKEN_KEY=your-access-token-key
TWITTER_ACCESS_TOKEN_SECRET=your-twitter-access-token-secret

```

### Running Liri

1. Run you local server.

2. Type `node liri` to run application.

3. Choose on of the options presented to you.


### Known Issues

1. I cannot get the "See Tweets" option to re-prompt the user. This requires you to type `node liri` to run again.

2. Liri wasn't working when run on Nodemon.


### Creator

* https://github.com/WilliamBork33

* http://www.williambork.com/


### Forked From User:
* https://github.com/jorgedelgado24