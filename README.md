# Song Title From Youtube

An application based on Win API to recognize YouTube video page and write a title to the file in a root folder for OBS/Twitch Stream copyright related needs.

USAGE: SongTitleFromYoutube.exe <milliseconds> <filename>
, where:
- <milliseconds> is interval to pull data (default: 5000)
- <filename> is desired name of file (default: songtitle.txt)

Example to start process in background: START /B SongTitleFromYoutube.exe 5000 songlist.txt
