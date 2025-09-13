# Emotion_Recognition

This project "Emotion Recognition" uses computer vision and deep learning techniques.  
We primarily used **CNN** as the main model and later tested **RNN, CNN_LSTM, CNN_RNN, CNN (MobileNetV2)** and traditional ML techniques such as **SVM, KNN, Random Forest, Logistic Regression, PCA**.  
The project is deployed via **Streamlit** and trained on the **FER-2013 dataset (Kaggle)**.

---

We developed **5 deep learning models** and **5 machine learning models**.  
Among them, the **CNN Custom Model** achieved the highest accuracy and best real-time performance (deployed via Streamlit).  

### How to run:
1. Install all required dependencies (see `requirements.txt`).  
2. Run the Jupyter notebooks (`.ipynb`) to generate models:
   - Deep Learning models → `.h5` files  
   - Machine Learning models → `.pkl` files  
3. Run the Streamlit app:  
   ```bash
   streamlit run <file_path>
