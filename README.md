pokeymusic
=====

This is a music player for the POKEY chip on Atari 8-bit systems.

It can play 4 voices simultaneously, but this requires configuring the POKEY to use 8-bit frequency divisors.
This reduces the pitch resolution, so to play in tune we must rapidly switch the divisor between two adjacent values every video frame.

This is similar to an approach we used on the [Atari 2600](https://8bitworkshop.com/v3.10.0/?platform=vcs&file=examples%2Ffracpitch.a).

[Open this project in 8bitworkshop](http://8bitworkshop.com/redir.html?platform=atari8-800&githubURL=https%3A%2F%2Fgithub.com%2Fsehugg%2Fpokeymusic&file=testmusic.c).
