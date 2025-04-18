---
tags: Semester-6/seminar/paper 
aliases: 
  - Robust machine-learning model for prediction of carbon dioxide adsorption on metal-organic frameworks
  - longeRobustMachinelearningModel2025
---

> [!link]
> journalArticle [PDF](zotero://select/library/items/4LV6FXQN)

> [!cite]
> longeRobustMachinelearningModel2025
> [https://doi.org/10.1016/j.jallcom.2024.177890](https://doi.org/10.1016/j.jallcom.2024.177890)

> [!authors]
> Promise O. Longe, Shadfar Davoodi, Mohammad Mehrad, David A. Wood

> [!keywords]
> **Tags:** CO2 generation,  carbon capture and storage,  adsorption capacity,  improvement,  MOF,  metal center,  MOF Example,  zeolites,  functional groups,  open metal sites,  pore size,  surface area,  traditional experiment,  machine learning,  screening,  pore volume,  predictive modeling,  density,  descriptors,  void fraction,  GCMC,  CIF File,  feature importance,  temperature,  hybrid machine learning,  features,  adsorption,  Fe metal center,  co2 selectivity,  feature correlation,  PDP,  SHAP,  ARE (average relative error),  Err (computing error),  error metrics,  RE (relative error),  performance index,  RMSE,  RRMSE,  R2,  pearsons correlation coefficient,  pressure,  methodology,  physisorption,  van der Waals forces,  chemisorption,  data preprocessing,  langmuir and bet,  dataset,  deep learning model

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


> <mark class="hltr-green">Carbon dioxide (CO2) plays a significant role in global warming, with atmospheric concentrations rising due to fossil fuel combustion in electricity generation, transportation, and industry</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=&annotation=ZEL9VW88)
**🏷️** | CO2 generation | 

> <mark class="hltr-green">To date, various CO2 capture and storage methods have been explored, including absorption techniques [10–12], membrane technologies [13,14] and carbon-based adsorbents [15,16], each showing a degree of promise</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=&annotation=ZPM74DWB)
**🏷️** | carbon capture and storage | 

> <mark class="hltr-green">For a material to be deemed effective in the CO2 capture process, it must exhibit superior CO2 adsorption properties and allow for easy release of CO2 during the regeneration phase</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=&annotation=CGXPGTDH)
**🏷️** | adsorption capacity | | improvement | 


### 📍 Page 2

> <mark class="hltr-green">Metal-organic frameworks (MOFs) are crystalline materials with metal ions/ ion-clusters integrated with organic molecules to form rigid, porous structures of up to three dimensions. MOFs have been identified as promising materials for CCS, due to their adaptable nature, hightemperature stability, and easily adjustable chemical structures</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=2&annotation=G9P2DALP)
**🏷️** | MOF | 

> <mark class="hltr-green">The choice of metal and linker affects the properties of MOFs. For example, IRMOF-1 contains zinc and terephthalic linkers, providing high-capacity adsorption pores. Some MOFs have unsaturated metallic centers (UMCs), offering more active sites for CO2 and enhancing the bond between the MOF structure and CO2</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=2&annotation=VIVYQ8CZ)
**🏷️** | metal center | | MOF Example | 

> <mark class="hltr-green">MOFs are favored over traditional materials like zeolites for CO2 adsorption, due to their larger pore sizes, enabling better molecular diffusion within and across crystal structures</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=2&annotation=P6TG69JN)
**🏷️** | MOF | | zeolites | 

> <mark class="hltr-blue">CO2 adsorption in MOFs is influenced by various factors, including pore size [36], surface area [36], functional groups [37], and the presence of open metal sites</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=2&annotation=ERLN4JXK)
**🏷️** | adsorption capacity | | functional groups | | open metal sites | | pore size | | surface area | 

> <mark class="hltr-red">Traditional experimental methods for evaluating the performance of MOFs are labor-intensive and time-consuming, often requiring extensive synthesis and characterization efforts</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=2&annotation=6TMIJMS4)
**🏷️** | traditional experiment | 

> <mark class="hltr-green">Machine learning (ML) offers a powerful alternative by enabling high-throughput computational screening of MOF libraries</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=2&annotation=452TEUDN)
**🏷️** | machine learning | | screening | 

> <mark class="hltr-blue">For example, a study by Mahajan and Lahtinen [37] reveals that the presence of open metal sites and specific pore geometries are the most critical factors influencing CO2 adsorption in MOFs</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=2&annotation=6L35MT6H)
**🏷️** | adsorption capacity | | open metal sites | | pore size | | pore volume | 

> <mark class="hltr-green">The advantages of cost and time-efficiency offered by machine learning (ML) without relying on oversimplified assumptions is an alternative for CO2 uptake predictions. Machine learning techniques known for capturing complex non-linear relationships, are increasingly used in predictive modeling</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=2&annotation=9Y3V3DK6)
**🏷️** | machine learning | | predictive modeling | 

> <mark class="hltr-blue">Various descriptors, such as geometrical, chemical, topological, and energy-based, can model CO2 uptake capabilities. Geometrical descriptors, which focus on the pore environment in MOFs, are commonly used in ML to predict gas adsorption and storage capacities. These descriptors include metrics like volumetric surface area, gravimetric surface area, pore volume, density, and void fraction, providing a general overview of the material’s properties</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=2&annotation=H2I9BLKF)
**🏷️** | density | | descriptors | | pore size | | pore volume | | surface area | | void fraction | 

> <mark class="hltr-red">However, GCMC simulations require significant computational resources, making them time-consuming and costly when working with large datasets containing millions of MOFs.</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=2&annotation=YU2WXX6I)
**🏷️** | GCMC | 


### 📍 Page 3

> <mark class="hltr-green">Lu et al. [51] created a deep-learning model to predict CO2 working capacity in metal-organic frameworks (MOFs) at low pressure, using only Crystallographic Information File (CIF) data instead of experimental results. This approach involves transforming 3D CIF data into 2D representations, which can lead to errors and uncertainties</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=3&annotation=NDPIQVS4)
**🏷️** | CIF File | | MOF | 

> <mark class="hltr-green">Sensitivity analysis revealed that temperature had a negative impact on CO2 adsorption, while specific surface area and pressure were the most significant factors</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=3&annotation=5IAE69FZ)
**🏷️** | feature importance | | surface area | | temperature | 


### 📍 Page 4

> <mark class="hltr-green">To enhance the predictive accuracy of traditional machine learning approaches, researchers often integrate optimization algorithms into their models. Little attention has been given to using hybrid machine learning (HML) models for robust prediction of CO2 uptake in MOFs systems, and the capabilities of HML models in this regard have yet to be evaluated</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=4&annotation=QXYV6SBS)
**🏷️** | hybrid machine learning | 

> <mark class="hltr-green">LSSVM and MLPNN hybridized with Growth optimization (GO) and particle swamp optimization (PSO) models are innovative approaches that have not previously been adapted for predicting CO2 uptake in MOFs system</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=4&annotation=B8YKJL9P)
**🏷️** | hybrid machine learning | | machine learning | 

> <mark class="hltr-blue">After data pre-processing, six key attributes were identified as predictors for CO2 uptake in MOFs, encompassing physical and operational parameters:  Brunauer-Emmett-Teller (BET) specific surface area (SBET, in m2/g),  Langmuir specific surface area (SL, in m2/g), total pore volume (VT, in  cm3/g), pressure (in kPa), temperature (in K), and the metal composition forming the MOF’s metal center. The target variable was CO2 uptake capacity (in mmol/g</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=4&annotation=BFZEMZQP)
**🏷️** | features | | metal center | | pore volume | | surface area | | temperature | 

> <mark class="hltr-green">On the other hand, Fe centers have notably higher median values for SBET, SL, and VT, but lower median CO2 uptake compared to other metal centers. This discrepancy between CO2 adsorption and surface area might be due to uncertainties in N2-based surface area analysis</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=4&annotation=QSY7JEQA)
**🏷️** | adsorption | | Fe metal center | | metal center | | pore volume | | surface area | 

> <mark class="hltr-red">Samples with Cd centers have the lowest feature values, possibly because of their low pore diameter, which likely limit their CO2 adsorption, as the pore diameter needs to be larger than the kinetic diameter of CO2</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=4&annotation=63UXUC78)
**🏷️** | co2 selectivity | | metal center | | pore size | 

> <mark class="hltr-green">To ensure robust model selection, overfitting evaluation, scoring, and regression error characteristics (REC) are used to determine the most predictive and generalizable model. Additionally, William’s plot helps identify outliers, while Shapley additive explanation (SHAP) and partial dependence plots (PDP) offer insights into the best model’s interpretability and the influence of individual input variables on the output.</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=4&annotation=M9I6I8J3)
**🏷️** | feature correlation | | PDP | | SHAP | 


### 📍 Page 5

> <mark class="hltr-green">Computing error (Err) values involve comparing experimental and predicted CO2 uptake values for each data point using Eq. (1). The division of Err values by measured CO2 uptake values yields the relative error (RE) (Eq. (2)). Subsequently, the average relative error (ARE) is determined by aggregating total RE values and the total number of data points (Z) (Eq. (3)).</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=5&annotation=GHPZUDMJ)
**🏷️** | ARE (average relative error) | | Err (computing error) | | error metrics | | RE (relative error) | 

> <mark class="hltr-green">The root mean square error (RMSE), a pivotal prediction-error metric, is computed using Eq. (4)</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=5&annotation=GLDYKQBW)
**🏷️** | error metrics | 

> <mark class="hltr-green">Gandomi et al. [60] introduced the performance index (PI), which concurrently considers the correlation coefficient (R) and relative RMSE (RRMSE) as calculated with Eq. (5).</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=5&annotation=EJDTXRGU)
**🏷️** | error metrics | | performance index | | RMSE | 

> <mark class="hltr-green">The RRMSE value is derived by dividing the RMSE value by the average measured CO2 uptake value using Eq. (6).</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=5&annotation=IJNDYC6W)
**🏷️** | error metrics | | RRMSE | 

> <mark class="hltr-purple">These prediction-performance metrics mentioned above primarily measure errors, where lower values indicate superior prediction performance.</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=5&annotation=6BPCT9J6)
**🏷️** | error metrics | | performance index | | RMSE | | RRMSE | 

> <mark class="hltr-green">Conversely, the coefficient of determination (R2) (Eq. (7)) is regarded as a positive criterion, with higher values signaling enhanced prediction performance</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=5&annotation=JV6468X7)
**🏷️** | error metrics | | R2 | 

> <mark class="hltr-green">A Pearson correlation analysis was conducted to evaluate the correlation between the variables considered and expressed as a heat map</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=5&annotation=K884PZCD)
**🏷️** | feature correlation | | pearsons correlation coefficient | 

> <mark class="hltr-blue">Most features show a direct correlation with CO2 uptake, except temperature (T), which has a weak inverse correlation, consistent with experimental studies</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=5&annotation=NK5LRMB3)
**🏷️** | adsorption capacity | | temperature | 

> <mark class="hltr-blue">Pressure (P) has the strongest linear correlation with CO2 uptake, due to the role it plays in pore-filling dynamics and pressure-dependent adsorption mechanisms in MOFs</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=5&annotation=QLYZW2RU)
**🏷️** | pressure | 

![[4 - Semester 6/M - Seminar/Image/longeRobustMachinelearningModel2025/longeRobustMachinelearningModel2025-5-x94-y432.png]]
**🏷️** | methodology | 


### 📍 Page 6

> <mark class="hltr-green">At lower pressures, CO2 uptake is driven by physisorption, where CO2 is held by weak van der Waals forces</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=6&annotation=M7YJXBXU)
**🏷️** | physisorption | | pressure | | van der Waals forces | 

> <mark class="hltr-green">As pressure rises, more CO2 molecules fill the MOF pores, although further increases in pressure have minimal effect once the pores are saturated. At higher pressures, chemisorption, involving stronger chemical interactions might occur.</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=6&annotation=YEXLXDKK)
**🏷️** | adsorption capacity | | chemisorption | | pressure | 

> <mark class="hltr-blue">Additionally, the weakest correlation is with metal center (MC), as demonstrated by previous studies</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=6&annotation=44ZCH9GM)
**🏷️** | feature importance | | metal center | 

> <mark class="hltr-blue">Strong Pearson’s correlation coefficients among SBET, SL, and VT features suggest a degree of interdependence.</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=6&annotation=UUB8RAUH)
**🏷️** | pearsons correlation coefficient | | pore volume | | surface area | 

> <mark class="hltr-purple">After evaluating the data and removing 12 incomplete data points, the remaining 475 data points were divided into training and testing categories with varying separation ratios from 0.6 to 0.95, as determined by the PSO algorithm</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=6&annotation=KDLNXSLK)
**🏷️** | data preprocessing | | methodology | 


### 📍 Page 8

> <mark class="hltr-green">The hybrid models, particularly those using the GO algorithm, achieve significantly lower RMSE than the simple ML models, indicating that the optimizers positively impact performance. All sixperformance metrics confirm that the LSSVM-GO model outperforms other models with the training dataset.</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=8&annotation=3XURM5BX)
**🏷️** | hybrid machine learning | | machine learning | 


### 📍 Page 10

> <mark class="hltr-green">Assessing the impact of input features on predictive models is crucial for building effective ML/HML models. It helps understand the relationships between input and output variables, allowing analysts to identify key features that significantly affect the model’s performance. This process facilitates adjustments to improve prediction accuracy and supports better decision-making. The SHAP (SHapley Additive exPlanations) tool was used to visualize the relative contributions of individual features to the model’s predictions.</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=10&annotation=PZ8ZN6QJ)
**🏷️** | feature importance | | SHAP | 

> <mark class="hltr-blue">SHAP values for the MC and VT features are close to zero, indicating a minimal impact on the model</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=10&annotation=FRWQEQCN)
**🏷️** | metal center | | pore volume | | SHAP | 

> <mark class="hltr-blue">According to the SHAP summary plot (Fig. 15b), SBET, P, and T have the most significant influence on CO2-uptake predictions, while MC, SL, and VT have the least impact</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=10&annotation=4HUJ37NQ)
**🏷️** | pressure | | SHAP | | surface area | | temperature | 

> <mark class="hltr-blue">First, while SBET and SL are indeed highly correlated, they reflect different surface characteristics because of the way they are measured: SBET accounts for both microporous and mesoporous regions, whereas SL primarily represents microporous areas</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=10&annotation=2H9FNT3Z)
**🏷️** | langmuir and bet | | surface area | 

> <mark class="hltr-green">PDP offers insights into the factors driving ML/HML model predictions by examining how CO2-uptake predictions are influenced by adjusting one feature while keeping another constant, which reveals interactions between input features.</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=10&annotation=XIWSTNPQ)
**🏷️** | feature importance | | PDP | 

> <mark class="hltr-red">The dataset size (475 data points) remains relatively small, which may affect the robustness and generalizability of the developed models.</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=10&annotation=PCBVUTVL)
**🏷️** | dataset | 


### 📍 Page 12

> <mark class="hltr-red">The dataset contains samples with ten specific metal centers—aluminum, nickel, zinc, zirconium, titanium, copper, cadmium, cobalt, iron, and hafnium—analyzed within a limited temperature and pressure range.</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=12&annotation=9L5RW6IH)
**💬** dataset only have 10 metal center, which could be the reason why the SHAP gives MC a close to zero score
**🏷️** | dataset | 

> <mark class="hltr-green">Deep learning algorithms, which can learn complex data patterns, are generally more effective for predicting larger datasets compared to traditional machine learning models.</mark> [🔗](zotero://open-pdf/library/items/4LV6FXQN?page=12&annotation=M5XM3FT4)
**🏷️** | deep learning model | | machine learning | 
