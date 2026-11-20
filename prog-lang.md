# Research: programming languages
So, I've been multitasking in that I want to see just what kind of skills I can use on the job, and which ones I can keep improving for personal use in the meantime. My ultimate goal with programming is to make old computers useful again, even if I have to break compatibility with prior software to do so, down to making a non-standard OS. Here's what I got so far.

## Studied/familiar
### C99: The classic
Ah, C99, this is what I really got into after realizing that Python is bunk. For my project I was working on a Lisp-like interpreter which is the core of a C99 tutorial I was reading and implementing. However, due to what I believe was the difference between ARM and x86, I got really stuck at a late part, the interpreter's functionality itself. How that I have Linux on x86_64 hardware again, I can do this once more and at last proceed with the study.
### Common Lisp: Descendant of the 90s AI efforts
Common Lisp, whether it's in the form of CLisp or Steel Bank Common Lisp, has become a very popular culture-hacking software. Stemming from various Lisp Machines and their dialects, the self-hackable nature of the language was once used to constantly experiment with AI (which were a different beast back then) and user interfaces (which needed that constant hacking to maintain developoment flow). Nowadays it's used for lots of purposes because it's become more comprehensive than the sum of its parts.
### Ruby
While Ruby may no longer officially work on Windows 7, VxKex saved my ass, so now I can use it on both my Orange Pi (which is currently an OP Macintosh) and my laptop (whether with Win7 or MX Linux.). Because of this, and the lack of format forcing, I decided to give it a shot. No wonder it's marketed towards children, this is one of the easier languages I've studied. Here's what I learned about it.

The language itself is very easy to learn, and can be written with either nmo tabs, a single space, multiple tabs or so on. Single line helps me see it a little better since I don't have to dart my eyes left or right as much. While it's interpreted, it can be compiled for the architecture you're on to make it faster. It has a variant, Ruby on Rails, which I have not tried yet, which people apparently frequently jokingly bash it, though it has (apparently) static typing.

*Note to selF:* Ruby is dynamically typed, the type of variable can change at any time, potentially without a recast.
### Dark Basic Classic: Where a lot of us got our start
I never used DarkBasic back in the day, or at least my memory is cooked on that front. However, the fact that it sold well enough for TheGameCreators to make DB Pro, FPS Creator, Dark Basic Studio and so on told me that there was some merit to this. To start with, I read all of the internal documentation in-app.

One of the things in there is a copy of the cave run demo code, which accessed files that already existed in the DB folders. To make it windowed properly, I used DxWnd, but found that the fullscreen nature allowed me to focus on the programming. Sometimes the right UI just gets you completely invested. I ended up scrapping running DB in windowed mode as a result.

The major hitch I have is that, in 3D games at least, if you hit a wall or slope, the compiler and interpreter dont' allow you to update your X and Y positions to slide along said wall as a reaction. This necessitates a plugin to do just that, which I don't mind, but it kind of bites that it took DB Pro for this functionality to be native.
### Smalltalk (Squeak)
Smalltalk is a family of programming environments both bare metal and emulated that serve as inherently-hackable graphical and programming environments. I tried it for the first time on Windows, and felt that Windows itself was distracting me from doing what I want to do on the system. That's when I heard about the No Operating System initiative, where the "OS" only facilitates the use of a complete system at the user level, and not the kernel level.

I tried it, but found that it was somewhat inscrutable, being a new paradigm for computing as a whole, from kernel level to kernel-user hybrid to userspace only. Because of that, I did what others would: do a minimal Linux install with needed drivers and boot Squeak on login. It was there that I felt I could hack to my heart's content, on that Sweet Potato that's getting less power than needed. since then I've become a little obsessed with running singular user experiences like hobby OSes. It's an excellent environment with lots of 
references and documentation baked in.
## Heard about/interested in
### GNU/Prolog
Prolog is a family of languages that, instead of branching on one or more true/false conditions, assesses all conditions at the same time. This was useful because, at the time, Lisp was not the only language being used for Ai research. Prolog's unique quirks allowed the "AI" to see multiple truths and falsehoods and not get tunnel vision.

Nowadays, Prolog is used as a general purpose data assessment language. Ironically, despite its lineage, it's not being used for the AI craze of the 2020s, which lends credence to my concerns that this is not just an AI endeavor. Moving on.

*Note to self*, start learning this, the data assessment capabilities will be helpful.
### QB64 Phoenix Edition
QB64 is a BASIC dialect written for both compatibility and expansion upon Microsoft QuickBasic, which ws a common sight in full MS-DOS installs. It wasn't very good, but it was used a lot, which is why it fuses compatibility with better functionality. However, it hasn't been updated in a long time. That would belong to QB64 Phoenix Edition.

Phoenix Edition adds a lot to the table, but given that this is an entirely different paradigm from what I'm used to for old BASIC, I'll have to reconcile that before proceeding. It was a little easier to process since DarkBasic is from the 2000s. Once I get used to it, I'll want to develop for it a lot.
### MMBasic
MMBasic wsa originally exclusively made as the firmware for the Maximite line of 8-bit computers that were released around the 2010s. They cost a hundred dollars, but nowadays you can run it on an ESP32, which will be a bit of work. There's a DOS version which has the weakness of not being able to use graphical commands. Once I can actually get my hands on an ESP32 computer or Maximite, I'll see what I can do here.
### LittleBigPlanet PSP: A programming language!?
Moreso a visual programming language. While it's a stretch to say that in front of even myself, I realized that with the visual tooling at my disposal (once I get all the parts), I can make a lot of stuff without too much internal programming effort. It's more like a scripting language in that sense, but it still counts since you're making the game do things as part of your level design.
### Dreams: A dream that Media Molecule was forced to abandon, regrettably
Dreams is a unified visual scripting, songwriting, animating and 3D modeling platform made by Media Molecule, whose last update supports a version of the PS4 OS that I can easily exploit and softmod. It's had a gigantic following ever since an initial hiccup they had with the beta, but unfortunately the company had to close up shop for the online portion. My best guess is that Sony was making it prohibitively expensive to keep this up, and to port it to PC.

Its killer feature was, besides the entire beginner-friendly but extensive suite, was the ability to use the DS4's gyro to speed things up and add precision to what you're trying to do.
### Unbound: Visual scripting and easy SDFs for strong PCs
Obviously I don't have a strong PC available currently. Unbound is a comprehensive but currently lacking experience/game engine with visual scripting, SDFs for 3D models, and support for sound. It's meant for rapid prototyping and making a comprehensive basis for whatever game you want to make.

This will likely be the first language that gets moved out of here once I get the Steam Machine.

[Return to Index\Knowledge](index.md#knowledge)

[Go up](#research-programming-languages)