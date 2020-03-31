# FairPut — Fair Machine Learning Output Framework

[Framework Case Study](https://colab.research.google.com/drive/1uxSP5_CuhxjjhcT_iIeL6lsmx1gwO5B6)

This is a holistic approach to implement fair outputs at the individual and group level.

FairPut is a light open framework that describes a preferred process at the end of the machine learning pipeline to enchance model fairness. Developers and researchers first follow the normal table processing, table exploration, feature processing, feature extraction, and model validation steps to obtain the **best possible model** to maximise a certain metric like sales or profit. The FairPut methodology follows on from this initial process. The aim is to simultaneously enhance model interpretability, robustness, and fairness while maintaining a reasonable level of accuracy. FairPut unifies various recent machine learning constructs in a practical manner. This method is model agnostic, but this particular development instance uses LightGBM.

#### **1. [Model Explainability](https://colab.research.google.com/drive/1uxSP5_CuhxjjhcT_iIeL6lsmx1gwO5B6#scrollTo=pXftn6tIdi5f&line=1&uniqifier=1)**
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
#### **2. [Model Robustness](https://colab.research.google.com/drive/1uxSP5_CuhxjjhcT_iIeL6lsmx1gwO5B6#scrollTo=cGreStojd5oc)**
---------------
  *	Residual Deviation
  *	Residual Explanations
  *	Benchmark Competition
  *	Adversarial Attack

#### **3. [Regulatory Fairness](https://colab.research.google.com/drive/1uxSP5_CuhxjjhcT_iIeL6lsmx1gwO5B6#scrollTo=HGLUFEIBbC0s)**
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
  title = {{FairPut}: Fair Machine Learning Output Framework.},
  author = {Snow, Derek},
  url = {https://github.com/firmai/fairput/},
  version = {1.15},
  date = {2020-03-31},
}
```
