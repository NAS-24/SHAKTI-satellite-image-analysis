## SHAKTI — Satellite-Based Historical Analysis for Knowledge and Trend Insights

SHAKTI is a satellite image analysis project developed as part of a **Semester 4 mini project**.  
The system analyzes historical satellite imagery to study **environmental changes** such as
urbanization and deforestation over time.

It uses a **U-Net deep learning model** to perform pixel-wise segmentation on satellite images
from different years, enabling trend analysis of land-use transformation.

---

### Problem Addressed
- Limited visibility into long-term land-use changes
- Difficulty in analyzing environmental trends at scale
- Need for data-driven insights for sustainable planning

---

### Solution Overview
SHAKTI performs:
- Pixel-level segmentation of satellite images
- Comparison of images across different time periods
- Visualization of land-use changes (urban growth, forest loss)

---

### Key Highlights
- Trained on the **DeepGlobe satellite dataset**
- Focused segmentation of **Urban** and **Forest** classes
- Implemented **U-Net architecture**
- Used data augmentation, early stopping, and learning rate scheduling
- Visualized temporal changes for trend analysis

---

### Tech Stack
- Python  
- TensorFlow / Keras  
- NumPy  
- OpenCV  
- Matplotlib  
- Jupyter Notebook  

---

### Project Scope
- Academic / prototype-level project
- First hands-on experience with deep learning
- Focused on understanding model architecture and real-world application

---

### Note
This project is a learning-focused implementation. While results are not fully production-ready,
it represents a practical step toward applying deep learning to real-world satellite imagery.

---

### Goal
To support **urban planners and environmental researchers** with a scalable,
data-driven approach for monitoring land-use changes and sustainability trends.
