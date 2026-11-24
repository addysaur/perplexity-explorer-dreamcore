# Perplexity Explorer — Dreamcore

A single-file Dreamcore-themed perplexity explorer that runs the real **DistilGPT-2** model (`Xenova/distilgpt2`, q8) entirely in your browser with Transformers.js — no backend, no API key.

## What it does
- Type a sentence and calculate its **perplexity**: per-token probability table (P and 1/P), the three steps, and perplexity computed as `exp(average of -ln P)` with token `50256` prepended and a stable softmax.
- See the model's **top 8 next-token predictions** as bars.
- Try it **by hand** in the simulated section (presets: "I love Python" → 2.32, "All 1/8" → 8).

## The dream
Real Dreamcore photographs in a sideways-scrolling journey: five rooms side by side whose 3D dimensions shift as you travel, animated photos, real Dreamcore eye pictures that watch your cursor, flat solid panels — no gradients.

## Run it
Open `index.html` in a browser (or serve the folder with any static server). First Calculate downloads the model (~85 MB) once and caches it.
