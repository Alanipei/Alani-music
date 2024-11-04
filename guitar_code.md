# 🎸 Guitar Code for Amnesia

The guitar provides harmonic support, enriching the melody and bass with a complementary sound.

```python
# Guitar Harmony Code
guitar_chords = [    [40, 43, 47], [43, 47, 50], [36, 40, 43], [33, 36, 40],  # E, G, C, A chords
    [40, 43, 47], [43, 47, 50], [36, 40, 43], [33, 36, 40],
    [40, 43, 47], [43, 47, 50], [36, 40, 43], [33, 36, 40],
    [40, 43, 47], [43, 47, 50], [36, 40, 43], [33, 36, 40]
]

def play_guitar():
    for chord in guitar_chords:
        playNote(chord, beats=2, velocity=85)
play_guitar()
