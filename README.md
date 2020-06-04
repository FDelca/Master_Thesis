# Master Thesis
# Machine Learning applied to energy demand forecast in IST Alameda campus

Energy consumption forecasting plays a crucial role in making planning decisions by facility managers and energy providers. These decisions are used to reduce the intrinsic environmental impact of the building sector. Nowadays, with the imminent application of Building Energy Management Systems (BEMS) and the consequent increased of generated data, the use of machine learning to provide such predictions becomes a natural solution. 

In this study, **four machine learning algorithms** were used and compared:
 - Multilayer Perceptron (MLP);
 - Support Vector Machines (SVM);
 - Random Forest (RF);
 - eXtreme Gradient Boosting (XGB).
 
In three different forecast horizons:
 - Hour
 - Day
 - Week

### <img align="right" width="100" height="150" src=Images/Alameda_Final.PNG>
For **four** buildings, located at [Alameda campus of Instituto Superior Técnico, Lisbon](https://bit.ly/3clBJ0L):
 - Civil;
 - Central;
 - North Tower;
 - South Tower.

**Available Data:**
 - Three years (2014, 2017, 2018) of hourly gathered data (buildings' consumption and outdoor weather conditions), where:
   - **Training Stage** - 2014 and 2017 ;
   - **Testing Stage** - 2018.
 
### <img align="right" width="250" height="250" src=Images/Final_Pipeline.PNG>
**Pipeline:** [(check diagram)](https://ibb.co/qRFgPB0)
 - Data Treatment;
 - EDA (Explonatory Data Analysis);
 - Feature Generation;
 - Feature Selection (Filter & Wrapper Method);
 - Hyperparameter Optimization;
 - Forecasting
 - Evaluate Predictions
 
 
 ### NOTE:
Due to the quantity of developed models (total 48) this study will only going to cover two buildings. Further details may be found in [Master Thesis](https://drive.google.com/file/d/1zlK6xB23vgEOCFrJcrTKi2UqYAVmpJQG/view?usp=sharing).
