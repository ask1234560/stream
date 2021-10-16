# stream
Stream files from your PC.

# Functionalities
* Stream movies, series.
* download streaming contents using youtube-dl
* control functionality using [http shortcuts](https://play.google.com/store/apps/details?id=ch.rmy.android.http_shortcuts&hl=en_IN&gl=US) app

# Installation
* git clone https://github.com/ask1234560/stream
* cd stream
* npm install

# Usage
* Http Shortcuts 
  * install [http shortcuts](https://play.google.com/store/apps/details?id=ch.rmy.android.http_shortcuts&hl=en_IN&gl=US) from playstore
  * use import feature in the app to import shortcuts.json.
* nodemon index.js
* setting path in config.js
  * Movies 
    * file path - config.movie_path 
  * Series 
    * directory path - config.movie_path 
    * default starting episode - config.series_current_ep 
    * blacklist file extensions - config.series_directory_files_blacklist_extensions 
  * Stream and download videos 
    * file path - config.xxx_path 
 
