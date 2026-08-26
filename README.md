# Audio Spectrum Lab

Build a tiny oscillator and analyser graph, then turn frequency energy into a live Canvas spectrum.

## What this demonstrates

Follow the `AudioContext → OscillatorNode → GainNode → AnalyserNode` graph. Change one control at a time, inspect `getByteFrequencyData()`, and confirm that Stop disconnects the nodes and closes the context. Audio begins only from a user gesture.

## Run locally

Open `index.html` directly for the non-network path, or serve this folder with `python3 -m http.server 4173`. No npm, bundler, framework, microphone, upload, or server is required.

## Privacy and compatibility

This lab keeps its state in the browser. It does not upload user content. Optional APIs are feature-detected and the page retains a visible fallback when the browser does not provide them.

## License

Released under the MIT License. See [LICENSE](LICENSE).
