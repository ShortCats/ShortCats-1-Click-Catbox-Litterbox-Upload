  SHORTCATS is a collection of, so far, two distinct ShortCuts for MacOS developed using a mostly 
shared shell script, but otherwise offering very different functionality to users. Both can be
downloaded (via iCloud) free of charge at the [ShortCats Website](https://sites.google.com/view/shortcats).

> [ShortCats | 1-Click Catbox & Litterbox Upload >⁽²·⁰⁾< ](https://sites.google.com/view/shortcats)

  For more information, contact, the latest iCloud download links for both of my free ShortCats tools,
or to donate exactly $3.50, visit my [ShortCats Website](https://sites.google.com/view/shortcats).

  This MacOS-only (shell scripts aren't supported on iOS currently, unfortunately), now fully portable 
Shortcut that allows you to upload files directly to the free file host Catbox.moe via right-click/control-click 
Finder context menu (or the keyboard shortcut 🌐︎ - aka fn-minus) with your file URL added to the 
clipboard automatically as soon as upload is complete, enabling seamless file sharing across platforms.

  A useful tool for anybody who wants to share images, eBooks, software, video clips and any other
filetype quickly and easily across different platforms and without the complication of an account.
Please use this tool responsibly and respect the Terms and Conditions that can be found on [free 
host Catbox's website](https://catbox.moe) - it is also possible to buy merchandise from them and donate
of course, as Catbox is free because it is a donation supported, essentially nonprofit operation.

  This code is nearly identical to shell script used in the module for my other ShortCat for macOS, to the point
that I may not really need to create a second repository for the shell script used in the other tool, the two
being developed simultaneously; 


> [ShortCats | 1-Click Reverse Image Searchˣ⁴  >⁽²·⁰⁾<](https://sites.google.com/view/shortcats)

For more information, contact, the latest iCloud download links for both of my free ShortCats tools,
or to donate exactly $3.50, visit my [ShortCats Website](https://sites.google.com/view/shortcats).

  This MacOS-only, also fully portable from v2.0 allows users to initiate a reverse image search from the 
Finder on MacOS, also via the right-click/control-click context menu (or keyboard shortcut 🌐︎ = aka fn-equals)
to locate the source of almost any image file (vector image files are currently supported in this ShortCat, they 
are working fine with the other one though) from the right-click context menu in Finder on MacOS, with the 
ability to search for an image on Google Lens, TinEye, Yandex Visual Search & Bing Visual Search at the same time
with a single command, drastically improving the odds of locating an image source, as the four major reverse 
image search providers have WILDLY different collection of indexed images, and none of them, individually 
can be relied upon to deliver results as consistently as Google searches do for text queries, for instance.

  The 1-Click Reverse Image Search ShortCat tool necessitated the development of the other 
One-Click Catbox/Litterbox upload ShortCat described above,  because it uses catbox's free 
[Litterbox](http://litter.catbox.moe/) service to upload images temporarily (for <1 hour) 
to the hosted API so that an accessible uploaded image URL can be generated and subsequently appended 
to the search prefixes and suffixes in the URL structures of the four major visual search providers 
Google, Yandex, Bing & TinEye - all at the same time, thus opening pre-populated visual search queries 
for potential sources of your image file in 4 new browser tabs, maximizing the possibility of success.

  Users may select any one of the four major reverse image search providers for any given image
query, or all four of them at onece, which delivers the most consistent search results.  Currently,
the ShortCat will also open the uploaded image file link so you may use the URL elsewhere as 
necessary, and/or verify that it has vanished from the server after no more than one hour (the minimum
expiration period avaiable with the Litterbox API.

  This tool may be especialy useful in OSINT, where rapid image tracing and other workflow optimization are
crucial attributes of an effective operator.  Needless to say I hope a few of you kind spooks will donate 
something around about $3.50 (or more, if doing so does not cause pain) if you find either of my tools useful.

  This readme is fairly comprehensive, but direct contact info, download links & changelog can be found on my page;
  
  https://sites.google.com/view/shortcats

  I would be particularly interested to find out if anyone was able to conveive of a way that my ShortCats could,
even theoretically, be rebuilt entirely using Shortcuts modules, which would enable their use on iOS, which
is currently not possible due to the extensive use of bash script in both ShortCats tools.

  ShortCats was coded and designed by u/alexbarbershop under a CC0 unrestricted use license, but credit is appreciated,
as would be any surprising donations as ShortCats took significant time to build & polish for modular use (i.e without 
the use of dependencies unique to my system), so consider dropping about $3.50 (or more) in the hat at;
    
  https://PayPal.com/donate/?hosted_button_id=K8VC9LKWFDV6U 
  
Or alternatively a few Satoshis to make me feel better about the 37 BTC I had when they cost less than a McDouble does. 
    
  BTC:  bc1qajz4zcarstnzm5sh5c70e43l9zd49ug45yr3g3

"There's nothing more depraved than a man in the depths of an ETH Binge" 
    
  ETH:  0xCEdF024875457c660b1eBC5f0af86Ae227164855

XMR Robot: 48qMQo4aUoH1XmaNSCowmo35c4qpUm5Jp9uN1BFQccB5dDUBD1P5txiK5fWn8U5q7HD37iwY9d1Dn9T5NuZWV2nrFGWPudb

  DOGE: RIP beautiful memecoin, ded by eLoN TrUcC.  I once lost 1000 of these in the 2013 Doge Vault hack, back before the 
innocence of the whole thing had been lost.  It was a beautiful thing, once, before D.O.G.E.

  But you can help me keep the LITes cOiN (: 
  
LTC:  ltc1q5xavwp3p4m2kwewvawupzjh93f5taccxlavjm0

  >   Notice to anybody wishing to use my script in other contexts; I of course would be thrilled to see my work used to enable
> the creation of other new tools beyond my current imagining, much as I did with MinebartekSA's catbox-cli source code,
> where served as the initial template for and dependency of the script prior to its extensive rewriting to add brctl variables
> and handle the passage of files handled by the iCloud bird daemon correctly without error, and ultimately integrating the
> curl components of the former catbox-cli dependency into the script to enable portabile use without complex manual configuration,
> however note that the script as written is configured to work with Apple's somewhat recently introduced Shortcuts {{PILL}}
> module, which appeared at some point before the current ShortCuts runtime (7.0), and are not especially well explained in
> the help documentation that currently exists.

  >   In particular, for reuse of my script, especially for use outside the context of MacOS Shortcuts, please do note
> that the first file path value, the first reference to upload type and the upload duration/litterbox expiration are all
> configured as {{PILL}} modules, and may not work with the specific textual values reproduced in the repository script,
> since the {{PILLS}} are non-text values with additional properties and dimensions not reproduced in text.

  >  Specifically, the first pill is currently working configured as {{SHORTCUT INPUT PILL (Type: File, Get: Path)}},
> and the second two linked to variable modules related to the values they define, and are specifically both functioning as
> {{VARIABLE PILL (Type: Text, Get: Text)}} with reference to variable text defined earlier in the workflow; specifically,
> "file"/"temp" for upload type and "1h"/"12h"/"24h"/"72h" defined as the upload duration/expiration time, albeit only if
> upload type is set to "temp", as "file" (catbox) uploads are by default stored indefinitely, unless a terms of service
> violation is identified by the host, of course, and the file has to be removed.  Use of this script outside the current
> context must either define these values as quoted, or set text variables similarly to their use in the script module.

  > That is all.
