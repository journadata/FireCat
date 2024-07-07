# Analysing 30 years of forest fires in Catalonia

This is a repository about the webpage about the fires in Catalonia created by Beatriz Gálvez.



**Catalonia has only reforested the 3,76 % of the Surface lost in fires**
This project illustrates the stark contrast between the hectares burned due to fires in Catalonia over the past decades. My primary objective was to analyze the data from the last 30 years about wildfires in Catalonia. I sought to determine whether there was a tendency at some point, for example, in the number of fires or in the extension burned. Additionally, I aimed to present the results in a map. 

However, I was unable to provide a positive answer to this question. Instead, I observed a decrease in the number of large fires and the area burned. I then realized that the most severe episode of fires had occurred 30 years ago. I decided to prioritize data analysis to identify a compelling approach related to forest repopulation, using another dataset I had found related to this topic. Consequently, I decided to defer the maps for a second version and focus on another question: The question of whether Catalonia is replanting all the land that has been burned in the past decades is addressed in the title of the webpage.
The user will find an article about the surface burned during the past decades in Catalonia, along with information about whether the land has been replanted or not.

## Data analysis process

These first weeks of July mark the 30th anniversary of the worst fires that took place in Catalonia since records began. They were also the most tragic and fatal. Not only because of the number of fires that occurred, but also because of the large area that ended up burning. 

A detailed information of the data analysis is in each notebook, but in general terms: 

* The data has been retreived and downloaded in .csv from an official source: the Government of Catalonia. 
* The data had to be cleaned analised (sum, mean, concat, etc) using python and some libraries, such as pandas, requests,numpy, fill in...etc. In one of the datasets, I had to learn a new way to convert str to numbers, for example. 



## Data collection 

To obtain the data, I searched the open data page of the Generalitat de Catalunya. There, some information is published although they are in separate databases or have no relation. 

The databases consulted are the following: 

* [Forest fires by county in Catalonia. current year](https://analisi.transparenciacatalunya.cat/Medi-Rural-Pesca/Incendis-forestals-per-comarques-a-Catalunya-Any-e/9r29-e8ha/about_data)
* [Forest fires by county in Catalonia. previous year](https://analisi.transparenciacatalunya.cat/ca/Medi-Rural-Pesca/Incendis-forestals-per-comarques-a-Catalunya-Any-a/crs7-idxi/about_data)
* [Forest fires in Catalonia. Years 2011-2023](https://analisi.transparenciacatalunya.cat/Medi-Rural-Pesca/Incendis-forestals-a-Catalunya-Anys-2011-2023/bks7-dkfd/about_data)

Extra: 
* [Fires by start time (1995-2023)](https://agricultura.gencat.cat/web/.content/06-medi-natural/incendis-forestals/enllacos-documents/estadistiques/fitxers-binaris/incendis-forestals-hora-inici-1995-2023.xlsx)

### Overview of the data analysis process

I have been able to apply all the Python knowledge acquired during the first month of the course. This has included using the command line to access the Jupyter Notebooks, carrying out simple calculations on datasets using Python, and applying more complex functions such as concatenation and combining datasets with Pandas.
Additionally, I have created maps using the DataWrapper tool, which I had already been using, but I have also learned how to utilise different tools such as the highlights and annotations. 

The course also included instruction on how to use Markdown for Jupyter notebooks and for creating the .md file. Additionally, I have learned how to read HTML code, understand its structure, and apply CSS to enhance the appearance of a website. 

How ever I will include here where I took the data: 

* [Fires by start time (1995-2023)](https://agricultura.gencat.cat/web/.content/06-medi-natural/incendis-forestals/enllacos-documents/estadistiques/fitxers-binaris/incendis-forestals-hora-inici-1995-2023.xlsx)

The original code: 
* [How to generate a clock chart using PLotly](https://stackoverflow.com/questions/72595317/is-it-possible-to-generate-a-clock-chart-using-plotly)

* [The final result](https://github.com/journadata/FireCat/blob/main/newplot.png)
 

## Things I would've liked to do:

As previously stated, it is reasonable to create a map to illustrate the extent of damage caused by the fires and to contrast this with the areas that have been replanted. This was demonstrated by Aaron in the second-to-last class with QGIS. I was able to replicate this using Mapbox. It would be beneficial to revisit this topic in the future.

The CSS has undergone minimal alteration, with the exception of the Google fonts that I chanched to [Fira Sans](https://fonts.google.com/specimen/Fira+Sans). However, I will focus on CSS in the next project.  

## Feedback

Tell me what you think at [@beaglvz](https://github.com/journadata)