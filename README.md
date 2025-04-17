# IPL Match Winner Prediction Model

A machine learning model that predicts the winner of Indian Premier League (IPL) cricket matches using historical match data.

## Overview

This project uses a Random Forest Classifier to predict IPL match winners based on various match features. The model achieves good accuracy by analyzing patterns from past IPL matches.

### Features
- Data preprocessing and cleaning of IPL matches dataset
- Handling of categorical variables using One-Hot Encoding
- Implementation of Random Forest Classifier
- Model evaluation and visualization

## Requirements
- Python 3.7+
- Required packages listed in `requirements.txt`

## Installation

```bash
git clone https://github.com/your-username/ipl-predictor.git
cd ipl-predictor
pip install -r requirements.txt
```

## Dataset
The model uses `matches.csv` containing historical IPL match data with features like:
- Teams playing
- Venue
- Toss winner and decision
- Match result

## Usage
1. Open `IPL_Prediction_Model.ipynb` in Jupyter Notebook
2. Run all cells to see the data processing, model training, and evaluation

## Model Performance
- The Random Forest Classifier achieves good prediction accuracy
- Detailed performance metrics are available in the notebook

## Contributing
Feel free to open issues and pull requests for any improvements.

## License
This project is open source and available under the MIT License.