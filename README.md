# Shazam-like Application

## Description

This project implements a Shazam-like music recognition application using Python. The application processes sound files to generate spectrograms and fingerprints, then matches them to a repository of songs. The key features include:

1. **Spectrogram Generation**: Given any sound file (either song, vocals, or music), the program generates its spectrogram for the first 30 seconds.
   
2. **Feature Extraction**: The application extracts key features from each spectrogram and hashes them using perceptual hash functions to create a unique fingerprint for each song.

3. **Song Matching**: The application compares the fingerprint of an input file to the repository and lists the closest matches with a similarity index in a sorted table displayed in the GUI.

4. **Weighted File Combination**: The user can select two files and create a weighted average of them. The new file is then treated as a new sound input, and the closest songs are found based on the new fingerprint.

## Features

- **Spectrogram Analysis**: The program generates spectrograms for full songs, music-only, and vocals-only files.
- **Feature Hashing**: Extracted features are hashed into a shorter sequence using perceptual hash functions.
- **Similarity Index**: The application calculates a similarity index between the input file and repository songs.
- **Weighted Average**: Allows weighted combination of two files, enabling the generation of new audio inputs.
- **Graphical User Interface (GUI)**: A user-friendly interface that displays results in a sortable table.

## Demo



https://github.com/user-attachments/assets/4021817c-7687-44dc-a8f5-3edd97bdf94e





## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/shazam-app.git
    ```

2. Navigate to the project directory:
    ```bash
    cd shazam-app
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the application:
    ```bash
    python app.py
    ```

2. Upload a sound file to generate its spectrogram and find the closest matches.

3. Use the slider to create a weighted average of two selected files and search for similar songs.

## Contributors

- [Mazen marwan](https://github.com/Mazenmarwan023)
- [Saif mohamed](https://github.com/seiftaha)
- [Mahmoud mohamed](https://github.com/mahmouddmo22)
- [Farha](https://github.com/farha1010)
- [Eman emad](https://github.com/alyaaa20)



## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
