# New-York-Solar-Resource-data

### **Context:**  

In this use case, we'll work with [Solar Resource Data](https://developer.nrel.gov/docs/solar/solar-resource-v1/) which returns various types of solar data for a location. The location here is the city of New York. We will use application programming interfaces (APIs) from a [Web service documentation](https://api.data.gov/docs/) to access and manipulate many federal agencies's datasets with information about the United States that covers several topics.  

### **Goal:** 

Our goal is to use APIs to extract the solar resource data for New York City in JSON format and convert it into a dataframe.   

**Note:** This code was written on RStudio.  
**Language:** R.  
**Packages:** httr, jsonlite, tibble, dplyr, ggplot2.  
