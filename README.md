# materialist
A project of co2 emissions database of building materials and calculator

In this application a user can create a small building project and save building materials used in a database. 
Materials are divided into indoor and outdoor category.
Each material item are saved with an amount, such as an area (m2) and co2/kg value. 
Thus, a user can calculate co2 emissions of a small building project.

Tables include:
- user id
- projects (user can add several projects)
- indoor/outdoor category (user can choose a category)
- materials such as tiles or timber (user can add materials and co2/kg values)
- project's materials and quantities

For example, a project of a small wooden sauna would include timber x m2, indoor tiles x m2, outdoor roof cladding x m2 and concrete x m2
User can add kg CO₂ eq/m² value by searching EPD (Environmental Product Declaration) of a certain product. Thus a query of total emissions can be done. 
