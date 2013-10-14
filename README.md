netrw (Network Oriented Reading, Writing, and Browsing)
=====
Mirror of Dr. Chip's netrw vim plugin for vundle  
http://www.drchip.org/astronaut/vim/index.html#NETRW  
Updated Sep 12, 2013 (v150h)

### From the site: ###
Supports network-oriented editing with urls. One may read and write files using one of several supported protocols 
(ex: ftp, scp) and browse directories, both remotely and locally. This version requires vim 7.0. 
Be sure to remove any older versions of netrw before attempting to install this version. In version v142b of netrw, 
g:netrw_winsize's meaning has been changed. Previously, it was the number of rows or lines to be used for new windows 
spawned off of netrw (ex. when using v or o). The new method uses g:netrw_winsize as a percentage of the netrw's 
window size in the appropriate direction (ie. winheight or winwidth). The percentage is an integer (by default, it is 50). 
Unfortunately, there was a bug that makes the netrw version that was distributed with vim v7.0 cause difficulties with a 
vimball-installation of a new netrw. So, for vim v7.0, you'll need to remove the older version of netrw:

Change directory to the directory holding the vim 7.0 distribution's plugin/ and autoload/ directories.

/bin/rm plugin/netrw*.vim autoload/netrw*.vim doc/pi_netrw.txt

Beginning with v108b of netrw: sourcing remote files is supported.

Here's a list of some netrw options that I myself use:
```vim
let g:netrw_altv          = 1
let g:netrw_fastbrowse    = 2
let g:netrw_keepdir       = 0
let g:netrw_liststyle     = 2
let g:netrw_retmap        = 1
let g:netrw_silent        = 1
let g:netrw_special_syntax= 1
```
