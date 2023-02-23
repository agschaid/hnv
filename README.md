# hnv
Probably the 1000th rewrite of good old [Notational Velocity](https://notational.net/) for terminal.

It aims to do what Notational Velocity did so well:

Doing full text search and file selection for a folder of .txt or .md notes.

    *******************************************
    * _search area_
    *******************************************
    * _file area_
    *
    *
    *******************************************
    * _content preview_
    *
    *
    *******************************************

* The curser/focus is ALWAYS on the search area. Type a search term to narrow down the files in the file area.
* The file area lists the filename as well as a "search hit peek" and the last modified date.
* By default always the upermost file (sorted by last modified date) is selected. Use Up and Down keys to change the current selection.
* Hit return to open the currently selected file. Hit Tab to create a markdown file with the contentent of the search area (if no such file already exists) and open it.
* The content preview always displays the contents of the selected file.

"Opening a file" means that this file will be opened with your `$EDTIOR`. When closing the editor you will return to hnv. ESC is going to exit hmv, I guess.

## Roadmap

First I'll try to get this functional. Everything else follows.

But I have some ideas:
* vertical layout
* markdown rendering in content preview
* Ctrl+f and Ctrl+b to browse content preview


## FAQ

### Aha! So this is a Haskell project. Is that what the 'h' in 'hnv' stands for?

No way! It stands for "hackers notational velocity". Just like in [https://github.com/nadrad/h-m-m](h-m-m). I swear.

### But why?

No note-taking/notational-velocity solution did quite what I wanted. Or felt quirky. Or failed all the time. Besides I was looking for a tiny project to get my hands dirty again with Haskell. So there you go.

### Can I contribute?

No. You obviously haven't had a look at the code base.
