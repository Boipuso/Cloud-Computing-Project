# Cloud-Computing-Project
This repository provides my project for the 8th Eagle gen cloud computing course in GEE. 

Backround: 
Borneos rainforests are amongst the most damaged and diminished rainforests in the world. In recent decades, efforts were made by several environmental organizations to preserve and restore these valuable forests. 
The Borneo Nature Foundations currently conducts a long-term project studying reforestation in some of the most damaged rainforests of Borneo. They introduced study sites in selected areas in the Sebangau Nationalpark were they have planted well over 250.000 trees with the goal to identify the best tree species to reastablishe healthy forests. In order to inspect the effectiveness of these measures, regular forest monitoring is mandatory.
More information at https://www.borneonaturefoundation.org/project/reforestation/ 

The Project:
The project aims to map deforestation and afforestation using a random forest classification in the Sebangau Nationalpark, Kalimantan, Borneo from 2015 - 2023 and to inspect accuracy differences when adding indices- and SAR data to the optical bands. 

Landsat 8 scenes were processed for optical information and used to compute ndvi and ndwi indices, while Sentinel 2 scenes were deployed for radar (VV/VH) information. 
The random forest function created allows´s to loop over different sets of bands serving as input for the classification and thus, allows to inspect changes in the implemented accuracy assessment in order to find the most suitable set of bands for the classification.  
The resulting landcover(-change) maps are complemented with a legend, a calculation of the area of the respective landcover classes in sqkm and a yearly timeline of the mean ndvi value of the area for the years 2015 to 2023. 

The code can easily be modified to inspect different areas, sets of bands or years of interest. 

This link directs you to the project in GEE: [https://code.earthengine.google.com/c3616795d895adfc943a289261ae00f0](https://code.earthengine.google.com/d62b6283a9d43c6f6f8b9cf04dfd977f)
