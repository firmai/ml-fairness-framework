# FairPut — Fair Machine Learning Outputs

This is a holistic approach to implement fair outputs at the individual and group level.

FairPut is a light framework that describes a preferred process at the end of the machine learning pipeline to enchance model fairness. This is a holistic approach to obtain less biased outputs at the individual and group level. Developers and researchers first follow the normal table processing, table exploration, feature processing, feature extraction, and model validation steps to obtain the **best possible model** to maximise a certain metric like sales or profit. The FairPut methodology follows on from this initial process. The aim is to simultaneously enhance model interpretability, robustness, and fairness while maintaining a reasonable level of accuracy. FairPut unifies various recent machine learning constructs in a practical manner. This method is model agnostic, but this particular development instance uses LightGBM.

##### **1. Model Interpretability**
*	Model Respecification 
       * Protected Values Prediction
       * Model Constraints
       * Hyperparameter Modelling
        1. Interpretable Model
        1. Global Explanations
        1. Monotonicity Feature Explanations
*	Quantitative Validation 
        1. Level Two Monotonicity
        1. Relationship Analysis
        1. Partial Dependence (LV1) Monotonicity
        1. Feature Interactions
        1. Metrics and Cut-off
##### **2. Model Robustness**
  *	Residual Deviation
  *	Residual Explanations
  *	Benchmark Competition
  *	Adversarial Attack

##### **3. Regulatory Fairness**
  *	Group
        1. Disparate Error Analysis
            * Parity Indicators
            * Fair Lending Measures
        1. Model Agnostic Processing
            * Reweighing Preprocessing
            * Disparate Impact Preprocessing
            * Calibrate Equalized Odds
        1. Feature Decomposition
  *	Individual
        1. Reasoning
            * Individual Disparity
            * Reasoning Codes

        1. Example Base
            * Prototypical
            * Counterfactual
            * Contrastive
