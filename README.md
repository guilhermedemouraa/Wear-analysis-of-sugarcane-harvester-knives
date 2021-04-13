# Wear analysis of sugarcane harvester knives
This repository contains code in both python (jupyter) and Matlab to process digital images of sugarcane harvesters' knives and extract geometric features that allow wear quantification, such as knife's area, perimeter, rectangularity, and percentage of area lost due to operation. If you're interested in getting to know more about this project, please search:
De Moura Araújo, G., dos Santos, F.F.L., de Almeida, S.L.H. et al. Sugarcane Harvesting Quality by Digital Image Processing. Sugar Tech 23, 209–218 (2021). https://doi.org/10.1007/s12355-020-00867-2

### Background:
Sugarcane, a major crop in the Brazilian agribusiness sector, has had significant changes in its cultivation over the years. The harvest of sugarcane was usually carried out
manually. However, due to the great demand for labors and high health hazards, manual harvesting was replaced by a mechanized process. Harvesters have a basal cutting mechanism
composed of blades that are responsible for cutting the sugarcane (Fig. 1). 

![Picture1](https://user-images.githubusercontent.com/39603677/114586618-ba717a00-9c39-11eb-8252-48d1f0986765.jpg)

Fig. 1 - Basal cutting mechanism of a sugarcane harvester

The blades must be continuously analysed and replaced if necessary, otherwise, dull blades (Fig. 2) can lead to greater collapse of the sugarcane stems, which favours the incidence of pests and diseases, entails the destruction or mechanical removal of the stalks, and harms the regrowth of the sugarcane for the next season (Fig. 3). 

![example of wear](https://user-images.githubusercontent.com/39603677/114476808-ce709980-9baf-11eb-9a14-b04e339baa9c.JPG)

Fig. 2 - Example of wear in the knives of a sugarcane harvester

![Picture2](https://user-images.githubusercontent.com/39603677/114586621-bb0a1080-9c39-11eb-8b61-791cd77bb768.jpg)

Fig. 3 - Sugarcane stalks damaged by worn basal cutting mechanism. Source: Xie et al. (2019)

The analysis of these blades is performed qualitatively, in which the operator analyses the current conditions of the blades (based on prior experiences); or quantitatively, using a digital calliper to measure the thickness of the blade, wherein the increase in thickness indicates greater wear. Both approaches require the harvester to be stationary and are extremely time-consuming. In order to obtain more efficient results, the present study proposes a novel method to analyse blade wear and harvesting quality through the use of digital image processing. The change in geometric characteristics (area, perimeter, rectangularity, and length) of the blades over time were evaluated along with blade wear and harvesting quality indices (damage index to stalks). The obtained results indicated that the proposed methodology was effective at assessing the quality of the harvesting operation of sugarcane and the wear in the mechanisms of basal cutting present in sugarcane harvesters. The error in estimating the damage index ranged between 0.030 and 0.033 %.

### Code pipeline

![pipeline](https://user-images.githubusercontent.com/39603677/114476853-ea743b00-9baf-11eb-89af-3b7c5b8aff9c.JPG)
