# Voilence_detection_using_AI
An AI/ML algorithm improves real-time CCTV monitoring by detecting violence percentages and sending alerts to a registered person when violence increases. Secured by Patent Application No: 202341029626.



-------------------------------------------------------------------------------------------------------------------------------------------------------------

# Real-time CCTV Monitoring with Violence Detection

**Patent Application No:** 202341029626

## Overview

This project involves an AI/ML algorithm to enhance real-time CCTV monitoring by detecting and analyzing violent activities within the monitored area. The system calculates the percentage of violence detected and sends immediate alerts to a registered individual when the violence exceeds a certain threshold.

## Features

- **Real-Time Monitoring**: Continuously monitors CCTV feeds for any signs of violence.
- **Violence Detection**: Utilizes AI/ML models to detect violent actions and behaviors within the feed.
- **Percentage Calculation**: Calculates the percentage of violence detected in the video footage.
- **Alert System**: Automatically alerts a registered person when the detected violence percentage exceeds a predefined threshold.
- **Secure Implementation**: Secured under Patent Application No: 202341029626.

## Prerequisites

- Python 3.7+
- TensorFlow or PyTorch (depending on the chosen ML framework)
- OpenCV
- Pre-trained AI/ML models (provided in the repository)
- Access to CCTV camera feeds

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/**********/violence-detection-cctv.git
   cd violence-detection-cctv
   ```

2. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Configure CCTV Feeds:**

   - Update the `config.json` file with the URLs or paths to your CCTV feeds.
   - Register the person who will receive alerts by updating the `alert_config.json` file with their contact details.

## Usage

1. **Run the Violence Detection Algorithm:**

   ```bash
   python detect_violence.py
   ```

2. **Monitoring:**

   - The system will start monitoring the CCTV feeds in real-time.
   - If violence is detected and the percentage exceeds the threshold, an alert will be sent to the registered person.

3. **Logs and Reports:**

   - All detected incidents are logged in the `logs/` directory.
   - Summary reports can be generated using the `generate_report.py` script.

## Customization

- **Violence Threshold**: You can adjust the threshold for violence detection in the `config.json` file.
- **Model Tuning**: If you wish to train or fine-tune the model, refer to the `model_training/` directory.

## Contribution

I want you to know that contributions to improve the algorithm or extend its capabilities are welcome. Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the terms of the patent application (No: 202341029626). Commercial use is prohibited without proper authorization.

## Contact

For any inquiries or issues, please contact [shinde vinayak rao patil] at [shindevinayakraopatil@gmail.com ].

