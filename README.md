Project Ultimate File Manager
=============================

Welcome!


### The Problem

In the past, we didn't own too many files, they weren't so big, we could afford to manually organize them into "Music" and "Pictures" folders, and we could find and retrieve those files easily from memory. We would even spend time manually de-duplicating and deleting unwanted files.

Nowadays, we're continuously storing new content to our computer storage from all different sources: digital camera, HD Camcorders, Music CDs & iTunes, friends' hard drives, work & school, and from everywhere imaginable on the internet. The required storage size for all content has only increased exponentially, and alas some of us have already grown past the Terabyte. We don't have enough time to sort through and organize all of our files, de-duplicate them, delete unwanted stuff (it's just another few megs!), record what the content is about or when it happened or who it involved, and of course at the same time - we don't have the time to waste trying to find that one specific file that we quickly dumped into some folder somewhere...

The result is impending doom; we find ourselves just dumping files into unorganized temporary "to-be-sorted-one-day(-yeah-right)" folders. And if we plug in another HDD for additional storage - now we're REALLY in trouble because our whole organized folder hierarchy was on the first drive, so how to keep that order on newly added drives?


### Alternatives

Ideally our Operating Systems would have built in functionality to handle our content in an efficient, expandable, easily organized and easily retrievable way. This may run as deep as the file system itself. In fact Microsoft has worked on this issue at some point - see http://en.wikipedia.org/wiki/WinFS.

But no. It's been some 20 years since the personal computer has gone mainstream and we're still using the good ol' directory tree...

Many of us have been using good tools/software to help with this problem in specific areas, such as Apple iTunes for music, Google Picasa for photos, and so forth. These tools are great in organizing your files for you and help you sort through them and find what you want quickly. The problem with these is their fragmentation; why have another program for every different content type? We should have one tool to handle all of our files.

Several commercial File Managers can be found out there - at a cost, and they don't even cover all of the pressing issues.

We should build a system that can do it all and do it right.


### The Idea

Here is a general overview of the desired workflow and list of functionality that this Ultimate File Manager (UFM) should ideally offer:

* You don't have to place files into specific directories anymore, instead you can just dump them on UFM which'll take it from there.

* UFM will automatically crawl through all content on a regular (possibly real-time) basis and

* UFM will store stuff however it sees fit for itself to retrieve them later (be it iTunes style or even custom file system altogether), and

* UFM will create an index / database of all files, using any info obtainable like: file type, date / time stamps, size, file name, metadata if present, etc. (In the case of a custom file system, this index/database would in effect be the volume's actual "file allocation table".)

* UFM will undoubtedly need your help in clarifying/confirming many uncertainties, such as "These 2 files seem like duplicates, should I delete one?" or "Are all these MP3s really part of one album?" or "Is this person in this picture correctly identified as 'Bob'?" or "All these photos seem to be of one event, what should we call this event and when was it?" etc. As such, UFM will create a queue of such issues to be resolved, and

* Whenever the user has time, UFM will go through these above-mentioned uncertainties with the user. This will increase the accuracy and integrity of the file store, as well as increase UFM's AI of this user's files so that better educated default-actions can be taken in the future.

* You can search UFM for your files however you wish based on whatever criteria works best for you!

* Another important thing would be storage management tools with flexible expandability where UFM will be able to seamlessly expand onto more drives as needed using any desired resources; internal/external storage, networked storage, and perhaps even remote storage.
