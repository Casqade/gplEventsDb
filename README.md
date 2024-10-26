# Grand Prix Legends Events Database

My collection of `event.ini` files for [gplSeasonManager](https://github.com/Casqade/gplSeasonManager). 

---

Somewhere along 2023 I downloaded 200+ tracks for Grand Prix legends 
and embarked on a long ride to find the best ones. Since almost 
every track out there uses a custom track installer to "install" itself, 
this approach isn't something I'm quite happy with. I needed 
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
to create an event file I had to
unpack track installers with 
[UniExtract2](https://github.com/Bioruebe/UniExtract2) 
and then occasionally use hex editor to find the 
required event data. 

Unfortunately, every track I didn't like got immediately 
deleted along with its event file, and as I didn't plan on 
publishing my program and this database, more than half 
of the `event.ini` files I initially created is missing. 
