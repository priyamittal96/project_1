# project_1

Technologies Used
Jupyter Notebook 



Data Analysis





Data Clean Up Exploration 

Data clean up was a fairly standard process. There was a lot to go through as some of the datasets we used were very large. We removed nulls and duplicates from our data. We also joined various dataset such as farmers market and census data on specifc critera, which was tricky at times, because it was difficult to determine what values were missing after the merge. Additionally, there were some difficulties in the conversions of variousvariables. For example, in the recipe data, nutritional information was categorized as an object rather as an integer and we had to get creative to convert the information. A split function and for loop was utilized to grab the caloric value within the object. The process of creating main and sub-categories also utilzed a similar concept where the split function was used to grab the first work of the ingredient - which was then used to create the main category. 