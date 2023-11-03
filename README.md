# kaggle

All the Kaggle competitions I competed in. I make this list to make the codes publicly available. 


**[Kaggle LLM 2023 :woman_scientist:](#kaggle-llm-2023-woman_scientist)**<br> 
**[Hubmap 2023 :hospital:](#hubmap-2023-hospital)**<br> 
**[:2nd_place_medal: Vesuvius Challenge :microscope:](#2nd_place_medal-vesuvius-challenge-microscope)**<br> 
**[Neutrino IceCube Challenge :ice_cube:](#neutrino-icecube-challenge-ice_cube)**<br>
**[AMEX Default Prediction :bank:](#amex-default-prediction-bank)**<br>


# Kaggle LLM 2023 :woman_scientist:


- The competition was about fine-tuning LLMs to answer difficult science-based questions written by a Large Language Model. 74.5 \% percentile score on the Kaggle leaderboard.
- Repo: https://github.com/viktorcikojevic/kaggle-llm


# Hubmap 2023 :hospital:

- Link to the competition [is given here](https://www.kaggle.com/competitions/hubmap-hacking-the-human-vasculature)
- This was a computer vision project with the aim to detect instances of microvascular structures from healthy human kidney tissue slides.
- Repo: https://github.com/viktorcikojevic/hubmap-2023
- Lessons learned: the best model would have achieve bronze medal if submitted to the competition. Lesson learned: don't forget to ensemble your models when dealing with unknown test data distribution!


# :2nd_place_medal: Vesuvius Challenge :microscope:


- Our team won silver medal here, 39th place out of 1,249 teams 🥳
- It was a computer vision project, about detecting ink from 3D X-ray scans and reading the contents. Read more at the [comp. link here](https://www.kaggle.com/competitions/vesuvius-challenge-ink-detection).
- Repo: https://github.com/viktorcikojevic/vesuvius-challenge
- I also have a "deprecated" branch here, which is basically the same code, but it is not as clean as the main branch. There, all the experiments were performed in notebooks and it's difficult to get back to it 😅: https://github.com/viktorcikojevic/vesuvius-challenge/tree/deprecated
- Inference notebook that led to the best score: https://www.kaggle.com/code/viktorcikojevic/fork-of-ensemble-all-models?scriptVersionId=141978154


# Neutrino IceCube Challenge :ice_cube:

- A Sequence modelling problem. The goal of this competition is to predict a neutrino particle’s direction. Read more at the [comp. link here](https://www.kaggle.com/competitions/icecube-neutrinos-in-deep-ice).

- I've made some public notebooks:
  - Public EDA notebook: [https://www.kaggle.com/code/viktorcikojevic/transformer-model-train](https://www.kaggle.com/code/viktorcikojevic/very-simple-eda-neutrino-trajectories)https://www.kaggle.com/code/viktorcikojevic/very-simple-eda-neutrino-trajectories
  - Train notebook using transformer architecture: https://www.kaggle.com/viktorcikojevic/transformer-model-train
  - Inference notebook: https://www.kaggle.com/viktorcikojevic/transformer-model-test
  - Lesson learned: don't be shy to stack moar layers! Transformers really shine with big data so this comp was easy in this regard. 


# AMEX default prediction :bank:


- Repo link is [given here](https://github.com/viktorcikojevic/amex-default-prediction/tree/master)
- Data is in tabular format, and the goal is to predict whether a person will default or not. 
- I've analyzed the dataset and wrote XGBoost models in BigQuery, so most of the work is done in BigQuery SQL. For me, the purpose of the comp was to learn more about the BigQuery ML.
