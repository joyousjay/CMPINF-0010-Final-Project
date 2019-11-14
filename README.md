# CMPINF-0010-Final-Project
Team Name: Panthers Central
## The Best Neighborhood Project
Metric: The higher amount of crimes committed (rape crime + murder crime) and SECOND DATASET METRIC would result in a higher living assistance needed from the city and vice versa. The best neighborhood would require the least amount of living assistance 

Link to Dataset 1: https://data.wprdc.org/dataset/a-community-profile-of-pittsburgh-neighborhoods-1974/resource/8ce92a4b-fa62-45c3-8cee-cc58fefede75
Link to Dataset 2: https://data.wprdc.org/dataset/fire-incidents-in-city-of-pittsburgh/resource/8d76ac6b-5ae8-4428-82a4-043130d17b02/view/ac72829e-0dba-4997-8dc6-0503b7dc6487#

import pandas as pd
pgh_arrests=pd.read_csv("https://data.wprdc.org/dataset/bce15079-618a-4bf3-badf-8aa372c3aea2/resource/8ce92a4b-fa62-45c3-8cee-cc58fefede75/download/arrests-for-major-crimes-1972.csv")
pgh_arrests.head(70)
