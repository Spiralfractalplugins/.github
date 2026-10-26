# Spiralfractal Plugins

**Experimental audio plugins, synthesizers, and synth firmware for music makers.**

This organization is a collection of open-source audio software projects — from VST3/AU/CLAP synthesizers to custom firmware for hardware grooveboxes.

---

## 🎛️ Flagship Projects

### [spiral303](https://github.com/Spiralfractalplugins/spiral303)
Roland TB-303 style VST3/AU/CLAP/LV2 synthesizer with a built-in sequencer, built on JUCE 8, plus a WASM CLAP build.
- **Language:** C++ · **License:** GPL-3.0

### [spiralquant](https://github.com/Spiralfractalplugins/spiralquant)
A wavetable synthesizer with a twist: instead of a classic wavetable, each voice's oscillator is a complex-valued solution of the 1D time-dependent Schrödinger equation, evolved in real time with a split-step Fourier method on a 128-point grid.
- **Language:** C++ · **License:** GPL-3.0

### [spiralfm1](https://github.com/Spiralfractalplugins/spiralfm1)
Custom firmware for the M-VAVE FM-1.
- **Language:** C

---

## 🎹 Synth & Emulation Forks

### [ms2000r-emu](https://github.com/Spiralfractalplugins/ms2000r-emu)
Fork and update of ms2000r-emu for macOS — Korg MS2000R emulation.
- **Language:** C++ · **License:** GPL-3.0

### [gearmulator](https://github.com/Spiralfractalplugins/gearmulator)
Fork of [dsp56300/gearmulator](https://github.com/dsp56300/gearmulator): low-level emulation of classic VA synths & effects of the late 90s/2000s by emulating the used ICs.
- **Language:** C++ · **License:** GPL-3.0

### [Animatek-NME](https://github.com/Spiralfractalplugins/Animatek-NME)
Fork of [animatek/Animatek-NME](https://github.com/animatek/Animatek-NME): modern JUCE/C++ reimplementation of the Nomad editor for the Clavia Nord Modular G1 synthesizer.
- **Language:** C++ · **License:** GPL-3.0

---

## 🥁 Hardware Firmware

### [fm1-x0x](https://github.com/Spiralfractalplugins/fm1-x0x)
Fork of [charlesvestal/fm1-x0x](https://github.com/charlesvestal/fm1-x0x): X0X groovebox firmware for the M-VAVE FM-1 (909, 808, two 303s with TB-3PO, breakbeat generator, song mode).
- **Language:** C · **License:** GPL-3.0

### [FM-1-TripDeck](https://github.com/Spiralfractalplugins/FM-1-TripDeck)
Fork of [anonymousacademe/FM-1-TripDeck](https://github.com/anonymousacademe/FM-1-TripDeck): psychedelic synth firmware for the M-VAVE FM-1. Every screen is an animated picture, and its four knobs change the sound and the picture together — sitar and tamboura, pads, organ and Leslie, FM bells, shimmer reverb, vowel filter, spiral echo.
- **Language:** C · **License:** GPL-3.0

---

## 🧰 Other

### [.github](https://github.com/Spiralfractalplugins/.github)
Organization profile and community health files.

---

## 🛠️ Tech Stack

| Area | Tools |
|------|-------|
| Plugin development | C++, JUCE 8 |
| Plugin formats | VST3, AU, CLAP, LV2, WASM |
| Firmware | C, embedded |
| Tooling | Rust |
| Emulation | C++ (DSP56300) |

---

## 🚀 Getting Started

Each repository contains its own build instructions in its `README.md`. Most C++/JUCE projects can be built with CMake, while firmware projects typically require an appropriate embedded toolchain and flashing procedure for the target device.

```bash
# Example: clone a plugin repo
git clone https://github.com/Spiralfractalplugins/spiral303.git
cd spiral303
# See the repo's README for build steps
```

---

## 🤝 Contributing

Contributions, bug reports, and feature ideas are welcome! Please open an issue or pull request in the relevant repository. Since several projects are forks, consider contributing upstream where appropriate.

---

## 📄 License

Most repositories are licensed under **GPL-3.0**; some are under **MIT**. Check each repository's `LICENSE` file for details.

---

## 🔗 Links

- **GitHub Organization:** [github.com/Spiralfractalplugins](https://github.com/Spiralfractalplugins)
- **Contact:** Open an issue in any repository.

---

*Built with a love of synthesis, DSP, and experimental sound design.*
