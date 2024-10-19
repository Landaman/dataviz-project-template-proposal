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

<img width="416" alt="image" src="https://github.com/user-attachments/assets/b93686b1-20fa-422f-b104-86d54827caff">

This visualization shows the percentage of lego sets that fall into each theme, relative to the others.
It also shows subcategories, representing how many sets fall into each subtheme within a given theme.

<img width="769" alt="image" src="https://github.com/user-attachments/assets/695ae9d8-dce3-40a3-89f8-b7e23249306a">

This visualization shows the interaction with this set. Hovering over a segment will show the number of sets and percentage in each theme, and clicking on a category within that popup will show the price distribution of the theme/subtheme

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

## Milestones

- Week 2 - Pick datasets
- Week 3 - Identify dataset tasks
- Week 4 - Initial sketches
- Week 5 - Sketch iterations
- Week 6 - Project Proposal
- Week 7 - Project Proposal Document
- Week 8 - Substantial Progress


