# DRL-w-reverse-action-space-
In this Repository, we used agents with normal and reverse action space to trade the DJI 30 index. Reverse actions space means where a normal action indicates buy, the agent short and when it indicates sell, the agent liquidates a short position. 

<h2>Introduction</h2>

In this repository will someone find one environment, 2 ensemble models, and 8 different Jupiter notebooks. The notebooks are representing 4 different scenarios for each of the models. 
The scenarios are uptrend, downtrend, no-trend, and multi-trend scenarios. 

<h2>How to run the notebooks? </h2>

To run a notebook just open the notebook in Google Colab, upload the env_reverse.py file from this repository, and the model_with_reverse_env_ppo.py file or the model_with_reverse_env_ppo_a2c.py depending on the notebook used. 
You can easily find which model each notebook use from its name.

<h2>What if someone wants to run the notebooks locally? </h2>

If you want to run the notebooks locally the requirements are:

- Python==3.6.0 or Python==3.7.0
- numpy==1.16.4
- pandas==1.0.3
- stockstats
- scikit-learn==0.21.0
- gym==0.15.3
- stable-baselines[mpi]
- tensorflow==1.15.4
