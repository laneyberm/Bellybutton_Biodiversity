# Belly Button Biodiversity

## Overview
Rosa is a biological researcher in a microbiology laboratory. Many bacterial species are not well studied and many more remain unknown to science. Rosa‘s role is to discover and document these bacteria. In particular, Rosa is interested in bacterial species that have the ability to synthesize proteins that taste like beef. Her lab has partnered with improbable beef, a food start up to research candidate species. Labs across the country have had success in synthesizing meat from algae, fungi, and micro organisms found on plant roots. However, improbable beef is still searching for the elusive bacteria that will provide the perfect taste. 

Rosa has a hypothesis that there’s a microorganism that can supply the next best taste, and she believes it can be found from bacteria found on the human body. The human body is a source of thousands of types of bacteria, and different parts of the body harbor different species. Bacteria can be found in the gut are not the same species that are found on a persons eyelashes, for example. Furthermore, between individuals the bacterial species may vary even in the same location. Rosa hypothesizes that the ideal bacterial species to make synthetic beef, may be found in the belly button, or at least in someone’s belly button. 

To test her hypothesis, Rosa has sampled the navels of people across the country to identify bacterial species that colonize on our belly buttons. Each person has been assigned an ID number. And Rosa wants to build a dashboard that both her and her research participants and fellow researchers can access. Those who participated in the study well be able to visit the website and select their ID numbers to see which bacterial species live in their navels. 

## Resources
- Data Source: https://cdnjs.cloudflare.com/ajax/libs/d3/4.11.0/d3.js, charts.js, samples.json
- Software: Javascript 1.5, Bootstrap 4.0, Visual Studio Code 1.72.2 

## Results
The below image is the initial webpage without using the filters.  

<img src="https://github.com/laneyberm/Bellybutton_Biodiversity/blob/main/static/images/index.png" width="800">

Users will enter their search in the "Filter Search" shown below. They can filter the data down by date, city, state, country, and shape. Users need to utilize lower case letters with typing in the search. In the search inputs, there is an example of the format needed for each search category. 

<img src="https://github.com/laneyberm/Bellybutton_Biodiversity/blob/main/static/images/test_subject.png" width="250">

An example of filtering the data by the date, 1/13/2010, is shown below with its results.

<img src="https://github.com/laneyberm/Bellybutton_Biodiversity/blob/main/static/images/top10.png" width="800">

The below image is a storyboard of the webpage and the locations on the webpage of the data.

<img src="https://github.com/laneyberm/Bellybutton_Biodiversity/blob/main/static/images/freq.png" width="500">

The below image is a storyboard of the webpage and the locations on the webpage of the data.

<img src="https://github.com/laneyberm/Bellybutton_Biodiversity/blob/main/static/images/per_sample.png" width="500">

## Summary
Dana’s webpage and dynamic table are working as intended. A drawback to the usabilty of the filters is the search is case-sensitive. For example, to search for Arkansas, the user must type "ar" to find all the Arkansas search results. Typing "AR" or "Arkansas" will not return any results. 

I would recommend adding drop down menus to all the search categories that would include the filterable data per category. Additionally, I would recommend removing the case sensitivity of the search inputs. 

