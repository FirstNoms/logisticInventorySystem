# Logistic Inventory System
Logistics inventory System includes various aspects as control and supervision of purchases from the customers, 
maintenance of stock storage, command on the product sale, and order fulfillment.

This Application was built using:
Stack: Java, 
WebFramework: Springboot,
Database: MySQL.

#Packages:
Item Inventory Package: has the:
* Controller Package: Has the Inventory controller Class.
* Data Package: has the Model package, Repository package and the Operation Enum.
  * Model package: has the Inventory class and the InventoryItem class.
  * Repository package: has the InventoryItem Repository and the Inventory repository.
* Services package: This is where the inventory operations (CRUD) happen
* Exception package
* The Db directory has the Insert.sql file in order for me to test the inventory service.

All Crud operations can be operated in the application.
An InventoryItem can be Created
An inventoryItem can be Edited
An InventoryItem can be Searched for (Read)
An InventoryItem can also be Deleted.

The Inventory apllication can also write a file to CSV.

