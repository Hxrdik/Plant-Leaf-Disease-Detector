🌿 Plant Leaf Disease Detection 🍃🍂

Detect plant leaf diseases using deep learning and image classification — with a simple web interface for instant results.

⸻

📝 Description

Plant Leaf Disease Detection is a machine learning-based project that identifies diseases in plant leaves through image analysis. It uses a trained Convolutional Neural Network (CNN) model to classify leaf images into healthy or infected categories. The project supports remote usage via a web interface, making it suitable for farmers, researchers, and students in the agricultural sector.

⸻

🧠 Model Details
	•	Model Type: Convolutional Neural Network (CNN)
	•	Dataset Used: Publicly available plant disease datasets (e.g., PlantVillage)
	•	Classes: Healthy, Powdery Mildew, Leaf Spot, Rust, and more
	•	Frameworks: TensorFlow / Keras
	•	Training Accuracy: ~95% (varies with dataset)

⸻

🛠️ Tech Stack
	•	Python
	•	TensorFlow / Keras
	•	Flask (for web deployment)
	•	Google Colab / Jupyter Notebook
	•	HTML/CSS (Web UI)

⸻

🚀 How to Run the Project
	1.	Run the main notebook:
Open and run Plant_Leaf_Diseases_Detection.ipynb to load the model and necessary libraries.
	2.	Upload Sample Images:
Provide the path to sample leaf images in the code (or upload to Colab if running there).
	3.	Run the Output Notebook:
Execute Plant_Leaf_Disease_Detector_Output.ipynb to generate predictions and deploy the web app.
	4.	Access Web Interface:
Once executed, a link will be generated. Click on it to open the webpage interface and view predictions for your uploaded images.

⸻

📸 Sample Preview
<img width="1430" height="813" alt="image" src="https://github.com/user-attachments/assets/bb93b937-5765-465b-9794-54bc4bbf7406" />



FOLDER STRUCTURE
📁 Plant-Leaf-Disease-Detection
├── Plant_Leaf_Diseases_Detection.ipynb
├── Plant_Leaf_Disease_Detector_Output.ipynb
├── /images/
│   └── sample_leaf.jpg
├── /model/
│   └── trained_model.h5
└── README.md
