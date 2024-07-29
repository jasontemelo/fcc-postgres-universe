Complete the POSTGRES challenge for FreeCodeCamp's Relational Database Certification. 
I created a Celestial Bodies database named 'unverse.sql' and passed all requirements, which are listed below:

You should create a database named universe<br>  
Be sure to connect to your database with \c universe. Then, you should add tables named galaxy, star, planet, and moon<br>  
Each table should have a primary key<br>  
Each primary key should automatically increment<br>  
Each table should have a name column<br>  
You should use the INT data type for at least two columns that are not a primary or foreign key<br>  
You should use the NUMERIC data type at least once<br>  
You should use the TEXT data type at least once<br>  
You should use the BOOLEAN data type on at least two columns<br>  
Each "star" should have a foreign key that references one of the rows in galaxy<br>  
Each "planet" should have a foreign key that references one of the rows in star<br>  
Each "moon" should have a foreign key that references one of the rows in planet<br>  
Your database should have at least five tables<br>  
Each table should have at least three rows<br>  
The galaxy and star tables should each have at least six rows<br>  
The planet table should have at least 12 rows<br>  
The moon table should have at least 20 rows<br>  
Each table should have at least three columns<br>  
The galaxy, star, planet, and moon tables should each have at least five columns<br>  
At least two columns per table should not accept NULL values<br>  
At least one column from each table should be required to be UNIQUE<br>  
All columns named name should be of type VARCHAR<br>  
Each primary key column should follow the naming convention table_name_id. For example, the moon table should have a primary key column named moon_id<br>  
Each foreign key column should have the same name as the column it is referencing<br>  
