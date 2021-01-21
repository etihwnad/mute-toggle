# zoom-toggle
Toggle Zoom, Meet, etc audio and video mute state in Linux.

# Usage

$ zoom-toggle [-v|v] [-a|a]

Find the active chat application and toggle the audio and/or video state on/off.

With no arguments, it defaults to toggling audio only.

* Zoom via window name "Zoom Meeting"
* Google Meet via window name prefix "Meet - ".  Note: this only works when the browser tab is active in its window.

# Installation
Make the script executable (`chmod +x zoom-toggle`) and either place in a directory in your $PATH or run from its current location (`./zoom-toggle`).


## Requirements

* `xdotool`

On Ubuntu (tested on Kubuntu 20.04 LTS):

`sudo apt install xdotool`