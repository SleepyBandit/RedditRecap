<!-- TITLE/ -->

# TIL Reddit Recap

<!-- /TITLE -->


<!-- BADGES/ -->

[![PayPayl donate button](https://img.shields.io/badge/paypal-donate-brightgreen.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=AHVCA49Y9AKNQ&lc=US&item_name=Reddit%20Recap&item_number=redditRecapGithub&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted "Donate once-off to this project using Paypal")
[![BitCoin donate button](https://img.shields.io/badge/patreon-donate-orange.svg)](https://coinbase.com/checkouts/9ef59f5479eec1d97d63382c9ebcb93a "Become a patreon contributor")

<!-- /BADGES -->


<!-- DESCRIPTION/ -->

A daily computer generated podcast that takes the top Today I Learned (TIL) posts from Reddit and reads them to you. This was created mostly for personal use, but I've published the podcast for free for everyone who cares to enjoy it.

Feel free to find links to the podcast on itunes or a link to the [XML Feed file](http://sleepybandit.github.io/RedditRecap/TILRedditRecapFeed.xml) itself at the [TIL Reddit Recap Site](http://sleepybandit.github.io/RedditRecap/)

<!-- /DESCRIPTION -->

<!-- WHAT/ -->

## What the App Does

This application was written in JavaScript on the NodeJS framework. It completes the following tasks daily:

- Queries Reddit for the top 25 voted TIL posts for the past 24 hours
- Cleans the headline text to limit potential error during TTS conversion
- Creates an intro, numerated headlines, and closing scripts for the day's podcast
- Creates a back up of the daily script text in json format
- Creates a show note text file of links to each post on Reddit
- Uses a TTS (text-to-speech) API to create the shows audio files
- Uploads the final podcast MP3 file to Archive.org
- Creates an updated, itunes' supported, XML feed
- Pushes the XML feed changes to the feed file hosted on GitHub
- Conducts internal cleanup and logging for the days tasks
- Backs up daily logs and script files to Google Drive

<!-- /WHAT -->

<!-- MODULES/ -->

## Modules

This application utilizes the following node modules;

- [node-podcast](https://github.com/maxnowack/node-podcast)
- [node-feedparser](https://github.com/danmactough/node-feedparser)
- [retext](https://github.com/wooorm/retext)
- [google-api-nodejs-client](https://github.com/google/google-api-nodejs-client)
- [octokats](https://github.com/philschatz/octokat.js)
- [MomentJS-Timezone](http://momentjs.com/timezone/docs/)
- [aws-sdk-js](https://github.com/aws/aws-sdk-js)
- [request](https://github.com/request/request)

<!-- /MODULES -->

More information pretaining to this application will be released in the future.
