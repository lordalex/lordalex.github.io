title: Upgrading MAC OS X Sierra PHP5 to PHP7
author: LordAlex Leon
tags: []
categories: []
date: 2017-08-18 17:56:00
---
### BREW
~~~~
1. brew update && brew upgrade
2. brew tap homebrew/dupes
3. brew tap homebrew/versions
4. brew tap homebrew/homebrew-php
5. brew unlink php56 
6. brew install php70
~~~~

### CURL
~~~~
1. curl -s http://php-osx.liip.ch/install.sh | bash -s 7.1
~~~~