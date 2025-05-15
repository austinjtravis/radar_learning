# radar_notes
Repo containing material for educating about radar/SAR topics.

Current course overview:
## Radar overview
### Introduction to radar (1-2 sessions)
* What is a radar?
*	Radar range equation
    - Tradeoffs in system design using radar range equation.
*	Common radar hardware elements/architectures (superheterodyne)
### How a radar determines range (1-2 sessions)
*	Basics on scattering problem
    - How we model scatterers
*	Ranging problem
    - Stick to sinusoidal waveform to avoid talking about pulse compression.
*	Radar resolution/compression
*	Potentially overview on sampling problem (Nyquist)
### Pulse compression and matched filtering (1-3 sessions)
*	Correlation (chirp) mode
*	Stretch mode.
*	Stepped frequency chirp approach
*	Overview on Fourier transform/convolution.
### Introduction to electromagnetics (wave propagation) and antennas (1-3 sessions)
*	Basics of EM (travelling waves)
    - How we model waves
*	Basics of antennas
### Antenna arrays and beamforming (1-2 sessions)
*	Overview of uniform linear array
*	Phased array antennas.
## SAR data collection overview
### SAR introduction (1 session)
*	Why do we form a synthetic aperture?
*	Common geometry terms
*	Types of collection modes
*	Basics of pulsed doppler radar
### Scene content (1 session)
*	Basics on scattering/RCS
*	Types of scatterers in scene
*	Brief scatterer modelling overview
### Range/Doppler and SAR geometry (2-3 sessions)
*	Range sphere/doppler cone
*	Ambiguities
*	Notion of slant range/slant plane/ground plane
### Sar timing (1-2 sessions)
*	Transmission/receiving of pulses.
*	Receive window sampling/timing.
### Spatial frequency (2-3 sessions)
*	Fourier transform reminder.
*	How the signal sampled is represented in spatial frequency.
*	How a scatterers position is represented in spatial frequency
*	How to form a bad image
### Scan mode overview (1 session)
*	Describe differences between
### Moving targets and doppler shifts (1-2 sessions)
*	We assumed everything we imaged was stationary but not anymore!
## SAR image formation techniques
### Overview of SAR polar formatting processing steps (1 session)
*	Just basic intro to stuff
### Motion compensation and matched filtering (1-2 sessions)
*	Maybe talk about ionosphere
*	Hopefully, matched filtering should be easy by this point!
### Polar formatting (2-3 sessions)
*	Motivation
*	How to polar format
*	How to form a good image
### Autofocus (1 session)
*	I’ll probably need help on this one or review a textbook.
### Detected image processing (1 session)
*	I’ll probably need help with this one or review a textbook.
*	What I mainly know about DI is
    - ground projection.
    - apodization
    - Trying to make square pixels in the ground (orthorectification).
