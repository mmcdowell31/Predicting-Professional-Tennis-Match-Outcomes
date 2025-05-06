# Predicting-Professional-Tennis-Match-Outcomes
Predicting Professional Tennis Match Outcomes: A Comparative Study of Ensemble models (XGBoost/Random Forests) and Baseline Models
## Data
The dataset used in this analysis has match ATP (men’s professional tennis) data from
1968 which is considered the beginning of the "Open Era" in men’s professional tennis.

However, this dataset only has complete in-game match statistics after 1991 therefore data
from after 1991 was exclusively used. The goal of this analysis is develop a prediction/classification
model that can accurately determine wether a player will win or lose a match based
on their performance.

This data was downloaded from: https://www.kaggle.com/datasets/sijovm/atpdata/data


In order to dowload the most recent version of this data see below: 

```python
import kagglehub

# Download latest version
path = kagglehub.dataset_download("sijovm/atpdata")
```

%![Alt Text](correlation_matrix.png)
