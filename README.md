# chronological-m3u

Generates .m3u playlists for a given list of artists.

Usage is `playlist discography_list.txt /playlist/directory`, where discography_list is a newline-delimited list of artist names you want playlists for, and `/playlist/directory` is where you want to move the m3u files to after creation. If you don't want to move any files, you can omit this argument.
Path search is limited to the current working directory, so make sure you move to wherever you store your music library.

Should work on any system with GNU utilities and Bash 4 or above.

Note: Output .m3u files are formatted for use on the HiBy R3 Pro Personal Media Player, which uses a:/ to denote its SD card and backslashes within paths. At this time, I don't have plans to generalize it, but I may return to this in the future. 
