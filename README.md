# Adaline
ML Adaline SGD and Perceptron 

## Dataset Info
This is a dataset that consists of various features of stars. Some of the pertinent ones are:
* Absolute Temperature (in K)
* Relative Luminosity (L/L_o)
* Absolute Magnitude (M_v)
* Spectral Class (O,B,A,F,G,K,,M)
* Star Type *(Red Dwarf, Brown Dwarf, White Dwarf, Main Sequence , SuperGiants, HyperGiants)*

Constant(s):
* L_o = 3.828 x 10^26 Watts (Avg Luminosity of Sun)

#### Source
Data from: Abundances in dwarfs, subgiants, and giants (da Silva+, 2015) (https://astronexus.com/hyg)
* Github rep link: https://github.com/astronexus/HYG-Database/blob/master/hygdata_v3.csv
- Output format specified: 



-- output format : csv
SELECT "J/A+A/580/A24/stars".Name,  "J/A+A/580/A24/stars".Class,  "J/A+A/580/A24/stars".SpType,  "J/A+A/580/A24/stars".Vbroad,  "J/A+A/580/A24/stars".Teff,  "J/A+A/580/A24/stars"."B-V",  "J/A+A/580/A24/stars".VMag,  "J/A+A/580/A24/stars".logL
FROM "J/A+A/580/A24/stars"

## Purpose
The purpose in studying this dataset is to classify stars in the celestial space based on the Hertzsprung-Russell (HR) Diagram by plotting their features on that graph. We do this by training a Perceptron model and an Adaline model to classify between Giant vs Dwarf stars based on luminosity and surface temperature data. 

We will compare the performance of the different models in classification of stars. This can be an important task because of the different properties, compositions, behaviors, etc. of different classes of stars. This has effects on their motion, reactions (chemical, nuclear, etc.), interactions with space and bodies around them, etc. Our very understanding of the universe can be based on our studies of the different spectral bodies. 
