# Grand Prix Legends Events Database

My collection of `event.ini` files for [gplSeasonManager](https://github.com/Casqade/gplSeasonManager). 

---

Somewhere along 2023 I downloaded 200+ tracks for Grand Prix legends 
and embarked on a long ride to find the best ones. Since almost 
every track out there uses a custom track installer to "install" itself, 
this approach isn't something I was comfortable with. I needed 
some way to quickly enable & disable any track, and came up with a 
[little program](https://github.com/Casqade/gplSeasonManager) 
to do it for me. 

But here's the caveat: for every track I want to enable, 
its directory must contain a special `event.ini` file 
with the contents which are usually written by track installers 
to GPL's season files. Here's an example of such event for 
[Rouen](https://github.com/Casqade/gplEventsDb/blob/main/events/1papurys/rouen/event.ini), 
taken from original `67season.ini`/`gp.ini` seasons. 

Since I didn't want to "install" every track, in order 
to create an event file for it, I had to
unpack track installer with 
[UniExtract2](https://github.com/Bioruebe/UniExtract2) 
and then occasionally use hex editor to find the 
required event data. 

Unfortunately, I deleted every track I didn't like 
(along with its event file), and as I didn't plan on 
publishing my program and this database, more than half 
of the `event.ini` files I initially created is missing. 
For this reason, I'd be really grateful if 
[GPL Track Database](https://gpladdons.the-fastlane.co.uk/tracks_list.php)
provided track event data for all tracks. However, until 
that happens, feel free to 
[contribute](https://github.com/Casqade/gplEventsDb/pulls) or 
[post](https://github.com/Casqade/gplEventsDb/issues/new) 
any `event.ini` files you have. 

Maybe I'll update `gplSeasonManager` to use `sgem.ini` 
file from GEM+ sometime in the future, but right now 
I'm quite happy with current functionality. 
