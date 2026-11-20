# r3dfox, Pale Moon, MyPal
It's curious how we got to the point where the only two choices we have are Chrome and Firefox, with only variations in between and projects on the outside that are still not good enough to meet the big duopoly. However there is some light at the end of the tunnel on either side. This time, I'll be listing Firefox forks and my experience with them. Ones that I had a bad time with will go in the Hall of Shame at the end, only to be removed from there once they prove themselves.
## The good
### r3dfox
Made by [^1] Eclipse Community, r3dfox is a browser based on Firefox meant specifically for the following: increased privacy, increased compatibility down to Vista, and increased performance. It's based on Firefox's main releases (though held back greatly) and has been pretty damn good. However, its defaults are still disappointing, Google cannot be trusted.
### Pale Moon
Based on a much older Firefox with full XUL support through UXP, the Pale Moon team[^2] recently dropped XP support if you're looking for that. A fork from a ReactOS [community member](###phantom-satellite) is trying to regain Windows XP functionality. That's besides the point for now.
Pale Moon, being based on a much older Firefox, has its issues with trying to load modern websites with modern Javascript madness and modern browser-based 3D graphics. However, it's really stable and appears to support the greats of the XUL era in terms of web apps and extensions. However, one major hitch is that, for me, uBlock Origin does not currently support it, so I have to use either a legacy version or AdBlock Latitude, which isn't as comprehensive as I'd like. Nonetheless, great browser if you aren't searching for the latest and greatest.
### MyPal
When it comes to a balance between features, performance and modern support, I don't think anyone has come closer than MyPal.[^3] Using an older version of Firefox which sits in the middle between the other two, this balance was struck pretty hard, as I can play modern Youtube videos and chat with people on Discord, especially after Discord has started breaking on my Ukrainian friend overseas. While I have the least experience with this browser, having only used it for a little bit for a test, whereas even Pale Moon saw more use as I was troubleshooting some things.

All in all, a good alternative if you need modern support without being too close to the sun.

### Phantom Satellite [^4]
Phantom Satellite is a fork of Pale Moon that works on early PPC architectures (say Mac G3 era) and Windows XP. I decided to try this recently and found it very usable, and I even customized it to my liking. It was also the only browser that I was able to trust with storing my passwords on my laptop. The only hitch is that it does not have the WebExtensions of modern Firefox, instead using UXP to provide XPI extension support. However, uBlock Origin, a must-have extension, is available.
### BONUS: Librewolf
I thought I should talk about this browser as a regular user, how its defaults for privacy and security end up clashing with how I usually browse the web (as a 90s user playing it safe). Librewolf, being a browser whose stated and explicitly-followed goal is to prevent security leaks on your end in the Clearnet, has defaults that are enforced by configuration files and numerous features stripped out for the sake of achieving this goal. The result? My history gets wiped, my passwords are not saved at all (which I already have set), and features such as anti-fingerprinting and random browser spoofing prevent me from accessing sites that "want to make sure I'm a human".

That's not a bad thing, that's not what I'm trying to say; it's just not what I'm after. I'd use the Tor Browser to additionally browse the dark web instead.
## The Bad
### Waterfox
Oh, Waterfox, you had a good promise and talked big game about being privacy-friendly. Turns out you just rebranded Firefox Quantum and called it a day! Firefox itself has been a privacy nightmare with all the telemetry that you can thankfully remove, but no regular user would think about sifting through tons of entries in about:config just to be free of the BS. Even disabling the visible telemetry doesn't stop it outright, necessitating a trip to Xibalba to see if they'll stop.
### The Ugly
I do not know why r3dfox ever experimented with the Fission era of Firefox. It's given them nothing but worse performance and failures to crank up the user's privacy. I'm smoking that opp pack, r3dfox's Fission era won't be missed.

[^1]: https://eclipse.cx
[^2]: https://palemoon.org
[^3]: https://mypal-browser.org
[^4]: https://github.com/DCFUKSURMOM/Phantom-Satellite

[Return to Index\Knowledge](index.md#knowledge)

[Go up](#r3dfox-pale-moon-mypal)