# Unreal Nanoscopic

This is repository for my smallest project yet.
Inspired by https://github.com/pfist/Nano/issues/1 a few years back, i've just been sitting on the smallest possible unreal engine project to my knowledge.

I heavily reccomend Nano instead, linked above, for inexperienced users. This project only had the content browser itself added at the last moment because I awakened from my madness.
There is virtually no headroom at all here, and no safety rails. Don't come crying to me when 90% of the engine features aren't here. (You can add them back in project addons/settings).

This is for some kind of game jam or something where size is a special issue or you get points or something. Maybe if you really want an experince to run on a toaster or something?

To be clear, project filesize has been minimized to the exclusion of all else. If it could be thrown overboard, it was. And the search was agressive and invasive, it will never recover emotionally.

It is specced for UE4, but it will load in ue5 just fine.

# A word to the wise

You only actually need the uproject file and the config directory, in principle. That stands at a whopping 13.5kb of etherial vapour of a project (to open in editor), and will jump to just 4.93mb on first run in the latest UE4.7.2 editor.

The project with all files included sits at a still outrageous 1.8mb, and contains some files such as the inital map file that actually reduce package size. (Everything pointing to an empty map stops nonsense being generated later). I didnt release these initially, but i've just commited them all. I'm not sure most of these are needed and may reduce the size further if removed, but not the final build size.

The final packaged and executable build zips to 39mb (39,018kb), and goes to 99.7MB in 64bit of barebones infrastucture, sound drivers, shader code and hopes and dreams held together with a stick of gum after publishing.

This is barely usable, but was a lot of fun to deep dive into. You have been warned.

If you make something with this, please let me know! I'd love to see it!
