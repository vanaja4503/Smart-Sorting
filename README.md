🍎 Smart Sorting: Transfer Learning for Identifying Rotten Fruits and Vegetables
📌 Project Overview
Smart Sorting is a Deep Learning-based image classification system that uses Transfer Learning to automatically identify and classify fresh and rotten fruits and vegetables.
This project aims to reduce food waste, improve quality control, and automate sorting processes in agriculture, supermarkets, and food supply chains.

🎯 Problem Statement
Manual inspection of fruits and vegetables is:
•	Time-consuming
•	Prone to human error
•	Inefficient for large-scale operations
There is a need for an automated system that can accurately detect rotten produce using image-based classification.

💡 Proposed Solution
We developed an AI-powered smart sorting system that:
•	Uses pre-trained CNN models (Transfer Learning)
•	Classifies images into Fresh and Rotten
•	Provides real-time prediction capability
•	Can be integrated into smart sorting machines

🏗️ Solution Architecture
Image Input → Preprocessing → Pre-trained CNN Model → Fine-Tuning → Classification → Output (Fresh/Rotten)

🛠️ Technology Stack
•	Python
•	TensorFlow / Keras
•	OpenCV
•	NumPy
•	Matplotlib
•	Scikit-learn
•	Flask (for deployment - optional)

📂 Dataset
•	Images of fresh and rotten fruits & vegetables
•	Dataset split:
o	Training Set
o	Validation Set
o	Test Set
You can use:
•	Kaggle datasets
•	Custom captured images

🔄 Project Workflow
1.	Data Collection
2.	Data Preprocessing
3.	Data Augmentation
4.	Model Selection (Transfer Learning Model)
5.	Model Training
6.	Model Evaluation
7.	Model Saving
8.	Deployment (Optional)

🧠 Transfer Learning Models Used
•	MobileNetV2
•	VGG16
•	ResNet50
(You can modify this based on the model you actually used.)

📊 Model Evaluation Metrics
•	Accuracy
•	Precision
•	Recall
•	F1-Score
•	Confusion Matrix

🚀 Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/smart-sorting.git
cd smart-sorting
2️⃣ Create Virtual Environment
python -m venv venv
source venv/bin/activate  # For Mac/Linux
venv\Scripts\activate     # For Windows
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Run the Project
python train.py

📁 Project Structure
smart-sorting/
│
├── dataset/
│   ├── train/
│   ├── validation/
│   └── test/
│
├── models/
│   └── model.h5
│
├── notebooks/
│   └── EDA.ipynb
│
├── app.py
├── train.py
├── requirements.txt
└── README.md

📸 Sample Output
•	Fresh Fruit → ✅ Fresh
•	Rotten Fruit → ❌ Rotten
(You can add screenshots here after training.)

🌍 Real-World Applications
•	Smart agriculture systems
•	Supermarket quality inspection
•	Food processing industries
•	Warehouse automation

🔮 Future Enhancements
•	Multi-class classification (different fruit types)
•	Real-time camera integration
•	IoT-based smart sorting machine
•	Mobile app integration

🤝 Contributing
Contributions are welcome!
Feel free to fork this repository and submit a pull request.

📜 License
This project is licensed under the MIT License.

👨💻 Author
Vanaja Dirisanapu
AI & ML Enthusiast
Vedio Demo link
https://drive.google.com/file/d/155ndWuhsh6JPXehg6wLzm5y3AEx8DAWc/view?usp=drivesdk
Documentation link
https://docs.google.com/document/d/1NOt9q9eSiYcrbuO1Cs70KxsLub8QZzlz/edit?usp=drivesdk&ouid=104548226717662373625&rtpof=true&sd=true
