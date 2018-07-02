---
layout: post
title:  "New papers in IJCNN and TOSN"
date:   2018-06-21 01:20:00 +1000
categories: cruise update
---

{::options parse_block_html="true" /}
Congratulations to the following two of our PhD students for their recent top quality papers!
<ol>
  <li>Hui Song</li>
  <li>Irvan Bastian Arief Ang</li>
</ol>

<div style="padding: 15px; margin-top: 10px; margin-bottom: 10px; border: 2px solid black;">
### International Joint Conference on Neural Networks (IJCNN)
------------------------------

[**Evolutionary Multi-objective Ensemble Learning for Multivariate Electricity Consumption Prediction**](https://github.com/cruiseresearchgroup/Evolutionary-Multi-objective-Ensemble-Learning-for-Multivariate-Electricity-Consumption-Prediction)

Authors: Hui Song, A. K. Qin and Flora D. Salim

Link: TBD

Paper: [PDF File](https://github.com/cruiseresearchgroup/Evolutionary-Multi-objective-Ensemble-Learning-for-Multivariate-Electricity-Consumption-Prediction/blob/master/paper/song2018evolutionary.pdf)

**Abstract**

Energy consumption prediction typically corresponds to a multivariate time series prediction task where different channels in the multivariate time series represent energy consumption data and various auxiliary data related to energy consumption such as environmental factors. It is non-trivial to resolve this task, which requires finding the most appropriate prediction model and the most useful features (extracted from the raw data) to be used by the model. This work proposes an evolutionary multi-objective ensemble learning (EMOEL) technique which uses extreme learning machines (ELMs) as base predictors due to its highly recognized efficacy. EMOEL employs evolutionary multi-objective optimization to search for the optimal parameters of the model as well as the optimal features fed into the model subjected to two conflicting criteria, i.e., accuracy and diversity. It leads to a Pareto front composed of non-dominated optimal solutions where each solution depicts the number of hidden neurons in the ELM, the selected channels in the multivariate time series, the selected feature extraction methods and the selected time windows applied to the selected channels. The optimal solutions in the Pareto front stand for different end-to-end prediction models which may lead to different prediction results. To boost ultimate prediction accuracy, the models with respect to these optimal solutions are linearly combined with combination coefficients being optimized via an evolutionary algorithm. We evaluate the proposed method in comparison to some existing prediction techniques on an Australian University based dataset, which demonstrates the superiority of the proposed method. 
</div>

<div style="padding: 15px; margin-top: 10px; margin-bottom: 10px; border: 2px solid black;">
### [Journal] ACM Transactions on Sensor Networks (TOSN)
------------------------------

**A Scalable Room Occupancy Prediction with Transferable Time Series Decomposition of CO2 Sensor Data**

Authors: Irvan B. Arief-Ang, Margaret Hamilton and Flora D. Salim

Link: TBD

Paper: TBD

**Abstract**

Human occupancy counting is crucial for both space utilisation and building energy optimisation. In the current article, we present a semi-supervised domain adaptation method for carbon dioxide - Human Occupancy Counter Plus Plus (DA-HOC++), a robust way to estimate the number of people within in one room by using data from a carbon dioxide sensor. In our previous work, the proposed Seasonal Decomposition for Human Occupancy Counting (SD-HOC) model can accurately predict the number of individuals when the training and labelled data are adequately available. DA-HOC++ is able to predict the number of occupancy with minimal training data, as little as one-day data. DA-HOC++ accurately predicts indoor human occupancy for five different rooms across different countries using a model trained from a small room and adapted to the other rooms. We evaluate DA-HOC++ with two baseline methods - support vector regression technique and SD-HOC model. The results demonstrate that DA-HOC++’s performance on average is better by 10.87% in comparison to SVR and 8.65% in comparison to SD-HOC.
</div>