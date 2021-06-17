**Relationships between tables in a Data Model:**

By creating relationships among different tables, will always add more power to our data analysis. A relationship is a link within two tables that contain data: one column in each table is the foundation for the relationship. To avoid storing a lot of redundant data, we should always split the data into multiple tables and define relationships between those tables. 

Relationships exist within a Data Model -- one that we explicitly create, or one that some tools automatically creates on our behalf when we simultaneously import multiple tables.

  _Columns and Keys:_
    Relationships are depend on columns in each table that contain the same data. In a relational database, there are several types of keys. A key is typically column with special properties.
* Primary key: uniquely identifies a row in a table.
* Alternate key (or candidate key): a column other than the primary key that is unique.
* Foreign key: a column that refers to a unique column in another table.
    
_Types of Relationships:_
 * One to One
 * One to Many
  Note: Many-to-many relationships are not supported in a Data Model.
  
  _Relationships and Performance:_
  After any relationship has been created. Processing can take some time, depending on the amount of data and the complexity of the relationships.
  
  _Multiple relationships with tables:_
  A Data Model can have multiple relationships between two tables. Always only one relationship between each pair of tables is active at a time. Though the others are inactive, we can specify an inactive relationship in formulas and queries.
  
  _Conditions for a table relationship:_
  * A unique identifier from each table.
  * The lookup column can't contain duplicate values.
  * Data types should be well matched.
  
