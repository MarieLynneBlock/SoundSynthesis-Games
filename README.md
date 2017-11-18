# Sound Synthesis for Games and Interactive Systems


### 1. ChucK
Covering the fundamentals of programming in general (logic, loops, functions, objects, classes) and also deals with advanced topics including multi-threading, events and signals. Throughout the course, students create meaningful and rewarding expressive digital “instruments” that make sound and music in direct response to program logic. The ChucK language provides precise high-level control over time, audio computation, and user interface elements (track pad, joysticks, etc.). ChucK is used (unknowingly in most cases, via SMule Apps) by millions of users throughout the world, and is the backbone of dozens of academic programs and laptop orchestras. Learning to program using ChucK, through the musical examples, will prepare students to program in C++, Java, and other languages.


### 2. Digital Sound Synthesis
Introduces the basics of Digital Signal Processing and computational acoustics, motivated by the vibrational physics of real-world objects and systems. We build anything from a simple mass-spring and pendulum to demonstrate oscillation, demostrate how to simulate those systems in the computer, and also prove that these simple oscillations behave as a sine wave. From that we move to plucked strings and struck bars, showing both solutions as combined traveling waves and combined sine wave harmonics. Then it continues by building and simulate more complex systems containing many vibrating objects and resonators (stringed instruments, drum, plate), and also show how to simulate echos and room reverberation. Through this process, we will learn to understand all about digital signals, filters, oscillators, harmonics, spectral analysis, linear and non-linear systems, particle models, and all the necessary building blocks to synthesize essentially any sound.

-----

## Build Up
### 1. ChucK Programming
__1.1 : Basics: Sound, Waves, And ChucK Programming__  
__1.2 : Libraries And Arrays__  
__1.3 : Sound File Manipulation__  
__1.4 : Functions__  
__1.5 : Unit Generators And Physical Models__  
__1.6 : Multi-Threading And Concurrency__  
__1.7 : Objects And Classes__  
__1.8 : Live Control: Keyboard, Mouse, MIDI & OSC__  


### 2. Digital Sound Synthesis
__2.1 : The Time Domain: Sound, Digital Audio, PCM Files, Noise Vs. Pitch, A Hint Of Spectra__  
    - Sound in Air, Traveling Waves  
    - Digital Audio, Sampling  
    - Quantization, Aliasing  
    - Soundfiles, Wavetables, Manipulating PCM  
    - Pitch (vs. Noise), Spectral Analysis 0.1  
    - Time-domain Pitch/Noise Detection: ZeroXings, AMDF, Autocorrelation    
    
__2.2 : Physics, Oscillators, Sines & Spectra, Spectral/Additive Synthesis__
    Mass-Spring-Damper system, simple Pendulum  
    Fourier analysis/synthesis, Spectrum Analysis 1.0  
    More on additive Sine-wave synthesis  
  
__2.3 : Digital Filters, Modal Synthesis__
  - Digital Filters, Finite Impulse Response (FIR)
  - Linearity, Time-invariance, Convolution
  - Infinite Impulse Response (IIR) Digital Filters
  - BiQuad Resonator Filter, Modal Synthesis  
    
__2.4 : Physical Modeling Synthesis I: 1D Systems__
  - 1D systems, Strings, Modal (Fourier) Solution
  - Strings II: Waveguide (D’Alembert) Solution
  - 1D systems, Bars, Tubes, solutions
  - Advanced Waveguide Synthesis for 1D systems
  
__2.5 : Physical Modeling II: 2D And 3D Systems__ 
  - 2D systems, plates, drums, higher-order modes Fourier (Sine and/or Modal) Solutions, Waveguide Solutions
  - 3D systems, rooms, resonators, Meshes, Waveguides
  - Resonator/Modal view and solution of 3D systems Pop bottles and other lumped resonators
  
__2.6 : Subtractive Synthesis, Vocal Sounds And Models__ 
  - Subtractive Synthesis, Voice Synthesis, Formants
  - Linear Prediction, LPC
  - FOFs
  - FM Synthesis: Horns, Bells, Voices
  
__2.7 : Grains, Particles And Statistical Models__
  - Wavelets
  - Granular Synthesis
  - Particle Models, Statistical Modal Synthesis
  - Wind, Water, Surf, and Other Whooshing Sounds

__2.8 : Extending And Refining Physical Synthesis Models__ 
  - Waveshaping Synthesis, Distortion Modeling
  - Time-Varying Systems
  - Stiffness, All-Pass Filters, Banded Waveguides
  - Commuted Synthesis
  - JULIUS on KS, strings, demos

__2.9 : Applications, Sonification, Interactions, And Control__
  - Scanned Synthesis
  - Don’t forget the laptop!!! SMELT:
  - Controlling Synthesis with game controllers (Wii, mobile TouchOSC, more)
  - Walking Synthesis, a complete system
  - Procedural Audio: Driving synthesis from process, game state, etc.
  - Data set Sonification

