# Research Notes
## Relevance
Credit card fraud is a pervasive and relatively modern issue. Card-not-present fraud (in which the physical card was not stolen or skimmed) in particular has been rising in recent years. The Bureau of Justice Statistics reported in 2021 that nearly 4% of the US population over 15 experienced credit card fraud within 12 months prior to the survey. The Federal Trade Commission's 2023 *Fraud Report* listed $219.9 million losses from credit card fraud (with $195.2 million and $163.5 million losses from debit cards and payment apps) in 2022 alone. In addition to financial losses, victims of credit card fraud often report psychological damages. To that effect, in a 2021 survey of 2000 identity theft victims (which includes victims of credit card fraud) aged 65 and older, 34% of victims reported that the experience was distressing despite only 7% facing "out-of-pocket" expenses [1].
## Detection Methods
### Automated Detection
#### Decision Tree
Disadvantages:
- Sensitive to noise
- Complex; difficult to interpret
- Expensive to train
#### Data-Driven
- Artificial Neural Network (ANN)
  - Feature Extraction
  - Supervised Classifiers
- Convolutional Neural Network
  - AdaBoost with Majority voiting
- Attention Mechanism
  - Uses computation: Attention (Q,K,V) = $softmax({QK^T}/\sqrt\{d_k})V$
  - Where Q = Query, K = Key, V = Value, d = unauthorized transaction, and T = transaction
[2]
<br>
### Self-Detection
In a survey of 150 victims of credit card fraud, 82 (54.7%) discovered the fraud on their own after reviewing their account statement. While the researchers conducting the survey speculated that the sample was perhaps more technically skilled than the average person, thus inflating the rate of self-detection [1]. 
### Timing
While the majority of victims detected fraud through their statements, only 38.7% of these incidents were detected in under an hour. This is signifcantly less than the 69.8% of incidents detected with notifications. [1].
## Resources
**[1]** Eman Alashwali, Ragashree Mysuru Chandrashekar, Mandy Lanyon, and Lorrie Faith Cranor. 2024. Detection and Impact of Debit/Credit Card Fraud: Victims' Experiences. In Proceedings of the 2024 European Symposium on Usable Security (EuroUSEC '24). Association for Computing Machinery, New York, NY, USA, 235–260. https://doi.org/10.1145/3688459.3688464
<br><br>
**[2]** Han Lk and Anh LT. 2024. Credit Card Fraud detection with Attention Mechanism. In Proceedings of the 2024 9th International Conference on Intelligent Information Technology (ICIIT '24). Association for Computing Machinery, New York, NY, USA, 430–433. https://doi.org/10.1145/3654522.3654586
