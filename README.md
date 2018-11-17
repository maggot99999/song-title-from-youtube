# Song Title From Youtube

An application based on Win API to recognize YouTube video page and read the title to the folder for OBS/Twitch Stream copyright related needs.

USAGE: SongTitleFromYoutube.exe <milliseconds> <filename>
, where:
- <milliseconds> is interval to pull data (default: 5000)
- <filename> is desired name of file (default: songtitle.txt)

Example to start process in background: START /B SongTitleFromYoutube.exe 5000 songlist.txt
