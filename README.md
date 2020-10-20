Four conclusions I made about the dataset:

1. The restaurants locations are scattered and there are no evident clusters. However, we can still use K-Means to group them together. For more details, please view the 
``Location Clustering`` notebook.
2. By using Elastic Net Regression and taking the log of ``Votes`` and ``Reviews``, I have managed to predict the ``Cook_Time`` with a Mean Absolute Error of about 8 minutes.
For more details, please view the notebook ``Cook Time Prediction``. 
    * I have also found out that restaurants that serve only Fast Food are quicker in preparing their meals than ones that don't by nearly five minutes but this effect should not be 
    considered significant.  
3. I have managed to find out a scoring algorithm that takes into account both the ``Rating`` and the number of ``Votes``. For the detailed algorithm, please view the 
``Restaurant Scoring`` notebook.
4. An interesting fact is that coffee is mostly served with Fast Food, other beverages, and Italian food. This conclusion is reached by examining the ``Cuisines`` column. 
You can try doing the same thing with other cuisine, too. For the details, please view the ``EDA`` (Exploratory Data Analysis) notebook. 
There are also other comments I made in this notebook.

For a better view of the notebook, please visit this link: https://nbviewer.jupyter.org/github/dcaohuu18/Xtern_20_DS/tree/master/.
