# SteamRedirect.heroku.com

[Steam protocol URIs](http://developer.valvesoftware.com/wiki/Steam_browser_protocol) are kinda handy as they let you do things with steam by using hyperlinks.
But sometimes you can't use a steam:// URI and you're stuck using things like boring old http://. This app provides a http:// to steam:// proxy.

## Sample Usage
* <http://steamredirect.heroku.com/install/440> redirects to [steam://install/440](steam://install/440) which prompts to install Team Fortress 2
* <http://steamredirect.heroku.com/connect/crits.org:27022> redirects to [steam://connect/crits.org:27022](steam://connect/crits.org:27022) which shall connect you to the [crits.org](http://crits.org/) TF2 server
*  <http://steamredirect.heroku.com/friends/joinchat/103582791430075519> redirects tp [steam://friends/joinchat/103582791430075519](steam://friends/joinchat/103582791430075519) which shall add you to the [official TF2 group](http://steamcommunity.com/games/TF2) chat
* A full list of steam:// commands can be fouund on the [Valve developer wiki](http://developer.valvesoftware.com/wiki/Steam_browser_protocol)


## Links
* URL: <http://steamredirect.heroku.com>
* Github: <https://github.com/BPScott/steamredirect.heroku.com>
