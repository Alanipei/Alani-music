# 🎶 Amnesia Instrumental Cover Project

## 📖 Table of Contents
* [Introduction](#-introduction)
* [Technologies](#-technologies)
* [Features](#-features)
* [Screenshots](#-screenshots)
* [Installation](#-installation)
* [Usage](#-usage)
* [Acknowledgements](#-acknowledgements)
* [Author](#-author)

## 🎯 Introduction
The *Amnesia Instrumental Cover Project* is a digital cover created using TunePad. The original project was a pure music song [Amnesia](http://163cn.tv/yM1rAaQ ). This project presents a structured, one-minute instrumental version of the song *Amnesia*, showcasing separate code blocks for bass, drums, keys, and guitar. Each instrument has its own code, allowing users to experience a layered musical arrangement with a clear beginning, middle, and end.

## 🛠 Technologies
This project utilizes:
* **TunePad**: A platform for music programming
* **Python-like Commands in TunePad**: Specific functions used to create and play music notes
* **Instruments**: Bass, Drums, Keys (Piano), and Guitar

## ✨ Features
- **Multi-Instrument Layers**: Separate code sections for each instrument make it easy to manage and customize the sounds.
- **Structured Composition**: Includes an intro, main melody (climax), and ending for a complete musical progression.
- **Dynamic Piano Melody**: The piano part includes variations with added notes to create an engaging, bouncy rhythm.

## 📷 Screenshots
![1](https://github.com/user-attachments/assets/9a6ae7bf-3f9c-4384-9a73-06c29476997a)

## 🚀 Installation
1. **Open TunePad**: Log in to your TunePad account and create a new project.
2. **Add Code Blocks**: Copy each instrument's code (Bass, Drums, Keys, and Guitar) into separate sections within the TunePad editor.
3. **Run the Code**: Run each section in the recommended order for optimal sound layering.

### Minimum Requirements
- **TunePad Account**: Required to create and run the project.
- **Audio Output Device**: Ensure you have headphones or speakers for listening.

Here's an expanded **Usage** section with examples and use cases, showing how to use each instrument code block and customize the music further.

## 🎼 Usage
To use this project effectively, you can follow these steps and explore various ways to customize the music.

### How to Use
1. **Run Each Code Block**: Start by running each instrument’s code block in TunePad in sequence:
   - **Bass**: Run the bass code first to establish a foundational rhythm.
   - **Drums**: Next, add the drum pattern to build up the beat.
   - **Keys (Piano)**: Then, introduce the keys with variations to create a main melody.
   - **Guitar**: Finally, add the guitar harmony for a fuller sound.

2. **Experiment with Timing**: Try adjusting the timing (beats) and velocity (volume) of notes to create different rhythmic effects. You can change each `playNote` function’s `beats` and `velocity` parameters to fit your desired style.

### Use Cases
- **Standard Playback**: For a simple, balanced playback, use the original code provided for each instrument, maintaining a consistent timing and volume.
- **Extended Play with Loops**: Repeat certain sections or adjust the code to loop the entire melody for a longer playback.
  
    ```python
    for _ in range(2):  # Repeat the melody twice
        play_main_melody()
    ```

- **Adding Rhythmic Variations**: Customize the keys or guitar sections by adding more rhythmic notes for a bouncier melody. Experiment by adding extra `playNote` calls to create a richer texture.

    ```python
    playNote([60, 64, 67], beats=1)  # Play a simple chord
    playNote(72, beats=0.5, velocity=95)  # Add a high, bouncy note
    ```

- **Layering with Volume Dynamics**: Create dynamics by changing the `velocity` parameter for softer or louder sounds. This can help add emotional depth to the piece.
  
    ```python
    playNote(48, beats=2, velocity=70)  # Softer bass note for a gentle intro
    playNote(48, beats=2, velocity=110)  # Louder bass for a powerful climax
    ```

### Code Examples
Here are some specific examples of ways to alter the existing code:

- **Loop the Entire Song**:
  
    ```python
    for _ in range(3):  # Repeat the full sequence three times
        play_intro()
        play_main_melody()
        play_ending()
    ```

- **Add a Custom Melody**:
    You can add your own melodic layer by creating new notes in the `Keys` section.
  
    ```python
    # Custom keys sequence with a higher pitch for a new melody line
    custom_melody = [72, 74, 76, 77, 76, 74, 72]
    for note in custom_melody:
        playNote(note, beats=1, velocity=90)
    ```

By experimenting with these variations and using the original code, you can explore different styles and interpretations of *Amnesia* in TunePad. Let your creativity flow by adjusting timing, rhythm, and harmonies for a truly customized musical experience!
By running each part in sequence, you will experience a full, instrumental version of *Amnesia* with a layered, dynamic sound.

## 📈 Acknowledgements
This project is complete, providing a structured, multi-layered cover of *Amnesia*. Future updates may include additional instrument variations or alternative versions.

## 👤 Author
**[Alanipei]**  
Feel free to reach out with questions or feedback.
