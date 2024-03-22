# Water-Quality
Introduction :

Water is one of the most crucial resources for most living creatures, including humans, and vital in sustaining life. We drink water daily to survive, so it is of utmost importance to ensure that the water we consume is potable. Most impurities have a certain limit till they are safe to consume, exceeding these limits will cause a threat to life and negatively impact it. Several methods are used to gauge water quality from rivers, lakes, and oceans.
There are also other different applications for which we need to gauge the quality of water - in the pharmaceutical industry, we need the utmost purity of water; for agriculture and industry, we need water that is not too salty, free of toxins that shouldn't damage the crops and soil and not damage the environment.
We will be using various Machine Learning algorithms to predict the water quality based on the parameters provided. The algorithms used in this project are Logistic Regression, K-Nearest Neighbours, Decision Tree, and Support Vector Machine (SVM).

About the dataset:
Source https://www.kaggle.com/datasets/adityakadiwal/water-potability
Number of data points 3275
Number of parameters 10

About the parameters:
1. pH: The pH of water determines whether water is acidic or alkaline. A pH value of 7 is an ideal case as extreme pH values affect the taste of water and might indicate the presence of harmful substances. 
2. Hardness: Hardness is the measure of calcium and magnesium salts in the water sample.
3. Total dissolved salts: High levels of TDS in water affect its taste, quality, and odor. Water samples with high TDS may taste salty and brackish making it unsuitable for consumption.
4. Chloramines: Chloramines and chlorides are used as disinfectants to purify public water systems. Chloramines are formed when chlorides react with ammonia. A value of 4 ppm of chloramines is safe for drinking water.
5. Sulfates: Sulfates are naturally occurring substances that are found in minerals, soil, and rocks. Samples with high sulfate content have a noticeably different odor and taste - bitter and rotten egg smell. High values of sulfates have adverse health effects on humans.
6. Conductivity: Pure water is a bad conductor of water due to the absence of ions. An increase in the ions in water enhances the electrical conductivity of water.
7. Organic Carbon: TOC is a measure of the total amount of carbon in organic compounds in pure water. It comes in water by decaying organic matter and synthetic matter in water.
8. Trihalomethanes: They are chemicals found in water when it is treated with chlorides. The concentrations of trihalomethanes vary with the level of organic matter in water, and the amount of chlorine.
9. Turbidity: The turbidity of water depends on the quantity of solid matter present in the suspended state. It is a measure of the light-emitting properties of water.
10. Potability: It indicates whether the water is safe to drink.

Experiments:
We tested 7 water samples which were available around our college. We could only test the water on 4 of the 9 input parameters due to the unavailability of equipment so we tested the samples on pH, conductivity, turbidity, and hardness.
These are the results we obtained.
![Experiments in the lab](https://github.com/sai-kul/Water-Quality/assets/164490846/e3068b50-bdf2-4733-9c5d-2d1f062ab625)
The hardness of water was measured in terms of the volume of EDTA required to change the color of the solution of wine red. The solution consisted of 50 mL of water sample, 3 mL of buffer solution, and 2-3 drops of indicator.
The conductivity of water was measured in units μS.
The turbidity of water was measured in units NTU.

Modeling:
We used 5 machine learning models - Logistic Regression, Decision Tree, Random Forest, KNN, and SVM.
The accuracy of these models is depicted in the table and bar graph.
![results](https://github.com/sai-kul/Water-Quality/assets/164490846/9594c029-7495-42c6-b58a-099f245ba6dd)
![results graph](https://github.com/sai-kul/Water-Quality/assets/164490846/e4259cd7-544e-4183-bccd-3a8ec2c9f602)

Conclusion:
We have tested our models on a very small dataset of about 3300 data points so there is scope to improve our models.
We can also use deep learning methods and neural networks to see improved performance in our models. Also, we have predicted the potability of water using only 9 parameters but we should also try to incorporate more parameters to get more accurate real-time results.
