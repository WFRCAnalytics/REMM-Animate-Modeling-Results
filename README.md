# REMM-Animate-Modeling-Results
Process modeling results and animate as a gif file

Requirements:
- base year parcel geometry with parcel_id_REMM attribute
- default feature classes for symbolization
- progression metrics output from REMM in folder called "Progression_Metrics"


Improvements:
- handle base year, then modeled base year
- improve default layer organization, particularly for parcels
- add indicators
- improve labels symbologies
- improve model output structure
  - separate by county
  - separate gifs by reporting area
- use join in arcpy rather than pandas to speed up parcel level processing
