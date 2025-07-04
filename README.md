# Nymeria-Gait Dataset

> **Note:** This repository will host the Nymeria-Gait dataset. The data will be made publicly available soon.

The **Nymeria-Gait** dataset is extracted from [Nymeria dataset](https://github.com/facebookresearch/nymeria_dataset) with a specific focus on walking sequences. It includes synchronized recordings of walking tasks captured from an observer’s perspective using smart glasses, alongside a reference motion capture from an inertial suit.

## 🖼️ Sample Data

![Sample Egocentric Views and 3D Reconstructions](./nymeria-gait-sample.png)

*Top:* Egocentric video frames from smart glasses worn by the observer.  
*Bottom:* Corresponding 3D reconstructions.

## 📁 Dataset Overview

- **54 participants** across 10 locations
- **908 walking sequences**
- **142 minutes** of total recordings (indoor and outdoor)
- **7.9 km** of walking distance
- Annotated with walking conditions: observer’s perspective (back, side, front,or combined), environment type (indoor or outdoor), terrain slope (flat, up, or down), and trajectory pattern (straight, turn, backward or combined).
- Data Available:

| **Data Type**                           | **Observer** | **Participant** | **Additional Info**                         |
|----------------------------------------|--------------|------------------|----------------------------------------------|
| RGB Video (30 FPS)                     | ✅           | ✅               |                                              |
| Grayscale Video (30 FPS)               | ✅           | ✅               | Used for global alignment                    |
| Eye Tracking (10 FPS)                  | ✅           | ✅               |                                              |
| IMU Motion Data (1 kHz)                | ✅           | ✅               | Right: 1 kHz, Left: 800 Hz                   |
| MiniAria Wristbands (10 FPS)           |              | ✅               |                                              |
| 3D Skeletal Motion (240 Hz)            |              | ✅               | XSens Motion Capture                         |
| SLAM Trajectory (6DoF)                 | ✅           | ✅               | Wristband + Glasses                          |
| Parametric Human Model                 |              | ✅               | Derived from XSens                           |
| Magnetometer (10 Hz)                   | ✅           | ✅               | Not in wristbands                            |
| Scene Point Clouds (Global Alignment)  | ✅           | ✅               | Generated via SLAM                           |
| Demographic Data                       |              | ✅               |                                              |

## 🗓️ Release Information

📅 **Expected release**: Q4 2025  

---

## 📫 Contact

For questions or dataset access requests:  
📧 **alexis.cantaloube@chuv.ch**
