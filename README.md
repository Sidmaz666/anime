# Anime
A CLI Tool to Search, Stream & Download Anime from Terminal either using Rofi or FZF(default). The script scrapes Anime from <a href="https://www.anistream.fun"> Anistream </a>.

## Showcasae

<img src="https://github.com/Sidmaz666/anime/blob/main/assets/preview.gif" width="100%">

## Dependencies

1. curl (for scrapping)
2. jq (for decrypting url)
3. sed (for regex)
4. grep (for regex)
5. fzf (for menu)
6. rofi (for menu-optional)
7. mpv  (video-player for streaming anime)
8. cat, head, tail, openssl, awk  

## Installation

You can run the script as usual!
                
       ./anime one piece
       ./anime --rofi

However, if you often watch anime and prefer not to open the browser or would liketo bind the script to a custom <i>keybinding</i>, then run the following command to install <b>Anime </b><i> system-wide</i>

       sudo cp anime /usr/bin/anime
                  
                  
# Usage

     [USAGE]: anime [SEARCH_QUERY]
     anime --rofi To Launch Anime With Rofi
                  By Default Menu is set to FZF	       
    
    Download Directory: $HOME/Documents/Anime

    Essential Dependencies: curl, mpv, sed, grep, awk, cat, head, tail, wc, fzf, curl , jq

    Note: There is No -h, --help Flags associated with the script!

# Misc

- Rofi uses dmenu and gruvbox-dark themes.  
- Select the last option, <b>0. Go to Next Page</b> to scrape more Anime!       



### Licensed under <a href="https://github.com/Sidmaz666/anime/blob/main/LICENSE.md"><b>GPL-3.0</b></a>
