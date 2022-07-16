# QtCopy
Multithreaded file copying/moving which doesn't suck

By default windows explorer copies/moves files inefficiently, using only a single thread. Which results in very poor transfer speeds when dealing with hundreds/thousands of small files as only a single file is transferred at a time. Microsoft themselves made robocopy which is more efficient/multi-threaded but for some reason didn't integrate it into explorer.

This tool is simply a gui for robocopy
