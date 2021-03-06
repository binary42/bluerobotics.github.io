---
layout: default
title: BlueROV2 Assembly Instructions
permalink: /brov2/assembly/
order: 1
nav:
- Introduction: introduction
- - Safety: safety
- Required Tools: required-tools-not-included
- What's Included: whats-included
- - Frame: frame
- - Electronics Enclosure: electronics-enclosure
- - Battery Enclosure: battery-enclosure
- - Thrusters: thrusters
- - Fairings: fairings
- - Tether: tether
- - Tools: tools
- Optional Configurations: optional-configurations
- - Standard Electronics: standard-electronics
- - Advanced Electronics: advanced-electronics
- - Lights: lights
- What's Not Included: what-you-need-for-operation-that-is-not-included

- Frame Assembly: assembling-the-frame
- - Battery Enclosure: mounting-the-battery-enclosure-to-the-bottom-panel
- - Center Panels: assembling-the-center-panels
- - Frame: assembling-the-frame-1
- Electronics Tray Assembly: assembling-the-electronics-tray
- - Electronics Enclosure: partially-disassembling-the-electronics-enclosure
- - Standard Electronics: installing-the-standard-electronics
- - Advanced Electronics: installing-the-advanced-electronics
- Electronics Tray Wiring: wiring-the-electronics
- - Power Wiring: power-cable-wiring
- - Signal Wiring: signal-cable-wiring
- - Standard Electronics Wiring: wiring-the-standard-electronics
- - Advanced Electronics Wiring: wiring-the-advanced-electronics
- Changing Propellers: changing-the-propellers
- Cable Installation: installing-the-cables
- - Penetrator Installation: installing-the-penetrators
- - End Cap Installation: installing-the-end-cap
- - Penetrator Power Wiring: installing-the-power-wires-from-the-penetrators
- - Penetrator Signal Wiring: installing-the-signal-wires-from-the-penetrators
- - Electronics Cable Routing: electronics-tray-cable-management
- Final Assembly: final-assembly
- - Mounting Electronics Enclosure: mounting-the-electronics-enclosure-onto-the-frame
- - Mounting Thrusters: mounting-the-thrusters-to-the-frame
- - Mounting Lights: mounting-the-lights
- - Mounting the Tether: mounting-the-tether-to-the-frame
- - Finishing Battery Enclosure: finishing-the-battery-enclosure
- - External Cable Management: thruster-and-lumen-cable-management
- - Installing Fairings: installing-the-fairings-and-buoyancy
- Operations: operating-the-rov

store-links:
- BlueROV: http://bluerobotics.com/store/rov/bluerov2/

manual-links:
- Specifications: /brov2/
- Operations Manual: /brov2/operation/
---

<img src="/brov2/cad/BlueROV2-Black-Sands-1.png" class="img-responsive" style="max-width:900px" />

# Introduction

The _BlueROV_ kit comes almost ready to dive. The assembly can be completed with basic hand tools; no soldering or potting is required. We have included a couple of the tools that will be used most often to make assembly and regular use go as smoothly as possible.

## Safety 

<i class="fa fa-exclamation-triangle fa-fw fa-2x text-warning"></i> When working with electricity, especially in water, always practice caution. Always ensure that connections are secure and watertight. Keep your body away from spinning motors and propellers.

# Required Tools Not Included

- 2mm Flat Head Screwdriver
- \#2 Phillips Head Screwdriver
- Adjustable Crescent Wrench
- Wire Cutters or Scissors (for cutting zip ties)
- Thread-locker such as [Loctite 243](https://www.amazon.com/Loctite-1330799-Resistant-thread-locker-6-milliliter/dp/B004L439FE/ref=sr_1_1?ie=UTF8&qid=1466440165&sr=8-1&keywords=loctite+243+thread-locker)
- Tweezers (for assistance installing wires into terminal blocks)
- Isopropyl Alcohol

# What's Included

## Frame

Quantity      | Part														| Usage
------------- | ------------------------------------------------------------| ----------------------
2             | Front Center Panel (1/2" thick black HDPE)        			|    
2             | Rear Center Panel (1/2" thick black HDPE)           		|     	       
1             | Bottom Panel (1/2" thick black HDPE)                       	|  
2             | Side Panel (3/8" thick black HDPE)                       	|
2             | Electronics Enclosure Cradle (Black Anodized Aluminum)  	| Mounting the electronics enclosure to the frame
8 			  | M4x18 Button Head Cap Screw (316 Stainless Steel)           | Mounting the electronics enclosure cradles to the frame        
12            | M5x16 Button Head Cap Screw (316 Stainless Steel)           | Assembling the frame
7             | 8-16 Thread, 5/8" Long, Thread-Forming Screw                | Mounting the ballast to the frame                         
7             | 200g Ballast												| 

## Electronics Enclosure                                                         

Quantity      | Part																		| Usage
------------- | ----------------------------------------------------------------------------| ---------------
1             | Electronics tray with terminal blocks and ESCs installed                    |                      
1             | 4" watertight enclosure with optically clear dome installed                 |            
1             | 14 hole end cap with 3 blank penetrator, 1 Bar30 pressure sensor, 1 vent, and 1 power cable installed	|
1             | Set of tether board power wires  											| Provided power to the tether board
4             | M3x16 Socket Head Cap Screw (316 Stainless Steel)  							| Mounting the electronics enclosure to the electronics enclosure cradle
1			  | Power module power wire														| Powering the PixHawk power module
4			  | 3-24 x 3/8" long self tapping screws (316 Stainless Steel)					| Mounting the tether interface board (Fathom-S or Fathom-X)
4 			  | 1/8" x 1/8" diameter spacers (nylon)										| Mounting the tether interface board (Fathom-S or Fathom-X)
10 			  | 5 1/2" Zip Ties (Nylon)															| Cable management inside the electronics enclosure

## Battery Enclosure

Quantity      | Part																		| Usage
------------- | ----------------------------------------------------------------------------| ------------------------
2             | Battery Enclosure Cradle (Black Anodized Aluminum w/ rubber strip)   		| Mounting the battery enclosure to the frame       
1             | 3" Watertight Enclosure 8-3/4" Long                             			|
1             | 3" Blank Endcap (Anodized Aluminum 6061)         							|
1             | 3" 4 Hole Endcap w/ 2 blank penetrators and 1 vent installed (Anodized Aluminum 6061)  |                                                              
1             | XT90 to 3.5mm Bullet Connector Adapter										| Adapting power wire connector to battery connector
4             | M4x14 Socket Head Cap Screw (316 Stainless Steel)   						| Mounting the battery cradle to the frame
4             | M3x12 Socket Head Cap Screws (316 Stainless Steel)             				| Connecting the battery cradles           

## Thrusters

Quantity      | Part													| Usage
------------- | --------------------------------------------------------|--------------
6   		  | T200 Thrusters w/ installed penetrator					|
16            | M3x16 Socket Head Cap Screw (316 Stainless Steel)      	| Mounting thrusters 1, 2, 3, and 4 to the frame
8 			  | M3x12 Socket Head Cap Screw (316 Stainless Steel)		| Mounting thrusters 5 and 6 to the frame
30            | 5 1/2" Zip Ties (Nylon)									| Routing the thruster and lumen cables

## Fairings

Quantity      | Part																	|
------------- | ------------------------------------------------------------------------| ---------------------
4             | Fairings (Blue Polycarbonate)                    						|
4             | Buoyancy Foam (R-3318 Urethane Foam)                        			|
16            | #4 Size, 3/4" Long Pan Head Self Tapping Screw (316 Stainless Steel)    | Mounting the fairings and buoyancy to the frame                               

## Tether

Quantity      | Part														| Usage 
------------- | ------------------------------------------------------------|--------------
1             | Fathom Tether w/ installed penetrator (25-300m)           	|
1             | Fathom Thimble                          					| Mounting the tether to the frame	
5             | Heavy Duty Zip Ties											| Mounting the tether to the thimble and frame            

## Tools                                                      

Quantity      | Part													| Usages
------------- | --------------------------------------------------------| ---------------
1             | Silicone Grease Tube									| Lubricate O-rings prior to installation 
1             | O-Ring Pick   											| Remove and install O-rings
1             | 2.5mm Hex Driver										| Install M3 screws 
1			  | #1 Phillips Head Screwdriver    						| Install the fairing screws 
2			  | Blue Robotics Penetrator Wrenches                       | Install penetrators
1			  | 1.5mm Hex Key											| Thruster dissassembly
1			  | 2mm Hex Key											   	| Change propellers
1			  | 3mm Hex Key												| Install M4 and M5 screws

# Optional Configurations

## Standard Electronics Package 

Quantity      | Part
------------- | --------------------------------------------------------
1             | Fathom-S Tether Interface Board
1             | Analog Camera with Camera Tilt
1             | 3DR PixHawk (Optional)

## Advanced Electronics Package

Quantity      | Part
------------- | --------------------------------------------------------
1             | Fathom-X Tether Interface 
1             | HD Raspberry Pi Camera with Camera Tilt
1             | Pre-loaded SD Card
1             | Power Supply
1             | 3DR PixHawk (Optional)
1             | Raspberry Pi 3 
1 			  | PixHawk Adapter Plate with Standoffs

## Lights

Quantity      | Part
------------- | --------------------------------------------------------
1-2           | Lumen Subsea Light w/ Mounts (Pair, Pre-Connected) (Optional)      

## What You Need for Operation that is Not Included 

There are some items necessary for operation that are not included with the kit. 

 - Analog screen for the standard BlueROV2. We recommend [this one](https://www.adafruit.com/products/2261).
 - A gamepad controller. We recommend [an Xbox360 Controller](http://www.xbox.com/en-US/xbox-360/accessories/controllers/wired-controller) or [a Logitech F310 Gamepad](http://gaming.logitech.com/en-us/product/f310-gamepad).
 - A laptop or a tablet. ArduSub works on Mac, Linux, Windows, iOS, and Android. 
 - A battery for the BlueROV2. We recommend getting 2 or 3 of [these](http://www.hobbyking.com/hobbyking/store/uh_viewItem.asp?idProduct=56844)   
 
# Assembling the Frame

## Mounting the Battery Enclosure to the Bottom Panel

To mount the battery enclosure to the bottom panel you will need the following parts and tools:

- 2 battery cradles 
- Thread-locker 
- Bottom panel 
- Bag with 4 M4x14 socket head cap screws and 4 M3x12 socket head cap screws
- Battery Enclosure

1. Open the battery enclosure and set the bags inside of it to the side, except for the bag with 4 M4x14 and 4 M3x12 screws in it.

	[picture of the battery enclosure with the stuff that comes in it neatly layed out next to it]

1. Remove one battery cradle from the bubble wrap and apply one drop of thread-locker to the screw holes on the bottom of the cradle. 

	<img src="/brov2/cad/locktite-application-blind.png" class="img-responsive" style="max-width:700px" />

2. Attach that battery cradle to the bottom panel, using 4 M4x14 socket head cap screws. Be sure that the screw head is in the [counterbore](https://en.wikipedia.org/wiki/Counterbore). The bottom panel is only counterbored on one side.

	<img src="/brov2/cad/brov-assembly-step1-annotated.png" class="img-responsive" style="max-width:700px" /> 

3. Apply one drop of thread-locker to the end of each of the 4 M3x12 screws.

	<img src="/brov2/cad/locktite-application-2.png" class="img-responsive" style="max-width:700px" />

4. Grab the battery enclosure and the other battery cradle and install the 4 M3x12 screws into the cradle to clamp the battery enclosure into place. Install all four screws loosly at first and then slowly tighten them on both sides evenly.
Keep the battery enclosure approximately centered in the cradles.

	<img src="/brov2/cad/brov-assembly-step2-annotated.png" class="img-responsive" style="max-width:700px" />
	
## Assembling the Center Panels

To assemble the center panels you will need the following tools and items:

- 2 front center panels 
- 2 rear center panels 
- Thread-locker 
- The bag with 8 M4x18 socket head cap screws 
- 3 mm allen hex key 

1. Apply one drop of thread-locker to the end of each of the 8 M4x18 screws.

2. Attach one of the electronics enclosure cradle to the rear center panels. 

	<img src="/brov2//cad/brov-assembly-step3-annotated.png" class="img-responsive" style="max-width:700px" />
	
3. Attach the other electronics enclosure cradle to the front center panels.

	<img src="/brov2//cad/brov-assembly-step4-annotated.png" class="img-responsive" style="max-width:700px" />
	
## Assembling the Frame

To assemble the frame you will need the following tools and items:

- thread-locker 
- The bag with 12 M5x12 button head cap screws 
- 2 Side Panels
- The bottom panel with the battery enclosure installed
- The front center panel assembly
- The rear center panel assembly
	
1. Apply one drop of thread-locker to the end of the 12 M5x16 screws.
	
2. Install the side panels to the bottom panel.

	<img src="/brov2//cad/brov-assembly-step5-annotated.png" class="img-responsive" style="max-width:700px" />
	
3. Install the center panel assemblies to the side panels.

	<img src="/brov2//cad/brov-assembly-step6-annotated.png" class="img-responsive" style="max-width:700px" />
	
Now the ROV should look like the picture below, and it is time to move on to setting up the electronics enclosure.

<img src="/brov2//cad/assembled-frame.png" class="img-responsive" style="max-width:700px" />

# Assembling the Electronics Tray
	
## Partially Disassembling the Electronics Enclosure

The electronics enclosure ships partially assembled, and will arrive looking like this.

[picute of the electronics enclosure as shipped]

To partially disassemble the electronics enclosure you will need the following tools and items:

- Large flat head screw driver
- The electronics enclosure assembly
- 2.5 mm allen key driver 

1. Remove the tube from the rear flange. You can twist a large flat head screwdriver in the slots if it does not pull off easily. Set the loose items that come inside the electronics enclosure to the side so you can find them easily later.

	<img src="/brov2/cad/electronics-assembly-step1.PNG" class="img-responsive" style="max-width:700px" />
		
2. Remove the rear 14 hole end cap by removing the screws using the M2.5 Allen key. Place the M3x12 screws, clips, and O-ring in a safe place. 

	<img src="/brov2/cad/electronics-assembly-step2-annotated.png" class="img-responsive" style="max-width:700px" />
	
	<img src="/brov2/cad/etray-disassemble.png" class="img-responsive" style="max-width:700px" />
	
## Installing the Standard Electronics

If you have the Advanced Electronics, please skip to [Installing the Advanced Electronics](/brov2/#installing-the-advanced-electronics)

To install the standard electronics, you need the following parts and tools:

- PixHawk Autopilot
- Fathom-S Tether Interface Board
- Bag with 4 short self tapping screws and 4 plastic spacers
- \#1 phillips head screw driver

1. Clean the back of the PixHawk and the area on the electronics tray (starboard side) that you want to mount the PixHawk to with isopropyl alcohol.

2. Attach the PixHawk using the two sided foam tape included with the PixHawk. 

	[picture of pixhawk with tape on it]
	
	[picture of etray with pixhawk on it]

2. 	Attach the Fathom-S Tether Interface Board to the Electronics Tray, using the self tapping screws and spacers. The tether board should mount to the port side.

	<img src="/brov2/cad/tether-board-install.PNG" class="img-responsive" style="max-width:700px" />

## Installing the Advanced Electronics

If you have the Standard Electronics, please skip to [Wiring the Electronics](/brov2/#wiring-the-electronics)

1. Attach the standoffs to the raspberry pi as shown:

	[CAD exploded view of standoffs attaching to pi]
	
2. Attach PixHawk adapter plate to Raspberry Pi standoffs.

	[CAD exploded view of standoffs attaching to adapter plate]
	
3. Install the Raspberry Pi camera.

	[picture of raspberry pi camera installed]
	
4. Install the Raspberry Pi to the Starboard side of the electronics tray.

	[exploded CAD view of the raspberry pi being installed]
	
3. Clean the back of the PixHawk and the top of the adapter plate with isopropyl alcohol

4. Attach the PixHawk using the two sided foam tape included with the PixHawk

	[Picture of the PixHawk with tape]
	
	[Picture of the PixHawk installed]
	

5. Install the Fathom-X Tether Interface Board to the port side of the Electronics Tray, using the self tapping screws and spacers.

	<img src="/brov2/cad/tether-board-install.PNG" class="img-responsive" style="max-width:700px" />

6. [installing raspberry pi and pixhawk, still need to figure out exactly how this happens don't forget that the camera wire needs to get installed early]

# Wiring the Electronics

## Power Cable Wiring

To complete the power cable wiring, you will need the following items:

- Large phillips head screwdriver 
- Tether board power wires 
- XT60 to spade adapter 
- PixHawk power module 
- PixHawk power module jumper cable

The following two diagrams show the power wiring for the port and starboard sides. Our convention for power wiring is to have the positive power terminal on the starboard side and the ground power terminal on the port side. The power terminal blocks come with 
jumpers installed. The white rectangular holes with rounded corners, in the diagrams, are physical holes in the electronics tray used to pass power cables from one side to the other.

<img src="/brov2/cad/sboard-side-power-wiring.png" class="img-responsive" style="max-width:900px" />
	
<img src="/brov2/cad/port-side-power-wiring.png" class="img-responsive" style="max-width:900px" />
	
1. Connect the ESC power and ground wires to the power and ground terminal blocks, using your large phillips head screwdriver. 

	[picture of the power side wires installed]

2. Attach the tether board power wires to the power terminal blocks and the tether board. 

	[picture of the wires installed]

3. Attach the included XT60 to terminal block spade adapter to the power terminal blocks and the PixHawk power module.

	[picture of this assembly installed]

4. Plug in the power module to the "Power" port on the PixHawk
	
5. Connect the ESC motor wires to the motor wire terminals. The motor wires should be attached as shown in the following diagrams. The wires from the thrusters will be attached to this terminal block at a later time.

	<img src="/brov2/cad/port-side-motor-power-wiring.png" class="img-responsive" style="max-width:900px" />
	
	<img src="/brov2/cad/sboard-side-motor-power-wiring.png" class="img-responsive" style="max-width:900px" />

## Signal Cable Wiring

To complete the signal cable wiring you need the following items:

- A small (~2mm) flat head screw driver
- Wire cutters

The following two diagrams show the signal wiring for the port and starboard sides.

<img src="/brov2/cad/sboard-side-signal-wiring.png" class="img-responsive" style="max-width:900px" />
	
<img src="/brov2/cad/port-side-signal-wiring.png" class="img-responsive" style="max-width:900px" />

1. Remove and cut the 5V line on 5 of the ESC signal wires. 3DR [recommends only connecting one ESC +5V output](https://pixhawk.org/users/actuators/pwm_escs_and_servos)

	i. Seperate the three wires coming into the connector plug to about 2 inches away from the plug.
	
	[picture of seperating the wires]
	
	ii. Remove the center pin from the plug by lifting up on the plastic with a small flat head screw driver.
	
	[picture showing how to pop the header pin out of the connector]
	
	iii. Cut off the +5V line using wire cutters or scissors about an inch away from the connector plug
	
	<img src="/brov2/cad/esc-5-volt-remove-2.png" class="img-responsive" style="max-width:700px" />

2. Connect the ESC signal wires to the PixHawk Main Out.

	- Channel 1: ESC 1
	- Channel 2: ESC 2
	- Channel 3: ESC 3
	- Channel 4: ESC 4 
	- Channel 5: ESC 5
	- Channel 6: ESC 6 
	
3. Connect the camera servo signal wire to PixHawk Main Out Channel 8. Do not remove the +5V line from this connector.

## Wiring the Standard Electronics

If you have the Advanced Electronics, please continue to [Wiring the Advanced Electronics](/brov2/assembly/#wiring-the-advanced-electronics)

To complete the wiring of the Standard Electronics kit you need the following items:

- The analog camera cable (included attached to the camera)
- PixHawk serial cable (included with the PixHawk)
	
1. Attach the camera wire to the "NTSC/PAL CAMERA" port on the Fathom-S Tether Interface Board.

	<img src="/brov2/cad/camera-wire-install.png" class="img-responsive" style="max-width:700px" />
	
2. Connect the serial wire from the "DF13 UART" port on the Fathom-S Tether Interface Board to the "Telem1" Serial Port on the PixHawk.

	[picture of the serial wire]

	[picture of the serial wire installed]

## Wiring the Advanced Electronics

If you have the Standard Electronics, please continue to [Changing the Propellers](brov2/assembly/changing-the-propellers)

1. Plug the included ethernet cable to the Raspberry Pi 3 and the Fathom-X Tether Interface Board.

	[picture of the installed ethernet cable]
	
2. Plug the Raspberry Pi power supply to the Raspberry Pi 3.

	[picture of a close up of the installation into the pi]
	
3. Connect the Raspberry Pi power supply to the terminal blocks.

	[picture of the power supply installed on the terminal blocks]
	
4. Connect the usb cable to raspbery pi and pixhawk
		
# Changing the Propellers

To change the propellers on three of the thrusters you will need the following items and tools:

- 3 T200 Thrusters (included with ROV)
- Large (~#3) Phillips Head Screwdriver (not included)
- 2mm Allen Hex Key (included with ROV)

1. Remove 3 thrusters from their tubes. These will become Thrusters 1, 2, and 5.
	
2. Switch the propellers from the clockwise thrusters that come installed to the counter-clockwise thrusters that come along with the thrusters. Please refer to our [Changing the Propeller Tutorial](/tutorials/changing-the-propeller) for detailed instructions.

3. The next few steps will be easier if you keep the clockwise and counter-clockwise thrusters seperated, and for reference the picture below shows clockwise and counter-clockwise propellers installed on thrusters.

	[annotated picture with cw and ccw thrusters]
	
# Installing the Cables

## Installing the Penetrators

To install the penetrators you will need the following items and tools:

- The bag with 2 black penetrator nuts, 7 red penetrator nuts, and 9 O-rings (included with ROV)
- Silicone grease (included with ROV)
- 14 hole end cap with blanks, Bar30, vent, and power wire installed (included installed on the electronics enclosure)
- 3 T200 with counter-clockwise thrusters (included in cardboard thruster tubes)
- 3 T200 with clockwise thrusters (included in cardboard thruster tubes)
- 1 set of daisy chained Lumen lights (included in the cardboard box under the tether interface board)
- 1 tether with penetrator installed (included in box strapped to ROV box)

The electronics enclosure end cap will ship with 3 blank penetrators, 1 Bar30 pressure sensor, 1 vent, and 1 battery power wire penetrator installed.

<img src="/brov2/cad/end-cap-as-shipped.png" class="img-responsive" style="max-width:900px" />

If you install the remaining penetrators as shown in the diagram below, it will keep everything neat, organized and logical.

<img src="/brov2/cad/end-cap-final.png" class="img-responsive" style="max-width:900px" />
	
1. Remove 8 of the O-rings and apply Silicone grease to them. Hold on to that other O-ring, you will need it in a minute.

	<img src="/brov2/cad/grease-o-ring.png" class="img-responsive" style="max-width:700px" />

2. Install the O-rings onto all of the thruster penetrators, the lumen penetrator, and the tether penetrator.

	[picture of installed o-ring]
	
3. Install the penetrators to the end cap in the order shown below. Tighten to finger tight, then use the provided wrenches to tighten them an additional ~1/16 of a turn. If you can't loosen them with your fingers, they are tight enough. 

	- Thruster 1 (CCW propeller) with red penetrator nut
	- Thruster 5 (CCW propeller) with red penetrator nut
	- Thruster 3 (CW propeller) with red penetrator nut
	- Lumen with red penetrator nut
	- Thruster 4 (CW propeller) with red penetrator nut
	- Thruster 6 (CW propeller) with red penetrator nut
	- Thruster 2 (CCW propeller) with red penetrator nut
	- Tether with black penetrator nut
	
At this point all of the thrusters, lights, and the tether should be loosly hanging from the end cap, and it should look something like this. 

[picture of the wires hanging from the end cap]
	
## Installing the End Cap

To reinstall the end cap you will need the following items and tools:

- The O-ring, the 6 M3x12 screws, and the clips that you removed from the end cap earlier
- Silicone grease
- End cap with thrusters, lumen, tether, and power cable hanging off the back
- 2.5 mm allen head hex driver

To reinstall the end cap you need the following parts and tools:

1. Retrieve the Face Seal O-ring, the 6 M3x12 screws, and the 2 clips that you removed earlier

	<img src="/brov2/cad/etray-disassemble.png" class="img-responsive" style="max-width:700px" />
	
2. Clean the O-ring and make sure that it is free of any debris or damage. If it appears to be damaged, replace it with the spare 4" face seal O-ring.

3. Apply Silicone grease to the O-ring.

4. Install O-ring back onto the flange seal

	[picture of the O-ring back in the flange seal]
	
5. Install the end cap onto the O-ring. Pay close attention to the orientation. Do not fully tighten any screws fully when first installing them; it may cause the O-ring to slip out of its groove.

	[picture of the endcap reinstalled]
	
## Installing the Power Wires from the Penetrators

To install the wires from the penetrators you will need the following parts and tools:

- Large (~#2) phillips head screw driver
 
Here is a diagram of where the power wires from the end caps should get connected. 

<img src="/brov2/cad/sboard-side-power-wiring-with-endcap.png" class="img-responsive" style="max-width:900px" />

<img src="/brov2/cad/port-side-power-with-end-cap.png" class="img-responsive" style="max-width:900px" />

1. Connect the battery power wires to the power terminal block

2. Connect the Lumen power wires to the power terminal block
	
## Installing the Signal Wires from the Penetrators
	
To install the wires from the penetrators you will need the following parts and tools:

- Small (~2 mm) flat head screw driver

Here is a diagram of where the signal wires from the end caps should get connected.

<img src="/brov2/cad/sboard-side-signal-wiring.png" class="img-responsive" style="max-width:900px" />
	
<img src="/brov2/cad/port-side-signal-wiring.png" class="img-responsive" style="max-width:900px" />
	
3. Connect the Lumen signal wire to the PixHawk channel 7. 

3. Connect the Bar30 cable to the I<sup>2</sup>C port on the PixHawk

4. Connect the motor wires to the motor wire terminal block, as shown in the diagrams below

	<img src="/brov2/cad/port-side-motor-power-wiring.png" class="img-responsive" style="max-width:900px" />
	
	<img src="/brov2/cad/sboard-side-motor-power-wiring.png" class="img-responsive" style="max-width:900px" />

5. Connect the tether wires to the tether board.
	
## Electronics Tray Cable Management

Occasionally, you may want to open and close the electronics enclosure, and it is very helpful to have the wires tidy so that they do not get caught up with the acrylic tube. We recommend something like this.

	[picture of the cable management]
	
# Final Assembly

## Mounting the Electronics Enclosure onto the Frame

To mount the electronics enclosure to the frame you need the following parts and tools:

- 4" WTE with dome installed
- Thread-locker
- Bag with 4 M3x16 screws
- 2.5 mm hex driver

1. Reinstall tube with dome over the electronics tray.

	<img src="/brov2/cad/installed-etray-empty-frame.png" class="img-responsive" style="max-width:700px" />

2. Apply one drop of thread-locker to each of the 4 M3x16 screws.

3. Install the M3x16 screws through the clips and into the cradles. It is easier to install these screws if the clips are not fully tightened until all screws are through the clips and threading into the cradles. This allows to clips to rotate so you can find the cradle hole easily.

	<img src="/brov2/cad/clip-installation.PNG" class="img-responsive" style="max-width:700px" />

## Mounting the Thrusters to the Frame

To mount the thrusters to the frame, you need the following parts and tools:

- 2.5 mm hex driver
- 6 T200 thrusters
- Bag with 16 M3x16 screws and 8 M3x12 screws in smaller bag
- The ROV frame

Here is a diagram of where the thrusters go. The order of installation does matter here. You cannot get the front thrusters on if the rear ones were installed first.

<img src="http://ardusub.com/images/vectored-frame.png" class="img-responsive" style="max-width:700px" />

1. Install thrusters 1 and 2, using the M3x16 screws. Tighten the screws so that they indent the frame slightly. It is physically possible to keep turning the screw at this point, but it isn't necessary.

	[close up picture of a screw slightly indenting the frame]
	
2. Install thrusters 5 and 6, using the M3x12 screws. Tighten the screws so that they indent the frame slightly.

3. Install thrusters 3 and 4, using the M3x16 screws. Tighten the screws so that they indent the frame slightly.

## Mounting the Lights

To install the Lumen mounts you will need the following parts and tools:

- The bag with the Lumen mounts, O-rings, and 4 M3x12 socket head cap screws 
- 2.5mm hex driver 
- ROV side panels
- Thread-locker

1. Apply one drop of thread-locker to each of the M3x12 screws.

2. Install the mounts as shown

	[exploded CAD view of mounts being installed]
	
3. Loop 1 size 133 O-ring from the bag that had the Lumen Mounts and screws around each Lumen Mount and Lumen as shown below.

<img src="/lumen/cad/lumen-tutorial-14.png" class="img-responsive" style="max-width:700px" />	

## Mounting the Tether to the Frame

The tether needs to be firmly mounted to the frame to prevent the tether penetrator from being loosened through normal use. To do this, you will need the following parts and tools:

- Bag with thimble and 5 large zip ties
- Tether 
- ROV frame

1. Grab the tether around 12 inches away from the tether penetrator.

2. Loop the tether around the plastic thimble.

	[picture of the tether looping]
	
3. Firmly attach 3 of the zip ties, alternating directions they are installed, around the tether right where it enters and exits the thimble.

	<img src="/fathom/cad/tether-tutorial-a1.png" class="img-responsive" style="max-width:700px" />	
	
4. Attach the thimble to the rear panel as shown

	[picture of the thimble attached to the rear panel with no fairings]
	
## Finishing the Battery Enclosure

To finish installing the battery enclosure you need the following parts and tools:

- The bag with one black penetrator nut and one O-ring left in it
- The 4 hole 3 inch enclosure end cap
- 2 16 mm wrenches
- XT90 to 3.5 mm bullet connector adapter
 
1. Find the bag that had the penetrator nuts and O-rings in it and grab the remaining black nut and O-ring.
	
2. Apply Silicone grease to the O-ring.

3. Install the O-ring onto the battery power cable penetrator.
	
4. Install the battery power cable penetrator into the opening in the battery end cap.

	[picture of it installed]
	
5. Install the XT90 to bullet connector adapter to the battery power wire. 

	[picture of the adapter installed]
	
## Thruster and Lumen Cable Management

To clean up the thruster and lumen wires, you will need the bag of 30 zip ties and your scissors/wire cutters. 

[bottom view of the frame point out cable routing points]

[picture of an example of cleaned up wires]

## Installing the Fairings and Buoyancy

The buoyancy comes preinstalled in the fairings, but make sure it is still in all of the fairings prior to installing the fairings. To install the fairings, you will need the following items:

- 4 Fairings with buoyancy installed (included with the ROV)
- Bag with 16 self tapping screws (included with the ROV)
- \#1 phillips head screwdriver (included with the ROV)

1. Remove the Lumens from their mount.

	[picture showing the unmounted lumens]

2. Install the screws through the center panels and into the fairings.
	
	<img src="/brov2/cad/fairing-install-cad.PNG" class="img-responsive" style="max-width:700px" />
	
3. Reinstall the Lumens.

	<img src="/brov2/cad/BlueROV2-front-angle.png" class="img-responsive" style="max-width:700px" />	

## Operating the ROV

Please refer to the [Operations Manual](/brov2/operation/) for detailed information of setting up the software and completing your first dive.
	










