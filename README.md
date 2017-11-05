# VLC-Radio Python script

- 11/4/17 edit, the channel I uploaded the video example on was deactivated. I'm setting up a dedicated PC to stream 24/7, and will post a new example once the stream is online again .ETA 1 week max.  

This is a python script I built for streaming music using VLC media player. This script will read metadata from VLC media player for the song's title, album, artist, year released, genre, and album artwork. The album art will be automatically resized, and copied to the location of a folder specified in the script whenever a new song is played.

To change where the album artwork is saved, change the 'dst' variable on line 6 of the file. To change where the text file of song info is save, change the 'save_path' variable on line 8 of the program.

You can see a working example here: https://www.youtube.com/watch?v=zVGp3FmGGlw&t=21928s I used OBS studio for broadcasting, and set it up to display the jpg titled art.jpg in a folder, as well as display the contents of a specific text file. The album art and text file are automatically updated when their contents are changed.

# VLC Setup
To setup VLC Media Player, you will need to enable an online connection. You can find instructions on how to do so in this post:
https://stackoverflow.com/questions/24178980/how-to-monitor-vlc-media-player-on-windows-7-using-python
