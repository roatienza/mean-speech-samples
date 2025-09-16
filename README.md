# Speech Samples Comparison

A simple web page for comparing audio samples in a 3x3 grid layout.

## Overview

This site provides a clean interface for comparing speech audio samples across different conditions or models. The page features:

- **3 rows × 3 columns** grid layout for audio samples
- **Row headers** for categorizing different conditions/models
- **Column headers** (Sample 0, Sample 1, Sample 2) for different test cases
- **Audio players** for each combination (e.g., row0/sample0.wav, row0/sample1.wav, etc.)
- **Scoring guidelines** displayed prominently at the top

## Usage

1. **View the page**: Visit the GitHub Pages URL for this repository
2. **Add audio files**: Upload your WAV files following the directory structure below
3. **Compare samples**: Use the audio players to listen and compare different samples
4. **Score quality**: Follow the 5-point scoring guidelines provided on the page

## Audio File Structure

```
/
├── index.html (main comparison page)
├── row0/
│   ├── sample0.wav
│   ├── sample1.wav
│   └── sample2.wav
├── row1/
│   ├── sample0.wav
│   ├── sample1.wav
│   └── sample2.wav
└── row2/
    ├── sample0.wav
    ├── sample1.wav
    └── sample2.wav
```

## Scoring Guidelines

- **1 – Bad:** Very annoying, hard to understand
- **2 – Poor:** Annoying  
- **3 – Fair:** Slightly annoying
- **4 – Good:** Perceptible but not annoying
- **5 – Excellent:** Imperceptible distortion

## Technical Details

- Built as a static HTML page suitable for GitHub Pages
- Responsive design that works on desktop and mobile devices
- No dependencies or build process required
- Audio players support WAV format natively in modern browsers

For detailed information about the audio file structure, see [AUDIO_STRUCTURE.md](AUDIO_STRUCTURE.md).
