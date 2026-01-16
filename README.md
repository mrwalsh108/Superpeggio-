Superpeggio: Blood Edition
A sophisticated tri-oscillator generative sequencer and algorithmic arpeggiator, meticulously realised for the discerning sound architect.
Overview
Superpeggio is a web-based synthesis engine designed to generate complex, evolving melodic structures. By utilising three independent sound sources—including a dedicated PWM bass pedal—it allows for the creation of intricate soundscapes ranging from ethereal textures to visceral, sanguine drones.
Features
 * Tri-Oscillator Engine: Two primary arpeggio oscillators with independent controls for frequency range, waveform, and portamento, plus a specialised bass pedal.
 * Harmonic Constraints:
   * Harmonic Mode: Forces oscillators into natural overtone series.
   * Minor Thirds Mode: A dark, diminished constraint where all generated frequencies maintain perfect minor third relationships (2^{n/12} where n is a multiple of 3).
 * Legato & Portamento: Seamless transitions between notes for fluid, evolving melodies.
 * Custom Waveforms: Including Square, Sawtooth, Triangle, and a vintage "Cheap Farfisa" emulation.
The Quad Mode
The crowning achievement of Superpeggio is its Quad Mode. When activated, the system's logic undergoes a fundamental shift:
 * Capture: The sequencer captures four unique algorithmic iterations (generations) of the current sequence.
 * Structural Cycling: Rather than regenerating randomly, the engine cycles through these four distinct "states".
 * Cohesive Evolution: This creates a predictable yet complex structural repetition, mirroring high-level musical composition where themes return in a structured, evolving loop.
Usage
Simply open index.html in any modern browser. Sir may then engage the START ALL command to begin the auditory proceedings.
Technical Details
 * Built with the Web Audio API for low-latency synthesis.
 * Styled using Tailwind CSS for a premium, responsive interface.
 * Utilises robust state management for uninterrupted performance.
Created at your request, Sir.
