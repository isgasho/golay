golay
=====

golay is a Go package which provides golay 23/12 error correction encoding and decoding.

This library is a port from [golay.c](https://github.com/ArduPilot/SiK/blob/8a690a28647ee6085e7dce456ab3963a350acb2d/Firmware/radio/golay.c) and [golay23.h](https://github.com/ArduPilot/SiK/blob/8a690a28647ee6085e7dce456ab3963a350acb2d/Firmware/radio/golay23.h) in [ArduPilot/SiK: Tools and firmware for the Si1000](https://github.com/ArduPilot/SiK)

## Project status
* All patterns of roundtrip of encode then decode without injecting error works correctly (confirmed with test).
* I am not sure about the behavior of error correction.
    *  TestEncodeDecodeOneError fails for some cases and I don't know whether it is expected or not.

## LICENSE
BSD-2-Clause
