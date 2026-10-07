# DSP Labs

Interactive Digital Signal Processing labs by Dr. Seán Mullery, Atlantic Technological University.

Each lab is a single self-contained HTML file. There is nothing to build: GitHub Pages serves the files as they are.

## Publishing with GitHub Pages

1. Create a new **public** repository (for example `dsp-labs`).
2. Choose **Add file → Upload files** and drag in everything in this folder, including `index.html`, `.nojekyll` and this README. Commit.
3. Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, and save.
4. After a minute or two the site is live at `https://<your-username>.github.io/dsp-labs/`.

## Updating a lab

Upload the new file with the **same name** and commit. It replaces the old one and the site updates within a couple of minutes. Keep the file names fixed, because they are part of each lab's web address.

## The labs

| File | Lab |
|---|---|
| `statistics-probability.html` | Statistics & Probability Lab (DSP 301, lecture 1) |
| `adc-dac.html` | ADC & DAC Lab: quantisation, aliasing, sampling and reconstruction (DSP 301, lecture 2) |
| `convolution.html` | Convolution Machine (DSP 301, lecture 4) |
| `dft.html` | DFT Lab (DSP 301, lecture 5) |
| `spectrum.html` | Spectrum Lab (DSP 302, lecture 1) |
| `discrete-signals.html` | Discrete Signals Lab (DSP 302, lecture 2) |
| `z-transform.html` | z-Transform Lab (DSP 302, lectures 3–4) |
| `filter-design.html` | Filter Design Lab (DSP 302, lecture 5) |
| `dsp-hardware.html` | DSP Hardware Lab (DSP 302, lecture 6) |

`.nojekyll` tells GitHub Pages to serve the files exactly as they are.
