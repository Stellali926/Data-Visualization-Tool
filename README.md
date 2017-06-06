# Project Discription
Read the subscription data of a particular magzines of all countries from 1960 to 2014. Use a GUI interface allowing user to select the country of data they want to display, observe and compare subscription numbers of different countries.

## Demo Screenshots
<img width="300" alt="screen shot 2017-06-06 at 10 13 43 am" src="https://user-images.githubusercontent.com/19808690/26842308-333ef884-4aa1-11e7-9f1e-73f39c640313.png">
<img width="600" alt="screen shot 2017-06-06 at 10 14 17 am" src="https://user-images.githubusercontent.com/19808690/26842564-1dcd531e-4aa2-11e7-8b2e-ad3e8831138a.png">

## File Description
### src/
- CSVReader.java - Read data from the "resources/cellular.csv" file, and get name of country, number of years, year labels etc and return values.
- SubscriptionYear.java - One object of class stores single year and subscriptions of a country.
- Country.java - One object of class stores representations of a country, and get name of country and calculate subscriptions in a period for a country.
- Node.java - One object of class stores the node of a object.
- LinkedList.java - One object of class stores the list of objects, and add, search and insert node in the list.
- GraphView.java  - One object of class stores the graph view of Country list, and generate graph panel and map the cellular data of country to the panel.
- ColoredPoint.java - One object of class stores the color of one point in the graph.
- LegendPanel.java - One object of class represents the panel to show the visual guide to the graphed countries, and generate legend panel and color and label matching the plots on GraphView panel.
- MouseHoverOverCountry.java - Construct a MouseHoverOverCountry class which implements MouseMotionListener
- MouseHoverOverData.java - Construct a MouseHoverOverData class that implements mouseMotionListener
- MouseClickCountry.java - Construct a MouseClickCountry class which implements MouseListener
- MouseClickCountryForFirstFrame.java - Construct a MouseClickCountryForFirstFrame class which implements MouseListener
- ShowCountryPanelForFirstFrame.java - One object of class represents the panel to show the list of all countries
- SelectedCountryPanelForFirstFrame.java - One object of class represents the panel to show the selected countries
- TestSelectedCountryandGraphView.java - Test the GraphView class.


### resources/
- cellular.csv - A CSV (Comma Separated Value) file.
       _First row contains the year of cellular data for each country.
       _First column contains the name of each country.
       _Lines 2 to EOF (end of file) contain cellular data for each country.
- cellular_short_oneDecade.csv - A file containing cellular data of three countries for one decade.
- resources/RUN1(a).jpg, RUN1(b).jpg, RUN2.jpg - pictures showing first Frame for selecting countries and second Frame for showing

### README.txt
description of submitted files
