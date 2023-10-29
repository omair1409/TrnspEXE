# TrnspEXE
In this project, I am trying to solve the basic transportation problem using OR-Tools and then build a standalone EXE so the user can use it without a coding background. It will ask for the CSV file and then provide the solution in two shapes: 1. HeatMap and 2. CSV File.





## Key tools used

- **Python App**: I used a Python environment to develop this tool (VSCode) and here are the main libraries I used:
- ***Tkinter*** : to build the basic GUI
- ***Pandas*** : to handle the data from the CSV file and process the DataFrame
- ***MatplotLib & Seaborn***: for visualization
- ***OR-Tools***: The Engine to solve the LP problem

![](https://github.com/omair1409/TrnspEXE/blob/main/Trnsp.gif)

## Notes
- **Prepare the CSV file as the following**:
- the first row has the names of the destinations
- the first column has the names of the suppliers
- the last column represents the capacity for each supplier
- the last row represents the demand for each destination
- the middle cells are the shipping cost (this can be seen as the distance between the source and the supplier)
- Here's a sample of the input and here's the [downlaod](https://github.com/omair1409/TrnspEXE/blob/main/Transpotation.csv)
  ![Alt text](https://github.com/omair1409/TrnspEXE/blob/main/input.PNG)




  
A solution looks like:

![Alt text](https://github.com/omair1409/TrnspEXE/blob/main/soln.PNG)


