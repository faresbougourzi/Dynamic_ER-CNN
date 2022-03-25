## CNN Based Facial Aesthetics Analysis through Dynamic Robust Losses and Ensemble Regression
In summary, the main contributions of this paper are as follows:

• ParamSmoothL1 regression loss function and a dynamic law that changes
the parameters of the robust loss function during training. For this 
purpose, we use the parabolic law with the following robust loss functions:
ParamSmoothL1, Huber and Tukey, to be able to solve the problem of
complexity in finding the best loss function parameter. Furthermore, these
dynamic losses improve the training convergence compared with the stan-
dard loss functions (MSE and L1) and robust loss functions (SmoothL1,
Huber and Tukey) adopting a fixed parameter.

• Two backbones network (2B-IncRex) for face beauty estimation based on
ResneXt-50 and Inception-v3 architectures is proposed for Facial Beauty
Prediction.

• Ensemble regression for estimating facial beauty by fusing the predicted
values of one-branch networks (ResneXt-50 and Inception-v3) and two
backbones networks (2B-IncRex) is proposed. This ensemble of five CNNs
are trained with these dynamic loss functions: Dynamic ParamSmoothL1,
Dynamic Tukey, Dynamic ParamSmoothL1, Dynamic Huber, and Dynamic
Tukey, respectively. Although the individual regression models are sepa-
rately trained with the same fixed hyperparameters, the estimates generated
by the resulting ensemble regression are more accurate compared to the
individual models as well as to the state-of-the-art solutions.

