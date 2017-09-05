title: My Linux Command-Line Cheat Sheet
author: LordAlex Leon
thumbnailImage: http://res.cloudinary.com/lordalex/image/upload/c_scale,w_243/v1486750414/terminal-100220826-large_slksmb
thumbnailImagePosition: top
tags:
  - cheats
categories:
  - tutorials
date: 2017-02-10 10:36:00
---
**Zip a file**
~~~~
sudo apt-get install zip
ip -r compressed_filename.zip foldername
~~~~
*Compress an Entire Directory or a Single File:*
~~~~
tar -czvf name-of-archive.tar.gz /path/to/directory-or-file
~~~~
or compress a file in the same directory:
~~~~
tar -czvf archive.tar.gz stuff
~~~~

**SSH**
~~~~
ssh-add [some random key]
ssh [user]@[at something].[dot something]
~~~~