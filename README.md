# Oil Well Location
The purpose of this project is to find the best place for a new well for a company. We have data for three different regions, and based on that we will build a model for predicting the volume of reserves in the new wells. The region with the highest estimated values and highest total profit and lowest risk of loss will be selected.

## To Run

1) Clone the project
```
git clone https://github.com/filzamazahir/OilWellLocation.git
```
Make sure to have pip installed, then do 
```
pip install -r requirements.txt
```
Run ```oilwelllocation_bootstrapping.ipynb```


## Results 
We analyzed data given for the three regions based on volume of well reserves and profits each region would generate. Based on that, Region 1 is picked as the most suitable location as it yielded in the highest average profit of $4,445,759 with lowest risk of loss at 1.5%, and also high values within a 95% confidence interval.
