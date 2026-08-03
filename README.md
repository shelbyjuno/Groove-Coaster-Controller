<h1 align="center">3D Printable Groove Coaster Controller</h1>
<p align="center"><img src="Images\banner.jpg"></p>

<h2 align="center">Overview</h3>

This is a fully 3D printable and easy to assemble Groove Coaster controller that is compatable with Switch & Xinput. I wanted the barrier of entry to be as low as possible, so it is designed to require no soldering, minimal 3D printing experience (parts require minimal post-processing), and zero programming experience. This project is a combination of my own designs as well as some great work from the community, see the **Credits & Thanks** near the bottom for more information!

<h2 align="center">Features</h3>

- Compatible with Switch & Xinput
- Fully 3D printable, with minimal post-processing required
- Easy to assemble, no soldering or programming required
- Relatively cheap to build
- L & R buttons included to support Groove Coaster: Future Performers

<h2 align="center">Parts List</h3>

<h3 align="left">Electronics</h2>

- (**1x**) [Leonardo R3](https://www.aliexpress.us/item/3256806579256192.html?spm=a2g0o.order_list.order_list_main.5.2a8d18022Ax2eS&gatewayAdapt=glo2usa)
- (**2x**) [60mm Circle Push Buttons](https://www.aliexpress.us/item/2251832842670457.html?spm=a2g0o.order_list.order_list_main.10.2a8d18022Ax2eS&gatewayAdapt=glo2usa)
- (**3x**) [33mm Square Push Buttons](https://www.aliexpress.us/item/2251832871484224.html?spm=a2g0o.order_list.order_list_main.15.2a8d18022Ax2eS&gatewayAdapt=glo2usa)
- (**2x**) [51mm Square Push Buttons](https://www.aliexpress.us/item/2255799984241874.html?spm=a2g0o.order_list.order_list_main.19.2a8d18022Ax2eS&gatewayAdapt=glo2usa)
- (**2x**) [Sanwa JLF Joystick](https://www.aliexpress.us/item/2255799843325270.html?spm=a2g0o.order_list.order_list_main.20.2a8d18022Ax2eS&gatewayAdapt=glo2usa)
- (**1x**) [2.8mm Hitbox Terminal Connectors](https://www.aliexpress.us/item/3256805906495100.html?spm=a2g0o.order_list.order_list_main.29.2a8d18022Ax2eS&gatewayAdapt=glo2usa)
    - I went with these as I was not sure how to solder and daisy chain ground wires, but if you are comfortable with soldering, you can use the [4.8mm Connectors](https://www.aliexpress.us/item/3256806216358457.html?spm=a2g0o.detail.0.0.6c1fUcXrUcXr8D&mp=1&pdp_npi=6%40dis%21USD%21USD+10.84%21USD+10) instead. It's quite jank, but you can bend the 2.8mm terminals to fit the 4.8mm connectors.
- (**1x**) [USB-A to USB-C Header](https://www.aliexpress.us/item/3256811414880220.html?spm=a2g0o.order_list.order_list_main.24.2a8d18022Ax2eS&gatewayAdapt=glo2usa)
- (**1x**) [Dupont Wire Pack](https://www.amazon.com/dp/B01EV70C78)

<h3 align="left">3D Printing</h2>

- Case Assembly
    - (**1x**) Center Assembly
    - (**1x**) Center Assembly Bottom
    - (**2x**) Joystick Assembly
    - (**2x**) Joystick Assembly Bottom

- Joystick Assembly
    - (**2x**) Joystick Bracket
    - (**2x**) Joystick Cover
    - (**2x**) Joystick Tube
    - (**2x**) Joystick Button

<h3 align="left">Hardware</h2>

- M3
    - (**8x**) M3x16mm Screws (Connects Joystick Assembly to Center Assembly & Joystick Tube to Joystick Button)
    - (**8x**) M3x12mm Screws (Connects Joystick Bracket to Joystick Assembly)
    - (**4x**) M3x6mm Screws (Connects Leonardo R3 to Center Assembly)
    - (**2x**) M3x8mm Screws (OPTIONAL: Connects Joystick Tube to Joystick Shaft)
    - (**6x**) M3 Nuts (Connects Joystick Assembly to Center Assembly)

- M5
    - (**8x**) M5x12mm Screws (Connects Joystick Cover to Joystick Assembly)
    - (**8x**) M5x8mm Screws (Connects Joystick Bracket to JLF Joystick)
    - (**8x**) M5 Nuts (Connects Joystick Cover to Joystick Assembly)


- Misc
    - (**4x**) Rubber Bands

<h2 align="center">Assembly Instructions</h3>

<h3 align="center">Chassis Assembly</h3>

1. Print all required parts from the 3D Printing section above. (see print orientation below)
2. Use 3x M3*16mm screws and 3x M3 nuts on each side to secure the Joystick Assembly to the Center Assembly. (see image below)
3. Use 4x M5x12mm screws and 4x M5 nuts to secure the Joystick Cover to the Joystick Assembly. (see image below)

<p align="center">
    <img src="Images\print_orientation.png" height = 250>
    <img src="Images\assembly_screw.png" height=250>
    <img src="Images\joystick_cover_screw.png" height=250>
</p>

<h3 align="center">Joystick Assembly</h3>

1. Use 4x M5x8mm screws to attach the Joystick Bracket to the JLF Joystick. (The screws should be inserted from the bottom of the JLF Joystick, into the joystick bracket.)
2. Unscrew the Joystick nob and slide the Joystick Tube over the Joystick shaft.
    - OPTIONAL: Use an M3x8mm screw to secure the Joystick Tube to the joystick shaft.
3. Slide 2x rubber bands through the joystick tube and attach to the nubs on the Joystick Bracket. (see image below)
    - This will stop the joystick from twisting and tangling the wires, at the cost of a slightly stiffer joystick. If you want a looser joystick, you can skip this step.
4. Use 4x M3x12mm screws to attach the joystick bracket to the Joystick Assembly. (see image below)
    - IMPORTANT: Ensure that the header on the JLF Joystick is facing the center of the controller, so that the wires can reach the Leonardo R3.

<p align="center">
    <img src="Images\joystick_rubber_band_irl.png" height = 250>
    <img src="Images\joystick_rubber_band.png" height = 250>
    <img src="Images\joystick_screws.png" height = 250>
</p>

<h3 align="center">Button Assembly</h3>

1. Place 2x 51mm Square Push Buttons into the Center Assembly, and secure with the nut provided with the button.
    - IMPORTANT: Ensure that the actual buttons are facing towards the center of the controller, so that there is enough clearance for the wires to reach the Leonardo R3.
2. Place 3x 33mm Square Push Buttons into the Center Assembly, and secure with the nut provided with the button.
    - IMPORTANT: Ensure that the actual buttons are facing towards the center of the controller, so that there is enough clearance for the wires to reach the Leonardo R3.
3. Place 2x 60mm Circle Push Buttons into each Joystick Button 3d Print.
    - For now, remove the actual switch from the button. We will install this later to make our lives easier in the Electronics Assembly

<h3 align="center">Electronics Assembly</h3>

1. Place the Leonardo R3 into the Center Assembly, and secure with 4x M3x6mm
    - IMPORTANT: Do not overtighten the screws, as the plastic is thin and can crack easily.
2. Insert the USB-A to USB-C header into the Center Assembly, and secure with the nut provided with the header.
3. Use 1x ground daisy chain wire to connect all the buttons to the ground pin on the Leonardo R3.
4. Use 5x connectors to connect the buttons to the appropriate pins on the Leonardo R3.
    - The end of the wire is a female connector, so youll need to use a male to male wire to connect to the Leonardo R3.
5. Connect the daisy chain ground wire to each 60mm Circle Push Button switch.
6. Use 1x connector on each Circle Push Button switch and thread through the joystick tube.
    - IMPORTANT: This step is kinda wonky, see the IRL image below. The switch should just be floating in the tube for now
7. Attach the switch to the 60mm Circle Push Button, then place the whole assembly on top of the joystick tube.
8. When the button is placed on the tube, twist the top part, while holding the tube from the bottom, to secure it.
9. Use 1x M3*16 on each Joystick button to secure the tube to the button.  

<p align="center">
    <img src="Images\joystick_bracket.png" height = 250>
    <img src="Images\joystick_tube_twist.png" height = 250>
    <img src="Images\joystick_tube_screw.png" height = 250>
</p>

<h3 align="center">Wiring</h3>

1. Wire Pins 0 and 1 to the 51mm Square Push Buttons for L and R inputs.
2. Wire Pins 4, 5, 6, 7 to the left Joystick (JLF) for the Up, Down, Left, Right inputs.
3. Wire Pins 8, 9, 10, 11 to the right Joystick (JLF) for the A, B, X, Y inputs.
4. Wire Pins 13, A0, and A1 to the 33mm Square Push Buttons for Start, Select, and Home inputs.
5. Wire pins A2 and A3 to the 60mm Circle Push Buttons for A and Up inputs.
    - Since Groove coaster only uses the D-Pad and A, B, X, Y buttons, the 60mm Circle Push Buttons get mapped to the A and Up buttons as well.
6. Wire the ground daisy chain wire to the GND pin on the Leonardo R3.
7. Wire each ground pin on the joysticks to the remaining ground pins on the Leonardo R3.

Here is the pin mapping for the buttons and joysticks:
```
#define PIN_UP 4     // UP
#define PIN_DOWN 5   // DOWN
#define PIN_LEFT 6   // LEFT
#define PIN_RIGHT 7  // RIGHT
#define PIN_X 8      // XBOX Y
#define PIN_B 9      // XBOX A
#define PIN_Y 10     // XBOX X
#define PIN_A 11     // XBOX B
#define PIN_L 0      // XBOX LB
#define PIN_R 1      // XBOX RB
#define PIN_PLUS 13  // XBOX START
#define PIN_MINUS A0 // XBOX BACK
#define PIN_HOME A1  // Switch HOME

#define PIN_UP_2 A2 // additional UP button
#define PIN_A_2 A3  // additional A button
```

<p align="center">
    <img src="Images\wiring.png" height = 250>
    <img src="Images\pinout.png" height = 250>
</p>

<h3 align="center">Programming</h3>

These instructions are largely based on [CrazyRedMachine's](https://github.com/CrazyRedMachine/LUFAHybridFightstick/tree/master) work.

1. Download the Arduino IDE from [here](https://www.arduino.cc/en/software).
2. Open the Arduino IDE, and open the `GrooveCoasterController.ino` file in the Arduino IDE. (`Sketch\GrooveCoasterController\GrooveCoasterController.ino`)
3. Download the Bounce2 Library
    - Click the icon that looks like a stack of books in the top left corner of the Arduino IDE, and search for "Bounce2". Click install.
4. Go to File > Preferences, and in the "Additional Boards Manager URLs" field, add the following URL: `https://github.com/CrazyRedMachine/Arduino-Lufa/raw/master/package_arduino-lufa_index.json`
5. Install LUFA AVR Boards from the Board Manager
    - Click the icon in the top left that looks like a terminal, and search for "LUFA" and click install.
6. Select Arduino Leonardo (LUFA) as your board type
    - In the top left, next to the checkmark, click the dropdown and select "Arduino Leonardo (LUFA)" as your board type. (Plug in your Leonardo R3 if you haven't already, as it will not show up in the list otherwise.)
7. Click on "Upload" to upload the code to your Leonardo R3.
8. After clicking upload, look at the bottom right of the Arduino IDE, once it changes from compiling to uploading, press the reset button on the Leonardo R3. The code should upload successfully.

<p align="center">
    <img src="Images\library_install.png" height = 250>
    <img src="Images\board_manager.png" height = 250>
    <img src="Images\board_manager_2.png" height = 250>
</p>

<h2 align="center">Notes</h2>

- If you are running into trouble, have specific questions, or want to help, feel free to reach out on discord (skitte), as well as fork and contribute to the project on GitHub!
- This is a rough draft of the README, will be updated with more detailed images and instructions in the future!
- The Joystick Button Assembly may require some post processing, and I am in the process of redesigning it to be simpler to print.

<h2 align="center">Credits & Thanks</h2>

- [Rigo Howard](https://github.com/RigoHoward/groove-coaster-printable-shell/blob/main/README.md)
    - The Arduino code for this controller is largely based on Rigo's adaptation of CrazyRedMachine's LUFAHybridFightstick code. I also used his 3D printable shell design as a reference for my own design.
- [CONS&STUFF](https://consandstuff.github.io/)
    - Fantastic community who answered some of the lingering questions I had (shout out Rigo again), as well as great vibes and supported my progress!
- [Vikbez](https://github.com/vikbez/groovecoastercontroller)
    - Used for design references and dimensions, as well as the Joystick STL.
- [CrazyRedMachine](https://github.com/CrazyRedMachine/LUFAHybridFightstick/tree/master)
    - The original LUFAHybridFightstick code that Rigo adapted for this project.