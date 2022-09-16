# ffmpeg tools

## How to Compile ffmpeg

Enabled features
* nvidia cuda 
* srt streaming
* blackmagic decklink

Make sure git is installed

`$ sudo apt install git`

Clone repository and copy to ~/bin

`$ cd ~ && git clone https://github.com/jdmartins/ffmpeg-tools.git && cd ffmpeg-tools && mkdir -p ~/bin && cp build-ffmpeg ~/bin && sudo chmod +x build-ffmpeg`

Run build ffmpeg script and follow the instructions

`$ sudo -E build-ffmpeg`