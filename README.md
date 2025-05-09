
# 🌾 Precision Agriculture using Machine Learning and IoT

![Python](https://img.shields.io/badge/python-3.8--3.10-blue)
![Platform](https://img.shields.io/badge/platform-Web-green)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

---

## 📊 Data Sources

- [Crop Recommendation Dataset](https://www.kaggle.com/atharvaingle/crop-recommendation-dataset)  
- [Fertilizer Suggestion Dataset](https://github.com/Gladiator07/Harvestify/blob/master/Data-processed/fertilizer.csv)  
- [Plant Disease Detection Dataset](https://www.kaggle.com/vipoooool/new-plant-diseases-dataset)

---

## 💡 Motivation

Agriculture is a key driver of economic growth, especially in countries like India where a large portion of the population relies on it.

This project leverages **Machine Learning**, **Deep Learning**, and **IoT** to help farmers increase yield and sustainability by offering:
- 🌾 Crop Recommendation
- 💊 Fertilizer Suggestion
- 🍂 Plant Disease Detection

---

## 🌱 Features

### 🌾 Crop Recommendation
- Input: N-P-K values, state, and city.
- Output: Suggests the most suitable crop.
- Uses real-time temperature and humidity data.
> 💡 Use common city names due to limitations in the weather API.

---

### 💊 Fertilizer Recommendation
- Input: Soil N-P-K values and desired crop.
- Output: Detects nutrient deficiencies or excess and recommends suitable fertilizers.

---

### 🍂 Plant Disease Detection
- Input: Image of a plant leaf.
- Output: Identifies crop type, disease (if any), and treatment options.
> ⚠️ Currently supports a limited set of crops.

---

## 🖼️ Home Page

![Home Page](https://github.com/atharval1/precision-agriculture-using-machine-learning/blob/main/Project-docs/App-snaps/Home.png)

---

## 🧪 How to Use

### ➤ Crop Recommendation
1. Enter N-P-K values, state, and city.
2. Click **Submit**.
3. View the recommended crop for your region and soil.

### ➤ Fertilizer Suggestion
1. Enter soil N-P-K levels and crop type.
2. Get fertilizer advice based on nutrient imbalances.

### ➤ Disease Detection
1. Upload a clear image of a plant leaf.
2. The model predicts:
   - Crop type
   - Health status
   - Disease name (if any)
   - Remedies

---

## 🛠️ Installation Guide

### ✅ Requirements
- Python **3.8 to 3.10**  
  ⚠️ Newer versions may not be compatible.

### 🔧 Setup Instructions

#### 1. Clone the Repository

```bash
git clone <your-repo-url>
cd <project-folder>
```

#### 2. Create a Virtual Environment

**On Windows:**
```bash
python-m venv venv
venv\Scripts\activate
```

**On macOS/Linux:**
```bash
python -m venv venv
source venv/bin/activate
```

#### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

---

## 🎥 Demo Videos

- [YouTube Demo 1](https://youtu.be/kU0nf-rzusE)  
- [YouTube Demo 2](https://www.youtube.com/watch?v=eJ-KytG2H5w&t=36s)

---

## 👨‍💻 Contributors

- [Atharva Labhasetwar](https://www.linkedin.com/in/atharva-labhasetwar)  
- [Venkata Narayana Bommanaboina](https://www.linkedin.com/in/bvnarayana515739/)  
- [Kundan Patil](https://www.linkedin.com/in/kundan-patil-638979199)

---

## 🧾 License

This project is licensed under the [MIT License](LICENSE).

---

## 📌 Notes

- Use a stable internet connection to fetch real-time weather data.
- Ensure that uploaded images are clear and in-focus for best disease detection results.
- Always cross-check fertilizer recommendations with agricultural guidelines for your region.
