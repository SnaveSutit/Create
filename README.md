Models that need optimizing to improve overall FPS and make the players happy! 😁
This will improve FPS for everyone, even if they aren't getting sub 60. Less elements is less time spent rendering!

Most of these require slight texture modifications, due to the nature of the changes.

I have not finished going though every model in the mod, but I've gone though a decent number of the most impactful ones.

| Model Name | Element Count | Optimized Element Count | Description of Changes | Changes pushed |
| ---------- | ------------- | ----------------------- | ---------------------- | -------------- |
| track/ascending_template | 18 | 7 | Extend rail ties across, remove extra "cap" elements for the ends of the ties, extend rail top and bottom element across. These optmizations could easily be applied to every rail, and it would SIGNIFICANTLY impact performance around large rail setups. This is a huge performance loss! | ❌ |
| mechanical_drill/block | 5 | 3 | Simplify the main cube | ✔️ |
| mechanical_drill/head | 10 | 8 | Simplify the protrusions on the side of the drill, and including the shaft as an extension of the drill head | ❌ |
| large_cogwheel | 16 | 13 | Simplify the center of the cog | ✔️ |
| white_sail | 9 | 5 | Simplify main body into 2 elements instead of 5, and then reduce the "feet" to 3 elements using some inside out cube wizardry | ❌ |
| valve_handle | 22 | 20 | Reduce the number of elements in the handle shape by extending and inverting elements | ❌ |
| stockpile_switch | 7 | 6 | Extend one of the redstone elements though the body of the block | ❌ |
| portable_storage_interface/block | 4 | 3 | Extend one of the top elements across | ❌ |
| portable_storage_interface/block_top | 10 | 6 | Reduce the number of elements used in the angled bits attached to the mouth of the interface | ❌ |
| portable_storage_interface | 10 | 7 | Simplify the main body from 4 to 2 elements, and use inverted cubes to reduce the center prongs by 1 element | ❌ |
| powered_shaft | 2 | 1 | Extend the element all the way though the model | ❌ |
| sail_frame | 8 | 5 | Same optimizations done to the white_sail | ❌ |
| belt_pully | 5 | 3 | Extend elements of the roller though the model | ❌ |
| item_drain | 7 | 4 | Simplify the 4 walls of the cube, and remove the extra element used to create the drain grate, and instead extend the bottom element up | ❌ |
| track_signal/block_cross_signal | 7 | 4 | Reduce elements by utilizing inverted elements | ❌ |
| track_signal/block_entry_signal | 7 | 4 | Same as above | ❌ |
