---
title: "Spatial Autocorrelation"
header:
  teaser: /assets/images/Persona3.PNG
---
Spatial autocorrelation is a concept that refers to the degree to which the values of a variable are correlated in space. In other words, it examines whether nearby locations tend to have similar values for a particular variable. It is an essential concept in understanding spatial patterns and dependencies in data. Understanding spatial autocorrelation is crucial for making informed decisions in spatial analysis and modeling, as it provides insights into the underlying spatial structure of data and helps to identify spatial dependencies that may affect statistical inference and modeling assumptions.

For testing spatial autocorrelation, there are statistical methods used to assess whether spatial patterns in a dataset are significantly different from what would be expected. These tests help researchers determine whether there is evidence of spatial dependence or clustering in the data. One of these tests for spatial autocorrelation is Moran's I.

## Moran's I test

Moran's I is a global measure of spatial autocorrelation that quantifies the degree of similarity between neighboring observations in a dataset. There different types of this test, one of them is the Moran's bivariate. This spatial test is an extension of Moran's I that allows for the analysis of spatial relationships between two different variables simultaneously. It measures the degree of association between the values of two variables across spatial units, considering both the values of each variable and their spatial locations.

# A study case

In order to make an example of this test, I simulated a database of socioeconomic status and the amount of homicides in Bogotá focusing in Teusaquillo town. For more information regarding the commands used, please feel free to email me on <a href="mailto:p.valcarcel@uniandes.edu.co">p.valcarcel@uniandes.edu.co</a>.

<div>
<p style = 'text-align:center;'>
<img src="/assets/Maps/Moran_Bivariado.PNG" alt="JuveYell" width="300px">
</div>
