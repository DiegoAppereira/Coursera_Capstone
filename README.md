# Capstone Project - 

Capstone Project - The Battle of Neighborhoods (Week 1)

This file, and other associated files, make up my contribution to the final Peer Reviewed Assignment for the Coursera Capstone Project for Applied Data Science Capstone. This was my final module in the IBM Data Science Professional Certificate program.

For reference I include the original definition for each part of the assignment.
Part 1

Clearly define a problem or an idea of your choice, where you would need to leverage the Foursquare location data to solve or execute. Remember that data science problems always target an audience and are meant to help a group of stakeholders solve a problem, so make sure that you explicitly describe your audience and why they would care about your problem.

This submission will eventually become your Introduction / Business Problem section in your final report. So I recommend that you push the report (having your Introduction/Business Problem section only for now) to your Github repository and submit a link to it.
Part 2

Describe the data that you will be using to solve the problem or execute your idea. Remember that you will need to use the Foursquare location data to solve the problem or execute your idea. You can absolutely use other datasets in combination with the Foursquare location data. So make sure that you provide adequate explanation and discussion, with examples, of the data that you will be using, even if it is only Foursquare location data.

This submission will eventually become your Data section in your final report. So I recommend that you push the report (having your Data section) to your Github repository and submit a link to it.

# Section 1: Introduction/Business Problem


Imagine the following scenario:

    You like to plan to travel to london and always review your options and make your choices about where you will visit and eat up front before you travel.
    You are flying to London for a Data Science Conference or just to Visit another place.
    you are not find a good restaurant to eat just the same restaurants like Japanese or Italian.
    But you know that far from you that a good places to go but need walk for a long time or  search on web sites to bring you to the best restaurants.
    Also the last time you went to london a 2 year ago your favority restaurant is closed.
    
What do you do ... ?
Project Idea

My idea for the Capstone Project is to show what is the most popular restautant by venue and location data from FourSquare,  where i will get what is the most popular, what is the distance of the tourism spot on this example i will use convent Garden, all the data will be generate a graphics showing map and graphics what is the best place to open a new restaurant.

A high level approach is as follows:

1. Where is the location for open new restaurant ?? 
2. What is popular food for tour or resident ?
3. How many is restaurant around Covent Garden and into Covent Garden?
4. How many kind of restaurant around Covent Garden?


Who is this solution targeted at

This solution is give to client or turism the clear vision of restaurant available and what will be the new possible restaurant available on the next years using the data science prospective. I want to see all the main restaurants the city of london will have, but at the same time, for whatever reaons unknown, is far from the location tourism spot.

Some examples of tourism spot:

   London Bridge
   convent Garden - i will use this spot.

There are many data science aspect of this project including:

    Data Acquisition
    Data Cleansing
    Data Analysis
    Prediction
    Data Visualization

Now that the we know what is the problem Lets See about the Data Section and how we can get all the information needed.

# Section 2: Methodology
Data Description

In this section, I will describe the data used to solve the problem as described previously.

As noted below in the Further Development Section, it is possible to attempt quite complex and sophisticated scenarios when approaching this problem. However, given the size of the project and for simplicity only the following scenario will be addressed:

    Query the FourSqaure website for the 4 top restaurants in covent garden london
    Use the FourSquare API to get supplemental geographical data about the 4 top restaurants
    Use the FourSquare API to get top restaurent recommendations closest to each of the top site
    
and also follow the simple questions:
1. Data number of restaurant around Covent Garden?
2. Data location restaurant around Covent Garden?
3. Data number of tourist or local residents on Covent Garden (effect to size of restaurant) ?. 
4. Data kind of popular food from Covent Garden?
5. Trends of demands food from Covent Garden? 

Top Sites from FourSquare Website
Although FourSquare provides a comprehensive API, one of the things that API does not easily support is a mechanism to directly extract the top N sites / venues in a given city. This data, however, is easily available directly from the FourSquare Website. To do this simply go to www.foursquare.com, enter the city of your choise and select Top Picks from I'm Looking For selection field.

The next part is the week2 of capstone Project.
