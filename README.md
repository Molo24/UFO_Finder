# UFO_Finder

## Overview of Project
The purpose of this project was to create an interactive webpage (leveraging the Bootstrap framework) connected to a JavaScript array consisting of UFO sighting information. Using JavaScript, the goal was to be able to present the UFO data onto a webpage but also allow the user to filter the data on specific criteria: Date, City, State, Country and Shape (of the UFO).

In order to achieve this two files had to be created:
1. Create an HTML file, ```index.html``` that imports not only the Boostrap framework, but also the releveant ```data.js``` and ```app.js``` JavaScript files. This HTML file also contains the layout of the webpage.
2. Create an ```app.js``` file which iterates through ```data.js``` and builds the data table in ```index.html```

## Results
In order to use the interactive webpage all the user needs to do is input values in the Date, City, State, Country and Shape (of the UFO) fields. Pressing Enter after inputing or removing values of the fields will automatically update the data table on the website.

Below are examples of how to use the filters menu on the interactive webpage.

### No Filters Applied
![datatable](https://user-images.githubusercontent.com/89284280/141701318-3626fb95-f608-44d1-b806-a4db7874a686.PNG)

### Filter by Date
![filterdate](https://user-images.githubusercontent.com/89284280/141701294-a21ee731-0edc-4c9b-a6ce-412409b104aa.PNG)

### Filter by City
![filtercity](https://user-images.githubusercontent.com/89284280/141701304-0259124c-a416-434e-9167-e58d7fc6f1e8.PNG)

### Filter by State
![filterstate](https://user-images.githubusercontent.com/89284280/141701312-974ef85e-ef8e-415a-8dad-a4722c3c600b.PNG)

### Filter by Country & Shape
![filtershape](https://user-images.githubusercontent.com/89284280/141701326-22a85aa1-134f-47bc-93e0-4cfc71ee6df6.PNG)

## Summary
The interactive webpage works as intended - it allows the user to interact with the webpage and apply filters to the table. The table is dynamic and responds to the users input. However, there are some drawbacks to this design, including:
- The user does not know all the fields they can search on. Because of the length of the table, it is hard for the user to know exactly all the field values they can input to filter on.
  - Recommended to instead provide a pull down menu of all eliglble fields that can be filtered on.   
- Total results is not know. When a user filters the data table the only way for them to know how many results they found is based on their ability to count each row returns by themselves.
  - Provide a count of total rows returned
- User is not able to filter by duration of the UFO sighting
  - Create a filter to search by duration (less than, greater than or equal to a specified duration)
- User is not able to filter by the comments
  - Allow the user to filter by comments by either exact or partial string matches.
- There is no sorting of the data table. For example, sorting by city to have all the results by each unique city shown together.
  - Add sorting toggles to each column that will sort the table.
