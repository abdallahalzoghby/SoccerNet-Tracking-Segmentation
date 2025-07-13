# ⚽ SoccerNet Player Tracking & Segmentation
> Semantic & Instance Segmentation of Soccer Players using U-Net and Mask R-CNN

This project was developed as part of the **Computer Vision IN412** course. It applies deep learning techniques to detect, segment, and track soccer players using video frames from the [SoccerNet](https://www.soccer-net.org/) dataset.

---

## 📌 Project Structure

- 📁 Data Extraction and Preprocessing  
- 🎯 Ground Truth Mask Creation  
- 🧠 U-Net Training for Semantic Segmentation  
- 🤖 Mask R-CNN Fine-Tuning for Instance Segmentation  
- 📈 Evaluation using metrics (IoU, precision, recall)  
- 📊 Visualizations of predictions and comparisons

---

## 🧰 Technologies Used

| Tool           | Description                         |
|----------------|-------------------------------------|
| PyTorch        | Model development and training      |
| OpenCV         | Frame extraction, mask rendering    |
| Matplotlib     | Plotting training metrics           |
| U-Net          | Semantic segmentation               |
| Mask R-CNN     | Instance segmentation & detection   |

---

## 📈 Evaluation Metrics

| Model       | IoU   | Precision | Recall |
|-------------|-------|-----------|--------|
| U-Net       | 0.79  | 0.81      | 0.76   |
| Mask R-CNN  | 0.84  | 0.88      | 0.83   |


