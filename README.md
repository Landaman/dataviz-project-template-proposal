# Data Visualization Project

## Data

The data I propose to visualize for my project is the [Lego Dataset](https://github.com/Landaman/dataviz-project-template-proposal). It can be found here on [VizHub](https://vizhub.com/Landaman/lego-csv). It contains information about every Lego set manufactured from 1970 to 2015, which is over 6000 sets.

A few attributes are included from each set:
- Its ID
- Its name
- Its manufacture year
- Its theme
- Its number of pieces
- Its number of minifigures
- Its price in various regions
- Its availability and box type


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

- I want to understand the correlation between cost and number of pieces
- I want to visualize how the number of pieces has changed over time
- I want to visualize how cost has changed over time
- I want to understand the correlation between theme and number of pieces
- I want to visualize which themes sets come from - perhaps a bubble chart or a pie chart could accomplish this

## Sketches
'
This visualization shows the percentage of lego sets that fall into each theme, relative to the others.
It also shows subcategories, representing how many sets fall into each subtheme within a given theme.

<img width="416" alt="image" src="https://github.com/user-attachments/assets/b93686b1-20fa-422f-b104-86d54827caff">

This visualization shows the interaction with this set. Hovering over a segment will show the number of sets and percentage in each theme, and clicking on a category within that popup will show the price distribution of the theme/subtheme

<img width="769" alt="image" src="https://github.com/user-attachments/assets/695ae9d8-dce3-40a3-89f8-b7e23249306a">

## Prototypes

I’ve created a proof of concept visualization of this data. It's a piechart and it shows the percentage of sets in each theme.

<img width="544" alt="image" src="https://github.com/user-attachments/assets/4d96f31f-ef93-4bed-9067-841d82b85bc4">

[VizHub](https://vizhub.com/Landaman/27e24f43fb8f4c69bb5d0f97c164361b)

An actual prototype with the PieChart data doesn't look very good (since most of the themes have a very small number of sets)

<img width="873" alt="image" src="https://github.com/user-attachments/assets/016dae58-b012-46d8-a6da-97101f7f1f66">

Leaving only the top 9 and combining the rest to a "Miscellaneous" group helps a lot

<img width="822" alt="image" src="https://github.com/user-attachments/assets/f965fbfc-ebce-42e3-ad7e-cf038ee725a4">

This then provides the sub-themes, using "g"s to group and scaling based on the percentages calculated for each price range

[VizHub](https://vizhub.com/Landaman/5f4b26c106a4455d819c2e1986cd8796)
<img width="770" alt="image" src="https://github.com/user-attachments/assets/9d662c51-1420-4cfb-88ea-f2337c5c2498">

Adding a legend improves the clarity of what the groups are doing

<img width="997" alt="image" src="https://github.com/user-attachments/assets/793ad9d8-c61d-43b8-89cb-9f05d3a1fc4b">

Reducing the size of the pie chart then helps make the screen more digestable

<img width="893" alt="image" src="https://github.com/user-attachments/assets/17ab80d7-e71c-4d4c-ac56-59974b3beb3e">

Moving the labels out of the chart then further helps to improve readability

<img width="1013" alt="image" src="https://github.com/user-attachments/assets/06e7d74f-fd6b-4b88-b48b-9249beaa32bd">

Improving the positioning of the labels relative to the spokes then further helps

<img width="924" alt="image" src="https://github.com/user-attachments/assets/7a03b0a0-7c92-4e6d-810f-1b4a73294759">

Finally, making the spokes mostly transparent makes them look less like the rest of the chart
[VizHub](https://vizhub.com/Landaman/0fd4095dfbfa4dbc94a7b0b6a9d6b85e)

<img width="941" alt="image" src="https://github.com/user-attachments/assets/947918f6-3e4d-4913-ac0e-056281ce04af">

Implementing the "hover color" effect improves readability
[VizHub](https://vizhub.com/Landaman/1d18052ce5524fccafa11b8f6e68b67f)

<img width="968" alt="image" src="https://github.com/user-attachments/assets/3c563030-ec63-4458-a087-f442134bc851">

Changing the order things are drawn in improves the "pop" of the entire graph

<img width="913" alt="image" src="https://github.com/user-attachments/assets/b43b3593-1622-46ca-805e-5f3cc7f1ea67">

Refactoring to make modifications easier and adding an "Unknown" category to better match the dataset

<img width="992" alt="image" src="https://github.com/user-attachments/assets/96fef519-cdbd-4ada-9c7f-f4d96642538f">

Implemented responsiveness
[VizHub](https://vizhub.com/Landaman/9be4b317a4cc4d21acb1752befb317a3)

<img width="891" alt="image" src="https://github.com/user-attachments/assets/703f6934-4b8a-4f14-84ac-b40b305e683d">

Implemented a hover effect on catagory hover
[VizHub](https://vizhub.com/Landaman/bf7265beccad426e9fc359e3a0ec0415)

## Milestones

- Week 2 - Pick datasets
- Week 3 - Identify dataset tasks
- Week 4 - Initial sketches
- Week 5 - Sketch iterations
- Week 6 - Project Proposal
- Week 7 - Project Proposal Document
- Week 8 - Substantial Progress
- Week 9 - Substantial Progress
- Week 10 - Hover Color Effect
- Week 11 - Interaction & Responsiveness
- Week 12 - Catagory Hover Effect


