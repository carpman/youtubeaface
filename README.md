youtubeaface
============

Command line youtube subscription program.

How does it work?

When you first run the script, it will blow up because you don't have the dependencies installed. Install them.
The second time you run the script, ~/.youtubeaface/config.json and cache.json will be created.
Cache.json is the history of what videos have been downloaded in the past, so they don't get downloaded again.
Config.json is the configuration file, Add the channel name to the channels array (with the name in quotes). 
For example, {'channels': ["eevblog"]}
