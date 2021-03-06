# BetterTouchTool
This contains the BetterTouchTool documentation and issue tracking for BetterTouchTool (https://boastr.net).

* Please post any bug, feature request, idea or even question (with the appropriate tag) in the Issues section https://github.com/fifafu/BetterTouchTool/issues.
* I'm marking some issues as FAQ/ Knowledge base, they might be interesting for everybody: https://github.com/fifafu/BetterTouchTool/issues?q=is%3Aissue+label%3A%22%E2%9C%B3%EF%B8%8F+Knowledge+Base+%2F+FAQ%22
* The current BetterTouchTool release notes can always be found here: https://updates.bettertouchtool.net/bettertouchtool_release_notes.html

For non-public issues please contact me by mail (boastr.net@gmail.com)

## BetterTouchTool Documentation (http://docs.bettertouchtool.com/)
Merge requests on the BetterTouchTool documentation are always very welcome.

To build the BetterTouchTool Documentation follow these steps:
* Install Node.js (I recommend to use nvm (https://github.com/creationix/nvm) to install Node. Current long term support version of Node.js is v6.9.1).
* Run ``npm install -g gitbook-cli``
* cd into the BetterTouchToolDocs directory and run ``node yarn-0.17.10.js install``
* run ``gitbook serve`` to build and run the documentation
* run ``gitbook build`` to just build the documentation
