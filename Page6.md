# Task 5: Collection Regions and Alignment #
1. Creating a collection region:
Since there are multiple items within each order, use a collection data region to extract details of the items ordered.

    -   Right-click on the previously created data region and select Add Collection Data Region.
![alt image](https://github.com/Raghukashyap1143/Astera-s-lab/blob/main/LabguideBhav/9.jpg?raw=true)
    -   Rename this region to “Order_Items”.
![alt image](https://github.com/Raghukashyap1143/Astera-s-lab/blob/main/LabguideBhav/10.jpg?raw=true)
    -   Specify the item code as the recurring pattern as it is the one unique identifier for all the line items.

    -   Make the pattern flexible enough to find all the item codes by using wildcards. Match any alphabet and digit, defining a pattern consisting of three alphabets and five numbers separated by a hyphen (e.g., ABC-12345).
![alt image](https://github.com/Raghukashyap1143/Astera-s-lab/blob/main/LabguideBhav/11.jpg?raw=true)

2. Adjust for Data Alignment
    -   If the data is not aligned, check the Floating Pattern option in the Pattern Properties panel to extract the data correctly.
![alt image](https://github.com/Raghukashyap1143/Astera-s-lab/blob/main/LabguideBhav/12.jpg?raw=true)

3. Creating Data Fields
    -   Once the collection region is defined, highlight the data points within the region to create the corresponding data fields.
![alt image](https://github.com/Raghukashyap1143/Astera-s-lab/blob/main/LabguideBhav/13.jpg?raw=true)
4. Saving the report model
    -   Select the Save icon from the toolbar and save the report model.
![alt image](https://github.com/Raghukashyap1143/Astera-s-lab/blob/main/LabguideBhav/14.jpg?raw=true)






