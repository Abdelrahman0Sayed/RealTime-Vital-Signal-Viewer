# Multi-Channel Signal Viewer
## Screenshots
![signal viewer]([images/signal viewer.jpeg](https://github.com/Abdelrahman0Sayed/RealTime-Vital-Signal-Viewer/blob/main/Images/signal%20viewer.jpeg))


## Introduction
Signal visualization is a vital tool in many fields, ranging from engineering and science to healthcare and finance. Whether monitoring real-time data from sensors, analyzing recorded signals, or comparing different signal patterns, an efficient signal viewer is essential for extracting meaningful insights.

This project is a Python Qt-based desktop application designed to handle multi-channel signal viewing, offering flexibility, interactivity, and advanced controls for visualizing and analyzing various types of signals.
## Features
- **Signal File Browsing**: Users can browse their PC to open signal files.
- **Independent Graphs**: Two identical graphs allow the user to display different signals, each with independent controls.
- **Graph Linking**: Users can link the two graphs, ensuring synchronized playback, zooming, panning, and viewport adjustments.
- **Cine Mode**: Signals are displayed dynamically. A rewind option is available to restart the signal from the beginning or stop it.
- **Signal Manipulations**:
  - Change signal color.
  - Add titles/labels to signals.
  - Show/hide signals.
  - Adjust cine speed.
  - Pause, play, or rewind signals.
  - Zoom in/out and pan signals.
  - Scroll through signals using sliders.
  - Move signals between the two graphs.
- **Non-Rectangular Visualization**: Provides non-rectangular views of the signal data for advanced insights and visualization beyond standard Cartesian graphs.
- **API Integration**: An API feature allows integration with external systems for importing/exporting signals or interacting with remote signal sources.
- **Boundary Conditions**: Scrolling is restricted within the signal boundaries to prevent empty graphs.
- **Signal Gluing**: Users can select and cut segments from the two signals displayed in each of the two viewers. These segments can then be glued together to create a continuous signal. This feature enables users to merge different parts of signals, which is useful for combining multiple segments or signals from different sources. Once glued, the new signal behaves as a single, continuous signal for further analysis or visualization.
- **Export and Reporting**:
  - Generate PDF reports with snapshots of graphs and signal statistics.
  - Include data statistics (mean, standard deviation, duration, min, and max values) in a well-structured table.
  - Support single or multi-page PDF reports with an organized layout.
- **User-Friendly Controls**: Includes intuitive sliders for scrolling, mouse-based panning, and easy-to-use UI elements for a seamless experience.


