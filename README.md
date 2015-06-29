<!-- TITLE/ -->

# TIL Reddit Recap

<!-- /TITLE -->


<!-- BADGES/ -->

[![PayPayl donate button](https://img.shields.io/badge/paypal-donate-brightgreen.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=AHVCA49Y9AKNQ&lc=US&item_name=Reddit%20Recap&item_number=redditRecapGithub&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted "Donate once-off to this project using Paypal")
[![Patreon donate button](https://img.shields.io/badge/patreon-donate-orange.svg)](http://patreon.com/redditrecap "Become a patreon contributor")

<!-- /BADGES -->


<!-- DESCRIPTION/ -->

A daily computer generated podcast that takes the top Today I Learned (TIL) posts from Reddit and reads them to you. This was created mostly for personal use, but I've published the podcast for free for everyone who cares to enjoy it.

Feel free to find links to the podcast on [iTunes](https://itunes.apple.com/us/podcast/til-reddit-recap/) or a link to the [XML Feed file](http://sleepybandit.github.io/RedditRecap/TILRedditRecapFeed.xml) itself at the [TIL Reddit Recap Site](http://sleepybandit.github.io/RedditRecap/)

You can also follow the show's [Twitter (bot) account](https://twitter.com/TILRedditRecap)  for all episode and image posts.

<!-- /DESCRIPTION -->

<!-- WHAT/ -->

## What the App Does

This application was written in JavaScript on the NodeJS framework. It completes the following tasks daily:

- Queries Reddit for the top 50 voted TIL posts for the past 24 hours
- Checks each post ID against json log of previously used posts to ensure no reuse occurs
- Generates images with text-overlay for twitter
- Schedules daily image twitter postings with buffer
- Downloads images for later backup
- Cleans the headline text to limit potential error during TTS conversion
- Creates an intro, numerated headlines, and closing scripts for the day's podcast
- Creates a back up of the daily script text in json format
- Creates a show note text file of links to each post on Reddit
- Uses a TTS (text-to-speech) API to create the shows audio files
- Uploads the final podcast MP3 file to Archive.org
- Creates an updated, itunes' supported, XML feed
- Pushes the XML feed changes to the feed file hosted on GitHub
- Creates bitly links and posts them to Twitter
- Conducts internal cleanup and logging for the days tasks
- Backs up daily logs, images, and script files to Google Drive

<!-- /WHAT -->

<!-- MODULES/ -->

## Modules

This application utilizes the following node modules;

- [node-podcast](https://github.com/maxnowack/node-podcast)
- [node-feedparser](https://github.com/danmactough/node-feedparser)
- [retext](https://github.com/wooorm/retext)
- [google-api-nodejs-client](https://github.com/google/google-api-nodejs-client)
- [octokats](https://github.com/philschatz/octokat.js)
- [twit](https://github.com/ttezel/twit)
- [MomentJS-Timezone](http://momentjs.com/timezone/docs/)
- [aws-sdk-js](https://github.com/aws/aws-sdk-js)
- [request](https://github.com/request/request)
- [Snoocore](http://snoocore.readme.io)
- [buffer-node](https://github.com/matthistuff/buffer-node)

<!-- /MODULES -->

For additional information or inquiries, please contact me via email or here on github. Thanks!
