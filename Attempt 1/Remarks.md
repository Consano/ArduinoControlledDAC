### The process
I started by designing the mounting board for the digital potentiometers in KiCad. I then exported the manufacture files and created an exposure image using UVtools that could be displayed on my Saturn 3 printer. 

By ironing UV photoresist film onto copper boards and then exposing them using the Saturn 3 I was able to selectively develop the boards similarly to using transparencies but without needing a printer.

This resulted in the copper parts of my design in dark blue on my copper boards indicating successful exposure.
![[Images/20250208_181330.jpg]]

These were then developed using a basic solution (Calcium Carbonate dissolved in water) that I made using baking soda (Calcium Bicarbonate) baked in an oven to reduce it to its mono carbonate form. When exposed to this solution the non exposed portions of the film dissolved.
![[Images/20250208_221336.jpg]]

This was then placed in an acidic solution of vinegar, Hydrogen Peroxide, and salt to dissolve the exposed copper and etch the board.
![[Images/20250208_223711.jpg]]
![[Images/20250208_225301.jpg]]
Finally the etched board was placed in a lye bath to neutralize the acid and strip the remaining photoresist.
![[Images/20250208_230100.jpg]]
This resulted in a board that could then be soldered and used to integrate the SMDs to a breadboard for prototyping. Unfortunately this attempt proved to be a failure both in part to my design, the limitations of this method, and my unfamiliarity with hand soldering SMDs
### What went wrong
- The UV film and Copper boards had enough defects that it was difficult to find enough space to prep the PCB based on its footprint
- Excess waste due to the lack of fill zones
- Fragile traces either failing to expose or being too close together and being joined
- Small pads made hand soldering difficult
- Alignment of the board on the DLP printer screen

### Going forward
- Potentially buy new boards/film to make larger PCB's without having to avoid scratches or defects
- Create larger fill zones to allow for easier placement and less usage of etchant
- Create larger traces and Pads using increased space to make prototyping more viable given limited number of SMD's to attempt with
- Create a template for alignment of PCB on the screen to which the outside of the PCB's can be aligned to properly expose the film