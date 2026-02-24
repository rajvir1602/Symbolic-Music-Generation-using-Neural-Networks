# Symbolic-Music-Generation-using-Neural-Networks


Built an end-to-end sequence modeling system to generate piano melodies from symbolic MIDI datasets.

Processed ~18,000 lead sheet MIDI files using pypianoroll, converting them into compressed pianoroll representations (128×768 → 128×128) for efficient training.

Implemented temporal downsampling and random pitch transposition for data augmentation across scales.

Trained a 2-layer feedforward neural network (≈131K parameters) using categorical cross-entropy and sliding-window context modeling (8-note input).

Developed an autoregressive generation pipeline with top-k probabilistic sampling to reduce repetitive patterns.

Converted generated outputs back to playable MIDI format.
