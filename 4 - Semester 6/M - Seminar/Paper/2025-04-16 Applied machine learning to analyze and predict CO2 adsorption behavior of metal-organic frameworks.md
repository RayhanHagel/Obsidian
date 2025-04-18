---
tags: Semester-6/seminar/paper 
aliases: 
  - Applied machine learning to analyze and predict CO2 adsorption behavior of metal-organic frameworks
  - liAppliedMachineLearning2023
---

> [!link]
> journalArticle [PDF](zotero://select/library/items/XLITHS9T)

> [!cite]
> liAppliedMachineLearning2023
> [https://doi.org/10.1016/j.ccst.2023.100146](https://doi.org/10.1016/j.ccst.2023.100146)

> [!authors]
> Xiaoqiang Li, Xiong Zhang, Junjie Zhang, Jinyang Gu, Shibiao Zhang, Guangyang Li, Jingai Shao, Yong He, Haiping Yang, Shihong Zhang, Hanping Chen

> [!keywords]
> **Tags:** adsorbent,  pore volume,  surface area,  MOF,  properties,  adsorption,  physiochemical properties,  pressure,  temperature,  CO2 Prediction,  M,  methodology,  GBDT,  LGBM,  models used for CO2 prediction,  RF,  XGB,  metal center,  data collection,  texture,  adsorption capacity,  features,  data interpolation,  data preprocessing,  KNN,  feature correlation,  pearsons correlation coefficient,  ensamble learning,  small dataset,  tree models,  unbalanced dataset,  bagging,  boosting,  grid search,  hyperparameter tuning,  kfold CV,  error metrics,  R2,  RMSE,  descriptive statistics,  element groups classification,  overfitting,  training-testing accuracy comparison,  feature importance,  SHAP,  lewis basic group,  open metal sites,  pore size

> [!hypothesis]-
> hypothesis:: 

> [!methodology]-
> methodology:: 

> [!result]- Result(s)
> results::

> [!summary]- Summary of Key Points
> summary:: 


---
## Notes


> <mark class="hltr-green">Porous solid adsorbents with high surface area and pore volume are potential choices for CO2 capture and utilization</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=&annotation=ZDEAYC2K)
**🏷️** | adsorbent | | pore volume | | surface area | 

> <mark class="hltr-green">Metal-organic frameworks (MOFs) have special structure features, chemical stability, tunability, larger specific surface area, large pore volume and low density</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=&annotation=7ALWTE6H)
**🏷️** | MOF | | properties | 

> <mark class="hltr-blue">adsorption of gas into the pores of the adsorbent and desorption based on pressure and/or temperature. The separation performance of the adsorbent depends on the pore structure and pore surface characteristics of the adsorbent and the physicochemical properties of the adsorbed gas</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=&annotation=QMFY58MA)
**🏷️** | adsorption | | physiochemical properties | | pressure | | temperature | 


### 📍 Page 2

![[4 - Semester 6/M - Seminar/Image/liAppliedMachineLearning2023/liAppliedMachineLearning2023-2-x31-y536.png]]
**🏷️** | CO2 Prediction | | M | | methodology | 

> <mark class="hltr-green">In this study, four ensemble models for small datasets were designed and evaluated, namely the Random Forest (RF), Gradient Boosting Decision Trees (GBDTs), Light Gradient Boosting Machines (LGBMs), and eXtreme Gradient Boost (XGB) algorithms.</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=2&annotation=7M3YWFFV)
**🏷️** | GBDT | | LGBM | | models used for CO2 prediction | | RF | | XGB | 

> <mark class="hltr-blue">These models were used to predict the amount of CO2 adsorbed by different MOFs based on their texture properties and metal center types, as well as the temperature and pressure of CO2 adsorption</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=2&annotation=7ZGCF69G)
**🏷️** | metal center | | MOF | | pressure | | temperature | 

> <mark class="hltr-purple">This study focused on collecting relevant data regarding the textures, adsorption parameters, and intensive metal centers of MOFs. Other characteristic data, such as compositional properties and preparation conditions, were not included due to the lack of available relevant data</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=2&annotation=AKREVVSJ)
**🏷️** | data collection | | methodology | | texture | 

> <mark class="hltr-blue">The final extracted features were BET surface area (SBET), Langmuir specific surface area (SL), total pore volume (VT), pressure (P), temperature (T), metal center categories, and CO2 adsorption capacity</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=2&annotation=72XGNMT5)
**🏷️** | adsorption capacity | | features | | metal center | | pore volume | | pressure | | surface area | | temperature | 

> <mark class="hltr-purple">The K-Nearest Neighbor (KNN) model was used to interpolate missing data</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=2&annotation=JGHI3N6J)
**🏷️** | data interpolation | | data preprocessing | | KNN | | methodology | 

> <mark class="hltr-green">The linear correlation between features is usually measured by Pearson’s correlation coefficient(PCC)</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=2&annotation=SZ84TSLI)
**🏷️** | feature correlation | | pearsons correlation coefficient | 


### 📍 Page 3

> <mark class="hltr-green">Ensemble learning is to accomplish machine learning tasks by combining multiple learners</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=3&annotation=7ENSIEM7)
**🏷️** | ensamble learning | 

> <mark class="hltr-green">In addition, ensemble learning based on tree models has great advantages in dealing with small and unbalanced data set</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=3&annotation=B85FZFSJ)
**🏷️** | ensamble learning | | small dataset | | tree models | | unbalanced dataset | 

> <mark class="hltr-green">There are two classes of ensemble learning that complete learning tasks by building multiple learners. One is the boosting method which is characterized by dependencies between the various weak learners, and the other is the bagging method which is characterized by no dependencies between the various weak learners and can be fitted in parallel.</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=3&annotation=46B2379S)
**🏷️** | bagging | | boosting | | ensamble learning | 

> <mark class="hltr-green">The main idea of boosting is to iterate over the weak classifiers and combine them according to different weights to form a strong classifier, and these basic classifiers have dependencies with each other. There are mainly Adaboost algorithms, lift trees, GBDTs, LGBMs, and XGB</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=3&annotation=V7I8D2FL)
**🏷️** | boosting | | ensamble learning | 

> <mark class="hltr-green">The main idea of bagging is to train several different models individually and then all the models vote on the output of the test samples.</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=3&annotation=4H3UN3CJ)
**🏷️** | bagging | | ensamble learning | 


### 📍 Page 4

> <mark class="hltr-green">RF was found to be a practical and popular bagging ensemble method due to its simple structure, excellent predictive performance, and easy-to-adjust hyperparameters. RF benefits from double randomness, which includes the randomness of data selection and the randomness of feature selection. This feature of RF greatly reduces the likelihood of overfitting. In addition, RF produces stable and reliable results, even with a large number of base tree models</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=4&annotation=9CTCTYAY)
**🏷️** | RF | 

> <mark class="hltr-green">GBDT is an iterative decision tree algorithm. It constructs a set of Decision Trees(DTs) (Kotsiantis, 2013). The latter DTs fit the first derivative expansion of the previous loss function, and reduce the loss function by continuous iteration. The GBDT conclusion is adding up the conclusions of all DTs. GBDT can flexibly handle discrete and continuous values and cleverly connect DTs sequentially to achieve high-precision learning. However, the sequential connection prevents DTs from being trained in parallel</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=4&annotation=JEJK28BP)
**🏷️** | GBDT | 

> <mark class="hltr-green">XGB is a variant of GBDT that fits the second-order derivative expansion of the previous loss function, so it has higher accuracy than GBDT (Hsu et al., 2020), At the same time, XGB can be multi-threaded when selecting the best segmentation point, which greatly improves the calculation speed</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=4&annotation=48WXS8K4)
**🏷️** | XGB | 

> <mark class="hltr-green">LGBM is another new variant of GBDT. It adopts the DT algorithm of Histogram, which makes the memory occupation and calculation cost smaller. Meantime, LGBM can be trained in parallel efficiently</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=4&annotation=VFU33R69)
**🏷️** | LGBM | 

> <mark class="hltr-purple">During the model training process, grid search and k-fold crossvalidation (k-fold CV) were used to adjust the hyperparameters of models to improve the prediction ability and generalization ability</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=4&annotation=R9486BY6)
**🏷️** | grid search | | hyperparameter tuning | | kfold CV | | methodology | 

> <mark class="hltr-green">Grid search is an exhaustive search method. It traverses the candidate parameters in a loop and selects the parameters with the best realization</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=4&annotation=II573LU6)
**🏷️** | grid search | 

> <mark class="hltr-green">K-fold CV was to divide the training data into k subsets. In each training iteration, one of the subsets was used as the validation set, and the remaining k-1 subset data were used as the training sets, so that k models were obtained</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=4&annotation=YRAYVK53)
**🏷️** | kfold CV | 

> <mark class="hltr-green">Performance evaluation of machine learning models used the correlation coefficient (R2) and the root mean square error (RMSE)</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=4&annotation=G36M9N95)
**🏷️** | error metrics | | R2 | | RMSE | 

> <mark class="hltr-green">The higher value of R2 and the lower value of RMSE means that the performance of the model is better</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=4&annotation=673WZTSX)
**🏷️** | error metrics | | R2 | | RMSE | 

![[4 - Semester 6/M - Seminar/Image/liAppliedMachineLearning2023/liAppliedMachineLearning2023-4-x306-y440.png]]
**💬** Fig. 3 showed that the PCC of MOFs characteristics (SBET, SL, VT) was above 0.8, indicating that these three variables had a strong positive correlation.
**🏷️** | pearsons correlation coefficient | 

> <mark class="hltr-purple">To avoid dimensional disasters, metal centers were classified according to element groups</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=4&annotation=KPULN4PX)
**🏷️** | descriptive statistics | | element groups classification | | metal center | | methodology | 

> <mark class="hltr-purple">Each model was built based on the training dataset, and the model hyperparameters were tuned by 5-fold CV and grid search methods to improve both their predictive ability and generalization ability.</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=4&annotation=L7TUJW5U)
**🏷️** | methodology | 

> <mark class="hltr-purple">The accuracy of four models on the training set was above 0.9 and the accuracy on the testing set was below 0.9, which showed that although the cross-validation and grid search methods were used to try to avoid overfitting, they all had a degree of overfitting.</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=4&annotation=TTL575JV)
**🏷️** | overfitting | | training-testing accuracy comparison | 


### 📍 Page 5

> <mark class="hltr-green">Ensemble learning is complex and is a black-box model in a broad sense</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=5&annotation=B9TYWLCA)
**🏷️** | ensamble learning | 


### 📍 Page 6

![[4 - Semester 6/M - Seminar/Image/liAppliedMachineLearning2023/liAppliedMachineLearning2023-6-x296-y415.png]]
**💬** From top to bottom is the most important, and the x axis shows the amount of data. Red = larger actual values. For P, the actual values are high (red) and the SHAP values are also large
**🏷️** | feature importance | | SHAP | 

> <mark class="hltr-green">SHapley Additive exPlanations (SHAP) (Nohara et al., 2022) provides a unified framework for interpreting the predictions of any model. It uses the concept of Shapley values from cooperative game theory to explain the contribution of each input feature to the final prediction of the model.</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=6&annotation=S6CBL6MU)
**🏷️** | feature importance | | SHAP | 

> <mark class="hltr-purple">The feature importance analysis assessed the relative importance of input features for CO2 adsorption by MOFs and their derivatives. Fig. 5(a) showed the Gini importance of the input features</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=6&annotation=RZ92HUJF)
**🏷️** | feature importance | | methodology | 

> <mark class="hltr-green">The SHAP absolute average value of all feature samples was taken as feature importance</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=6&annotation=APEVYWJM)
**🏷️** | feature importance | 

> <mark class="hltr-blue">Among the input features, P, and T were found to be the most important, with P having the greatest impact.</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=6&annotation=Z9LXS6CZ)
**🏷️** | feature importance | | pressure | | temperature | 

> <mark class="hltr-green">The adsorption of CO2 by MOFs is mainly physical adsorption and is mainly driven by van der Waals forces, which are very sensitive to temperature and pressure</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=6&annotation=JNVJ6LVU)
**🏷️** | feature importance | | pressure | | temperature | 

> <mark class="hltr-green">In Gini importance, SL and VT were more important, and SHAP feature importance calculation results showed that IB and VIII were more important. In addition, both Gini importance and SHAP feature importance rankings suggested that some specific elements of IIB, IIIA, and IVB as metal centers had little effect on CO2 adsorption</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=6&annotation=XADCTK8R)
**🏷️** | feature importance | | metal center | 

> <mark class="hltr-blue">The correlation between P and CO2 adsorption capacity was positive. Therefore, the adsorption capacity would greatly be improved when the P is increased,</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=6&annotation=HA4UZDBK)
**🏷️** | adsorption capacity | | feature importance | | pressure | 

> <mark class="hltr-blue">there was a negative correlation between the increase of T and the adsorption capacity of CO2, suggesting that higher temperatures negatively impacted CO2 adsorption</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=6&annotation=5ETUJXG9)
**🏷️** | adsorption capacity | | feature importance | | temperature | 


### 📍 Page 7

> <mark class="hltr-blue">the contribution of MOFs to CO2 adsorption capacity increased significantly with the increase of SBET, SL and VT under high pressure.</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=7&annotation=F2BV7NMK)
**🏷️** | adsorption capacity | | pore volume | | surface area | 

> <mark class="hltr-blue">For CO2 adsorption in lowpressure regions, it is mainly considered to be dominated by the affinity between MOFs and CO2. This can be achieved by pore size control (Furukawa et al., 2008), open metal sites (He et al., 2016), Lewis basic groups and other polar groups.</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=7&annotation=DVQHG7Y7)
**🏷️** | adsorption capacity | | lewis basic group | | MOF | | open metal sites | | pore size | | pore volume | 


### 📍 Page 8

> <mark class="hltr-blue">Specifically, the metal centers with IB and VIII element groups were found to be favorable for CO2 adsorption capacity</mark> [🔗](zotero://open-pdf/library/items/XLITHS9T?page=8&annotation=KZHTSS6J)
**🏷️** | adsorption capacity | | metal center | 
