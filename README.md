# scot_lib_2022

This .csv dataset contains the names, postcodes, approximate latitude and longitude, and local council authority for all current libraries in Scotland (470 locations). Mobile libraries with no fixed address are ignored and multiple libraries within the same building (e.g. a specialist local history library housed within a general library) are treated as a single entity. 

## The .csv datamap is:
![Screenshot 2022-04-29 at 11 24 35](https://user-images.githubusercontent.com/14912609/165927612-b1b1f031-b2f3-4419-ba46-39b49991d9dc.png)

| field     | type   | purpose                                   |
|-----------|--------|-------------------------------------------|
| library   | string | Official Library Name                     |
| postcode  | string | Full postcode                             |
| latitude  | float  | position for centre of postcode area      |
| longitude | flat   | position for centre of postcode area      |
| county    | string | local authority council area              |
| region    | string | UK region (only Scotland in this dataset) |
| country   | string | Country (only UK in this dataset)         |


##Example of coverage
![Screenshot 2022-04-29 at 11 25 33](https://user-images.githubusercontent.com/14912609/165927758-94869db8-19bf-4742-a758-865fc6a4b188.png)
A simple R script for this visualisation is included in the repository.
