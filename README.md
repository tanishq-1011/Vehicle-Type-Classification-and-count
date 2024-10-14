
---

# 🚗 Vehicle Type Classification and Count

**A powerful, real-time vehicle detection and counting system using YOLOv3** that helps monitor road traffic with precision and speed. This project is designed to detect and classify different types of vehicles and count them using advanced computer vision and deep learning techniques.

## 🌟 Features

- **Real-time Detection**: Detect and classify vehicles such as cars, trucks, buses, motorcycles, and more in real-time.
- **Efficient Counting**: Accurately count vehicles as they pass through a designated area using a powerful counting mechanism.
- **Customizable Detection Area**: Easily define specific areas on the screen for monitoring and counting vehicles.
- **Video Input**: Supports multiple video formats like `.avi`, `.mp4` for seamless integration with existing traffic camera systems.
- **Detailed Reporting**: Get a breakdown of the number of vehicles detected for each type, with the option to store results in text files.

## 🚀 How It Works

1. **Upload a Video**: Start by uploading a video of traffic footage from a road or intersection.
2. **Select Counting Area**: Define the area in the video where you want the system to track and count vehicles.
3. **Real-Time Counting**: Start the system to detect, classify, and count vehicles in real-time.
4. **Pause & Resume**: Pause and resume the counting as needed for convenience and control.
5. **Track Results**: View vehicle counts on the GUI and save the results to a file for further analysis.

## 🔥 Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.8+
- PyTorch
- OpenCV
- PyQt5
- YOLOv3 Weights (included in `weights/` folder)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/tanishq-1011/Vehicle-Type-Classification-and-Count.git
cd Vehicle-Type-Classification-and-Count
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Download the pre-trained YOLOv3 weights and place them in the `weights/` folder.

4. Run the application:

```bash
python app.py
```

### 🚥 Usage Instructions

- **Upload a Video**: Click the "Open Video" button to load your traffic footage.
- **Select Counting Area**: Define the area for vehicle detection by selecting points on the video.
- **Start Counting**: Click "Start" to begin vehicle classification and counting.
- **Pause/Resume**: Pause the process anytime and resume where you left off.
- **Results**: Check the real-time count of different vehicle types on the GUI and in the `results.txt` file.

## 🛠️ Tech Stack

- **Object Detection**: YOLOv3
- **GUI**: PyQt5
- **Image Processing**: OpenCV
- **Machine Learning**: PyTorch, Darknet
- **Utilities**: SORT Algorithm for object tracking

## 📊 Output Example

- **Real-time vehicle detection with classifications**: Cars, Trucks, Motorcycles, Buses, etc.
- **Counting results stored in `results.txt`**: Each line contains the count and type of detected vehicles along with timestamps.

## 🌍 Use Cases

- **Traffic Monitoring**: Perfect for monitoring traffic flow on highways, streets, or intersections.
- **Smart City Applications**: Can be integrated into smart city infrastructures for automated traffic control and surveillance.
- **Data Collection**: Useful for gathering traffic data for research or analytics.
