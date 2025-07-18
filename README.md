# Dual X-rail mod fo Voron v0.2 - beta v1
<img width="1140" height="788" alt="image" src="https://github.com/user-attachments/assets/43213127-4ae9-4957-8eb2-521ec3745fcd" />

This is a successor to https://github.com/BarsMonster/Voron-V0-dual-rail-mini-aftersherpa

One of the limitations on the path to better print quality, higher accelerations, less ringing is rigidity of the printer. Weakest point in Voron V0 is arguably X-rail carriage. I believe that dual MGN7 offers more rigidity / less play than even single MGN9 rail due to less "amplification of backlash". In my view the only competing single-rail approach offering similar rigidity is [Pandora-style](https://github.com/MasturMynd/Pandora) rail mount on the front  with wide rail (MGW7 / MGW9) - but it requires significantly more changes to the printer.

This mod still requires raising X extrusion by 4mm by other mods.
It should be compatible with all v0.2 printheads, and especially [Dragon Burner](https://github.com/chirpy2605/voron/tree/main/V0/Dragon_Burner). 

# Variations
* X_Carriage_Support_dual_rail_wide_2mm_lower_x1.stl - **Main, recommended version.** Wider body for extra rigidity. Upper part is 2mm thinner, printhead mount point is lowered by 2mm. So your printhead is only 2mm higher than stock (taking into account X-rail being 4mm higher). Uses longer heat inserts instead of drop-in M3 nuts for printhead mounting. 3 heat inserts at the bottom to install "loop" mount of Dragon Burner as a 4th mount point of the printhead (optional) or other additional hardware.
* X_Carriage_Support_dual_rail_maxcompatible_x1 - upper part is exactly as stock v0.2, ensuring maximum possible compatibility, but raises printhead 4mm (due to higher X gantry).

# Travel range

* XY travel range is unaffected.
* Z travel range is increased 2mm (if allowed by Z-axis). You might need to shift Z rails up few mm if you don't reach Z=0mm level.
* Free space above carriage is reduced by 2mm, so you will benefit from any of tophat mods with more space (but stock v0.2 already has some extra space, so it is less critical).

# Requires

* Second 150mm MGN7 rail with MGN7H carriage, medium preload. I personally order custom 155mm ones to allow to mod for slightly larger X-travel range (for wiping e.t.c), otherwise standard 150mm one will do just fine.
* 10xM2 nuts and 10x M2x6mm screws to mount secondary rail, print 1x standard nut carrier.
* Mod to raise X rail by 4mm : TBD for v0.2, for v0.1 : https://github.com/camerony/VoronCustom/tree/main/V0.1_Raise_X_Axis_Extrusion_by_4mm
* 6x M2x5mm or M2x6mm screws to mount bottom rail. Recommended to get ultrathin ones, as it's quite tight on the bottom. If screws hit extrusions, and you only have regular hex screws - you can sand them down by ~0.5mm to make thinner head.
* 2-4x M3 heat inserts. "2mm_lower" version is also using 2 extra heat inserts for printhead mounting instead of sunk m3 nuts. You can use longer heat inserts (5-7mm) for printhead mounting for maximum strength - this will require the most care.

# Installation
* You might need to lower Z-axis extrusions ~1-2mm to the bottom to improve clearance.
* You will need to be more careful with wiring - as there is less space below printhead, but in good designs wiring is hidden & routed inside printhead.
* The most tricky part is matching distance between 2 X-rails. If you have small gap there due to 3d print or extrusion variation - don't sqeese carriage, as it will apply constant preload on the bearing blocks and will make it less smooth. If you have a gap >0.1mm - add spacers or scale carriage in Z direction slightly to fit snugly. In my case there was a gap of 0.3mm and I added a spacer. 
