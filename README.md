# Wireless 6 Column Choc Corne Case

This case is modeled for the smaller choc-spaced PCB from Typeractive. It includes both solid and cutout covers for the display, providing flexibility based on your preferences. Additionally, I've included **tenting legs attached with magnets** for added comfort and flexibility.

## Features

- **Sturdy design** with thicker walls
- Just thin enough for a standard USB-C connector to still fit through the wall
- **Very low profile** for a sleek look
- Tight tolerances for a clean and polished build
- Insets for screws on the bottom allow using the case without rubber feet if desired
- **Two cover options**: Solid or cutout for the display
- **Magnetic tenting legs** for ergonomic positioning
- **STL and Shapr3D files provided** for easy customization

## What You Need

### Printed Parts

- **[Plates](./plates)** for the left and right sides
- **[Cases](./cases)** for the left and right sides
- **[Covers for the microcontroller (solid)](./covers/solid)** or **[cutout](./covers/cutout)**
- **[Tenting legs](./tenting-legs)**

**Printing Tips:**

- I printed everything in PLA with a 0.4mm nozzle at a 0.2mm layer height.
- To achieve a flawless print, I reduced the maximum material flow to 8mm³/s.
- For a weightier feel and better sound, I made the prints solid.
- Print profiles are attached to the repository.

If you print the covers with your own profile, make sure to use ironing for a perfect surface finish.

---

### Bought Parts

You’ll need the following hardware:

#### General

- **[Typeractive choc-spaced 6 Column Corne PCB](https://typeractive.xyz)**
- **42 Kailh Choc switches**
- **42 Keycaps**
- **2 [Nice!Nanos](https://nicekeyboards.com/nice-nano)** (wireless microcontrollers)
- **OPTIONAL: 2 [Nice!Views](https://nicekeyboards.com/nice-view)** (displays for customization)

#### Screws and Standoffs

- 10x M2x3 screws with countersunk head (for the bottom of the case)
- 10x M2x4 female/female standoffs (for connecting the case and the plate through the PCB)
- 10x M2x3 screws with flat head (for the plate)
- **OPTIONAL:** 8x M2x3 screws with flat head or longer (for the optional display covers)
- **OPTIONAL:** 4x M2x10 female/female standoffs (for the optional display covers)

#### Miscellaneous

- Rubber feet (e.g., 3M bumpons)

**Note:** Slightly longer screws may still work if the exact sizes are unavailable.

---

## Firmware

The firmware configuration for this case is available in my repository:  
**[Corne ZMK Firmware Configuration](https://github.com/jakmaz/corne-zmk)**.

This includes the keymap and settings optimized for a wireless Corne keyboard build using ZMK.

---

## Assembly

Here’s a general guide for assembly:

1. **Assemble/Solder the PCB:**

   - Solder all components to your PCB.

2. **Insert Switches:**

   - Insert switches into the plate first, then into the PCB. Avoid attaching keycaps at this stage to prevent interference.

3. **Optional Steps:**

   - If using the decorative covers, screw in the standoffs and attach the covers on top.
   - Attach the tenting legs using the built-in magnets for ergonomic positioning.

4. **Attach the PCB to the Case:**

   - Screw the standoffs into the cases.
   - Drop the assembled PCBs into the cases onto the standoffs, making sure the switches align with the side cutouts.

5. **Secure the Plates:**

   - Use the remaining screws to secure the plates to the case standoffs.

6. **Add Rubber Feet:**
   - Glue some rubber feet to the bottom of the case for stability.

---

## STL and Shapr3D Files

To make this case customizable, I’ve included both the **STL files** for 3D printing and the **Shapr3D files** if you want to edit the parts yourself.

---

## Credits

This project wouldn’t be possible without the inspiration and ideas from these sources:

- **[Makerworld Case](https://makerworld.com/en/models/518698#profileId-435003):** This was the main source for the case design and documentation.
- **[Forager Tenting Feet](https://github.com/carrefinho/forager/tree/main?tab=readme-ov-file):** The tenting leg design was inspired by this project.

---

## Need Help?

If you have questions or need assistance, feel free to **[open an issue](../../issues)** in this repository or **[email me](mailto:jakmaz.dev@icloud.com)**.

Happy building!
