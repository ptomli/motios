---
title:  "inception"
layout: post
date:   2014-02-14
---

### What's the plan?

We're building a CNC mill, Bob!

Inspired by the likes of
[5 Bears Research](http://www.5bears.com/cnc.htm),
[Mikko Kuivamäki](https://picasaweb.google.com/100091857805186061651/CNCV3?noredirect=1),
[Gabe](http://www.cnczone.com/forums/vertical_mill_lathe_project_log/143269-custom_computer-numeric-control_vertical_mill_build_t-minus_24_a.html),
[Arie](http://www.cnczone.com/forums/vertical_mill_lathe_project_log/30262-first_computer-numeric-control_design_buidling_progress.html),
[Bob](http://www.fordforums.com.au/showthread.php?p=2884611)
and many others, I've decided it would be nice to build a CNC mill for my little workshop. In the true spirit of geeking about
the build is actually a good part of the reason itself, it's just gonna be fun, regardless. Who knows, maybe I'll be able to use
the mill to build the mechanical parts for [my clock](http://ptomli.github.io/pic-wordclock/), and find the necessary circular tuits to _finish_ that.

I'm writing this a little after I started to work on the project, so I have a few things in hand already. I've also been working in
[Rhino3D](http://www.rhino3d.com), specifically the Mac version, which is in development as I type and McNeel are graciously making available
to the public. Kudos! Anyhoo, it's really interesting that muscle memory from circa 20 years ago, working in AutoCAD 12-ish, bubbles to the
surface while I bumble my way through.

The local model engineering society has a workshop, and some of the members have shops in their businesses, so there are a few options
for either making, or finding someone who will make, the parts necessary.

Game on...

### What's in hand so far?

  * 3 off NSK 10mm ground ballscrew, 4mm lead, with roughly 300mm of nut travel
  * 2 off HIWIN AG15U400H
  * 2 off HIWIN AG15U350H
  * 2 off HIWIN AG15U300H
  * 12 off HIWIN AGW15CAZ1H
    
    4 bolt flange bearing block, with tapped mounting holes for mounting from above. Z1 preload
	
  * Chinese C12 ER16A 150mm straight shank collect holder
    
    This will form the basis of the spindle.

### What's on the boat from China?

  * 3 off FK10/FF10 bearing supports
  * 1 off BK10/BF10 bearing supports
  * 3 off Spider shaft couplers, 8mm/6.35mm
  * 1 off Turnigy G160 290kv brushless outrunner
  * 1 off Turnigy dlux 120A high voltage, opto isolated, brushless speed controller

### What's still to be got?

  * 2 off 7001/7201 angular contact bearings
  * 1 off 6001/6201 radial bearing
    
    Both of the above are for the spindle, once that design has been firmed up a bit.
	
  * 1 off Ethernet SmoothStepper
    
    I suspect using an Ethernet connection between the computer and the controllers
	will assist at some point when the workshop goes through a phase shift.
	
  * 3 off Geckodrive G203V/G213V stepper drivers
  * 3 off NEMA 23 ~2Nm stepper motors, eg: Geckodrive G723-400-4
    
    Not set in stone, and I've even looked at the Leadshine closed loop stepper motor system,
	but these are really the sort of ballpark I'm looking at.
	
  * Power supplies
    
    These will be dictated by the spindle and steppers that finally appear on the scene.
	
  * Bosch Rexroth aluminium extrusion
    
    I've already spoken to the local distributor, so I know what they generally carry, and
	a rough estimate of the number zeros that will be on the invoice. I'm just waiting for
	the design to be more concrete before I order the needed lengths.

### Issues?

The Turnigy G160 outrunner might not be ideal, given that the can rotates, unlike a more traditional motor where the can remains stationary.
I'll wait to see what can be made of it. It does seem like it might be small enough to fit into a spindle housing though, so I think I'll
see what the CAD comes up with before I stress too much about that.

HobbyKing do list a Turnigy TrackStar inrunner, at 760kv max 30V giving a theoretical unloaded speed of 22800 RPM. I don't yet have a plan
for a PSU, so thinking about 160A @ 24V is just theory right about now.

The ballscrew on the Z axis might need to be a tad shorter than the ones I have on hand. I can either extend the Z column to accommodate the
length of the ballscrew or get a shorter unit. Also, the rails I have provisionally assigned to the column are only 300mm long, which results
in something like 150mm of actual platform travel. Of course, I could simply get some more rail, which would probably be cheaper than a new
ballscrew, but I'm undecided as yet.

The ballscrews are pretty small, at 10mm. This is unlikely to be an issue for the X and Y axes, since I'm not intending to machine anything
particularly hard. On the Z axis there is the added complication of gravity, although I do intend to assist the ballscrew with a gas strut.
I'm still a little concerned about the mass of the spindle head. I know I can source something like a 16mm ballscrew, which would also be
a bit shorter than the others I have, potentially assisting with the issue above.

### Next?

Next I need to get more of the design down on virtual paper. There are a few issues I've found with the existing model, and a few ideas
that have occurred to me recently. I'll use the [Github ticketing system](https://github.com/ptomli/motios/issues) to track these issues,
pretty straightforward and accessible.

Obviously it would be nice to put up some images of the design, maybe some comparisons with others I've found online. Yeah, that'd be nice...
