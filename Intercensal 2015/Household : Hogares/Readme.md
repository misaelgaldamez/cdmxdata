# Data File Description

This datafile is a summary of the 2015 Intercensal Survey, aggregated at the borough level by *household*. Each statistic represents the characteristics of the average *household* in the respective borough.

The microdata is harmonized and cleaned by the Minnesota Population Center via IPUMS International and I have uploaded here my processed files. For most indicators, I first created binary variables based on the original IPUMS dataset (for instance, coding 0 for a household if it had less than 2.5 persons per room, and 1 if it had more). From these binary variables, I summarized the dataset and created borough-level indicators using the household survey weights provided by IPUMS.

Reference: *Minnesota Population Center. (2018). Integrated Public Use Microdata Series: International (Version 7.1 [Mexico 2015 data via National Institute of Statistics, Geography, and Informatics.]).*


# Variable Definitions

**mun2**: Unique identifier for each borough, composed of the state ID and the municipal ID.

**country**: IPUMS country code for Mexico (484).

**state**: INEGI's identification code for Mexico City (9).

**borough**: INEGI's identification code for the boroughs within Mexico City.

**name**: The name of the borough (delegación) within Mexico City.

**hh**: The total number of households within the borough.

**persons**: The average number of persons per household within the borough.

**crowd**: The percentage of households in the borough that are overcrowded, defined as having greater than 2.5 persons per room (not including hallways or the bathroom).

**medhhinc**: Median Household Income for the borough, defined as the sum of the wages for a household (2015 Pesos).

**nofloor**: The percentage of households in the borough whose dwelling lacks a finished, covered floor. 

**noroof**: The percentage of households in the borough whose dwelling lacks a finished roof of a superior quality (per CONEVAL's definition).

**nowalls**: The percentage of households in the borough whose dewlling lacks walls or whose walls are built of unacceptable material (see CONEVAL's definition).

**nchild**: The average number of children per household in the borough.

**cell**: The percentage of households with access to a cellular phone.

**internet**: The percentage of households with internet access.


