
# Smart Traffic Management System

## Overview
The Smart Traffic Management System is an AI-driven solution to optimize traffic flow using adaptive signal control. The system uses real-time video feed processing to detect traffic anomalies and adjust traffic light timings accordingly. The goal is to reduce traffic congestion and improve efficiency by dynamically controlling traffic signals.

## Technologies Used
- **C++**: For traffic signal simulation and optimization algorithms.
- **Python**: For implementing the machine learning model and handling real-time video feed processing.
- **OpenCV**: For capturing and processing live traffic video feeds.

## Features
- **AI-based Adaptive Traffic Control**: Automatically adjusts signal timings to optimize traffic flow.
- **Anomaly Detection**: Uses real-time video feed to detect traffic anomalies and take necessary actions.
- **Efficient Congestion Management**: Reduces traffic congestion by adapting the traffic signal logic to current traffic conditions.

## Installation and Setup

### Prerequisites:
- Python 3.x
- OpenCV for Python

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/smart-traffic-management-system.git
   ```
2. Install required dependencies:
   ```bash
   pip install opencv-python
   ```
3. Run the project:
   ```bash
   python main.py
   ```

4. The system will use your webcam to simulate traffic monitoring and control the traffic light system based on real-time analysis.

## Usage
- The program simulates the traffic light system and automatically changes light colors based on a simplified AI decision model.
- Press **'q'** to stop the simulation.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
