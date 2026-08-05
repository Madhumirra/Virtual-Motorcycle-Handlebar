#  Virtual Motorcycle Handlebar

A real-time computer vision application that enables users to control motorcycle or racing games using hand gestures and a webcam. The system tracks both hands using MediaPipe and converts steering gestures into keyboard inputs for gameplay.

---

## Features

- Real-time hand tracking using MediaPipe
- Gesture-based steering control
- Throttle and brake detection
- Smooth steering angle calculation
- Live HUD displaying steering angle, FPS, and control status
- Compatible with Windows systems
- Supports games that use keyboard controls

---

## Technologies Used

- Python
- OpenCV
- MediaPipe
- NumPy
- pynput

---

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/Virtual-Motorcycle-Handlebar.git
```

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## Run

```bash
python bike_handlebar.py
```

---

## Controls

| Gesture | Action |
|---------|--------|
| 👊 Both fists | Accelerate |
| 🖐 Both open hands | Brake |
| Tilt Left | Steer Left |
| Tilt Right | Steer Right |

---

## Project Structure

```
Virtual-Motorcycle-Handlebar/
│
├── bike_handlebar.py
├── requirements.txt
├── README.md
├── LICENSE
└── screenshots/
```

---

## Future Improvements

- Calibration mode
- Adjustable steering sensitivity
- Multiple game profiles
- Voice feedback
- Driving statistics dashboard

---

## Contributors

- Madhumirra R and Jayapreeti D


Developed  as a computer vision project using Python, OpenCV, and MediaPipe.

---

## License

This project is licensed under the MIT License.
