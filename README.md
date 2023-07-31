# BaroneREU2023
The following information is used for the summer 2023 REU research project at Michigan Technological University(MTU). All data was gathered by MTU affiliates and should be recognized accordingly. The PIs on this project are: Amy Marcarelli, Evan Kane, Steve Techtman, and Laura Brown. The undergraduate researcher is Stelle Barone <sbarone@mtu.edu> with partnership with many graduate students who helped with the Dissolved Organic Matter project. 

Labeled Properties:
Site: There were two sites used for field collection, both in and near the Pilgrim River in Houghton Michigan, 49931. Site one was located at (47.1016884, -88.5165550) with site two at (47.084059, -88.550323). 
Plots: There were three plots listed as 1 through 3 or “Terrestrial” in the data frame where collection occurred near the Pilgrim rove in the riparian zone. Similarly, plots 4 through 6  or “Aquatic” represent the plots collected in the Pilgrim River. Plot 4 is the same as “left edge”, plot 5 is equal to “center”, and plot 6 matches “right edge” indicating where the samples were collected relative to the center of the Pilgrim River at that site. **Note that Terrestrial plots may be labeled as 1 while Aquatic are labeled as 0. 
Additionally, Site 0, Plot 0 represents data collected at a different time and used as constants.
Date: The date was always collected in month-day-year format or just the year. 
Plot Code: This is an identified that combines the site, plot, and date(day) in one number. Site one, plot one, on 06-09-2023 would be 119. 
Insect Code: This is a unique identifier for collected insects that is the Plot Code plus the numbered insects for that plot code section. For example, the third insects collected at site one, plot one, on 06-09-2023 would be 11903. 

CSVs:
Water Temperature: The water temperature was collected each day the macro-invertebrates were collected from the Pilgrim River. The site, plot, date of collection, and degrees in Celsius and Fahrenheit were reported. 

TresIns: This is the data for all of the invertebrates collected from the pitfall traps in the Pilgrim River riparian zones. This includes: site, plot, date of collection, plot code, insect code, and insect/invertebrate order. 

AquaInv: This is the data for all of the invertebrates collected from the D-nets in the Pilgrim River. This includes: site, date of collection, replication number, sampling location in the river, insect code, insect common name, stage of invertebrate, insect/invertebrate order. 

Insects: This data shows all of the invertebrate orders collected and their relative abundance per site and plot type. 

DTDataSmall: This is a smaller subset of the Insects data with “Type” representing the plot type(Terrestrial and Aquatic) and the five orders, Araneae, Coleoptera, Cyclopoida, Diptera, and Ephemeroptera. 
