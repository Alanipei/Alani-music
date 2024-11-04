# 🎸 Bass Code for Amnesia

This code provides the bass line for the song *Amnesia*, laying down the foundational rhythm for other instruments to build upon.

```python
# Bass Code
bass_notes = [
    40, 43, 38, 36,  # Root notes for E, G, C, A chords
    40, 43, 38, 36,
    40, 43, 38, 36,
    40, 43, 38, 36
]

def play_bass():
    for note in bass_notes:
        playNote(note, beats=2, velocity=90)  # Medium volume for each note
play_bass()
