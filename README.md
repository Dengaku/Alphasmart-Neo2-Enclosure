### Alphasmart Neo2 replacement case

Dear all,

I present a case design for the legendary Alphasmart Neo2 portable word processor. It should also fit the Alphasmart Neo.

---

### Acknowledgements

Thanks to **Un Kyu Lee**, creator of the Microjournal devices, for generously sharing the STL files for his enclosure design. His work inspired this project. I also drew inspiration from **Adam Wilk**’s Zerowriter Ink project.

---

### Motivation

I owned a Neo2 that worked well mechanically and electronically but had internal plastic failure that left the display loose. I could have repaired the original case, but I never liked the Neo2’s appearance. I wanted a cleaner, lighter, more compact case that felt modern and practical rather than needlessly aerodynamic.

---

### Design goals

1. **Lightweight and strong** — keep the device stiff and the internals protected, with nothing exposed.  
2. **Compact and rectangular** — easier to tilt on a stand, rest on the lap or belly, and fit neatly in an A4 bag.  
3. **Print cleanly** — minimal supports and few visible print lines.  
4. **Recess for a collapsible leg** — a long recess at the back, along the PCB area, allows adding collapsible legs to tilt the device.

---

### Design decisions and trade-offs

- I prioritized lightness, compactness, and a shape that prints cleanly over adding features like a built-in light or extra screen tilt.  
- I considered an independently tilting screen, but the keyboard bus cable is thin and brittle, so I avoided that risk. Tilting the entire device should provide sufficient viewing-angle adjustment and is easier with this rectangular design.  
- The display sits close to the case surface so the bezel does not obscure the last line of text.  
- To save weight and space, the case accepts **AAA batteries** instead of AA. They deliver the same voltage with less capacity, which I considered an acceptable trade-off.  
- The case includes a single port hole for the **USB Type B** cable used for data transfer. Additional holes can be added if desired.  
- The device could be slightly more compact if the screen were closer to the keyboard, but that would stress the delicate bus cable. I avoided that trade-off.  
- The final wedge is a bit thick at the top; switching the data port to USB-C and moving it elsewhere could have saved more space, but the required electronics changes were beyond my skill level.

---

### Printing and assembly notes

- Prototype printed in white PLA and painted; painting is optional and time consuming. The print looks good straight off the printer.  
- Parts are designed to print with zero support for a clean, almost industrial finish. Experienced 3D printer users should find the design straightforward.  
- I used brass heat-set inserts for the back cover screws (**4.5 mm diameter, 5 mm depth**) and **M3** screws. The display and PCB were attached without inserts due to tight clearances, but the base files can be modified to add the required holes.  
- The keyboard mounts from the back, so you do not need to thread its cable through awkward ducts. This avoids using tape and simplifies assembly.

---

### Files and compatibility

- **STL and Rhino files** are available for download and modification. A relatively large printer (like the Bambu H2D) is needed to print the pieces in one go.  
- If there is interest, I can modify the files for smaller printers such as the **Bambu X1 Carbon**.

---

### Closing

I hope others enjoy printing and using this case. Thanks again to **Un Kyu Lee** and **Adam Wilk** for the inspiration. Feel free to print, modify, and share feedback.
