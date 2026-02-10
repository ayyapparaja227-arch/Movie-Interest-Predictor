# Movie Interest Predictor

A Machine Learning powered web application that predicts a user's movie interest based on their age and gender.

## 🚀 Features

- **Interactive Web Interface**: Built with Flask for a smooth user experience.
- **Machine Learning Model**: Uses a Decision Tree Classifier (Entropy-based) for accurate predictions.
- **Data Visualization**: Includes visualizations of the decision tree model.
- **Responsive Design**: precise and user-friendly interface.

## 🛠️ Technology Stack

- **Python**: Core programming language.
- **Flask**: Web framework for the backend.
- **Scikit-learn**: Machine learning library for model training.
- **Pandas**: Data manipulation and analysis.
- **HTML/CSS**: Frontend structure and styling.

## 📂 Project Structure

```
Movie-Interest-Predictor/
├── app.py              # Main Flask application
├── train_model.py      # Script to train and save the model
├── explore_data.py     # Script for initial data exploration
├── model.pkl           # Trained machine learning model
├── requirements.txt    # Project dependencies
├── static/             # Static files (CSS, images)
└── templates/          # HTML templates
```

## ⚙️ Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/ayyapparaja227-arch/Movie-Interest-Predictor.git
    cd Movie-Interest-Predictor
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Train the model (optional if model.pkl exists):**
    ```bash
    python train_model.py
    ```

4.  **Run the application:**
    ```bash
    python app.py
    ```

5.  **Access the app:**
    Open your browser and visit `http://127.0.0.1:5001/`

## 👨‍💻 Author

**Ayyapparaja** - *Architect & Developer*

---
*Built for educational purposes and checking movie interest patterns.*
