YoutubeCD
=========

Have root.sh working.

Todo:	think about distribution
	get subz working
	change https to http (or vice versa)
	refactor

------------------------------------------------------------------------

*Note: youtube-dl outdated. Need to install most recent version.*

Create python file that parses database output

feed output from that into youtube-dl

make the sql delete those bookmarks

have diifferent behavior for folders or links in >Songs

have an initiator that creates the folder

*database editing is not immediate. closing ff MAY do the trick*


------------------------------------------------------------------------

Note - bash equivalent included in this folder.

Steps:

*All programs that are used must be for Windows and accessible from the command line.

1)Make sure there is a program to download audio from Youtube URL's.

Try this one out:
http://rg3.github.io/youtube-dl/download.html

Note - youtube-dl requires Python version 2.6, 2.7, or 3.3+ to work.

2)Make sure the downloaded files are burnable, or get a file converter.

3)Pull up CD burner with appropriate files.




------------------------------------------------------------------------

1)Learn sqlite (check this website out)
http://www.sqlite.org/cli.html

2)get youtube files from database, download the songs & remove from bookmarks

3)there will be a separate file that stores the bookmarks for downloading, which
must be found by the program

4)yep, just link this with what you have already