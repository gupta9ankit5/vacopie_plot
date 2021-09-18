# vacopie_plot

A utility function that can be used to analyze the variance and covariances of multiple featured data at once and can be used as an alternative to pair plot.

This plot shows the variances and co-variance both normalized, in the form of a 2-layer pie chart. The inner pie chart is plot of variances (normalized) of each feature while each sector of inner pie chart contains on outer layer pie chart, the normalized co-variance of rest of the features with respect to the feature of the corresponding sector.

The inner pie chart therefore, gives an idea about the feature wise information content while the outer layer tells about the feature interactions in a highly simplistic and comparative manner since the very values of variances and co-variance are not the actual but normalized ones. These plots are generated using the matplotlib library in python.

function is named <b>vacopie()</b>: It accepts data in the form of a pandas dataframe.


<h3>Results</h3>

![image](https://user-images.githubusercontent.com/31762475/133897650-24b615ef-a70a-4b53-bd48-73859371b4d4.png)
<br><br>

![image](https://user-images.githubusercontent.com/31762475/133897659-424a0f72-7b16-49f0-b53d-47d005e0e9dc.png)

