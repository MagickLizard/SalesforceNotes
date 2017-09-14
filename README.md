# Salesforce Notes 
This is a collection of notes I have consolidated on Salesforce.

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

Force.com is an object-oriented relational database management system. The backbone of the entire system based on Force.com is in relationships.


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


# Fields

•	A field are similar to a database column 

•	Salesforce provides two types of fields

•	Standard fields that are system generated

•	Custom fields that are user-created

•	ID value - First three characters identify the type of object - Primary Key

•	Indexed by default - system generated.

•	Store information and data about custom objects. 

•	Some examples of available field types include: text, formula, number, checkbox and picklist. 


# Relationships 

# Lookup Relationships (1:N)

•	Are loosely coupled and have the following properties:

     The two objects with no relationship dependency on each other.
     The lookup field value is optional.
     Updating and deleting the child record has no effect on the parent.
     Objects have their own owners and sharing rules.
     A record can have 25 lookup fields with 25 different objects.

# Master-Detail Relationship (1:N) 

Master-Detail relationships are tightly coupled relationships in comparision to Look-up relationships the follow are properties for Master-detail:

        • The ownership of the child record is given to the master object's owner. 
        
        • The detail inherits the sharing, security settings as well as the look and feel of the master.
        
        •	Master record is always required for storing the child record.
        
        • If the master record is deleted, the child record is also deleted.
        
        • In a relationship between a standard object and custom object, the custom object will always be the detail record.

• An object can have maximum of two master objects. In otherwords a junction Table can be created in Salesforce.
In cases of multiple objects, both the masters are required. If one master is deleted, the child object gets
deleted immediately. 

• A Master-Detail can be multiple levels deep, for example :

      If the master is standard object: two multiple level's deep.
      If the master is child object: three multiple level's deep.
      example: "parent-child-grand-children".
    

