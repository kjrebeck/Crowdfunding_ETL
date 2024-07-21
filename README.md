# Crowdfunding_ETL
In this group project we worked with two excel files and used them to create a pipeline. We started with creating an erd diagram so that we could later load the files into a database in PgAdmin. We then created our database and created our tables inside PgAdmin with the erd documentation we had previously created. After that we loaded our excel file data into jupyter notebook so that we could modify and clean the data so that it would have the columns and datatypes we wanted to match our erd diagram. Next, we took the data we cleaned and modified and loaded it into our database that we had created in PgAdmin so we could query off the data and answer any questions pertaining to the data given. Finally we made our queries based off six questions we had and wanted answered.
    1. Which category pledged the most
    2. Which subcategory pledged the most
    3. Who pledged the most money individually
    4. Who pledged the most in the Plays subcategory
    5. Did each category meet/exceed/miss their pledged goal
    6. Which subcategory pledged the most for the music category
After querying this data we made each result into a dataframe so that we could create visualizations on the results and have an easier way of viewing and reading the results.