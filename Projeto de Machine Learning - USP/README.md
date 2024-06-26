# MACHINE LEARNING PROJECT

The project consists of finding a dataset from the Kaggle website, in order to conduct exploratory data analysis of its attributes and apply machine learning models to reach possible conclusions.

After data preprocessing and exploration of the dataset using classification algorithms such as KNN and Decision Tree, it was possible to obtain a model that, given the fire conditions and acoustic device, would predict, with adequate accuracy, whether the fire would be extinguished.

# DATASET

Yavuz Selim TASPINAR, Murat KOKLU and Mustafa ALTIN

Citation Request :
1: KOKLU M., TASPINAR Y.S.,  (2021).  Determining the Extinguishing Status of Fuel Flames With Sound Wave by Machine Learning Methods.  IEEE Access, 9, pp.86207-86216, Doi: 10.1109/ACCESS.2021.3088612
Link: https://ieeexplore.ieee.org/document/9452168 (Open Access)
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9452168

2: TASPINAR Y.S., KOKLU M., ALTIN M., (2021).  Classification of Flame Extinction Based on Acoustic Oscillations using Artificial Intelligence Methods.  Case Studies in Thermal Engineering, 28, 101561, Doi: 10.1016/j.csite.2021.101561
Link: https://www.sciencedirect.com/science/article/pii/S2214157X21007243  (Open Access) https://www.sciencedirect.com/sdfe/reader/pii/S2214157X21007243/pdf

3: TASPINAR Y.S., KOKLU M., ALTIN M., (2022).  Acoustic-Driven Airflow Flame Extinguishing System Design and Analysis of Capabilities of Low Frequency in Different Fuels.  Fire Technology, Doi: 10.1007/s10694-021-01208-9
Link: https://link.springer.com/content/pdf/10.1007/s10694-021-01208-9.pdf"

CV:https://www.muratkoklu.com/en/publications/
DATASET: https://www.muratkoklu.com/datasets/



SHORT DESCRIPTION: The dataset was obtained as a result of the extinguishing tests of four different fuel flames with a sound wave extinguishing system. The sound wave fire-extinguishing system consists of 4 subwoofers with a total power of 4,000 Watt placed in the collimator cabinet. There are two amplifiers that enable the sound come to these subwoofers as boosted. Power supply that powers the system and filter circuit ensuring that the sound frequencies are properly transmitted to the system is located within the control unit. While computer is used as frequency source, anemometer was used to measure the airflow resulted from sound waves during the extinguishing phase of the flame, and a decibel meter to measure the sound intensity. An infrared thermometer was used to measure the temperature of the flame and the fuel can, and a camera is installed to detect the extinction time of the flame. A total of 17,442 tests were conducted with this experimental setup. The experiments are planned as follows:
1. Three different liquid fuels and LPG fuel were used to create the flame.
2. 5 different sizes of liquid fuel cans are used to achieve different size of flames.
3. Half and full gas adjustment is used for LPG fuel.
4. While carrying out each experiment, the fuel container, at 10 cm distance, was moved forward up to 190 cm by increasing the distance by 10 cm each time.
5. Along with the fuel container, anemometer and decibel meter were moved forward in the same dimensions.
6. Fire extinguishing experiments was conducted with 54 different frequency sound waves at each distance and flame size.
Throughout the flame extinguishing experiments, the data obtained from each measurement device was recorded and a dataset was created. The dataset includes the features of fuel container size representing the flame size, fuel type, frequency, decibel, distance, airflow and flame extinction. Accordingly, 6 input features and 1 output feature will be used in models. The explanation of a total of seven features for liquid fuels in the dataset is given in Table 1, and the explanation of 7 features for LPG fuel is given in Table 2.
The status property (flame extinction or non-extinction states) can be predicted by using six features in the dataset. Status and fuel features are categorical, while other features are numerical. 8,759 of the 17,442 test results are the non-extinguishing state of the flame. 8,683 of them are the extinction state of the flame. According to these numbers, it can be said that the class distribution of the dataset is almost equal."				

KEYWORDS: Fire, Extinguishing System, Sound wave, Machine learning, Fire safety, Low frequency, Acoustic

Data properties and descriptions for liquid fuels				
FEATURES	MIN/MAX VALUES					UNIT	DESCRIPTIONS	
SIZE		7, 12, 14, 16, 20				cm		Recorded as 7 cm=1, 12 cm=2, 14 cm=3, 16 cm=4, 20 cm=5	
FUEL		Gasoline, Kerosene, Thinner				Fuel type	
DISTANCE	10 - 190						cm		
DESIBEL		72 - 113						dB		
AIRFLOW		0 - 17							m/s		
FREQUENCY	1-75							Hz		
STATUS		0, 1									0 indicates the non-extinction state, 1 indicates the extinction state	
				
				
Data properties and descriptions for LPG				
FEATURES	MIN/MAX VALUES									UNIT		DESCRIPTIONS	
SIZE		Half throttle setting, Full throttle setting				Reocerded as Half throttle setting=6, Full throttle setting=7	
FUEL		LPG															Fuel type	
DISTANCE	10 - 190										cm		
DESIBEL		72 - 113										dB		
AIRFLOW		0 - 17											m/s		
FREQUENCY	1-75											Hz		
STATUS		0, 1														0 indicates the non-extinction state, 1 indicates the extinction state
