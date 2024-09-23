
# Federated Learning for Global Environmental Monitoring

## Overview

This project presents a novel framework utilizing Federated Learning (FL) to monitor global environmental changes such as deforestation, air quality, and climate anomalies. The decentralized approach ensures data privacy and scalability by training models on environmental data from sensors, satellites, and monitoring stations, without centralizing the raw data. The FL approach enables continuous model updates as new data becomes available, allowing for timely and accurate environmental predictions.

## Features

- **Federated Learning:** Local models train on decentralized environmental data.
- **Privacy-preserving:** Only model updates are sent to a central server, ensuring data privacy.
- **Global Environmental Monitoring:** Predicts temperature, air quality, and environmental anomalies using data from various nodes.
- **Scalable and adaptive:** The system allows seamless integration of new nodes and adapts to new data inputs.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/environmental-monitoring-federated-learning.git
   ```

2. Install required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. (Optional) Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Linux/macOS
   .\venv\Scripts\activate  # For Windows
   ```

## Usage

1. Run the main script to initiate federated learning training:
   ```bash
   python main.py
   ```

2. The model will train on decentralized nodes, aggregate results, and output performance metrics.

## Results

- MSE across nodes
- Global model coefficients (using federated averaging)
- True vs predicted temperature comparison for global model

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
