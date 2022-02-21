# Web_App_ETF_Analyzer

Application developed to analyze Electronic Traded Funds. 

This program runs a **Python** application within Jupyter Lab to perform 
financial planning analysis for the evaluation of a ETF portfolio. 

Line and Bar Plots are created to visualize the information for better understanding and decision making.
When working in jupyter lab, 

---

## Technologies

This application is developed on the **Python** *3.7.11 version*. It incorportates the following required 3 dependancies to run:

1. **import pandas as pd**
2. **import numpy as np**
3. **import hvplot.pandas**
4. **import sqlalchemy**

---

## Installation Guide

The following installation must be performed before running the program. It include:


**Installations:**

SQLALchemy
```conda install -c SQLALchemy```

Voila
```conda instal -c Conda-forge voila```

---

## Usage

To run this application, create a clone on the local desktop. Then, initiate your conda environment and 
open ```jupyter lab ```. 

Steps for running application:

*Import required dependencies and library*

*Read CSV files into DataFrame*

Then produce 4 visuals to interpret data and information. They are:

**1st. Calculate and Bar Plot the Housing Units per Year**

    * groupby function utilized to aggregate housing units yearly averages
    
<img width="712" alt="Housing Units Bar Plot" src="https://user-images.githubusercontent.com/93550651/153762181-0786c334-2018-49f4-b6e1-e1db0771ca20.png">


**2nd. Calculate and Line Plot the Average Sale Prices per Square Foot**

    * grouby function utilized to aggregate year averages

<img width="786" alt="Line Bar Price and Rent" src="https://user-images.githubusercontent.com/93550651/153762303-fb507198-5685-4598-8b3e-0238616f4192.png">


**3rd. Line Plot and compare the Average Sale Prices by Neighborhood**
    
    * grouby function utilized to aggregate Neighborhood yearly averages
    
<img width="994" alt="Line Bar by Neighborhood" src="https://user-images.githubusercontent.com/93550651/153762315-a8241d33-2cb6-413a-81ec-cce5500842d8.png">

    
**4th. Build an Interactive Neighborhood Map**

    * Utilize hvPlot with GeoViews enabled to create points for map

<img width="900" alt="Interactive Map" src="https://user-images.githubusercontent.com/93550651/153762345-e68075be-dee8-4ee2-afb7-1bc580dfcb4b.png">

The images above illustrates the results.

In conclusion: Data Story composed.

## Contributors

Contributor: John Batarse  

Email: jbatarse@hotmail.com

LinkedIn: [Find me on LinkedIn](<https://www.linkedin.com/in/john-a-batarse-760a26116/>)


## License
