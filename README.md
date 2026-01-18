# 🌱 AI Crop Doctor

# Team TITANIC
Tarang Kumar

## 📖 About the Project

**AI Crop Doctor** is an intelligent web application that revolutionizes agricultural diagnostics by helping farmers, gardeners, and agricultural experts identify plant diseases from leaf images. By combining cutting-edge machine learning image analysis with context-based follow-up questions, it delivers accurate diagnoses and practical treatment suggestions.

### 🎯 How It Works

1. **Upload** an image of your plant or leaf (drag-and-drop or click to select)
2. **Answer** a few simple questions about symptoms and conditions
3. **Receive** a confidence-based disease diagnosis and actionable recommendations

### ✨ Key Highlights

- 📸 **AI Image Recognition** for plant disease detection
- 🧭 **Interactive Q&A** for improved accuracy
- 📊 **Confidence Scores** for transparency
- 📱 **Fully Responsive** and mobile-friendly design
- 🎯 **Actionable Recommendations** to help protect crops

---

## 🧑‍🌾 Step-by-Step Usage Guide

Follow these simple steps to use AI Crop Doctor effectively:

1. Open the AI Crop Doctor web application in your browser
2. Upload a clear image of the affected plant leaf using drag-and-drop or file selection
3. Ensure the image is well-lit and focused for accurate analysis
4. Click on the **Analyze Image** button to start the diagnosis
5. Answer the follow-up questions related to plant condition and symptoms
6. Wait a few seconds while the AI processes the image
7. View the detected disease along with confidence score and treatment recommendations

---

## 🗂 Project Structure

```
ai-crop-disease-detection-agent
│
├── app.py                          # Main Flask application
├── class_indices.json              # Disease class mappings
├── crop_diagnosis_best_model.tflite # TensorFlow Lite model
├── README.md                       # Project documentation
├── requirements.txt                # Python dependencies
├── .gitattributes
├── .gitignore
│
├── static/
│   ├── css/
│   │   └── style.css              # Application styling
│   ├── images/
│   │   ├── apple_black-rot.JPG
│   │   ├── apple_cedar_rust.JPG
│   │   ├── apple_healthy.JPG
│   │   └── ... (other sample images)
│   └── js/
│       ├── history.js             # History management
│       ├── main.js                # Main application logic
│       └── user_guide.js          # User guide interactions
│
└── templates/
    ├── history.html               # Diagnosis history page
    ├── index.html                 # Main application page
    ├── tools.html                 # Tools and utilities
    └── user_guide.html            # User guide page
```

---

## ⚡ Installation & Setup

### Prerequisites

- Python 3.8 or higher
- pip package manager

### Quick Start

1. **Clone the repository:**
   ```bash
   git clone https://github.com/2006anand/AI-Crop-Doctor.git
   cd AI-Crop-Doctor
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application:**
   ```bash
   python app.py
   ```

4. **Open your browser and navigate to:**
   ```
   http://127.0.0.1:5000
   ```

---

## 🛠 Tech Stack

- **Backend:** Flask (Python)
- **Machine Learning:** TensorFlow Lite
- **Frontend:** HTML5, CSS3, JavaScript
- **Deployment:** Render

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 👥 Team TITANIC

This project was developed by **Team TITANIC** as part of a hackathon competition.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🔗 Links

- **GitHub Repository:** [https://github.com/2006anand/AI-Crop-Doctor](https://github.com/2006anand/AI-Crop-Doctor)
- **Live Application:** [https://ai-crop-doctor-app.onrender.com/](https://ai-crop-doctor-app.onrender.com/)

---

## 📞 Support

If you encounter any issues or have questions, please [open an issue](https://github.com/2006anand/AI-Crop-Doctor/issues) on GitHub.

---

<div align="center">

**Made with ❤️ by Team TITANIC**

⭐ Star this repository if you find it helpful!

</div>
