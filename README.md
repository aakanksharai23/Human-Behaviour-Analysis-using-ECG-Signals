[README (2).md](https://github.com/user-attachments/files/21944582/README.2.md)
# Human Behaviour Recognition using Deep Learning

This project demonstrates human activity recognition using the **Mobile Health Dataset**. 
It applies deep learning techniques (CNN + LSTM) to classify different human activities 
such as walking, jogging, sitting, running, and more.

## Dataset
The dataset used is the **Mobile Health Dataset** available from Kaggle via `kagglehub`.

- Dataset: [gaurav2022/mobile-health](https://www.kaggle.com/datasets/gaurav2022/mobile-health)
- The dataset includes multiple human activities collected via sensors.

## Features
- Data preprocessing (resampling, outlier removal)
- Sequence dataset creation for activity recognition
- CNN + LSTM based deep learning model
- Model training, validation, and evaluation
- Performance visualization (loss & accuracy plots)
- Confusion matrix and classification report

## 🛠️ Requirements
Install the dependencies before running the project:

```bash
pip install numpy pandas seaborn matplotlib tensorflow keras scikit-learn kagglehub
```

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/human-behaviour.git
   cd human-behaviour
   ```

2. Run the script:
   ```bash
   python human_behaviour.py
   ```

3. The script will:
   - Download the dataset automatically using `kagglehub`
   - Train the model
   - Save the best model as `mhealth_best.keras`
   - Display training/validation performance and evaluation metrics

## Results
- Achieves high accuracy in classifying multiple activities
- Generates plots of training vs. validation accuracy/loss
- Displays confusion matrix with activity labels

## Future Work
- Hyperparameter tuning for improved accuracy
- Deployment as a real-time activity recognition app
- Experimenting with different deep learning architectures

## Author
Developed as part of a deep learning experiment for human activity recognition.

