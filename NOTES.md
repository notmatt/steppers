# What the heck is this stepper, anyway?

Notes on the various steppers I have, relevant links (doubtful), and any notes on their provence that I happen to remember, which is also unlikely, since I've accumulated them over a number of years.

---
Table of Contents
- [What the heck is this stepper, anyway?](#what-the-heck-is-this-stepper-anyway)
- [List of steppers](#list-of-steppers)
	- [21-02485-03](#21-02485-03)

---

# List of steppers

## 21-02485-03

Small (nickel-sized) stepper from [Goldmine Electric][gme], product [G14197](https://www.goldmine-elec-products.com/prodinfo.asp?number=G14197), that must have been on a deal at some point. Has a ["datasheet"](./G14197.pdf) that's actually a schematic.

> 2 phase bi-polar / Quadrature miniature stepper motor. Small 0.8" diameter x 0.68" thick stepper motor features a knurled 0.30" long x 0.06" diameter shaft.

5V, 9V [reported works](https://lcamtuf.coredump.cx/gcnc/ch5/), 20 steps per revolution, 15° per step. 4-pin connector, but weirdly 5 leads, with the black and white shorted at the connector, so presumably it's not actually bipolar construction, but let's go with that.

> a 5-wire hybrid that is best operated in bipolar mode (where the polarity of the windings needs to be reversed, necessitating the use of H-bridge drivers), and runs fine at 9V. 15° per step, 100 mA per coil, around 40 g*cm of torque.

Good practical guide available here: https://ryanschenk.com/code/driving-a-040-stepper-with-arduino.html ([pinboard](https://pinboard.in/u:smillie/b:b9911a1aecab)).



<!-- linkadelia -->
[gme]: https://www.goldmine-elec-products.com
