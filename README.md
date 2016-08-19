# gameshelf-bgg-edition
An implementation of GameShelf's Amazon Alexa integration for Board Game Geek.

## Overview
Katherine Bedell's [GameShelf](https://github.com/kbedell/gameshelf) is a Rails-based web application that allows users to track the board games they own. In addition to its web interface, GameShelf utilizes a custom Amazon Alexa Skill that allows users to ask an Amazon Echo, Tap, or Dot for a random game based on the number of players they have.

This implementation eliminates the web application and instead hooks in to version 2 of the [Board Game Geek XML API](https://boardgamegeek.com/wiki/page/BGG_XML_API2) for game tracking.
