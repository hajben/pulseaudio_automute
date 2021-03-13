# pulseaudio_automute
An automatic mute script for PulseAudio

I've created this script because my laptop speaker was buzzing when idle during charging.

The script uses pacmd, pactl, awk and grep to mute the speakers when there are no audio streams and turns it back on (within 0.1 s) when it detects a running audio stream.

There is also a toggle script which can be easily set as a shortcut if you want to turn on/off the script (e.g. to mute the audio). For this to work, the script must be in your PATH.
