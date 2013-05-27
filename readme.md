Sick Beard Dutch Edition
=====

This fork is based on mr-orange ThePirateBay branch
https://github.com/mr-orange/Sick-Beard

Feature list of his branch:
- More Torrent Provider: TPB-DTT-TL-IP + all other provider (usenet/torrent) in master
- Magnet Link & .torrent Private Tracker handling 
- Client Support for uTorrent/Transmission/Deluge (rtorrent magnet handling via hack)
- Full TV Season Search handling for TPB Provider
- Proxy use for TPB & untrusted user filtering
- Nicer Gui with thumbnail support (Poster/Banner)
- Multi Language subtitle management
- 1080p Qualities support (thanks to Zoggy)
- Imdb use for other usefull info
- Traktv Watchlist Integration (courtesy of EchelonFour)
- Personal SceneName exceptions Handling 
- AutoUpdate tv on Start & Ignore Words setting on gui

Extra's on Dutch Edition:
- Failed download handling support based on Tolstyak's work. https://github.com/Tolstyak/Sick-Beard
Note: Use nzbToMedia post-processing scripts for better integration. https://github.com/clinton-hall/nzbToMedia
- NL Series Support (Newznab providers, nzbX)
- Custom Scan and Process interval
- Custom Subtitle Search interval
- Modified Scene Exceptions focused on Dutch users
- Different color for Snateched releases.
- Minor (bug)fixes on SB/Gui.
- And stuff I forgot

*Sick Beard is currently an alpha release. There may be severe bugs in it and at any given time it may not work at all.*

Sick Beard is a PVR for newsgroup users (with limited torrent support). It watches for new episodes of your favorite shows and when they are posted it downloads them, sorts and renames them, and optionally generates metadata for them. It currently supports NZBs.org, NZBMatrix, Bin-Req, NZBs'R'Us, EZTV.it, and any Newznab installation and retrieves show information from theTVDB.com and TVRage.com.

Features include:

* automatically retrieves new episode torrent or nzb files
* can scan your existing library and then download any old seasons or episodes you're missing
* can watch for better versions and upgrade your existing episodes (to from TV DVD/BluRay for example)
* XBMC library updates, poster/fanart downloads, and NFO/TBN generation
* configurable episode renaming
* sends NZBs directly to SABnzbd, prioritizes and categorizes them properly
* available for any platform, uses simple HTTP interface
* can notify XBMC, Growl, or Twitter when new episodes are downloaded
* specials and double episode support


Sick Beard makes use of the following projects:

* [cherrypy][cherrypy]
* [Cheetah][cheetah]
* [simplejson][simplejson]
* [tvdb_api][tvdb_api]
* [ConfigObj][configobj]
* [SABnzbd+][sabnzbd]
* [jQuery][jquery]
* [Python GNTP][pythongntp]
* [SocksiPy][socks]
* [python-dateutil][dateutil]
* [jsonrpclib][jsonrpclib]
* [Subliminal][subliminal]

## Dependencies

To run Sick Beard from source you will need Python 2.6+ and Cheetah 2.1.0+. The [binary releases][googledownloads] are standalone.

## Bugs 

If you find a bug please report it or it'll never get fixed. Verify that it hasn't [already been submitted][googleissues] and then [log a new bug][googlenewissue]. Be sure to provide as much information as possible.

[cherrypy]: http://www.cherrypy.org
[cheetah]: http://www.cheetahtemplate.org/
[simplejson]: http://code.google.com/p/simplejson/ 
[tvdb_api]: http://github.com/dbr/tvdb_api
[configobj]: http://www.voidspace.org.uk/python/configobj.html
[sabnzbd]: http://www.sabnzbd.org/
[jquery]: http://jquery.com
[pythongntp]: http://github.com/kfdm/gntp
[socks]: http://code.google.com/p/socksipy-branch/
[dateutil]: http://labix.org/python-dateutil
[googledownloads]: http://code.google.com/p/sickbeard/downloads/list
[googleissues]: http://code.google.com/p/sickbeard/issues/list
[googlenewissue]: http://code.google.com/p/sickbeard/issues/entry
[jsonrpclib]: https://github.com/joshmarshall/jsonrpclib
[subliminal]: https://github.com/Diaoul/subliminal
