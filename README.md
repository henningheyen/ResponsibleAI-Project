# ResponsibleAI-Project

Welcome to this notebook on Responsible AI. This project aims to touch on the most important topics in the field of Responsbile AI including bias, fairness, interpretability, error analysis and counterfactuals. 

We use the famous [UCI Adult Census Income dataset](https://archive.ics.uci.edu/ml/datasets/adult) to apply the repsonsbile AI concepts. We pretend to goal is to build an unbiased fair credit score system.

# Content

1. **ML models**: After an in-depth exploratory analysis of the dataset we create two white box model (Decsision Trees) and one black box model (Gradient Boosting).
2. **Interpretating models**: This section aims to introduce common interpretabilty techniques including global (tree plots, feature importance, PDP plots) and local (SHAP, LIME) techniques
3. **Error Analysis**: Here we compare the models based on fairness and create a bias mitigated model using the [fairlearn](https://github.com/fairlearn/fairlearn) library. We further investigate potential fairness-accuracy tradeoffs and discover the sources of bias in the data. 
4. **What if Counterfacticals**: Inspired from Causal ML modeling we test how the models' prediction changes when we change individual features using the [DiceML](https://interpret.ml/DiCE/dice_ml.html) library.
5. **Documentaion**: We create a datasheeet for the dataset and a model card for our most fair model.
6. **References**

