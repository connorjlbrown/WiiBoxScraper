# WiiBoxScraper
full cover and disc art retrieval tool for people who are playing wbfs backups off of an external storage device, and want an easy way to get all your cover art.

# Dependencies
- curl
- wit

This tool's default behavior is to be used in tandem with [wiiflow](https://oscwii.org/library/app/wiiflow). It assumes all directories for cover art wiiflow needs have already been made, and will pull box and disc art from gameTDB to put in there.

Assumes all wbfs files are in the format `media:/wbfs/Game Name [GAMEID]/GAMEID.wbfs`.

## Doesn't wiiflow have this feature built in?
Yes, but lots of shittier ISP routers (like mine) only have one band of wi-fi, being 5ghz. This is incompatible with the Wii since it's a little older, so I can't connect it directly to the internet to download cover art without spending some money. I don't wanna spend any money.

This thing is by no means perfect, so feel free to bend and break it however. It's just a shell script.


