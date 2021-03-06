# youtube-dl-mp3

Downloads videos from YouTube and convert them to mp3.

## Installation

Just copy the `youtube-dl-mp3` script to somewhere in your `$PATH` (try /usr/local/bin).

    sudo cp youtube-dl-mp3 /usr/local/bin/

## Requirements
  * [ffmpeg](https://ffmpeg.org/download.html)
  * [youtube-dl](https://github.com/rg3/youtube-dl)

On Ubuntu, these requirements can be installed using this comand:

    sudo apt-get install youtube-dl ffmpeg

On Arch Linux

    sudo pacman -S youtube-dl ffmpeg

On Fedora

    sudo dnf install youtube-dl ffmpeg

Or you can also use pip to install `youtube-dl`

    sudo pip install --upgrade youtube_dl

## Usage

    youtube-dl-mp3 "video-url"

Example:

    youtube-dl-mp3 "http://www.youtube.com/watch?v=0714IbwC3HA"

If `xclip` is installed and `youtube-dl-mp3` is called with no arguments the URL address will be automatically retrieved from clipboard

	# xclip is used to get copied URL from clipboard
	youtube-dl-mp3

You also can download songs from a playlist at once:

    youtube-dl-mp3 --playlist-items 1-16 "https://www.youtube.com/watch?list=PL-kcLKhqCpgT6WwL3p16MvxJFUKv0NRdB"
    

## Bugs and Feedback

If you discover any bugs or have some idea, feel free to create an issue on GitHub:

<https://github.com/jweslley/youtube-dl-mp3/issues>


## License

MIT License. Copyright (c) 2012 [Jonhnny Weslley](<http://www.jonhnnyweslley.net>)
