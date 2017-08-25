# Titanic Data Visualization


## Summary
This project involves visualization of Titanic survival using passenegers data such as class, gender and age group. Created total three graphs:

1. Titanic survival by class: First class passengers have the highest survival rate among all the different classes.
2. Titanic survival by age group: The Children belonging to the age group 0-15 have the highest survival rate.
3. Titanic survival by class and gender: The First class female have maximum survival rate and the third class male have minimum survival rate.

## Installation

Clone the GitHub repository and install the dependencies.
* Download [Python](https://www.python.org/downloads/)
```
git clone https://github.com/AizazSharif/P6-DAND-Make-Effective-Data_Visualization-Using-D3js.git
cd P6-DAND-Make-Effective-Data_Visualization-Using-D3js
```

* Then run **python3 -m http.server** to start the local web server on localhost.

## Design
* Chart type: As the dataset contains passsengers information in different categories, a bar charts is the best way to see trends of the titanic survival.
* Layout: Since only two survivorship status exist so stacked bar chart layout is best suited to visualize the data.
* Legend: Data are represented in the ratios, the stacked bar chart of y-axis are same for all the categories so, legend are moved to the right hand side of the chart.
* Visual encodings: X-axis represents different categories of an information and y-axis represents ratio of passengers. Sequential colors are used to differentiate between 'survived' and 'perished'. Shape of the stacked bar chart is rectangle. 

## Feedback
### 1 [by my friend (Software Enginner)]
There is no mouseover interaction over visualizations and it gives less user interaction. 

So I tried to add mouseover hover on bars of stacked bar charts to show the ratio of survived and perished.

### 2 [by my friend (MSCS Student)]
Change the Legend of Chart No. 2 from Died to Perished like rest of the charts.

So I changed it accordingly.

### 3 [by my elder sister (MSEE Graduate)]
The combination of colors in first chart does not look good. Try some other combination where in green or any range.

So I tried different colors to finalize the final color range.

### Resources


* [d3 documentation's](https://github.com/d3/d3/blob/master/API.md)
* [DashingD3js](https://www.dashingd3js.com/table-of-contents)
* [Color Brewer](http://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3)

