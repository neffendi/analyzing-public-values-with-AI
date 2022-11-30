# Overview

In this project, the European Social Survey (ESS) data was used to see if a model could be created which would predict if an individual will vote for a left winged candidate, or a right winged candidate, or if they were undecided. 
<br/>
<br/>
The ESS data aims to "monitor and interpret changing public attitudes and values within Europe and
to investigate how they interact with Europe's changing institutions". Respondants answers were categorized and the statistical techniques mentioned below were used to check robustness of the models.

<br/>
<br/>

# Statistical Techniques Used:
- AIC
- BIC
- Likelihood Ratio Test
- Wald Test
- Odd Ratios
- Spearman Correlation

<br/>
<br/>

# ML/AI Models Used:
- Ordered logit model
- Random Forest
- Ada Boost
- Gradient Boost
- Multi-layer Perceptron
    - Activation function: ReLu
    - Optimizer: Adam
    - Loss function: Categorical Crossentropy
    - Regularization with EarlyStopping


<br/>
<br/>

## Evalutation metric used: Accuracy Score