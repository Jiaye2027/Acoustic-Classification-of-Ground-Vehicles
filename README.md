# Acoustic-Classification-of-Ground-Vehicles

## Objective
Develop an algorithm to differentiate vehicle types using their sound emissions.

## Purpose
Advance autonomous acoustic sensing capabilities to accelerate the deployment of smart cities and infrastructure.

## Data Sources
- **[New Delhi, India (MVDA)](https://www.kaggle.com/datasets/omkarmb/idmt-traffic-dataset/code)**
- **[Munich, Germany (IDMT)](https://github.com/Ashhad785/MVD)**

## Team Members
| Name                | Email               | Role                                      |
| ------------------- | ------------------- | ----------------------------------------- |
| **Redford Hudson**  | rfhudson@uci.edu    | Code Infrastructure, SQL, Linear Models  |
| **Jiaye Liu**       | jiayel7@uci.edu     | Feature Extraction, LSTM Model           |
| **Lazar Salvador-Smith** | lcsalvad@uci.edu | Research, LSTM Debugging, Presentation   |
| **Yuqian Ma**       | yuqianm1@uci.edu    | Data Cleaning, Feature Engineering       |
| **Xingjian Wang**   | xingjiw4@uci.edu    | Spectral Analysis, CNN+LSTM Architecture |

## Methodology
* Feature Engineering.
* LSTM Model, used grid search and random search for parameter/hyperparameter tunning.
* Model Evaluation

## Features Used in LSTM
Utilizing the Librosa audio library for feature extraction:
- **MFCCs**: Analyze frequency and rescale
- **Chroma-stft**: Track pitch changes over time
- **Root Mean Square (RMS)**: Measure energy in the signal
