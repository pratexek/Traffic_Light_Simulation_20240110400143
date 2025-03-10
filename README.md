# Traffic Light Simulation

## Introduction
This is a basic Traffic Light Simulation created with Python and Matplotlib. It graphically illustrates how traffic lights function, including a countdown timer and concise messages for every light.

## What This Does?
- Simulates actual traffic lights** (Red, Yellow, Green)
- Displays a countdown timer** for every light
- Shows messages to direct users:
  - Red Light → "STOP"
- ⚠️Yellow Light → "READY TO GO"
  - ✅ Green Light → "GO"
- Runs in Google Colab with easy-to-execute execution

## What You Need?
To execute this project, ensure you have:
- Google Colab or any Jupyter Notebook
- Python 3 installed
- These Python libraries:
  - `matplotlib` (visualization)
  - `time` (countdown timer)
  - `IPython.display` (for the display update)

## How to Use?
### Running in Google Colab
1. Open [Google Colab](https://colab.research.google.com/).
2. Paste the Python script into a new notebook.
3. Run the script and observe the lights change!

### Running on Your Computer:
1. Install the necessary library if you don't have it:
   ```bash
   pip install matplotlib
   ```
2. Save the Python script as `traffic_light.py`.
3. Run it within a Jupyter Notebook or Python environment.

## How It Works?
1. **Traffic light is represented** with `matplotlib.patches`.
2. **Lights change automatically** in a cycle:
   - Red Light (10 sec)
   - Yellow Light (5 sec)
   - Green Light (10 sec)
3. Updates every second** to display the countdown and the corresponding message.

## Try It Out!
Run the script and observe how a traffic light system functions in real life, with the right timing and signals.

## License:
This project is free to use and open-source. Feel free to enhance it!

---

Happy coding and safe travels on the roads!

