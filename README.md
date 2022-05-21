# mp3search
Code for searching for mp3s from open file servers on Google using Firefox

This Perl script searches Google using Firefox for mp3 (or wma or ogg) directories with the string given in arguments (use quotes). The syntax is just `mp3search "songname"`. You can then just use `wget -r -np "http://url.example/directory"` to get whole albums this way.
