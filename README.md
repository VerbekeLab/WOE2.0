# Weight-of-evidence through shrinkage and spline binning for interpretable nonlinear classification </br><sub><sub>Jakob Raymaekers - Wouter Verbeke - Tim Verdonck [[2022]](https://doi.org/10.1016/j.asoc.2021.108160)</sub></sub>
In many practical applications, such as fraud detection, credit risk modeling or medical decision making, classification models for assigning instances to a predefined set of classes are required to be both precise and interpretable. Linear modeling methods such as logistic regression are often adopted since they offer an acceptable balance between precision and interpretability. Linear methods, however, are not well equipped to handle categorical predictors with high cardinality or to exploit nonlinear relations in the data. As a solution, data preprocessing methods such as weight of evidence are typically used for transforming the predictors. The binning procedure that underlies the weight-of-evidence approach, however, has been little researched and typically relies on ad hoc or expert-driven procedures. The objective in this paper, therefore, is to propose a formalized, data-driven and powerful method. To this end, we explore the discretization of continuous variables through the binning of spline functions, which allows for capturing nonlinear effects in predictor variables and yields highly interpretable predictors that take only a small number of discrete values. Moreover, we extend the weight-of-evidence approach and propose to estimate the proportions using shrinkage estimators. Together, this method offers an improved ability to exploit both nonlinear and categorical predictors to achieve increased classification precision while maintaining the interpretability of the resulting model and decreasing the risk of overfitting. We present the results of a series of experiments in fraud detection and credit risk settings, which illustrate the effectiveness of the presented approach.

## Repository structure
This repository is organised as follows:


## Citing
Please cite our paper and/or code as follows:

```tex

@article{raymaekers2022,
  title={Weight-of-evidence through shrinkage and spline binning for interpretable nonlinear classification},
  author={Raymaekers, Jakob and Verbeke, Wouter and Verdonck, Tim},
  journal={Applied Soft Computing},
  volume={115},
  pages={108160},
  year={2022},
  publisher={Elsevier}
}


```
