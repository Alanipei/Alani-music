# 🎹 Keys Code for Amnesia

The keys provide the main melody, including intro, climax, and ending sections to create a structured progression.

```python
# Intro, Main Melody, and Ending for Keys
intro_keys = [...]
main_melody_keys = [...]
ending_keys = [...]

def play_intro():
    for chord in intro_keys:
        playNote(chord, beats=2, velocity=75)

def play_main_melody():
    for chord in main_melody_keys:
        playNote(chord, beats=1.5, velocity=85)
        playNote([chord[0] + 12], beats=0.5, velocity=90)

def play_ending():
    for chord in ending_keys:
        playNote(chord, beats=2, velocity=70)

play_intro()
play_main_melody()
play_ending()
