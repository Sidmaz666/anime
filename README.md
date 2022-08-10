# Anime
A CLI Tool to Search, Stream & Download Anime from Terminal either using Rofi or FZF(default). The script uses <a href="https://github.com/Sidmaz666/aniswim-api"> Aniswim-API </a>.

## Showcasae

<img src="https://github.com/Sidmaz666/anime/blob/main/assets/preview.gif" width="100%">

## Dependencies

1. curl (HTTP Request)
2. jq (JSON Parsing)
3. fzf (Default menu)
4. rofi (Menu Optional)
5. mpv (Video player)
6. ffmpeg (For Download)
7. Core GNU Utils (cat, head, tail, awk, sed, grep)  

## Installation

You can run the script as usual!
                
       ./anime one piece
       ./anime --rofi
       ./anime -l
       ./anime -r

However, if you often watch anime and prefer not to open the browser or would liketo bind the script to a custom <i>keybinding</i>, then run the following command to install <b>Anime </b><i> system-wide</i>

       sudo cp anime /usr/bin/anime
                  
                  
# Usage

     [USAGE]: anime [SEARCH_QUERY]
     anime --rofi To Launch Anime With Rofi
                  By Default Menu is set to FZF	       

     anime -l To Fetch All the Latest Anime

     anime -r To Fetch New Released/Recent Anime
    
    Download Directory: $HOME/Documents/Anime

    Note: There is No -h, --help Flags associated with the script!

# Misc

- Rofi uses dmenu and gruvbox-dark themes.  
- Select the last option, <b>0. Go to Next Page</b> to scrape more Anime!       


### Licensed under <a href="https://github.com/Sidmaz666/anime/blob/main/LICENSE.md"><b>GPL-3.0</b></a>
