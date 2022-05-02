<div align = center>
    <h2>Relational Database Design</h2>
</div>

<br>


## What is Relational Database Design?

A Relational Database Design is a way of database construction on basis of four different parameters which are provided as a guideline and those parameters are listed bellow.   
In Relational database the data is stored in multiple tables and those tables are connected with each-other by using common attribute. 

1. Semantics of attributes
2. Reducing redundant information. 
3. Reducing null values.
4. Reducing the possibility of spurious tuple.

<br>

## Tables or Relations

* There can be a multiple tables in the relational database system.
* Tables can also called relations.
* Tables are made using rows and columns.
* **Rows**
    * Rows can also called tuple.
    * Number of rows == Cardinality of table
* **Columns**
    * Columns can also called attribute or fields.
    * Number of columns == Degree of table

<br>

## Keys

### Primary Key

- The Primary Key is the unique identity of tuple.
- Tuples can differentiate by using this key.
- There can be multiple primary key in single table.

### Candidate Key

- As we seen in primary key there can be multiple primary keys in the table in that case it called candidate key.
- Candidate keys are ready to be a primary key.   

### Alternate Key
- If the table has more than one primary keys it means we have candidate keys also in that case we only make one key to primary key and remaining keys called Alternate Keys.

### Super Key

- Super key is an attribute set that can uniquely identify a tuple. A super key is a superset of a candidate key.

### Composite Key

- Whenever a primary key consists of more than one attribute, it is known as a composite key. This key is also known as Concatenated Key.

### Foreign Key

- When we have multiple tables in that case foreign key can help to connect them together.
- Foreign Key can be a primary key of the other table.

<br>

## Joins

1. Left Join ~ (A - B)
2. Right Join ~ (B - A)
3. Inner Join ~ (A ∩ B)
4. Full Outer Join ~ (A ∪ B)