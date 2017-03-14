# **Discord Music Bot**
A bot for playing music in voice channels on Discord. 
## General Features
* Play queued songs in voice channels
* Songs can be requested via SoundCloud or YouTube URL's 
* Playlists can be added to the queue (SoundCloud & YouTube)
* Can download SoundCloud users' favorites & add to queue on the fly

## Music Queue Features
* Songs can be added via URLs from SoundCloud or YouTube (ex: ```$queue add https://www.youtube.com/watch?v=HEXWRTEbj1I```). If URL is a playlist then all songs will be added to the queue
* Songs can also be added by entering search terms (ex: ```$queue add what is love```)
* Songs can also be enqueued from saved SoundCloud favorites (ex: ```$queue add jack-belford-1 [ALL]```)
* Queue requests can be followed up with optional flags such as ```--shuffle``` and ```--next``` the former shuffles the list before adding to the queue and the latter tells the bot to add to the top of the queue.
* Multiple requests can also be strung together to quickly get the bot queued up! (ex: ```$queue add https://www.youtube.com/watch?v=HEXWRTEbj1I jack-belford-1 [0,200] --shuffle --next```)

## Requirements
* MongoDB
* YouTube API Key
* SoundCloud API Key
* Discord API Key

## *More detailed README to come..*