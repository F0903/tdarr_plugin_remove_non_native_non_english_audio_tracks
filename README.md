# Filter Languages And Set Defaults

A Tdarr flow plugin that removes non-native and non-english audio streams and sets the first native audio track and first english subtitle track to the defaults.

The native language of the media is provided via the Sonarr or Radarr API.

Tested in a library with 1000+ files with 0 errors.

**IMPORTANT NOTE:**  
This REQUIRES you to follow the TRaSH guides naming convention by having the series TVDB id like so: [tvdbid-*id*] in the series root folder. And for movies you need the movie TMDB id in the file name like so: [tmdbid-*id*]

## Installation

The easiest way to install the plugin is to clone the repo locally, and move the plugin subfolder into your Tdarr servers LocalFlowPlugins directoy. Then it just simply appear for you to use in your flows under the "Local" section.
