# matplotlib_tutorial
Plotting the intensity of Australian wildfires using matplotlib

### Dataset
All tasks will work on the Australia Fire dataset:
https://www.kaggle.com/carlosparadis/fires-from-space-australia-and-new-zeland
We will work with fire_nrt_V1_96617.csv which is described here:
https://earthdata.nasa.gov/earth-observation-data/near-real-time/firms/viirs-i-band-active-firedata

### Task 1: Density Plots (50 points)
1.1 Plot the longitude vs latitude several ways within a single figure (each in its own axes):
1) Using the matplotlib defaults.
2) Adjusting alpha and marker size to compensate for overplotting.
3) Using a hexbin plot.
4) Subsampling the dataset.
For each but the first one, ensure that all the plotting area is used in a reasonable way and that
as much information as possible is conveyed; this is somewhat subjective and there is no one
right answer.
1.2 In what areas are most of the anomalies (measurements) located?


### Task 2: Visualizing class membership 
Visualize the distribution of Brightness temperature I-4 as a histogram (with appropriate
settings). We are certain of a fire if this value is saturated.   
2.1 Do a small multiples plot of whether the brightness is saturated, i.e. do one plot of lat vs
long for those points with brightness saturated and a separate for those who are not (within the
same figure on separate axes). You can pick any of the methods from 1.1 that you find most
suitable. Can you spot differences in the distributions?  

2.2 Plot both groups in the same axes with different colors. Try changing the order of plotting
the two classes (i.e. draw the saturated first then the non-saturated or the other way around).  
Make sure to include a legend. How does that impact the result?  

2.3 Can you find a better way to compare the two distributions? 
