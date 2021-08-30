# FairPut — Fair Machine Learning Framework

Colab Notebook: [Mortgage Case Study](https://colab.research.google.com/drive/1uxSP5_CuhxjjhcT_iIeL6lsmx1gwO5B6)

https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3619715

---------

## Sov.ai Research Lab (Sponsorship)

Animated Investment Management Research at [Sov.ai](https://sov.ai) — Sponsoring open source AI, Machine learning, and Data Science initiatives.

---------

This is a holistic approach to implement fair outputs at the individual and group level. Some of the methods developed or used includes ```quantitative monotonic measures```, ```residual explanations```, ```benchmark competition```, ```adverserial attacks```, ```disparate error analysis```, ```model agnostic pre-and post-processing```, ```reasoning codes```, ```counterfactuals```, ```contrastive explanations```, and ```prototypical examples```. 

FairPut is a light open framework that describes a preferred process at the end of the machine learning pipeline to enchance model fairness. The aim is to simultaneously enhance model interpretability, robustness, and fairness while maintaining a reasonable level of accuracy. FairPut unifies various recent machine learning constructs in a practical manner. This method is model agnostic, but this particular development instance uses LightGBM.

#### **1. [Model Explainability](https://colab.research.google.com/drive/1uxSP5_CuhxjjhcT_iIeL6lsmx1gwO5B6#scrollTo=pXftn6tIdi5f&line=1&uniqifier=1)** (Colab)
---------------
*	Model Respecification 
       * Protected Values Prediction
       * Model Constraints
       * Hyperparameter Modelling
       * Interpretable Model
       * Global Explanations
       * Monotonicity Feature Explanations
*	Quantitative Validation 
       * Level Two Monotonicity
       * Relationship Analysis
       * Partial Dependence (LV1) Monotonicity
       * Feature Interactions
       * Metrics and Cut-off
#### **2. [Model Robustness](https://colab.research.google.com/drive/1uxSP5_CuhxjjhcT_iIeL6lsmx1gwO5B6#scrollTo=cGreStojd5oc)** (Colab)
---------------
  *	Residual Deviation
  *	Residual Explanations
  *	Benchmark Competition
  *	Adversarial Attack

#### **3. [Regulatory Fairness](https://colab.research.google.com/drive/1uxSP5_CuhxjjhcT_iIeL6lsmx1gwO5B6#scrollTo=HGLUFEIBbC0s)** (Colab)
---------------
  *	Group
      *  Disparate Error Analysis
            * Parity Indicators
            * Fair Lending Measures
      *  Model Agnostic Processing
            * Reweighing Preprocessing
            * Disparate Impact Preprocessing
            * Calibrate Equalized Odds
      *  Feature Decomposition
  *	Individual
      *  Reasoning
          * Individual Disparity
          * Reasoning Codes
      *  Example Base
            * Prototypical
            * Counterfactual
            * Contrastive


If you end up using any of the novel techniques, or the framework as a whole, you can cite the following. 

BibTeX entry:

```
@software{fairput,
  title = {{FairPut}: Fair Machine Learning Framework},
  author = {Snow, Derek},
  url = {https://github.com/firmai/fairput/},
  version = {1.15},
  date = {2020-03-31},
}
```
Stack: [Alibi](https://github.com/SeldonIO/alibi), [AIF360](https://github.com/IBM/AIF360), [AIX360](https://github.com/IBM/AIX360), [SHAP](https://github.com/slundberg/shap), [PDPbox](https://github.com/SauceCat/PDPbox)

What Questions Do We Attempt to Answer?
------------

1. Can the model predict the outcome using just protected values? (Protected Value Prediction)
2. Is the model monotonic and are variables randomly selected? (Model Constraints, LV1 & LV2 Monotonicity)
3. Is the model explainable? (Model Selection, Feature Interactions)
4. Can you explain the predictions globally and locally? (SHAP)
5. Does the model perform well? (Metrics)
6. What individuals have received the most and least accurate predictions? (Residual Deviation)
7. Can you point to the feature responsible for large individual residuals? (Residual Explanations)
8. What feature values could potentially be outliers due to their misprediction? (Residual Explanations)
9. Do some models perform better at predicting the outcomes for a certain type of individual? (Benchmark Competition)
10. Can the model outcome be changed by artificially perturbing certain values of interest? (Adversarial Attack)
11. Do certain groups suffer relative to others as measured through group statistics? (Parity Indicators, Fair Lending Measures)
12. Can various data and prediction processing techniques improve these group statistics? (Model Agnostic Processing)
13. What features are driving the structural differences between groups controlling for demographic factors? (Feature Decomposition)
14. What individuals have received the most unfair prediction or treatment by the model? (Individual Disparity)
15. Why did the model decide to predict a specific outcome for a  particular individual or sub-group of individuals? (Reasoning Codes)
16. What individuals are most similar to those receiving unfair treatment and were these individuals treated similar? (Prototypical)
17. What individual is the closest related instance to a sample individual but has a different predicted outcome? (Counterfactual)
18. What is the minimal feature perturbation necessary to switch an individual's prediction to another category? (Contrastive)
19. What is the maximum perturbation possible while the model prediction remains the same? (Contrastive)


Noteworthy Screen Captures
------------
![text](assets/Screen%20Shot%202020-04-01%20at%2010.30.38%20AM.png)
![text](assets/Screen%20Shot%202020-04-01%20at%2010.31.00%20AM.png)
![text](assets/Screen%20Shot%202020-04-01%20at%2010.33.01%20AM.png)
![text](assets/Screen%20Shot%202020-04-01%20at%2010.33.15%20AM.png)
![text](assets/Screen%20Shot%202020-04-01%20at%2010.33.58%20AM.png)
![text](assets/Screen%20Shot%202020-04-01%20at%2010.34.09%20AM.png)
![text](assets/Screen%20Shot%202020-04-01%20at%2010.34.24%20AM.png)
![text](assets/Screen%20Shot%202020-04-01%20at%2010.34.41%20AM.png)
![text](assets/Screen%20Shot%202020-04-01%20at%2010.40.51%20AM.png)
![text](assets/Screen%20Shot%202020-04-01%20at%2010.51.12%20AM.png)
![text](assets/Screen%20Shot%202020-04-01%20at%2010.51.22%20AM.png)
![text](assets/Screen%20Shot%202020-04-01%20at%2010.51.34%20AM.png)
![text](assets/Screen%20Shot%202020-04-01%20at%2010.51.45%20AM.png)
![text](assets/Screen%20Shot%202020-04-01%20at%2010.51.55%20AM.png)



