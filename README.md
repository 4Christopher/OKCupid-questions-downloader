# OKCupid questions downloader

This is a user script which can download your answers to OKCupid match questions and output it as JSON. (This takes a while.)
The script can be used with [Greasemonkey](https://addons.mozilla.org/de/firefox/addon/greasemonkey/).

Accessible from userscript command menu when on the [OkCupid question profile page](http://www.okcupid.com/questions). Creates an infobox so that you can watch the progress and dumps JSON into a textarea.

This repository is a fork and tracks the changes made after userscripts.org has gone offline.

## Version control

If you are like me you will probably want to keep your answers under version control. I wrote a little script to write each question into it‘s own file to avoid ending up in big useless diffs. The script can be found in the [OkCupid-questions-formater repository](https://github.com/4Christopher/OkCupid-questions-formater/blob/master/converter).

## Known bugs

* Number of harvested questions does not match total?
* Some overlap between consecutive pages. Any gaps?

## Todo

* Write a script to take this data and answer questions based on it! (Basically, an importer to match this exporter.)
* Harvest questions you created.

## Related projects

For downloading messages from OkCupid, I can recommend the [OkCupid-Message-Downloader](https://github.com/lehrblogger/OkCupid-Message-Downloader).
