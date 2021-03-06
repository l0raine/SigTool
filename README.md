# SigTool
![image.png](https://s31.postimg.org/rtrvn5o3v/image.png)

Utility for scanning signatures, as well as 
converting them between different formats.  

Works on x64.  Actual sig scanning is performed in the background, 
and updaded asynchronously to the UI.

Todo:
* Add custom ._sig_ files to save and load, making this 
the ultimate sig scanning utility.
* Fix the IDA-style sigs on the converter.  They work fine on 
the actual sig page, but not on the converter for whatever the reason.
* Clean the holy hell out of the code, make it publishable.
* Get a better way for filtering 64 bit processes, so it isn't 
as slow.
* Fix a regex error on the conversion page.
* Disable mask when IDA or PEiD sigs are used (like on Converter page).
* Fix some themeing stuff.
* Add some more color themes to the wrapper DLL.

[![image.png](https://s18.postimg.org/p70lf08mh/image.png)](https://postimg.org/image/5p5xz2bol/)


[![image.png](https://s18.postimg.org/jk48h6iux/image.png)](https://postimg.org/image/4beb3ep6d/)

[![image.png](https://s18.postimg.org/lbx7c44sp/image.png)](https://postimg.org/image/50x3fssat/)

