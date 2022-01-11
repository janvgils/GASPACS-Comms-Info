# GASPACS CubeSat Communications Information
GASPACS is a 1U CubeSat designed, developed, and completed by undergraduate students on the Get Away Special team at Utah State University.

GASPACS stands for **G**et **A**way **S**pecial **P**assive **A**ttitude **C**ontrol **S**atellite. The satellite is a technology demonstration for an inflatable boom structure that will double as a passive attitude stabilization device due to the aerodynamic drag in Low Earth Orbit (LEO). 

GASPACS was launched on 12/21/2021 on SpaceX CRS-24. GASPACS is currently aboard the International Space Station (ISS), with deployment into orbit via the NanoRacks CubeSat Deployer (NRCSD) scheduled for the week of 1/24/2022. This page will be updated after deployment with information on tracking GASPACS and ongoing mission operations.

## RF Specifications:
- Center frequency: 437.365 MHz
- Baudrate: 9600
- Modulation: 2GFSK
- Polarization: Circular 
	- Both RHCP and LCHP
    - Polarization will change as GASPACS slowly rotates in space
- TX Power: 1W
- Antenna Gain: ~ 0 dBi, omnidirectional
- AX.25 beacon every 120 seconds
- Audio beacon every 300 seconds
- Telemetry & images downlinked when passing over Logan, Utah
- LEO orbit, deployed from ISS

## CubeSat Communications Hardware:

- Radio: [Endurosat UHF Transceiver](https://www.endurosat.com/cubesat-store/cubesat-communication-modules/uhf-transceiver-ii/)
- Antenna: [Endurosat UHF Antenna](https://www.endurosat.com/cubesat-store/cubesat-antennas/uhf-antenna/)

## Packet Structure:
- All packets transmitted by GASPACS utilize the Endurosat radio packet structure, containing a preamble, sync word, payload, and CRC16:


## GAS Team Ground Station:
- List all of our equipment for receiving
- Brief description of software we use
