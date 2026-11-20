# Interface Part 2
- [ ] Top of screen replica
- [ ] Left of screen replica
- [ ] Center of screen replica
- [x] Mouse already exists and is used by many OSes

> 

### Interface Programming

In analyzing how TENEX works in its roughest sense, it's clear that I will have to start from scratch. Because TENEX itself is a high-level language with some low-level access, my best chance is to learn GNU Prolog or use Ruby. Optimizations will be necessary here, even though I'm just using text files. Windows 7's Notepad struggles with relatively large files, even without special characters.

### Why Ruby?

It's *easy* to use, and doesn't require a lot of tenuous formatting work, though some formatting will be needed to help with readability. It's also easy to optimize, as while it does dynamic typing, I can lock it down for good unlike the finicky Javascript used in web browsers. It can also make **native** applications for both Windows and Linux I recall.

### What about networking?
That **is** an important question. However, putting the cart before the horseis a bad idea. Until I actually have something functional, I should save this question for later, but what I *will* tell you is roughly how NLS handled terminals. ~I will say, this is very, VERY loose.~

NLS, when starting for the first time, will assign the first terminal as Terminal 1. When assigning terminals, you'll make a username and password. Each successive connection will receive ascending, permanent, and local IDs that tell the system where it is in the configuration. Each terminal had an intercom where you can choose which terminal to call. Software-side, you can also request permission to access another terminal, say your co-worker was having trouble understanding a piece of data that's in front of him. The owner of the connected-to terminal can kick the guest (say your job is done or you get unruly), restrict access to commands (if they're just showing you something), and most notably work with you in real time as both input systems work at once, sometimes provoking a funny "bug fight".

Modern RDP and VNC solutions for working on another PC are limited in this respect, as both computers are trying to use the same mouse and keyboard interface that the OS provides. A workaround would be to use an artificial secondary MNK app, but those can only go so far. That's where the intermediary part of the program will come in.

### The Fellowship of the Terminal
This is one of the major features of the NLS, and something I'll be replicating once I have the application ready. The way it's developed will have some elements of a multiplayer game, in that the host's view and data will be synced in RAM for the guest. However, only the host's data will be authoritative.

I should also set up voice chat when I can. It will be built-in, sidestepping the need for things like Discord or Revolt (now Stoat, goofy name).

[Return to Interface Part 1](nls-interface.md)

[Go up](#high-level-user-interface)