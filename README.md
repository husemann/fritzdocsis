FritzDOCSIS
============
This PHP script glues together three components to provide Trending, Monitoring and Graphing of
Fritz!Box DOCSIS Informations obtainable only from the WebUI. This PLugins was developed for
the Fritz!Box 6360 with Unitymedia branding but should work for Kabel-BW and Kabel Deutschland
as well.

This script uses a library from Gregor Nathanael Meyer <Gregor [at] der-meyer.de>.
Also used is a library for working with World of Warcraft LUA files from  david.stangeby@gmail.com.

Requirements
------------
`apt-get install php5-cli php5-curl`

Configuration
-------------
Set variables in .php file and chmod 700. Then run `php fritzdocsis_.php suggest`. This will output
suggestions for all in-built plugins.


German HowTo
------------
There is a blog article explaining this script in German:

http://falkhusemann.de/blog/2012/09/fritzbox-cable-mit-munin-uberwachen-ohne-alternative-firmware/
