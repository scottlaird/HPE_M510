# HPE_M510

Tools and notes for working with HPE M510 Moonshot cartridges.

## Heat Sinks

Many used M510 cartridges come without heatsinks or the mounting base
plate that holds the heatsinks in place.  Replacement HPE heat sinks
are generally unavailable online, and (as of February 2021) list for
more than the current selling price of M510 cartridges.  I am working
on sourcing a workable replacement.

The heatsink base plate also contains the mounting points for the M.2
cards on the bottom side of the cartridge.  So, without a baseplate,
there's no safe way to mount M.2s.  I've designed a custom
3D-printable base plate and included a STL
[here](M510+Heatsink_Mount.stl').  This is designed to connect to the
heatsink using M3 screws which thread directly into the plastic of the
baseplate.  I'd generally prefer to use threaded brass inserts, but
there is only a tiny amount of clearance between the baseplate and the
second DIMM slot, and every single brass insert that I can find is too
thick.

The baseplate has room for up to 3 M.2 SSDs.  The two NVMe-compatible
slots have screw holes for 2280 and 22110 cards.  One of them also has
a hole for a 2260 M.2.  In addition, the SATA M.2 slot should be able
to fit either a 2242 or 2260 card, although this is untested.  The M.2
cards should be screwed in using a short M2 screw with a plastic washer.
Either 3mm or 4mm screws should work when used with a washer.

Here's what I'm using, but any similar screw should work.

* [M2 3mm pan-head phillips screw](https://www.mcmaster.com/90116A007/)
* [M2 plastic washer](https://www.mcmaster.com/95610A510/)

Make sure that you screw doesn't go throught the baseplate and into
the motherboard.  The baseplate is 3mm thick and M.2s are generally
1mm thick, so a 4mm screw+washer is the maximum that should be used.

The baseplate was designed in Fusion 360.  [My
design](https://a360.co/3drTb7T) is available if you wish to make
modifications.