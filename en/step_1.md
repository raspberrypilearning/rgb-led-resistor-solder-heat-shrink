## Gather components

You will need:
+ 4 x socket-socket jumper wires, ideally including red, green and blue and black
+ 3 x same value resistors, around 70 Ohm or higher
+ 1 x common cathode RGB LED
+ Solder and heat shrink
+ wire cutters or strippers

![4 socket jumper leads, 3 75ohm resistors, heat shrink and an EGB LED](images/kit.jpg)
## Find the red leg of the RGB LED

A common cathode RGB LED has one longer leg which is the cathode and needs to be connected to ground (GND). Check the specification for your RGB LED but the order of the legs is usually red, cathode (longer leg), green, blue.  

![An RGB LED with four legs, the second one is longer.](images/rgb-led-legs.png)

Carefully spread the legs of the LED, and secure the LED using a helping-hands or a bulldog clip.

![An RGB LED with the legs spread apart](images/spread-legs.jpg)
## Tin the LED's legs

For each of the LED's legs, use a soldering iron to heat them for a few seconds, then apply solder so that each leg is coated with an even layer of solder.

--- no-print ---

![The legs of the RGB LED coated in solder.](images/tin_rgb.gif)


--- /no-print ---

--- print-only ---

![The legs of the RGB LED coated in solder.](images/tinned-legs.jpg)

--- /print-only ---

## Tin the resistors

Repeat this procedure with both legs of the three resistors.

--- no-print ---

![resistor with it's leg tinned with solder.](images/tin_resistor.gif)

--- /no-print ---

--- print-only ---

![image of a resistor with it's leg tinned with solder.](images/tinned-resistor.png)

--- /print-only ---
## Solder the resistors to the legs of the LED

Hold the leg of the resistor along side one of the anode legs of the LED.

![leg of LED alongside one of the RGB LED's legs](images/adjacent-legs.jpg)

Then use the soldering iron to heat both legs, so that the solder melts and they bond together.

--- no-print ---

![leg of RBG LED soldered to the resistor](images/bond_resistor.gif)

--- /no-print ---

--- print-only ---

![leg of RBG LED soldered to the resistor](images/bonded-legs.jpg)

--- /print-only ---

## Repeat for the remaining legs

Repeat this procedure for all the LED legs, apart from the cathode (the longest leg).

![three resistors soldered to to the anodes of the RGB LED](images/led-three-resistors.jpg)

## Attach the four jumper wires

Cut your jumper leads to your desired length and strip about 1cm of insulation from the end of the wires.

Sheath the jumper wires with heat shrink.

![Cut and stripped jumper lead with lose heat shrink around most of it's length](images/jumper-lead.jpg)


Tin the stripped ends of the jumper leads, then bond them to the legs of the LED. If you have a black jumper lead, it should be attached to the cathode of the LED (the longest leg).

--- no-print ---

![the stripped end of a jumper wire being tinned](images/tin_jumper.gif)
![the jumper wire being bonded to a resistor](images/bond_jumpers.gif)

--- /no-print ---

![Four jumper wires are attached to an LED and a resistor.](images/soldered-jumper-leads.jpg)

Move the heat shrink up, so that it meets the base of the LED and covers the resistors and all the soldered joints.

Then use the edge of the soldering iron (not the tip) and gently rub it up and down the heat shrink, causing it to shrink around the joints, and provide an insulated covering.

--- no-print ---

![heat shrink being slid over the resistors and legs](images/position_heat_shrink.gif)
![edge of soldering iron held near the heat shrink tubbing](images/shrink_heat_shrink.gif)

--- /no-print ---

--- print-only ---

![edge of soldering iron held near the heat shrink tubbing](images/shrinking-heat-shrink.jpg)

--- /print-only ---

Once all four sections of heat shrink have been secured around the joints, you should have your completed RGB LED, ready to connect directly to your GPIO pins.

![RGB LED with resistors and four jumper wires, wrapped in heat shrink.](images/rgb-led-finished.jpg)