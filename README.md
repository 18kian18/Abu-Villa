# How to Build an FPV Drone (Analog)



In this tutorial, I’ll walk you through the process of building an FPV drone from scratch, providing detailed guidance for analogue FPV systems. We’ll cover everything from selecting the right components, to wiring and assembly, and even share insider tips and tricks to ensure you have a reliable and enjoyable FPV drone experience.

![alt text](<img/bumble bee drone (3).jpg>)
# Table of Contents
1. **Parts List**
   - Essential Tools and Supplies
   - Frame
   - Stack
   - Motors
   - FPV Setup
   - Radio Receiver
2. **Steps of Building FPV Drone**
   - Frame Assembly
   - Wiring Diagram
   - Installing ESC
   - Installing Motors 
   - Installing Camera
   - Installing GPS to Flight Controller
   - Installing Receiver
   - Installing VTX


## Parts List
In this tutorial, we’ll be using the following parts to guide you through the FPV drone building process

| Component       |                                                  | Links                 |     price      |
|-----------------|--------------------------------------------------|-----------------------|----------------|
| Frame           |SpeedyBee Master 5 V2                             |https://amzn.to/3XUsccb| $119.99 |
| FC & ESC (stack)|SpeedyBee V3 F7 Stack                             |https://amzn.to/3Wb61NN| $119.99 |
| Motors          |iFlight XING2 2306 1755KV 6S                      |https://amzn.to/3XNwUZ9| $89.99 | 
| Propellers      |Gemfan Hurricane                                  |https://amzn.to/3RWwPi3| $14.99 |
| Battery         |Gaoneng LiPo Drone Battery 1850mah 6S 100c XT-60  |https://bit.ly/45ZHbnd | ₱1,990 (≈ $58.40) |
| GPS Module      |BN-220 Dual GPS Glonass Module                    |https://amzn.to/3xIzmWo| $21.98 |
| Receiver        |RadioMaster RP1 2.4ghz w/ ELRS                    |https://amzn.to/3W8TR7T| $19.99 |
| Transmitter     |RadioMaster TX16S 2.4GHz                          |https://amzn.to/3xK6T2p| $109.90 |
| Goggles         |Skyzone Cobra X Goggles                           |https://amzn.to/3W8aGQw| $279.98 |
| VTX             |AKK X2-Ultimate 5.8GHz                            |https://amzn.to/45VfZGo| $23.99  |
| Antenna         |FPV Antenna Lollipop 5.8G                         |https://amzn.to/3RUQZJA| $21.99 |
| Camera          |RunCam Phoenix 2                                  |https://amzn.to/4cuDY1n| $37.99 |

**Total Estimated Cost:** <span class="math-inline">$919.18 \(approx\.\)<br>
**Notes:**
* The price for the battery was converted from Philippine Pesos (₱) to US Dollars ($) using an estimated exchange rate.
* Prices are based on estimates and may vary depending on the retailer.
* Additional parts and tools may be required for assembly and flight operation (e.g., soldering iron, battery charger).
</span>

## Essential Tools and Supplies
To successfully build your FPV drone, you’ll need the following tools and supplies. Some of these items may already be in your toolkit, while others can be easily found online or at your local hardware store:
- Soldering Iron and solder
- Soldering Flux
- A pair of scissors for stripping and cutting wires
- Shrinkable tube to organize wires
- 3M double sided foam tape
-A collection of 2mm wide zip ties (ideally 15cm or longer)

 ## Frame
 ![alt text](img/frame.png)

 I select this frame it because it designed to handle both cinematic and freestyle flying, Master 5 V2 with great Deadcat geometry, places the flight controller closer to the center of gravity than other DC frames

The innovative anti-vibration stack structure dampens the effect of motor noise on the gyro, offering a stabilized running environment. Averaging 1.5 screws per arm, the quick-release structure makes assembly and disassembly easily

Honeycomb-shaped aluminum alloy CNC drone head ensures a better strength and look, with H-FOV 130° section, the drone head gets a larger field of view. Furthermore, the incorporated DJI O3 Air Unit also supports ND filters and changeable side plate mounting

The TPU side plate inside the CNC part helps dampen the vibration on the camera, and it can be modified by pilots on their own to get it compatible with more mounting holes and get rid of vignetting for clear images

Under the VTX, there is a honeycomb-shaped aluminum alloy heat sink improving the operation stability of FPV and high-power analog VTX.

 ## Stack
 ![alt text](img/stack.png)

 Selecting an “FC stack” – which includes both a flight controller board and a 4in1 ESC board – is a wise choice for beginners. With minimal soldering required, these stacks are often plug-and-play, making assembly smooth and straightforward.

 ## Motors
 ![alt text](img/motors.png)

 While popular motors of similar sizes often have comparable performance, the key differentiator typically lies in their build quality. For a 5″ FPV drone, motor sizes such as 2306, 2207, and 2208 are all viable options – for further more info you can visit this link https://oscarliang.com/2306-2207-mini-quad-motor/

 Another important factor to consider is motor KV, which is determined by battery voltage. For 6S LiPo, KV values ranging from 1600 to 1900 are common, with higher KV values providing more aggressive and power-hungry performance. In this build, we’re using 1855KV motors, as I plan to use 6S LiPo battery. While 4S builds are also popular, I personally prefer 6S over 4S you can visit this link https://oscarliang.com/6s-mini-quad-racing-drone/ for more idea.

 ## FPV Setup
 This FPV VTX delivers clearer video image, longer transmission range, and, most importantly, an unforgettable FPV flying experience. Moreover, it supports smart audio, pit mode. The power up to 1200mW is quiet suitable for longe range flight. 

 ![alt text](<img/Akk x-2 ultimate.png>)

 ## Radio Receiver

 ![alt text](img/radioreceiver.png)

Your choice of radio transmitter dictates the type of receiver (RX) you can use.your radio should support ExpressLRS
 ExpressLRS is affordable, high-performance, and incredibly reliable!
  I’ve selected the Radiomaster RP1 receiver, which ensures reliable, stable, and accurate signal reception, allowing for superior performance in demanding environments and enhancing the flight experience.
**For Other equipment check it out in the parts list table.**

## Steps of Building FPV Drone

<p align="center"><span style="color:#E5C129; font-size:30px">Frame Assembly</span><br></p>
You don`t need to worry about the frame assemble because when you buy a frame for drone it provide manual of how to assemble that frame.

![alt text](img/img1.png)
![alt text](img/img2.png)
![alt text](img/img3.png)
![alt text](img/img4.png)
![alt text](img/img5.png)
![alt text](img/img6.png)
![alt text](img/img7.png)
![alt text](img/img8.png)

 - ## Wiring Diagram
Before proceeding, it’s a good idea to create a wiring diagram on a piece of paper outlining how to connect all the components. If you’re using the components I recommended, here are connection diagrams you can follow.
![alt text](img/wiringfc.png)


## 1. Installing ESC <br>
Begin by replacing the four shorter screws in the frame with the long M3 30mm bolts that come with the Speedybee F405 V3 stack. Avoid using nylon standoffs for installing FC, ESC and VTX, they break easily in crashes. Use metal bolts instead.
Use metal bolts for installing stack (with a metal nut at the botttom), it reduces vibration and wobble, makes the drone fly better and easier to tune.

- Slide the 4in1 ESC and FC boards onto the four long screws, ensuring the ESC board’s power pads face backward and the motor solder pads face up. The front of the frame is identifiable by the cut-outs for the camera mounting plates.
- Inspect the bottom of the ESC to ensure it’s not touching the frame. Additionally, check for any contact between the ESC and FC.
Next, you’ll do some soldering
## 2. Installing Motors 
![alt text](img/motors-wiring.png) 
- Determine the required motor wire lengths, leaving a little slack, and cut them accordingly. Secure the motor wires on the arms with cloth tape or electrical tape.
- Then, strip about 2mm off the tip of the wires and tin the ends.
- Using the trimmed off motor wires, solder two of them to the input power of the ESC (ideally on the bottom side). Mark the positive wires with a piece of tape to solder the capacitor to later. 
- Tin all the solder pads on the 4in1 ESC. To prevent solder from accidentally dropping onto the components and causing electrical shorts, cover the areas of the board where you’re not soldering with tape, such as electrical tape, kapton tape, or masking tape.

Solder the motor wires onto the ESC. Don’t worry about wire order and motor direction yet; you can change this later in the software. If you have the skills, you could try to solder motor wires side way, make it nicer to grab the quad.

Solder the XT60 power lead to the power pads on the ESC, making sure to maintain the correct polarity (positive and negative). This step may be challenging due to the amount of heat required to melt the solder on the large copper pads. Be patient and use a higher temperature on your iron.

Soldering Tips:
- Use a good amount of solder and solder flux (solder paste) for the large pads, ensuring the solder joints are shiny and full. If you can see the wire strands, you haven’t applied enough solder.
- Apply more flux if the solder “sticks” to the tip when you remove it from the joint.
- Feel free to use a high temperature when soldering large solder pads, but be quick and avoid overheating the pads for too long. Use 450°C (840°F) for motor wires and XT60, and 380°C for signal wires.
- Now solder the 1500uF capacitor that comes with the Speedybee stack. Bend and shorten the legs with pliers, then tin them with solder.
- Solder the capacitor to the wires connected to the ESC power pads earlier, being mindful of the polarity. The side with yellow marking is the negative side of the capacitor.

## 2. Installing Camera
![alt text](img/RUNCAM.png)
- Solder the CAMERA wires connect to the flight controller **5v, ground, cam** pads.

## 3. Installing GPS to Flight Controller
Wiring a GPS module to the flight controller is quite straightforward. Simply connect it directly to any available UART on the FC, (TX to RX, RX to TX), and power it with 5V.
![alt text](img/modifyGPS.png)
- Solder the **5v** wire of the gps to the **4v5** pad of the FC 
- Solder the **G** wire of the GPS to the **G** pad of the FC
- Solder the **TX** wire of the gps to the **T6** pad of the FC
- Solder the **RX** wire of the gps to the **R6** pad of the FC
- Solder the **SDA** wire of the gps to the **SDA** pad of the FC (if GPS has a compass/barometer) 
- Solder the **SCL** wire of the gps to the **SCL** pad of the FC (if GPS has a compass/barometer)

## 3. Installing Receiver
![alt text](img/receiver.png)
- Solder the **5v** wire of the receiver  to the **4v5** pad of the FC
- Solder the **G** wire of the receiver  to the **G** pad of the FC
- Solder the **RX** wire of the receiver  to the **T2** pad of the FC
- Solder the **TX** wire of the receiver  to the **R2** pad of the FC

## 3. Installing VTX
 ![alt text](<img/VTX (1).png>)
- Solder the **7-26v** wire of the vtx  to the **9v** pad of the FC
- Solder the **G** wire of the vtx  to the **G** pad of the FC
- Solder the **Video** wire of the vtx  to the **VTX** pad of the FC
- Solder the **Smart Audio(SA)** wire of the recvtxeiver  to the **T1** pad of the FC

## Software
![alt text](img/inav.png)

Inav is a flight control software, which was forked from Clean Flight. The software supports both multi-rotors and fixed wings and has good GPS modes like Return to launch (RTH) etc. The software has a mission planner, which allows for setting full autopilot GPS way-point navigation. It supports a variety of Flight controller boards and is actively being developed by the community.

## Download iNav Configurator
- Download the latest iNav Configurator here: https://github.com/iNavFlight/inav-configurator/releases

## Checking iNav Compatibility
- Before proceeding, verify if your flight controller is compatible with iNav.
In the iNav Configurator, on the Firmware Flasher page, search for your FC’s firmware target. If it’s listed, congratulations, you can proceed to the next step. If not compatible, consider getting a new FC, such as the Speedybee F405 V4 – an affordable, feature-rich option ideal for an iNav drone build.

![alt text](img/firmware.png)
 

 ## Flashing  INAV
 - First if you have an existing setup in Betaflight you need to backup your setup before you proceed INAV, Then if you have done backup you setup in BetaFlight.<br> Select the firmware target for your FC. Note that the Auto-select button may not work if your FC is still running Betaflight.

Enable “Full chip erase” and leave the other options unchecked. 

![alt text](img/Flashing-INAV.png)


## Default Values
- After installing iNav, you’ll be prompted to choose a preset that most closely matches your quad, such as 3-inch, 5-inch, or 7-inch quad.
![alt text](img/sizequad.png)

## Setup Tab
- In the first page – Setup, you can view the status of your drone.
![alt text](img/setup-tab.png)

## Board Orientation

Hold the drone in your hand, point the camera towards the computer screen, and click the “Reset Z-Axis” button. Now move the drone around and see if the 3D model moves exactly as you do.

Troubleshooting:
- If the 3D model is inverted (upside down), and you have a red cross next to “UAV is levelled” in pre-arming checks, you can fix this in the board alignment tool, e.g., enter 180 in roll.
- If the drone moves in the opposite direction because the FC is rotated, you can also correct this in the board alignment tool, e.g., enter 180 in yaw.

## Calibration Tab


Here we will calibrate the accelerometer.

![alt text](img/calibrationtab.png)

Place the drone on a level surface and go through the 6-step calibration. Note that for every step, you need to click the “Calibrate Accelerometer” button.

It might seem a bit complicated at first, but don’t be afraid to start over if needed. The calibration doesn’t have to be super precise—just do your best to position the quad in each intended position.

## Mixer Tab

Normally, you shouldn’t need to change anything here since the “Default Values” should have applied these settings for you. However, it’s good practice to double-check.

- Platform: “Multirotor”.
- Mixer preset: “Quad X”.

![alt text](img/mixertab.png)

If you want to run reverse motor direction (props out), select “Reversed motor direction / Props-out configuration”.

Click Save and Reboot.

## Outputs Tab

This tab functions similarly to the Motors tab in Betaflight.

Note that motor outputs are disabled by default in iNav, a safety feature that differs from Betaflight. Motors WILL NOT work until you manually enable the “Enable motor and servo output” option.

![alt text](img/outputstab.png)

In the Outputs tab, select DShot300 as the ESC protocol.

I personally set a default Motor Idle Power % for 7-inch quads.
Since default in iNav is high Idle Power, which is more suited for larger drones with high power.

Click Save and Reboot. Power cycle the FC by unplugging both the USB cable and battery.

**Warning:** Ensure to remove propellers before proceeding to the next step.

Now, test the motors using the sliders in the Outputs tab to check if they spin, and if they spin in the correct direction.

![alt text](img/outputsmotor.png)

**Troubleshoot: What if the motor order is wrong?**<br>
Unlike Betaflight, iNav does not support resource remapping. To change motor order, you can adjust settings in the Mixer tab. Remember, after making changes, just hit Save and Reboot—there’s no need to click LOAD and APPLY. After changing the motor order in the Mixer, it won’t reflect in the outputs tab, but you should conduct a test hover to make sure it works correctly.


## Ports Tab
Setting up ports in iNav should feel familiar to those used to Betaflight. If you’ve taken screenshots from Betaflight, you can simply replicate the setup here.

![alt text](img/portstab.png)

## Configuration Tab
In the Configuration tab, you can select the sensors connected to the flight controller, such as GPS, compass, barometer, optical flow sensor, etc.

## How to bind receiver to transmitter?
Here are the steps for binding a traditional RC receiver to a transmitter using the "plug in the battery 3 times" method.

1. Prepare the transmitter:
    - Turn on the transmitter
    - Click "Sys" button on the right side of the transmitter
    - Select ExpressELRS
    - Locate the "BIND" labeled on the transmitter.
2. Prepare the Receiver:
    - Disconnect the receiver from any power source.

3. Enter Binding Mode:
    - Plug in the receiver's battery three times, pausing for a few seconds between each connection.
    - On the third connection, the receiver's LED should start blinking, indicating it is in binding mode.

4. Initiate Binding on the Transmitter:
    - Press the "BIND" labeled on the transmitter.

5. Wait for Successful Binding:
    - The transmitter and receiver will now communicate and establish a connection.
    - Once the binding is successful, the receiver's LED will typically change to a solid pattern.

6. Verify the Connection:
    - Move the transmitter's controls and observe the corresponding movements on the connected devices (e.g., servos, motors) on the receiver tab in INAV.

## Receiver Tab
For ExpressLRS or Crossfire receivers, select SERIAL as the receiver type, and CRSF as the receiver provider. Click Save and Reboot.

Now, you can test the radio link to ensure the channel values correctly respond to your radio stick movements. If the channel order is wrong, try a different channel map.

![alt text](img/receiverTab.png)

I recommend setting “Use automatic RC smoothing” to ON, then adjusting the auto smoothing factor to fine-tune response to stick movements. This is particularly beneficial for radio links with dynamic refresh rates, such as ExpressLRS and Crossfire.

## GPS Tab
- Check the GPS for navigation and telemetry
- Select UBLOX protocol **Note:** you must check the gps if support UBLOX protocol.
- Select Gps use Galileo Satellites (EU) **If supported**
- Gps use Glonass Satellites (RU) **If supported**

![alt text](img/gpsTab.png)

## Advanced Tuning Tab
Stick with default settings.

## PID Tuning Tab
Stick with default settings.

## Failsafe Tab
If you want to try the RTH,<br>
select RTH
![alt text](img/failsafeTab.png)

## Modes Tab
The Modes tab in iNav closely resembles that of Betaflight, but it uses CH5, CH6, etc., instead of AUX1, AUX2. It’s all quite straightforward.

![alt text](img/modesTab.png)

If using ExpressLRS receiver, be sure to assign CH5 to ARM, as this is the default channel for arming.

Useful modes in iNav for an FPV drone include Angle mode, Turtle mode, Beeper. And if your drone is equipped with GPS, Nav Position Hold and Nav Return to Home are also very important.

## OSD

Under Video Format, select your preferred video system. Enable any elements you desire and arrange them as in Betaflight.

![alt text](img/osdTabs.png)