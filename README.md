AudioVisualizer:: AudioVisualizer is a Python application that allows users to visualize live audio input or playback of audio files. It features a graphical user interface (GUI) built with PyQt5 and displays audio waveforms in real-time using PyQtGraph.

## Features

- **Live Audio Visualization**: View real-time audio waveforms from a microphone or other audio input devices.
- **File Playback**: Load and visualize audio from WAV files.
- **Recording**: Record live audio and save it as a WAV file.
- **Adjustable Speed and Buffer Size**: Customize visualization speed and buffer size.
- **Real-Time Sample Rate Display**: Display the current or loaded sample rate.

## Requirements

- Python 3.x
- PyQt5
- PyQtGraph
- NumPy
- PyAudio
- SciPy

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/PayalLakra/AudioVisualizer.git
    cd AudioVisualizer
    ```

2. **Create a virtual environment** (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Run the application**:
    ```bash
    python main.py
    ```

2. **GUI Controls**:
    - **Start**: Begin visualizing live audio input.
    - **Stop**: Stop the audio input visualization.
    - **Record**: Toggle recording of live audio. Save the recording as a WAV file when stopped.
    - **Load File**: Open a WAV file and visualize its waveform.
    - **Speed**: Select between "Fast" and "Slow" update rates for the plot.
    - **Buffer Size**: Choose the buffer size for the x-axis range of the plot.

## Code Overview

- **`AudioVisualizer` Class**: Main class for the GUI application, handling audio input, visualization, and recording.
- **`start_recording` Method**: Initializes audio stream and starts the timer for visualization.
- **`stop_recording` Method**: Stops the audio stream and timer.
- **`update_plot` Method**: Updates the plot with new audio data or file data.
- **`toggle_recording` Method**: Starts or stops recording audio based on the current state.
- **`load_file` Method**: Loads an audio file and visualizes its waveform.
- **`update_timer_interval` Method**: Adjusts the timer interval based on selected speed.
- **`update_plot_range` Method**: Updates the plot range based on selected buffer size.

##Screenshots
<img width="959" alt="Screenshot 2024-08-13 111612" src="https://github.com/user-attachments/assets/cb68eed7-3bfc-4c21-a9b8-f4b424525d14">
![Screenshot (266)](https://github.com/user-attachments/assets/185d399c-6453-4f0f-b9d2-0ce102c05302)

## Credits
Support and Guidance: Special thanks to http://upsidedownlabs.tech/ for their continuous support and guidance.



https://github.com/user-attachments/assets/1394b456-35ab-4c96-8411-1785f7f8b84b





