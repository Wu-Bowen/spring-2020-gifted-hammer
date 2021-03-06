# Spotilytics
[![Build Status](https://travis-ci.com/nyu-software-engineering/spring-2020-gifted-hammer.svg?branch=master)](https://travis-ci.com/nyu-software-engineering/spring-2020-gifted-hammer)

## Overview
In the age of streaming, sifting through new music can be overwhelming at times. You have to jump from
service to service listening to music you might not enjoy. Spotilytics seeks to make it easier to discover music you love. Spotilytics will bridge the gap between services and introduce exciting new ways to discover music.

## Vision
Spotilytics will combine music from multiple services and present related info such as user reviews and comments. It will also include advanced sentiment and musical analysis tools to determine user preference and mood. User input together with advanced track analytics will form the basis of Spotilytics's powerful music recomendation alogrithim. Spotilytic's main features will be its reccomendations, social features (reviewing, posting,sharing) and it's abilty to combine music from multiple sources.

## Target Features
  * Mood & Sentiment analysis
  * Musical analysis
  * Powerful Recomendations & Filters
  * Review Sourcing
  * Service independent playlists
  * Social Features

## Prototype
https://invis.io/M6W6PEZ7D93

## Contributing
If you would like to contribute to this project please see our [contributing rules](./CONTRIBUTING.md)

## Running the Project:
1. Starting Backend
    - `cd` into 'backend' directory
    - Run `$ npm install` to get all necessary modules
    - MacOS/Linux:
        - Run `$ pip3 install -r requirements.txt` to get python modules necessary for face analyzation 
    - Windows:
        - Run `$ python -m pip install -U pip setuptools`
        - Run `$ pip3 install -r requirements.txt` to get python modules necessary for face analyzation 

    - Run `$ node server.js`

2. Starting Frontend
    - `cd` into 'frontend' directory
    - Run `$ npm install` to get all necessary modules
    - Run `$ npm start`
    - Navigate to 'localhost:3000' in your browser

