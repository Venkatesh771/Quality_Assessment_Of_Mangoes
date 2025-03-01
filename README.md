<h3 align="center">Integrated System for Quality Assessment Based on Texture, Health, and Ripeness Evaluation for Mangoes</h3>

<p align="center">
  <img src="images/image1.png" alt="Project Image" width="900" style="border-radius: 30%;">
</p>

## 🔍 **Project Overview**
**🚀 An AI-powered system** designed to assess mango quality based on **🟢 Texture**, **🍅 Health**, and **🥭 Ripeness**.  
This project leverages **📸 Image Processing** and **🤖 Deep Learning Techniques** to automate the classification of mangoes for better quality control.

## 📂 Dataset Description  
The dataset used in this project consists of **mango images** collected from publicly available sources. Each mango sample is assessed based on three key parameters: **Texture, Healthiness, and Maturity**, using a **Likert scale (1 to 5)**.  

<p align="center">
  <img src="images/image.png" alt="Project Image" width="900">
</p>

## 📊 Data Labeling and Annotation  
Each mango image in the dataset is labeled based on the following assessment criteria:  

### **1️⃣ Texture Assessment**  
📌 **Likert Scale (1 to 5):**  
🔵 **1 – Very Smooth** 🟢  
🟢 **2 – Smooth**  
🟡 **3 – Moderately Smooth**  
🟠 **4 – Slightly Rough**  
🔴 **5 – Very Rough**  

---

### **2️⃣ Healthiness Assessment**  
📌 **Likert Scale (1 to 5):**  
🟢 **1 – Very Healthy** ✅  
🟢 **2 – Healthy**  
🟡 **3 – Moderately Healthy**  
🟠 **4 – Slightly Unhealthy**  
🔴 **5 – Very Unhealthy** ❌  

---

### **3️⃣ Maturity Assessment**  
📌 **Likert Scale (1 to 5):**  
🔴 **1 – Overripe** 🍂  
🟠 **2 – Ripe** 🥭  
🟡 **3 – Partially Ripe**  
🟢 **4 – Early Ripe**  
🔵 **5 – Unripe** 🌱  

---

### ✂️ Preprocessing  
- **Resizing** (e.g., **224×224 pixels**).  
- **Color Normalization** for uniformity.  
- **Noise Reduction** to remove distortions.  
- **Data Augmentation** (rotation, flipping, scaling).  

### 🔄 Splitting the Dataset  
- **70%** – Training Set  
- **15%** – Validation Set  
- **15%** – Test Set  

### 🏗️ Feature Extraction  
Extracting **texture, color distribution, and edges** to enhance model learning.  

### 🛠️ Model Input Preparation  
Images are converted into **numerical matrices**, normalized (0-1 range), and prepped for deep learning models.  

✅ **Final Output:** A clean, structured dataset ready for training.  





