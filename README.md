# Federated Ensemble-Learning for Transport Mode Detection in Vehicular Edge Network

This is my undergraduate thesis which has been published in <a href="https://www.sciencedirect.com/journal/future-generation-computer-systems"> Future Generation Computer Systems</a> Journal. Please find the details below. 

Publication page: https://doi.org/10.1016/j.future.2023.07.022 

ResearchGate: https://www.researchgate.net/publication/372454503_Federated_Ensemble-Learning_for_Transport_Mode_Detection_in_Vehicular_Edge_Network 

Abstract: Transport Mode Detection (TMD) has become a crucial part of Intelligent Transportation Systems (ITS) thanks to the recent advancements in Artificial Intelligence and the Internet of Things, which enable the collection and processing of a vast amount of information on how people move and behave over space and time. Since smartphones and smartwatches have enabled people to stay connected to the internet all the time, predicting a person’s mode of transportation has become easier since live location data can be collected easily. Vehicular Edge Networks (VEN) connect all smart vehicular edge devices and global cloud servers collect those devices’ sensory data to try to predict a person’s commute route using Machine Learning models. However, since the data is shared globally, security can be compromised, causing a large section of the population to be unwilling to share their sensory data with global cloud servers. The current state-of-the-art methods have achieved high accuracy in identifying a person’s transportation mode. Nevertheless, most of the approaches do not address the privacy issues of the user data as the methods use centralized training systems. There are also decentralized federated learning systems that address the privacy issues of user data by often sacrificing the performance of the models by training them on a vast amount of decentralized data. In this research, we propose a hybrid Federated Ensemble-Learning (FedEL) model to detect transportation modes in VEN, which improves federated strategies in terms of performance as well. XGBoost, Random Forest, and MLP are trained with data from each local client through an ensemble method. A prediction is then delivered based on a majority vote among the three models, and the most-voted class is considered. Based on extensive testing, the FedEL technique delivers a 95.10% accuracy rate for a first dataset (5-second window) and a 98.61% accuracy rate for another dataset (half-second window) on a TMD dataset available in the literature.

Please cite our paper if it helps in your research.

Citation BibTex: 
```
@article{ALAM202389,
title = {Federated Ensemble-Learning for Transport Mode Detection in Vehicular Edge Network},
journal = {Future Generation Computer Systems},
volume = {149},
pages = {89-104},
year = {2023},
issn = {0167-739X},
doi = {https://doi.org/10.1016/j.future.2023.07.022},
url = {https://www.sciencedirect.com/science/article/pii/S0167739X23002674},
author = {Md. Mustakin Alam and Tanjim Ahmed and Meraz Hossain and Mehedi Hasan Emo and Md. Kausar Islam Bidhan and Md. Tanzim Reza and Md. Golam Rabiul Alam and Mohammad Mehedi Hassan and Francesco Pupo and Giancarlo Fortino},
keywords = {Transport Mode Detection, Intelligent Transportation System, Vehicular Edge Network, Federated Learning, Distributed, Majority voting},
abstract = {Transport Mode Detection (TMD) has become a crucial part of Intelligent Transportation Systems (ITS) thanks to the recent advancements in Artificial Intelligence and the Internet of Things, which enable the collection and processing of a vast amount of information on how people move and behave over space and time. Since smartphones and smartwatches have enabled people to stay connected to the internet all the time, predicting a person’s mode of transportation has become easier since live location data can be collected easily. Vehicular Edge Networks (VEN) connect all smart vehicular edge devices and global cloud servers collect those devices’ sensory data to try to predict a person’s commute route using Machine Learning models. However, since the data is shared globally, security can be compromised, causing a large section of the population to be unwilling to share their sensory data with global cloud servers. The current state-of-the-art methods have achieved high accuracy in identifying a person’s transportation mode. Nevertheless, most of the approaches do not address the privacy issues of the user data as the methods use centralized training systems. There are also decentralized federated learning systems that address the privacy issues of user data by often sacrificing the performance of the models by training them on a vast amount of decentralized data. In this research, we propose a hybrid Federated Ensemble-Learning (FedEL) model to detect transportation modes in VEN, which improves federated strategies in terms of performance as well. XGBoost, Random Forest, and MLP are trained with data from each local client through an ensemble method. A prediction is then delivered based on a majority vote among the three models, and the most-voted class is considered. Based on extensive testing, the FedEL technique delivers a 95.10% accuracy rate for a first dataset (5-second window) and a 98.61% accuracy rate for another dataset (half-second window) on a TMD dataset available in the literature.}
}
```
