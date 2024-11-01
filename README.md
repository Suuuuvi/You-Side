# You-Side


The project seeks to reinterpret the Chinese pop ballad 'You Will Be By My Side' through coding. This project was created as part of my university final assignment, aimed at enhacing my programming skills and understanding of sotware development. The primary goal is to apply the concepts learned throughout the course to build a musicial composition that demonstrates my ability to code.

# Table of Content
- [General Information](#general-information)
- [Technologies Used](#technologies-used)
- [Screenshot](#screenshot)
- [Usage](#usage)
- [Launch](#launch)
- [Project Status](#project-status)
- [Room for Improvement](#Room-for-Improvement)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

# General Information

- **Problem Solved**

This project aims to express emotions through music, helping people find hope and courage when facing life’s challenges. The original song reflects expectations for the future and a farewell to the past. I hope to reinterpret it through TunePad, allowing more people to experience this positive emotion.

- **Purpose of the Project**

The main goal is to use Python to create a musical piece that resonates with the original song and reflects my personal emotional journey. Through music, I aim to express my love for life, acceptance of the past, and vision for the future, inspiring others to maintain faith and move forward bravely.

- **Reason for the Project**

This project is driven by the profound impact this song has had on my life, providing me with hope and courage during difficult times. By transforming these feelings into code and music, I hope to share this power and inspiration with others, allowing them to feel the same uplifting emotions when they listen to it

# Technologies Used

- **Programming Language**: Python 3
- **Development Tool**: TunePad
- **Version Control**： GitHub

# Screenshot
![Screenshot Description](IMG_1640.jpeg)

# Usage

- `playChord`: The function is defined to play chords at appropriate positions. For example, to play F and G major chord, can use:

    ```python
    from tunepad import playChord

    # Play a F and G major chord
        playChord(['65', '69', '72'], beats = 0.5)
        playChord(['67', '71', '74'], beats = 0.5) # Melodic variations are introduced, using chords to enrich the musicial texture.
    ```

- `sustainedNotes`: The function adds sustained notes, enhancing the melody's dynamics. Here’s an example of playing a G2 note for 0.5 seconds:

    ```python
    from tunepad import sustainedNotes

    # Play the note G2 for 0.5 seconds
    sustainedNotes('56', beats= 0.5)
    ```

- `playNote`: The function allows to play individual notes. For example, to play the note G3:

    ```python
    from tunepad import playNote

    # Play the note G3
    playNote(67, beats = 0.5) # note should be play for a duration of 0.5 beats.
    ```

- `rest`: The function introduces pauses in music. For instance, use it to pause for 0.25 second:

    ```python
    from tunepad import rest

    # Rest for 0.25 second
    rest(0.25)
    ```
- `for _ in range`: A cyclic structure repeats certain melodic segments for cohesion. Here’s an example of using a loop to repeat a melody:
    ```python
    from TunePad import for _ in range
    
    # for _ in range(1): # Repeat the melody 1 times
    playNote(64, beats=0.5)
    playNote(62, beats=0.5)
    playNote(67, beats=0.5)
    playNote(60, beats=0.5)
    playNote(67, beats=0.5)
    playNote(60, beats=0.5)
    playNote(68, beats=2)
    playNote(67, beats=1)
    playNote(64, beats=1)
    playNote(66, beats=0.25)
    playNote(66, beats=0.5)
    rest(0.25) # rest for 0.25 seconds between notes
    ```
## Set up

**Running the Project**
1. **Go to the branches** - [master](https://github.com/Suuuuvi/You-Side/tree/master)
   
3. **Open the file** - [tunepad_project_86233.json](tunepad_project_86233.json)
   
4. **Download the raw file and save it in your laptop、 computer or iPad**
   
5. **Access TunePad Website** - [TunePad](https://tunepad.com/)
   
7. **Please log in first, then go to MyTunes to import the raw file**

8. **You done it, you can listen it freely**
   
**No Minimum Hardware Requirements**

**Easy to Access**

**Input Data**

If the project requires input data, please ensure the data is in the following format:
- **CSV**: Comma-separated values for datasets.
- **JSON**: For structured data inputs.
- **MIDI**: For music-related data, if applicable.

By following these steps, you should be able to successfully launch and run the project.

# Project Status
The project has been completed.

# Room for Improvement
- **Areas for Improvement**:
    - Lack of the sound quality by incorporating a better audio library to support highter fidelity playback.

 # Acknowledgements
 - This project was inspired by a song 'You Will Be By My Side'
 - This project was based on [Quick Start Guide](https://tunepad.com/project/67954), 
 - Many thanks to the contributor of the [TunePad Song Tutorials](https://learn.tunepad.com/tutorials/) for the support, which greatly enhanced the development of this project.
 - Special appreciation to the TunePad for providing tools and teaching tutorial that made this project possible.

# Contact

If you have any questions, suggestions, or feedback regarding this project, please feel free to reach out to me:
- **Email**: Junjie.su-1@student.uts.edu.au
- **GitHub**: You can submit issues or pull requests on my [GitHub project page](https://github.com/Suuuuvi/You-Side.git)
- **Social Media**: Follow me on my social media channels for updates.
  - Instagram: [@cokiesuuuuvi](https://www.instagram.com/cokiesuuuuvi/profilecard/?igsh=OTloOXdvYThpbDhu)

Welocome all feedback and suggestions and thank you for your listen for this project.
