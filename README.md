# conjoint_mds_ch1
Python Code w small data from Mkt Dt Science book -- conjoint analysis

Data source is from Marketing Data Science Thomas Miller
Data is stored on .csv file - describes rank of preference of various attributes on CellPhone
Using statistics package statsmodel.api

Based on https://github.com/mtpa/mds/blob/master/MDS_Chapter_1

Walkthrough: Read data
Use regression model to run -- auto convert categorical variable using pansy contrast. Sum

After regression estimate is generated
Run and create different contrast values of importance

Another model is examined for interaction based on chapter suggestion
