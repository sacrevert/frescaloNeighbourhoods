# frescaloNeighbourhoods
Various neighbourhoods for the Frescalo algorithm (https://besjournals.onlinelibrary.wiley.com/doi/abs/10.1111/j.2041-210X.2011.00146.x)

British neighbourhoods were created using the UKCEH Land Cover Map 2020 (10 m resolution), combined with information on calcareous bedrock and peaty
soils. Irish neighbourhoods were created using the Corine Land Cover Map 2018 (100 m resolution), combined with information on calcareous bedrock and peaty
soils. Site-to-site environmental similarity matrices were calculated using the cosine approach. The only exception is the file `britishFresWeights_Feb2022_SPARTA.rdata` which was created using the Land Cover Map 2020 alone, using a Euclidean distance measure rather then the cosine approach, for comparison with the weights provided with the sparta implementation of Frescalo (see https://github.com/BiologicalRecordsCentre/sparta); the site coordinates for this file are those contained in the British zipfile download.

Files can be visualised here: https://olipes.shinyapps.io/visualiseFresNeighbours, with the code for the RShiny app visualisations here: https://github.com/sacrevert/visualiseFresNeighbours. A comparison, for Britain, of two different approaches to neighbourhood construction can be found here: https://github.com/sacrevert/frescaloNeighbourhoods/blob/main/spartaWeightsComparison.pdf

## Update 2022/03/30
The Oxon file is a weights file for the Watsonian county of Oxfordshire, created at the 2 km rather than 10 km resolution for more local analyses. This used the UKCEH Land Cover Map 2020 (25 m resolution), combined with information on calcareous bedrock only.

## Update 2022/06/29
The IDF file is a weights file for the Ile-de-France region of France (including Paris), created at the commune level. Current similarity measures are based on the  Corine Land Cover Map 2018 (100 m resolution) and distance only. Note also that this version contains neighbourhoods of 50 communes.

## Update 2024/07/15
The Wilts and Leics files are weights file for the Watsonian counties of Leicestershire and South + North Wiltshire combined, both created at the 2 km rather than 10 km resolution for more local analyses. These used the UKCEH Land Cover Map 2020 (25 m resolution), combined with information on calcareous bedrock only.

## More info
Please contact Dr Oli Pescott (https://www.ceh.ac.uk/staff/oliver-pescott) for more information.
