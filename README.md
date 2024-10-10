# Wildlife Monitoring AI System

This project aims to create an AI-powered real-time wildlife monitoring system to reduce human-wildlife conflicts, protect endangered species, and ensure tourist safety in areas near wildlife habitats. The system utilizes computer vision techniques to detect, track, and classify animals from video feeds, leveraging drones, cameras, and sensors deployed in wildlife zones.

## Features

- **Real-Time Animal Detection**: Uses deep learning models (e.g., YOLO, Faster R-CNN) to identify and classify different species from video streams.
- **Automated Tracking**: Tracks the movement of animals in real-time using object tracking algorithms (e.g., Kalman Filter, SORT).
- **Alert System**: Triggers alerts when dangerous animals are detected near human-populated areas to ensure the safety of tourists and locals.
- **Data Collection and Analysis**: Collects data on wildlife behavior and movement patterns for conservation research and wildlife protection strategies.

## Project Structure

- **/data**: Contains datasets used for training the AI models, including labeled images of animals.
- **/models**: Pre-trained models and custom-trained models used for detecting and classifying wildlife.
- **/scripts**: Python scripts for data preprocessing, model training, and real-time video analysis.
- **/notebooks**: Jupyter notebooks for model experimentation and performance evaluation.
- **/results**: Stores output videos, logs, and visualizations of the system in action.

## Setup

### Prerequisites

- Python 3.8 or later
- TensorFlow or PyTorch
- OpenCV
- NumPy
- Flask (if setting up the web interface)
- Drone/CCTV API access (optional for real-time feeds)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/wildlife-monitoring-ai.git
    cd wildlife-monitoring-ai
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Download pre-trained models or train custom models using the provided scripts.

### Running the System

1. To run the real-time wildlife monitoring system:
    ```bash
    python scripts/real_time_monitoring.py
    ```

2. For tracking and alert generation:
    ```bash
    python scripts/tracking_alerts.py
    ```

3. To view data visualizations:
    ```bash
    jupyter notebook notebooks/visualization.ipynb
    ```

## Data Sources

- Animal behavior datasets from [Wildlife Insights](https://www.wildlifeinsights.org/)
- Public datasets from [iNaturalist](https://www.inaturalist.org/)
- Custom dataset collected using cameras and drones

## Models Used

- **YOLOv5**: For object detection and classification
- **ResNet**: For animal image classification
- **SORT**: For tracking detected animals in video streams

## Usage

- **Conservation**: Protect endangered species by analyzing animal behavior and migration patterns.
- **Tourism Safety**: Alert authorities in real-time when dangerous animals enter tourist areas.
- **Research**: Collect data to support ecological studies and environmental conservation efforts.

## Contribution

Contributions are welcome! Please submit a pull request or open an issue to propose any improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Wildlife Insights](https://www.wildlifeinsights.org/) for providing valuable wildlife data.
- Open-source contributions from the computer vision and AI community.
  
## Group 2
Syamraj Syamraj
Jeremiah Onah Otokpa
Preshanth Dhanapal
Shivam Nyati
Ashwini Seelan Gnanaseelan Vimala
