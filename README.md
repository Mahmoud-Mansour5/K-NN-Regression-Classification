           <<<<<Problem Statement 1 (Classification)>>>>
Given the MAGIC gamma telescope dataset. This dataset is generated to simulate registration of high
energy gamma particles in a ground-based atmospheric Cherenkov gamma telescope using the imaging
technique. The dataset consists of two classes: gammas (signal) and hadrons (background). There are
12332 gamma events and 6688 hadron events.
You are required to do the following:
1. the dataset is class imbalanced. To balance the dataset, randomly put aside the extra readings
for the gamma “g” class to make both classes equal in size.
2. Split your dataset randomly so that the training set would form 70% of the validation set 15%
and 15% for the testing set (Don’t use it while tunning the model parameters).
3. Apply K-NN Classifier to the data.
4. Apply different k values to get the best results.
5. Report all of your trained model accuracy, precision, recall and f-score as well as confusion
matrix.
6. Add your comments on the results and compare between the models.
--------------------------------------------------------------------------------------------------------------------
            <<<<<<<<Problem Statement 2 (Regression)>>>>>>>>>>
Given California Houses prices data. This data contains information from the 1990 California census., it
does provide an accessible introductory dataset the basics of regression models.
The data pertainsto the houses found in each California district and some summary stats about them
based on the 1990 census data. The columns are as follows; their names are self-explanatory:
 Median House Value: Median house value for households within a block (measured in USDollars) [$]
 Median Income: Median income for households within a block of houses (measured in tens of thousands of US Dollars) [10k$]
 Median Age: Median age of a house within a block; a lower number is a newer building [years]
 Total Rooms: Total number of rooms within a block
 Total Bedrooms: Total number of bedrooms within a block
 Population: Total number of people residing within a block
 Households: Total number of households, a group of people residing within a home unit, for a block
 Latitude: A measure of how far north a house is; a higher value is farther north [°]
 Longitude: A measure of how far west a house is; a higher value is farther west [°]
 Distance to coast: Distance to the nearest coast point [m]
 Distance to Los Angeles: Distance to the center of Los Angeles [m]
 Distance to San Diego: Distance to the center of San Diego [m]
 Distance to San Jose: Distance to the center of San Jose [m]
 Distance to San Francisco: Distance to the center of San Francisco [m]
