# 🥁 Drums Code for Amnesia

This code provides a simple drum pattern for *Amnesia*, adding rhythm with kick, snare, and hi-hat.

```python
# Drums Code
drum_pattern = [
    (36, 42), (36, 42), (38, 42), (36, 42),  # Kick and hi-hat, snare and hi-hat
    (36, 42), (36, 42), (38, 42), (36, 42)
]

def play_drums():
    for beat in drum_pattern:
        for drum in beat:
            playNote(drum, beats=1, velocity=100)  # Standard volume for rhythm
play_drums()
