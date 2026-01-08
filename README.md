# Spectral Fusion – Audio Morphing Playground

This is an experimental audio tool for **morphing two audio files** into a new blended sound. It uses **FFT-based spectral fusion** with optional detuning and dynamic blending to create evolving textures from your inputs.  

> ⚠️ **Work in progress:** This is an experimental playground, not a production-ready tool. Results can vary depending on the audio you use.

## Features

- Blend two audio files (voice, piano, or other tonal sounds) into a single audio output.
- Interactive sliders for:
  - **Fusion (alpha):** how much each audio contributes
  - **Detune (cents):** subtle pitch shift for harmonic richness
  - **Alpha modulation speed:** slow evolving changes for a more dynamic blend
- Maintains audio clarity while adding movement and interest.

## How to Use

1. Run the notebook in **Google Colab**.
2. Upload your two audio files when prompted.
3. Adjust the sliders to explore different blends.
4. Listen to the output directly in Colab.

**Tip:**  
- Works best with audio files that share similar tonal content (e.g., two voices or voice + piano).  
- Feel free to experiment — part of the fun is seeing what unusual combinations produce.

## Installation

```bash
!pip install librosa soundfile ipywidgets --quiet
