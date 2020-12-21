##	4.1 Describe the EAV data access process in Magento
-	Getting an attribute instance, impact of attribute sets, large number of attributes and attribute sets
-	What is the impact of 10,000 attribute sets? 1,000 attributes in a set?
-	How to get information about an attribute
-	How to perform attribute operations programmatically: assign it to a set/group, update properties, etc.
##	4.2 Describe the database tables for EAV entities and how to create them
-	The EAV database structure, performance considerations, entity-level attribute properties (catalog_eav_attribute)
-	Where are catalog-specific attribute properties stored and what are they used for?
-	How does Magento store the attribute to attribute group association?
-	What backend types are available? How do you add a new backend type?
-	Specifics around static attributes
##	4.3 Demonstrate an ability to operate with attribute options
-	Different ways to store attribute options. Using eav_attribute_option_* tables
-	Config base, database base options
-	The eav_attribute_option_ table: tables that contain shared options between different entities, pros and cons of using the table
##	4.4 Demonstrate an ability to use non-catalog EAV entities
-	Adding an attribute to Customer, Customer Address and Sales entities. Making an attribute visible in the Admin or the storefront. Pitfalls in attributes operations in non-catalog EAV attributes
-	Adding an attribute to customers, saving and loading the attribute, problems related to the save process. What is the role of attribute sets and groups for customer attributes?
-	Adding an attribute to customer addresses, the role of the ""is_system"" property and why it only works for the Customer Address entity
-	How to make a customer or customer address attribute visible in the My Account, Checkout, and Admin pages
-	What is the purpose of the SalesSetup class and why do you use the addAttribute method for sales entities?
