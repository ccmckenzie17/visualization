
My fist visualization is an interactive map showing how many waterfowl birds have been observed on different beaches in Toronto by city employees. The data spans from 2008 to Sept 2025 and is collected from mid May to mid September each year.

Data was taken from the City of Toronto open data catalogue
https://open.toronto.ca/dataset/toronto-beaches-observations/

> What software did you use to create your data visualization?

Python

> Who is your intended audience? 

This map visualization could be for urban ecologists studying birds in Toronto and potentially using them as a climate indicator. Although to be really useful for this purpose the visualization would need a time scale component.

This map could also be useful for people who like beaches but don't like birds and would prefer a beach with as few birds as possible.
    
> What information or message are you trying to convey with your visualization? 

The location of different Toronto beaches and the number of waterfowl each beach gets.
    
> What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 

I wanted to visualization to be easy to look at and understand while also being fun and informative. At first I just made a simple bar chart of the waterfowl counts by beach but I didn't even know where several of the beaches included were so I though a map based visual would be more informative. I also wanted a visual representation of how many waterfowl the beaches had that was instantly understandable. So instead of just a simple point with a number I made the points scale so that beaches with more waterfowl had larger points and different colours. 
    
> How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

With Python it is easy to ensure reproducibility. The code can be copied and run by anyone and it will produce the same result. I also added comments to the code so that it is easier to read, understand, and modify.
    
> How did you ensure that your data visualization is accessible?  

I did several things to make the visualization more accessible. First, the default map background was overly complicated and didn't contrast wel with the data points so I switched to a simple background with better contrast. I also made the data points scale by size as well as colour so that colourbilnd individuals would still have a visual representation of the data. The title and the interactive text should also work with a text screen reader.
    
> Who are the individuals and communities who might be impacted by your visualization?  

This map could potentially affect residents who live near the beaches as low-waterfowl beaches might get too popular and high-waterfowl beaches might lose tourism revenue. 

However this map could also benefit beach lovers who have bird phobias. 
    
> How did you choose which features of your chosen dataset to include or exclude from your visualization? 

This data set includes several different variables which describe the wind, water conditions, and precipitation. However, for this visualiztion the focus was on waterfowl and other information could make the visual unnecessarily complicated. 
    
> What ‘underwater labour’ contributed to your final data visualization product?

This visualization is only possible due to the work of many city employees over almost 20 years. They easily could have decided to not collect this data or to not post it publicly but there work made this project possible. In addition, several packages (like folium and cartopy) were used for this project which were created and shared for free by their developers. 