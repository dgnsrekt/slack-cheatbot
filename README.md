UNDER DEVELOPMENT
# slack-cheat.sh
[![Build Status](https://travis-ci.com/dgnsrekt/slack-cheatbot.svg?branch=master)](https://travis-ci.com/dgnsrekt/slack-cheatbot)
[![Code Style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

cheat.sh bot for slack. http://cheat.sh/
## Config
Evironmental Variables
```
OAUTH_ACCESS_TOKEN
BOT_CHANNEL
BOT_DISPLAY_NAME
TOPICS
TITLE_LINE_NUMBER
```
## Heroku
## Help
```
Usage: /{TOPIC} {SUBTOPIC}
  /python {SUBTOPIC} - Returns a python cheatsheet based on the sub.
  /rust {SUBTOPIC} - Returns a rust cheatsheet based on the sub.
  /linux {SUBTOPIC} - Returns a linux cheatsheet based on the sub.
  /bash {SUBTOPIC} - Returns a bash cheatsheet based on the sub.
  /git {SUBTOPIC} - Returns a git cheatsheet based on the sub.
  
  /help - Shows this message
  /topics - List all searchable topics which can be added to the command list.
  /add {TOPIC} - Adds topic to list of commands. Must be a searchable topic.
  /learn {TOPIC} - Returns a descriptions of the language basics.
  /list {TOPIC} - Returns a list of common cheat sheets from the TOPIC.
  /hello {TOPIC} - Returns information on how to build and run hello world.
  /oneliner {TOPIC} - Returns oneliners from the topcs.
  /weird {TOPIC} - Returns weird things in the language.

Examples:
  /python How do you reverse a list?
  /add haskell

If you are not satisfied with the answer, request the same subtopic again. 
The bot will respond with a new unique cheat sheet variation from the requested subtopic.
```
