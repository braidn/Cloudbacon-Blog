---
title: Laptop Super Juice
date: '2011-08-02'
---

Like the rest of the intelligent world, I run all of my development life on a
Mac laptop. The Unix underneath is exactly what the doctor ordered. However, my
February 2009 17inch Macbook Pro is beginning to show it's age . This model
roughly translates to a Core2Duo shoved into Apple's newly updated 17' unibody
for anyone who doesn't have Apple's processor usage
	[memorized](http://www.mactracker.ca/).

Hemming-and-hawing over the brand new Air's was extremely difficult because
they are insanely fast, however; are still probably not the best choice for a
single computer setup. In addition, there wasn't much of a chance that I would
be buying a brand new MBP this year. Especially with the [heavy
rumors](http://www.macrumors.com/2011/07/26/apple-finishing-up-work-on-an-ultra-thin-15-notebook/)
that the entire line might be updated in late 2011/2012 (If you are looking for
a computer and need one, don't wait, nothing is definite).

The choice fell on upgrading my current machine, so where to start for anyone
in the same place?  Maxing out your ram never hurts (8 gigs in most MBPs) but,
by far the best upgrade for money is jumping on the
[SSD](http://en.wikipedia.org/wiki/Solid-state_drive) wagon. Most of the
latency that is witnessed in every-day computing is built around how fast you
can access your files and an SSD will drastically lower said latency. A final
and somewhat, hardware-hacker route is to add a secondary hard drive in the
place of the internal SuperDrive.

Since there is no new hardware in my near future, the decision was simple:
upgrade all 3. 8 gigs of ram, [120gig
SSD](http://www.newegg.com/Product/Product.aspx?Item=N82E16820167052), an
[optibay drive](http://www.mcetech.com/optibay/), and a
[hybrid](http://www.newegg.com/Product/Product.aspx?Item=N82E16822148591&Tpk=momentus%20xt)
500gig secondary drive.  A word of warning for people pining to move out their
SuperDrive, use the manuals at [iFixit](http://www.ifixit.com/Browse/Mac). With
all unibody MacBook Pros you need to move the bluetooth module from the
internal SuperDrive onto the new optibay. This can be a little tricky due to
the fact that the holes in the optibay are NOT pre-threaded. In addition, the
bluetooth module has small screws, cramped angles, and is just a PIA for anyone
with fingers larger than a 3 year old.

The result is a worthwhile upgrade and a computer that handles Lion with
blazing speed. Below are a couple of tweaks that I recommend if going down the
SSD route OR buying an optibay.

1. _Obtibay_: Two hard drives spinning at the same time will definitely reduce
	 your battery life. In addition, people frequently complain that there isn't
	 much cooling going on in the optibay. The fix is to spin the drive up and
	 down [when
	 needed](http://forums.macrumors.com/showthread.php?p=9596575#post9596575). I
	 connected the scripts to [Alfred](http://www.alfredapp.com/) so the drive
	 can be easily managed. [Quicksilver](http://qsapp.com/) would also work
	 here.

2. _SSD_: OS X and even Lion fail to be truly built for SSDs(from the ground up).
	 Hot File Clustering, which basically tracks frequently used files and moves
	 them into the outer-rim is still enabled at the kernel level.  Aww...last
	 time I checked SSDs don't have "outer-rims" like their spinning platter slow
	 cousins from the north. Anyway, here are a few
	 [tweaks](http://www.ocztechnologyforum.com/forum/showthread.php?52845-Mac-OSX-Speed-Tweaks&highlight=osx%20tweaks)
	 that can be used to improve your SSD experience on OS X.

3. _SSD/Trim_: Trim support is still only supported for Apple branded SSDs. Not
	 to worry, there is an easy way to [get it
	 functioning](http://gdgt.com/question/in-os-x-lion-how-do-you-enable-trim-support-for-ssds-f16/)
	 with 3rd party drives.  Please, don't use Trim Enabler on Lion! The patch is
	 based on the 10.6.8 kernel and has yet to be updated (as of 2011.08.02).

4. _SSD_: Install a fresh version of Lion, from a USB key or CD. Imaging an old,
	 spinning drive doesn't make sense if you are migrating to a much quicker
	 SSD. Moreover, it is likely that there are a ton of unused files and junk
	 "cruft" sitting on your hard drive.  Install fresh, rebuild and be happy
	 that everything is clean and as new as possible.
