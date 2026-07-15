Novel audio visualization using real-time microphone input.

## Quick Start

```bash
npm install
npm run dev
```

Open http://localhost:5173 and allow microphone access when prompted.


## Audio Pipeline

The `useAudio` hook captures microphone input.

From the hook, you will receive:
- **frequencyData** — 1024 FFT frequency bins from low to high.
- **timeDomainData** — 2048 raw waveform samples. A value of 128 is silence, and 0 and 255 are the lowest and highest values respectively.

