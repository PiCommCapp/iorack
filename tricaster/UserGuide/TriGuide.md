# Tricaster Mini 4K User Guide

## General Information

A homepage can be found on the engineering computer, or any computer on the IO Rack network by using a web browser and navigating to [http://192.168.10.12:3000](http://192.168.10.12:3000). The page includes links to all device configuration pages, as well as manufacturer websites. All hardware devices will also show it ping latency next to the title.

## Kit Contents

### Tricaster Mini Case

- 1x Tricaster Mini 4K
- 1x Tricaster Mini Control Panel
- 1x Power Supply w/ IEC cable
- 1x USB Keyboard
- 1x USB Mouse
- 4x Mini-DisplayPort to Displayport Adapters
- 2x Spark Plus HDMI bi-directional NDI interface

## Equipment

### Tricaster Mini 4K

| Information     | Website                                                                                                        |
|-----------------|----------------------------------------------------------------------------------------------------------------|
| Product website | [vizrt.com/products/tricaster/tricaster-mini-4k/](https://www.vizrt.com/products/tricaster/tricaster-mini-4k/) |
| Documents       | [docs.vizrt.com](https://docs.vizrt.com/)                                                                      |

#### Physical Connections

##### Front Panel

![Tricaster Mini 4k Front Panel](./photos/tri_front.png)

- Line level audio inputs and outputs.
- Monitoring headphones output.
- Microphone input

##### Rear Panel 



- Displays should always be connected via one of the four Mini Display-port connectors.
- The principle network should be connected to the blue network port.
  - additional network ports can be connected to expand network bandwidth to device. **Not generally needed.**
- Keyboard, mouse, and control surface connect via USB.

#### Show Creation & Configuration

#### Operation

##### Mini Controller Layout

##### Switching

###### Transistions



### Engineering Computer

The Engineering computer hosts services for the setup and monitor of the IO system. 

One Primary purpose is to act as the NDI Router. It does this by running [ZEN NDI Router](https://www.ndistuff.uk/zen-ndi-router-remote-panel/). Zen must be started after the computer is started. This can be done with a local keyboard and screen, or using MS Remote Desktop at the PC's IP address. Once the router software is running select "Load Config" and load the config from the desktop.

The PC also hosts the [system webpage](http://192.168.10.12:3000).

### Spark IO Devices

- Device should be connected via the "NDI/PoE" port to the network
  - Device can be powered via USB-C is needed
- Navigate 

### PTZ Controller

#### Installation

![PTZ Rear Panel](./photos/ptz_keyboard_rear.png)

- Connect Keyboard to network using the "LAN/PoE" RJ45 connector on the back of the device. (A)
- Power can be provided by PoE, or by using a power supply. (B)

#### Operation

![PTZ Keyboard](./photos/ptz_keyboard_key.png)

| Command       | Keypress                                                   |
|---------------|------------------------------------------------------------|
| Select Camera | Type Camera NUM [0-9] then CAM (D)                         |
| Record Preset | Type Position NUM [0-9] then hold PRESET (B) for 3 seconds |
| Recall Preset | Type Position NUM [0-9] then CALL (C)                      |
| F1*           | Select Camera 1                                            |
| F2*           | Select Camera 2                                            |
| F3*           | Select Camera 3                                            |
| F4*           | Home Position                                              |
| F5*           | Calibrate Pan and Tilt                                     |
| F6*           | Power Cycle Camera                                         |

*- In Pi Comms 3/1 Camera Setup

#### Configuration

### Birddog PTZ Cameras

### Netgear Network Switch

### Unifi Gateway