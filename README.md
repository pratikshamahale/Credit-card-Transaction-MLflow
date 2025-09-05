# Credit-card-transaction
This project showcases the use of MLflow for tracking, managing, and visualizing Machine Learning experiments. MLflow enables seamless logging of parameters, metrics, artifacts, and models, making it easier to reproduce experiments and compare different models efficiently.

Preview
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/05e6f840-0082-4814-92f4-e7485a6289c1" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/210b6426-e6f5-44c4-8980-a00911de885a" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/42929afb-59c6-42ee-b982-663113a0d7a2" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8145e5bc-fae4-42f4-9d8f-c232177a8143" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c3e18d50-869c-4dc6-a875-0abb17b3c6d2" />


# 🚀 Key Features

📊 Experiment Tracking – Record metrics, parameters, and artifacts.

📂 Model Registry – Store, version, and manage multiple models.

🔄 Reproducibility – Ensure consistent experiment reruns.

📈 Visualization – Compare model performance with an interactive UI.

🔌 Integration – Compatible with scikit-learn, TensorFlow, PyTorch, and custom ML code.

# 🛠️ Tech Stack

Language: Python

ML Libraries: scikit-learn / TensorFlow / PyTorch

Tracking Tool: MLflow

Data Handling: Pandas, NumPy

# 📦 Installation

Clone the repository

git clone https://github.com/yourusername/mlflow-experiments.git cd mlflow-experiments

Install dependencies

pip install -r requirements.txt

# ▶️ Usage

Start the MLflow UI:

mlflow ui

Open your browser at http://127.0.0.1:5000 to explore experiment logs.

📂 Project Structure project/ │── data/ # Dataset │── notebooks/ # Jupyter notebooks │── src/ # Source code for training │── mlruns/ # MLflow experiment logs │── requirements.txt │── README.md

📊 Example MLflow Output

After training, MLflow logs include:

Parameters: learning rate, batch size, etc.

Metrics: accuracy, precision, recall, etc.

Artifacts: model files, performance plots, confusion matrices
