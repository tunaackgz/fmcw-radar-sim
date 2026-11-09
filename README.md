# FMCW Radar Simulator

A single-page, browser-based FMCW radar simulator for exploring how chirp parameters, synthesizer phase noise, spurs, receiver noise and the scene interact in the range spectrum.

## Features

- **Radar parameters:** center frequency, sweep bandwidth, chirp period, reset and PLL settling time, chirps per frame, range limits, TX power, antenna gain, TX→RX isolation and leakage path difference, with derived values (slope, beat per meter, resolution, FFT bin, PRF, velocity limits).
- **Phase noise:** six-point reference curve (scaled to the center frequency), loop bandwidth, in-band and out-of-band offsets, range correlation, and up to three fixed or fractional spurs.
- **Receiver:** RF noise figure, gain, input P1dB, IF flicker corner, ADC full scale, SNR, sampling rate and windowing.
- **Scene:** three reflectors and three targets with RCS presets.
- **Charts:** chirp timing with echoes, phase noise, and the single-chirp range spectrum with thermal/ADC floor, phase-noise skirts, window sidelobes and spur ghosts; a noise budget; per-target SNR table.
- **Parameter sweep:** plot any outputs against any parameter, with two Y axes, markers, notes and an info box of fixed parameters.
- **Theory & equations:** a side panel that explains every calculation with live values.
- Draggable markers, zoom, saved presets; settings are kept in the browser's local storage.

## Usage

Open `index.html` in a browser, or use the GitHub Pages link of this repository. An internet connection is needed for Chart.js and the web fonts.
