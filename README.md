welcome to BleMD.
this project was for goal to import nintendo GC/Wii ".bmd" 3D models,
using blender (blender.org)


<h4>
HOW TO USE: *this section was too long, and moved to MANUAL.md*
</h4>


**HISTORY:**
His history is long, and incredibly hard to trace.

It started with BMD Viewer and BMDview2, from YAZ0 (just where is this person's home page?), in C++

it has a copy on the google code server (http://code.google.com/p/bmdview2/)

Originally it came from this discussion thread:
http://www.emutalk.net/threads/54262-BMDView2-Linux?p=447701

And that had this download link:
http://dl.dropbox.com/u/21757902/bmdview2.tar.gz

An older Readme.txt file that was found from a file BMDview2.rar said:
```
latest version of BMD View 2 at
http://emutalk.net/showthread.php?t=26919&page=18
[...]
The official emutalk thread for this program can be found at
http://www.emutalk.net/showthread.php?t=26062 (part 1), and at
http://emutalk.net/showthread.php?t=26919 (part 2).
```
Oh, and it is here (http://www.vg-resource.com/thread-21121.html) too.

then, because the exportation war really lossy, there was MaxBMD, a MaxScript variation that used 3dsMax from Autodesk.
It was based on bmdview2pre3 by thakis (homepage at http://amnoid.de/gc/ download source at http://www.emutalk.net/showthread.php?t=26919&page=39)
it still had a lot of bugs, and a HELL lot of different branches. Plus this software is expensive. And it was really uneasy to debug.
the discussion is here: http://www.emutalk.net/threads/44490

It was then adapted by Niacdoial (me) from Avatarus-One's version on Github(https://github.com/Avatarus-one/MaxBMD/)
and a bit of the latest BMDView2 program (and planning to use more of it for better materials)
to use blender instead (plus, it is a python plug-in, so that language is far easier to debug)

Finally, the current verion (BleMD) is part of a no-admin-needed pipeline (if you have the right C++ libraries (most PCs do)?)