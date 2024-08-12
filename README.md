AUDIO VISUALIZATION :: An Audio Visualizer application built using PyQt5 and PyAudio. This application captures audio input from a microphone, visualizes it in real-time using pyqtgraph, and allows users to record and save the audio data.

## Features
- Real-time audio visualization
- Adjustable visualization speed
- Adjustable buffer size for x-axis range
- Start and stop audio recording
- Save recorded audio as WAV files

## Requirements
To run this project, you need Python 3 and the following Python packages:

- `PyQt5`
- `pyqtgraph`
- `numpy`
- `pyaudio`
- `scipy`
You can install the required packages using the `requirements.txt` file provided:

```bash
pip install -r requirements.txt

Installation::
Clone this repository:

bash
git clone https://github.com/yourusername/audiovisualizer.git
Navigate to the project directory:

bash
cd audiovisualizer
Create and activate a virtual environment (optional but recommended):

bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install the dependencies:

bash
pip install -r requirements.txt
Usage
Run the application:

bash
python main.py

The main window will open with the following controls:
Start: Begin capturing and visualizing audio.
Stop: Stop capturing and visualizing audio.
Record: Start/stop recording the audio. The button text toggles between "Record" and "Stop Recording".
Speed: Select "Fast" or "Slow" to adjust the update frequency of the visualization.
Buffer Size: Select the size of the buffer to adjust the x-axis range of the visualization.
To save recorded audio, click the "Record" button to start recording, and click it again to stop. A file dialog will prompt you to save the recorded audio as a WAV file.
