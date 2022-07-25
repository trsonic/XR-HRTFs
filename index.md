---
title: Home
layout: default
---

This paper discusses a Head Related Transfer Function (HRTF) measurement system utilizing a minimal hardware configuration. Thanks to the visual 3D cues displayed by a mixed-reality headset, the subject positions their head in relation to the single loudspeaker following a predefined list of measurement points. During this automated procedure, Head Related Impulse Responses (HRIRs) of the individual are captured at different sound incidence angles. The proposed post-processing of the measured responses is aimed at eliminating the acoustic characteristic of the room where the measurement was taken. A direction-dependent correction filter derived from laboratory measurements is proposed in order to compensate for the influence of the XR headset on HRTFs.

## Hardware Requirements
## XR headset
Currently the only supported headset is Quest 2.

## Loudspeaker
The system was mainly tested with a custom 3D printed loudspeaker, however it should work fine with any decent audio source.

## In-ear Microphones

## PC with Audio Interface

Any Windows, Mac or Linux PC should work. The systems was tested with RME Fireface USB interface.

## Software
### XR Interface
[SOURCE](https://github.com/trsonic/XR-HRTF-Q2/)

### Measurement control app
[SOURCE](https://github.com/trsonic/XR-HRTF-capture-juce/)

### Postprocessing
[SOURCE](https://github.com/trsonic/XR-HRTF-processing/)
