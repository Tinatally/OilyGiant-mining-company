# OilyGiant-mining-company
About the project: Your task is to find the best place for a new well. 
- Collect the oil well parameters in the selected region: oil quality and volume of reserves;
- Build a model for predicting the volume of reserves in the new wells;
- Pick the oil wells with the highest estimated values;
- Pick the region with the highest total profit for the selected oil wells.
Build a model that will help to pick the region with the highest profit margin. Analyze potential profit and risks using the Bootstrapping technique.

Summary result: We built a model that would predict the volume of reserves in new wells at oilyGiant mining company by; first splitting data into train and test samples. we also calculated the RMSE score of the model using Linear regression and calculate the profit of each well and it's average profit. Using the bootstrap technique with 1000 samples to find the distribution of profit we Calculated the average profit at 95% confidence interval and risk of losses. Region 2 had the highest risk of loss of 8.70% whiles Region 1 had the optimal confidence interval among the three regions.
