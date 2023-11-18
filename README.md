# Agro_DS_Cup

# ✍️ What was the task?

Predict milk yield of cows.

# 🏆 Result

5-th of 368.

# 🔆 Details

All details are in main.ipynb. Further only briefly.

# 💾 Data

 We had data from previous lactations and yields of cows, information about pedigree of cows.

# Eda 
As we can see, mean of targets gets higher every year.

It's better to use data only after 2019 because in test set we have samples only from 2021 and 2022. 
![image](https://github.com/MaksKhan/Agro_DS_Cup/assets/72515541/e2fea714-ad70-4a9d-ae60-29b37a40f704)


Information about lactations

![image](https://github.com/MaksKhan/Agro_DS_Cup/assets/72515541/00d669d1-590a-4c45-8505-25807e1d9822)

# New features
1 - Age of the cow

2 -The difference between the birth of a calf and the beginning of lactation.

3 - Number of days since previous lactations

4 - Data from previous lactations

5 - Number of calves

6 - Month of birth and lactation

7 – Average mother’s milk yield

8 - Average milk yield of grandmothers

# 😼 Models
The best was CatBoost. LightGBM and XGBoost wweren't as good. I trained one model for every feature (there were 8 features).

# 💻 Interpretation

SHAP values and permutation importance were reaaly good.
![image](https://github.com/MaksKhan/Agro_DS_Cup/assets/72515541/a9df8410-c6a3-4d32-9029-7dca4eccb587)

![image](https://github.com/MaksKhan/Agro_DS_Cup/assets/72515541/9fc2fa41-f30f-4d40-ab5f-bdb8dd0a2b00)
