# kTaskLight

> This repo is a work in progress. Hopefully will have it in "good 'nuff" state next weekend, but under the weather
this weekend. Wanted to get at least something up as there was a request for pictures. The names of the STL's *will* be
updated and I'll get all the F360 files uploaded when I do that (again, hopefully next weekend.)

---

This task light project is heavily inspired by Steve Bennett's [Open-Task-Light][sb_otl_github] project, specifically
the "Open Task Light Express". With the closing of Open Builds however, I turned to what parts I could get from Amazon.

With the exception of the counterweight and the Carriage Belt clip, I've remodeled all parts for this light. My carriage
and pulley used design cues and measurements from the parts in Steve's Open Task Light Express.

The "big differences" between my implementation versus Steve's:

* Ability to rotate the light along the YZ plane.
* Use "dog-holes" for workbench mounting.
* Use the workbench mount in conjuction with a desktop base

I would encourage anyone that is interested in this light to check out Steve's build logs on YouTube:
[Open Task Light Build Logs][sb_otl_youtube]

![Picture of Task Light](images\IMG_1802.jpg)

More pictures of the light in the `\images` folder.

## STLs

Most are in the STL subdirectory. As noted above will be renaming them and will add part count (e.g. *name*_x2.stl) for
the couple that need more than one. I think the only part that needs two is `RingMagnetA`.

I'll also be doing an alternative desktop base that will fit on smaller printers. You can't just scale this one, but
when I get the F360 files added, it will be easy to customize.

I use a few STL's from the Open Task Light Express GitHub:

* [Carriage Belt Clip](https://github.com/stevenbennett/Open-Task-Light/blob/main/Open%20Task%20Light%20Express/Printed%20Parts/STL/Carriage%20Belt%20Clip.stl)
* [Counterweight Belt Clip](https://github.com/stevenbennett/Open-Task-Light/blob/main/Open%20Task%20Light%20Express/Printed%20Parts/STL/Counterweight%20Belt%20Clip.stl)
* [Counterweight Flex Tab (x2)](https://github.com/stevenbennett/Open-Task-Light/blob/main/Open%20Task%20Light%20Express/Printed%20Parts/STL/Counterweight%20Flex%20Tab%20(2x).stl)
* [Counterweight Enclosure](https://github.com/stevenbennett/Open-Task-Light/blob/main/Open%20Task%20Light%20Express/Printed%20Parts/STL/Coutnterweight%20Enclosure.stl)
* [Counterweight Lid](https://github.com/stevenbennett/Open-Task-Light/blob/main/Open%20Task%20Light%20Express/Printed%20Parts/STL/Coutnterweight%20Lid.stl)

## Hardware Required

With the closure of Open Builds, and my desire to just dive in and get working on my take of a task light, I got what
I needed from Amazon or from within my store of parts that I maintain (I build Voron printers, so I've got a good
selection of screws, etc). Similar parts can probably be found through other avenues and probably for less cost.


Most of the parts, if you are buying them from Amazon, will come in a quantity that is more than you need. For me this
is a bonus as it adds to the random parts I have for other projects, but if you are after building a single light and
don't want the extra parts, this will drive up the cost.

> This is a little bit incomplete...will dig through and figure out what I missed when I feel better.

| Part | Qty | Source |
|---|---|---|
| ULANZI L2 Bi-Color COB Video Light Mini Cube Light | 1 | https://www.amazon.com/dp/B0B9M7ZQWQ |
| 2020 Extrusion, 500mm | 2 | https://www.amazon.com/dp/B08Y8KCJW4  |
| Metal Dowel 1/2" diameter, 3" length | 1 | https://www.amazon.com/dp/B0DMPDRB45 |
| V-Wheels and Hardware | 1 set | https://www.amazon.com/dp/B0CHRYLV1V |
| Ring Magnet 0.98" x 0.19" Hole 0.62" | 2 | https://www.amazon.com/dp/B0B3DVM4VW |
| Brass Bushing 1/2" Bore x 11/16" OD x 1" Length | 1 | https://www.amazon.com/dp/B0D4TNYWHN |
| Lead Shot | 1# | https://www.amazon.com/dp/B0D3J7G5CQ |
| 8mm Ball Bearing | 1 | https://www.amazon.com/dp/B09H6LXL9Y |
| Spring (size?) | 1 | 
| 6x3 Magnets | 3 | https://www.amazon.com/dp/B0CCXLS8QM |
| M3 Heatset Insert | 1 | ? |
| M3 Hexnut | 1 | ? |
| M3x16 SHCS | 1 | ? |
| M3x10 SHCS | 2 | ? |
| M3x8 SHCS | 3 | ? |
| M6x8 BHCS | 1 | ? |
| M3 Hammerhead nuts | 2 | ? |
| 2GT/GT2 Timing Belt 6mm | ~ 400 mm  | https://www.amazon.com/dp/B0F317NCBD |
| GT2 16 Toothless Timing Belt Idler Pulley for 6mm Belt | 1 |https://www.amazon.com/dp/B07RV32G8W

### Other things needed

* Some epoxy...I used Gorilla, any that will do plastic and metal should work. Don't need but a bit.
* Something to add weight to the desktop base. I used quickrete topped with acquarium gravel and finished with resin.


### Hardware Notes

* `The M6 Screw` - The 2020 extrusion that I sourced had a profile such that I couldn't tap it for M5, so I used a
single M6 to mount the pulley. This screw *probably* could be omitted.
* `V-Wheels` - Need 6 wheels, 6 screws, 4 spacers, and 2 eccentric spacers. The Amazon link provides all that along with
a couple metal plates. You end up with a couple spares and a couple metal plates for other things.
* `Lead Shot` - It takes about a pound to fill the counterweight and that seems to be about the right amount, the link
provided is not the best price. I've since gotten 25# of shot for much cheaper per pound.
* `Ball Bearing and Spring` - These could be ommitted. The parts I sourced were parts of a kit. I wanted several for
other projects, YMMV.
* `6x3 magnets` - I have a ton of these and use them as my "goto" magnet. Might be better choices than the link I
provided


## Assembly

There are a couple "order of operations" that need to be followed. But first, the "prep" items. These just need to be
completed before the final assembly.

General note: I do post processing on my parts as needed, primarily sanding and a bit of filing as needed.

* Tap M6 threads into top of vertical extrusion
* Epoxy dowel into `TaskLightBase`. I just rolled the end of the dowel in a bit of epoxy, inserted it, then cleaned
where it squished out with a blue shop towel.
* Add M3 heatset insert into `ExtrusionToRing`
* Test fit ball bearing into `TestDetentSleeve`...on ABS I needed to lightly sand the inside where the bearing drops
down...you don't want to bearing to fall out, but it should extend over 2mm (mine looks to be 2.26mm). Then add spring
and press fit into `ExtrusionToRing`
* Insert 3 magnets into `TaskLightLampMountExtended`. You will want to check the polarity by setting them on the lamp,
these need to grab onto the lamp. They are press fit, but feel free to add a small drop of superglue if that's your
thing. Note: I needed the bit of superglue on my ABS parts...for the PLA version it was not needed.
* Counterweight screws. I used non-self-starting M2 screws, but ran a self-starting M2 into each of the four holes (one
on top, four where the belt connects) to establish the threads. Makes it a lot easier. Skip if you are using
self-starting screws
* Superglue (carefully) the `RingMountAxel` into one of the `RingMagnetA`'s. The bevel on the axel should be on the
non-superglued side (a small drop of glue is all that is needed)
* Add Ring magnet to the `RingMagnetA` that doesn't have the axel, checking that it's polarity does not repeal the lamp.
Fasten with M3 hexnut and M3x10 SHCS. Check fit, it *must* be proud of the rest of the mount...doesn't matter by how
much as long as it's proud. Use `RingMagnetSpacerRing` shims to adjust.
* Add Ring magnet to the `RingMagnetA` that does have the axel, checking that it's polarity will connect with other.
Fasten with M3x8 SHCS. Check fit, it *must* be proud of the rest of the mount...doesn't matter by how
much as long as it's proud. Use `RingMagnetSpacerRing` shims to adjust.
* Attach `ExtrusionToRing` to horizontal extrusion with two M3x8 SHCS and two M3 hammerhead nuts.
* After eopxy cures, attach `TaskLightBase` to bottom of Vertical extrusion with 2 ea M3 T-nut and M3x8 SHCS. T-nut
hole should be toward bottom.
* Attach V-wheels to `TaskLightCarriage`

At this point, you can put the carriage and counterweight on the vertical extrusion and measure the timing belt...or
just cut it at 400mm. I cut a *small* "chamfer" on the belt ends to help feed it, then pulled with needle nose.


1. Attach timing belt to carriage and counterweight onto vertical extrusion.
1. Screw pulley mount to top of vertical extrusion.
1. Put idler onto pulley mount with M3x16 and M3 hexnut
1. Recheck timing belt length...doesn't have to be exact, just has to suit you...but it's more of a pain to change from
this point on.
1. Slide horizontal extrusion into carriage. Note: carriage now has weight, lower it to bottom instead of just letting
it go!
1. Attach endstop to horizontal extrusion with T-nut and M3x10 SHCS. T-nut hole toward endstop.
1. Carefully (reccommend funnel) fill counterweight with lead shot. I filled mine all the way and seemed perfect, but go
until it counter-balances nicely.
---
[sb_otl_github]: https://github.com/stevenbennett/Open-Task-Light
[sb_otl_youtube]: https://www.youtube.com/playlist?list=PL0szyq6FLzZi2BB8-iA09LrTv0rd4K04u