# 🌊 AuraFlux 

**Procedural Water & Resonance Synthesizer**  
*(The advanced, multi-parameter successor to AuraFlow)*

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat-square&logo=javascript&logoColor=%23F7DF1E)
![Web Audio API](https://img.shields.io/badge/Web_Audio_API-03DAC6?style=flat-square)

## 📖 Overview

**AuraFlux** is a browser-based procedural audio generator that transforms raw, mathematical noise into a musical, interactive soundscape. 

Instead of using pre-recorded audio samples, AuraFlux uses the native **Web Audio API** to generate chaotic noise algorithms and sweeping sine waves that simulate the fluid dynamics of water. By clicking "Resonant Water", the engine routes this chaotic water audio through extreme High-Q bandpass filters tuned to specific musical chords, effectively turning rushing water into a harmonic, playable synthesizer.

Whether you want the sound of a slow, dripping cave, a rushing waterfall, or an ethereal, ringing soundscape, AuraFlux gives you real-time control over the elements.

## ✨ Features

* **💧 100% Procedural Audio:** No samples are used. Every drop, bubble, and splash is generated in real-time via mathematics.
* **🎵 Resonant Harmonization:** Route the chaotic water audio through a bank of extreme High-Q bandpass filters tuned to musical scales (C Major, A Minor, F Maj7, D Dorian, Mystic).
* **🎨 Dynamic Noise Colorization:** Hot-swap the algorithmic background noise tone:
  * **Brown Noise:** Deep, sub-heavy rumbles.
  * **Pink Noise:** Balanced, natural flow.
  * **White Noise:** Hissy, rain-like texture.
  * **Blue Noise:** Crisp, high-end splashes.
* **🎛️ Live Density Control:** Scale the simulation from 1% (a slow, dripping stalactite) to 100% (a violently boiling geyser).
* **📊 Dual Visualizers:** Real-time canvas rendering featuring both an **Oscilloscope** (Waveform) and an **FFT Spectrum Analyzer** (Frequencies).
* **⚡ Zero Dependencies:** Written in pure HTML, CSS, and Vanilla JavaScript.

## 🚀 Getting Started

Because AuraFlux uses the native Web Audio API with zero external dependencies, installation is effortless.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/AuraFlux.git
   ```
2. **Open the app:**
   Simply double-click the `index.html` file to open it in any modern web browser (Chrome, Firefox, Safari, Edge).
   
*(Note: Browsers require you to interact with the page before audio can be played, so click one of the "Play" buttons to initialize the AudioContext).*

## 🗺️ Roadmap (Future Features)

We are constantly looking to expand the sonic capabilities of AuraFlux. Here is what is planned for future releases:

- [ ] **Custom Chord Builder:** Allow users to input their own frequencies or select specific notes on a virtual piano roll to create custom resonant filters.
- [ ] **MIDI Integration:** Support for Web MIDI API, allowing users to hook up a MIDI keyboard and "play" the water filters like a traditional synthesizer.
- [ ] **Audio Recording & Export:** Add a "Record" button to capture the procedural stream and export it as a `.wav` file for use in DAWs (Ableton, FL Studio, Logic).
- [ ] **Spatial Audio (3D Panning):** Implement binaural panning so different bubbles and frequencies spawn in random locations in the stereo field.
- [ ] **LFO Modulation:** Add Low-Frequency Oscillators to automatically sweep the water density and filter cutoffs (creating "tide" or "wave" effects).
- [ ] **Built-in FX Rack:** Add procedural Reverb and Delay nodes to create massive, cavernous atmospheres.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/yourusername/AuraFlux/issues).

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.
```

### How to use this:
1. Create a file named `README.md` in the same folder as your `index.html`.
2. Copy and paste the text above into the file.
3. Update the `yourusername` placeholders in the "Getting Started" and "Contributing" sections with your actual GitHub username.
