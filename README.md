# DRL-w-reverse-action-space- 

<h2>Reference</h2>
This code is used as a base and modify code from https://github.com/AI4Finance-Foundation/FinRL-Live-Trading/tree/master/old_repo_ensemble_strategy repository and https://github.com/AI4Finance-Foundation/FinRL/blob/master/tutorials/2-Advance/FinRL_Ensemble_StockTrading_ICAIF_2020.ipynb repository. 

<h2>Introduction</h2>
I used agents with normal and reverse action space in this repository to trade the DJI 30 index. Reverse actions space means where a normal action indicates buy, the agent short and when it indicates sell, the agent liquidates a short position. Someone can find one environment, 2 ensemble models, and 8 different Jupiter notebooks. The notebooks are representing 4 different scenarios for each of the models. 
The scenarios are consisting of uptrend, downtrend, no-trend, and multi-trend scenarios. 
 
<h2>How to run the notebooks? </h2>

-	Choose a notebook from folders PPO&A2C&ReverseModels and PPO&ReversePPO.
-	Open the notebook in Colab.
-	Upload the env_reverse.py file and model_with_reverse_env_ppo.py file or the model_with_reverse_env_ppo_a2c.py depending on the notebook you are using from the Models&Environment folder. 
-	Run the notebook 


