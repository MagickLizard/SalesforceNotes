# Salesforce Notes 
This is a collection of notes I have collobrated on Salesforce.

# Topics to be covered
•	Objects 

•	SOAP API

•	Creating Custom Objects

•	Fields

•	Dependencies with Fields

•	Encrypted Fields 

•	Object Relationships

•	Object Relationships

•	Lookup Filters

•	Lightning Schema Builder

Force.com automatically appends a __c to custom object api names. This is how Force.com distinguishes between standard objects and the custom objects. The API name of a custom Account object becomes Custom_Account__c.

Salesforce uses APEX which is a library on top of Java. 


# Objects

•	Object api names contain underscores. e.g "Account_Billing__c"

•	 Objects are unique

•	Objects are a higher level of abstraction than database tables

•	Have configurable access control features

•	Relational Object Orientation, Objects have inheritance. 

•	Are reportable, searchable and securable.

•	Salesforce provides two types of objects:

•	Standard objects that are pre-defined

•	Custom objects that are user-defined. 


# Field

•	A field are similar to a database column

•	They store a piece of information related to objects

•	Salesforce provides two types of fields

•	Standard fields that are system generated

•	Custom fields that are user-created

•	ID value - First three characters identify the type of object - Primary Key

•	Indexed by default - system generated.

•	Store information and data about custom objects. 

•	Some examples of available field types include: text, formula, number, checkbox and picklist. 

