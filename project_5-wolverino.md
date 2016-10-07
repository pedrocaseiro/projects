# Wolverino

## Introduction

Wolverino is a multimodal plug & play controller for artificial limbs, human augmentation and/or animatronics pieces, which can use muscle signals or remote control over a mobile app to trigger specific actions on the pieces. 

## Description

Wolverino uses (relatively) low-cost battery powered devices that can be attached to standard 3D printed prosthetics, exoskeletons or animatronic pieces, to enable dynamic control based on user inputs. It has two operation modes, namely "Interactive" and "Presets" mode. 

In "Interactive" mode, Wolverino provides interactive control of the prosthetics and/or animatronics piece by measuring signals from any surface muscle on the body and using them to trigger an action.

In "Presets" mode, Wolverino is wirelessly controlled from and Android app to place the prosthetics and/or animatronics piece in a pre-programmed position (e.g. clench, pinch, open hand, ...). 

The target audience are people with prosthetic limbs, cosplayers and bio-hackers.

To bring our proof-of-concept to life we will use littleBits, Android, BITalino and a lot of 3D. 

## Team

 * Hugo Silva https://pixels.camp/hugoslv
 * Paulo Pires https://pixels.camp/pires
 * Ricardo Pereira

## Code repository

You can find our code at https://github.com/hugoslv/wolverino

All the resources are released under the [Apache License, Version 2][1].

## URL 

http://enablingthefuture.org

http://bitalino.com

http://littlebits.cc

https://beeverycreative.com

https://www.android.com

## Other information

The current limitations of Wolverino are the fact that it only uses a single muscle channel for input, which provides few degrees of freedom for control and the fact that it doesn't yet have an integrated form factor. Furthermore, the servo currently only sweeps about 140º due to hardware limitations. We intend to solve these problems after Pixels Camp by using multiple input channels and creating a purpose-built hardware base.

[1]: https://www.apache.org/licenses/LICENSE-2.0
