# SALEK HIGHTECH

Professional JUCE/C++ **VST3 + Standalone** synthesizer  
Target: **Hi-Tech / Darkpsy / Psytrance / FM Bass / Acid / Screech / Metallic / Alien / Cyberpunk**  
Typical range: 170–190+ BPM

## Build (Windows CI)

Push to `main` or run **Windows VST3 + Standalone** workflow.  
Artifact: `SALEK-HIGHTECH-Windows.zip` (`.vst3` + `.exe`)

```bash
cmake -B build -G "Visual Studio 17 2022" -A x64
cmake --build build --config Release
```

## Features (real DSP)

- 3 wavetable oscillators (morph, warp, fold, drive)
- FM / PM / AM / RM cross-mod
- Multimode SVF filter + LFO + mod matrix
- Amp ADSR, 4 macros
- Arpeggiator + 16-step sequencer
- Master drive + stereo delay
- Wavetable lab
