# Dual X-rail mod fo Voron v0.2 - beta0
<img width="1328" height="848" alt="image" src="https://github.com/user-attachments/assets/ae01ae8a-5e38-4bd2-af1d-d7aafe375e90" />


This is a successor to https://github.com/BarsMonster/Voron-V0-dual-rail-mini-aftersherpa

One of the limitations on the path to better print quality, higher accelerations, less ringing is rigidity of the printer. Weakest point in Voron V0 is arguably X-rail carriage. I believe that dual MGN7 offers more rigidity / less play than even single MGN9 rail due to less "amplification of backlash". In my view the only competing single-rail approach offering similar rigidity is Pandora-style rail mount on the front (https://github.com/MasturMynd/Pandora), preferably with wide rail (MGW7 / MGW9) - but it requires significantly more changes to the printer.

This mod still requires raising X extrusion by 4mm by other mods.
It should be compatible with all v0.2 printheads, and especially [Dragon Burner](https://github.com/chirpy2605/voron/tree/main/V0/Dragon_Burner). 
6 heat set inserts in the bottom part are placeholders - for potential mount of print head by 2-3 points (likely possible with Dragon Burner). For standard printheads keep these unpopulated. 

Mount point is kept as-is to keep compatibility with all printheads. 

# Travel range

* XY travel range is unaffected.
* Z travel range is increased by 4mm.
* Free space above carriage is reduced by 4mm, so you will benefit with any of tophat mods with more space.

# Requires

* Second 150mm MGN7 rail with MGN7H carriage, medium preload. I personally order custom 155mm ones to allow to mod for slightly larger X-travel range (for wiping e.t.c).
* 10xM2 nuts and 10x M2x6mm screws to mount secondary rail, print 1x standard nut carrier.
* Mod to raise X rail by 4mm : https://github.com/camerony/VoronCustom/tree/main/V0.1_Raise_X_Axis_Extrusion_by_4mm
* 4x M2x5mm or M2x6mm screws to mount bottom rail. Recommended to get ultrathin ones, as it's quite tight on the bottom. If screws hit extrusions, and you only have regular hex screws - you can sand them down by ~0.5mm to make thinner head.
* 2x M3 heat inserts (when using standard top-mount for printheads)
