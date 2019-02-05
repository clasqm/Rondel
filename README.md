# Rondel

**by Michel Clasquin-Johnson**

Rondel is a Markdown-capable Text Editor with spell checking, easy access to high-ASCII and some Unicode characters, and the built-in ability to generate HTML, EPUB and PDF  files from Markdown files.

![Rondel](rondel.png)

Versioning: the first number refers to the major version of Trope on which this program is built. The second number refers to Rondel-specific changes. The third number refers to updates of the Markdown dependency

Written in yab using the Yabadabbadoo IDE, but you can load the file Rondel.yab in the "binder" directory into the Official yab IDE.

Written under Haiku x86_64 Beta 1, emulated under QEMU on a Linux Host. I am no longer testing my applications on 32-bit Haiku, but you are of course welcome to try.

MIT -LIcensed software.

**Dependencies:**
* yab
* aspell
* perl
* sed
* awk
* python
* discount
* htmldoc


To compile in Yabadabbadoo, the file "mainloop" and the contents of the entire "sub" directory from [Trope](https://github.com/clasqm/Trope2) must be copied or symlinked within Rondel's directory. These files will not normally appear in the Rondel github repository.
