# CellProliferationExtraction

This project is written in MATLAB (Version: 9.9.0.1467703 (R2020b)) in conjunction with the Image Processing Toolbox (Version 11.2 (R2020b)), and is open source.  Biological images used in the code were provided by Dr. Theresa Casey at the Department of Animal Sciences, Purdue University and fellow colleagues Dr. Ariany Suarez-Trujillo and Kelsey Teeple. This project was carried out under the mentorship of Dr. Uduak George at San Diego State University. This work was supported by a PUMP research grant (NSF grant No. DMS-1916494). 

### Project Information
- Authors: Brooke Tyler & Sashiel Vagus
- Purpose: To assist in the automation of determining the ratio of proliferating to nonproliferating cells within a given tissue.  The orignal purpose of the project was to determine this ratio in gilt uterus tissue samples, with respect to different tissue types.  For this reason, a separate image segmentation code was created to split the original image by these classifications utilizing hand drawn ROIs to create new images of each isolated portion that were later run in the tissue area masking portion of the code. Dependent upon the needs of the user, the two codes may be run separately, or in conjunction with one another. Lastly, an excel file containing the order of the areas is populated by the tissue area masking code.     
