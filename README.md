# Phase Modulation DAW One HTML

A browser-based digital audio workstation (DAW) for phase modulation synthesis, implemented entirely in a single HTML file. Compose, design, and export complex sounds and music using advanced waveform and modulation controls—no installation required.

## Demo Video

Watch the demo video to see the DAW in action.
English subtitles are available.

[![Phase Modulation DAW Demo](https://img.youtube.com/vi/Wlhfg3w6xiA/0.jpg)](https://www.youtube.com/watch?v=Wlhfg3w6xiA&cc_load_policy=1&hl=en&cc_lang_pref=en)


## Features

- **Single-File Application**: All code, UI, and styles are contained in `Main.html` for easy use and sharing.
- **Multi-Channel Synthesis**: Add, copy, and delete multiple independent channels, each with customizable parameters and names.
- **Phase Modulation Synthesis**: Create rich, evolving sounds using phase modulation (similar to FM synthesis).
- **Comprehensive Controls** for each channel:
  - Carrier and modulator waveform selection (sine, square, triangle, sawtooth, noise, const)
  - Frequency, pitch, and volume controls (with min/max, LFOs, and phase)
  - Modulation depth and phase settings for both waveform and volume
  - Envelope shaping (attack, decay, sustain, release via LFOs)
  - Reverb (delay, feedback, decay)
  - Step quantization for melodic/rhythmic effects
  - Stereo panning
- **Timeline Sequencing**: Visual timeline for arranging channel start/end times and durations. Drag handles to adjust.
- **Real-Time Visualization**: Interactive waveform, volume, and pitch graphs update as you tweak parameters.
- **Audio Export**: Render and download your composition as a 24-bit stereo WAV file.
- **Project Management**: Save and load project configurations as JSON files.
- **No Dependencies**: Runs offline, no external libraries or frameworks required.

## Getting Started

1. Download `Main.html`.
2. Open it in a modern web browser (Chrome, Firefox, Edge, or Safari).
3. Start creating music!

## Interface Overview

- **Channel Tabs**: Each channel appears as a tab. Use the "+" button to add channels, the "Copy" button to duplicate, and the "Delete" button to remove. You can rename channels by editing their name field.
- **Parameter Panels**: Each channel exposes grouped controls for General, Melodic, Reverb, Waveform, Volume, and Pitch. Adjust sliders, dropdowns, and number inputs to shape your sound.
- **Timeline Panel**: Visualize and edit when each channel plays. Drag handles to set start/end times. Use the timeline scale and scroll controls for navigation.
- **Graph Panel**: See real-time waveform, volume, and pitch graphs for the selected channel.
- **Transport Controls**: Play (Preview), Stop, Export (WAV), Save (project), and Load (project).

## Usage

1. **Set Global Parameters**: Adjust total duration (Global End Time) and timeline scale.
2. **Add Channels**: Click "+" to add a new channel. Use "Copy" to duplicate settings or "Delete" to remove. Rename channels as needed.
3. **Edit Channel Parameters**: Select a channel tab and adjust its controls (waveforms, frequency, modulation, envelope, reverb, etc.).
4. **Arrange in Timeline**: Drag handles to set when each channel plays. Use the timeline scale/scroll for navigation.
5. **Visualize**: Watch the waveform, volume, and pitch graphs update as you tweak parameters.
6. **Preview**: Click "Play" to listen, "Stop" to halt playback. The timeline marker shows playback position.
7. **Export**: Click "Export" to render and download your composition as a WAV file.
8. **Save/Load Project**: Use "Save" to export your project as a JSON file, and "Load" to restore it later.

## Synthesis Concepts

### Phase Modulation

- The phase of a carrier wave is modulated by another (modulator) wave, producing complex harmonics.
- Adjust carrier/modulator ratios and depths for a wide range of timbres.
- Use step quantization for melodic or rhythmic patterns.

### Sound Design Tips

- Start with sine waves to understand modulation basics.
- Experiment with different waveforms and ratios for unique sounds.
- Use envelope and reverb controls for dynamic, spatial effects.
- Try step quantization for arpeggios or rhythmic effects.

## Technical Details

- **Web Audio API**: High-quality synthesis and audio processing.
- **HTML5 Canvas**: Real-time waveform, volume, and pitch visualization.
- **Vanilla JavaScript**: No external libraries or frameworks.
- **CSS3**: Responsive, modern UI.
- **24-bit Stereo WAV Export**: Audio is exported as high-quality 24-bit stereo WAV files.

### System Requirements

- Modern web browser with Web Audio API support.
- No server or installation needed—works offline.

## Contributing

Contributions are welcome! Fork the project, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
