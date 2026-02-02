My Second visualization uses the same data set to show how waterfowl number change on each Toronto beach overtime and and overall average. 

Data was taken from the City of Toronto open data catalogue
https://open.toronto.ca/dataset/toronto-beaches-observations/

> What software did you use to create your data visualization?

R

> Who is your intended audience? 

Like before, this visualization could also be used by both ecologists and beach goers. However this visualization is likely more useful from an ecological perspective as you can see changes over time. This may be less usful for planning which beach you would like to visit however because you need to know where each beach is and there is fairly high year to year variation.
    
> What information or message are you trying to convey with your visualization? 

This visualization is intended to show how waterfowl observations change across time on Toronto beaches both individually and overall. I came into this without a bias and was not intentially trying to convey any message in particiular. However, it does appear that observations have gone down overtime. There is no difference among beaches.
    
> What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 

When creating this visualization I wanted to show the data in a clear and honest way. I had to consider how to have many lines displayed without it looking too overcomplicated. Therefore, each line has its own distinct colour and the average line is noticably different from the others. I also kept the background to a minimalist design that makes it easy to compare data to the axes. I also added small data points for each line the shows where the value for that year is.
    
> How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

Since this visualization was made in the R programing language the code is early reproducible. I have also added comments for clarity.
    
> How did you ensure that your data visualization is accessible?  

To ensure accessibility I chose a high contrast background and labelled the plot clearly. Also, I used the R viridis package which provides colourblind friendly color pallates so that the most people posibile will be able to tell apart the different lines for each beach. 
    
> Who are the individuals and communities who might be impacted by your visualization?  

Like before this visualization could also potentially impact communities living nearby Toronto beaches. 
    
> How did you choose which features of your chosen dataset to include or exclude from your visualization? 

This visualization also focused on the data for waterfowl observations and excludes data on wind, water, and precipitation data. While the map in visualization 1 includes spatial infromation, this visualization instead presents temporal data to give a different view of the same data set.
    
> What ‘underwater labour’ contributed to your final data visualization product?

Like before, this visualization was supported by the city of Toronto workers who collected and processed this data as well as the creators of the packages used like viridis