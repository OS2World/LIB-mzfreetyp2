This is a build of Freetype 2.4.12 with the infinality patch set from http://www.infinality.net/blog/infinality-freetype-patches/ compiled to be used by the Mozilla applications and also qpdfview
Also includes infinality-settings.cmd for setting the various environment variables to change how freetype displays fonts. This cmd file is courtesy of Lewis Rosenthal. See infinality-settings.txt.
Warning, running this cmd file can cause Firefox hangs on exit, crashes on exit and also cure Firefox hangs, your mileage will vary and it never hurts to backup your profile before experimenting.
Also included in this release are 2 alternative builds of fntcfg2.dll. The only changes were to the default fonts.
The fntcfg2.dll.windows uses Arial for san serif and Courier New for monospaced. Probably most people will have these installed or can be found in http://hobbes.nmsu.edu/download/pub/multimedia/fonts/mswbfnts.zip. (watch word wrap)
The fntcfg2.dll.linux uses Liberation Serif for serif, DejaVu Sans for sans serif and Liberation Mono for monospace.
The fonts are available as http://hobbes.nmsu.edu/download/pub/multimedia/fonts/truetype/DejaVu-fonts233.wpi and http://hobbes.nmsu.edu/download/pub/multimedia/fonts/truetype/liberation_107.wpi (watch word wrap).

Install by backing up the original DLLs then with Firefox etc closed, copy over freetyp2.dll and whichever fntcfg2.dll you decide to use while renaming the fntcfg2.dll by removing the suffix.
These are built from the sources at https://bitbucket.org/dryeo/mzfntcfgft specifically changeset:   138:96a6aa431934e24f57f68f71d569d2cd22da5a1b with the included patches applied.

Dave Yeo
dave.r.yeo@gmail.com
The mozilla newsgroup is perhaps the best place to discuss this package.