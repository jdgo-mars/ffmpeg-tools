# ffmpeg tools

## How to Compile ffmpeg

Enabled features
* nvidia cuda 
* srt streaming
* blackmagic decklink

Make sure git is installed

`$ sudo apt install git`

Clone repository and copy to ~/bin

`$ cd ~ && git clone https://github.com/jdmartins/ffmpeg-tools.git && cd ffmpeg-tools && sudo chmod +x build-ffmpeg`

Before compiling you can set software versions by changing directly on the script
Currently we are compiling:
- srt version: 1.5.0
- ffmepg version: 5.1.1


Run build ffmpeg script and follow the instructions

`$ sudo -E ./build-ffmpeg`