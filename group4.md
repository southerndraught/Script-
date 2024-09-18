# Script

Member 1

1. Entity Type - Salesman
(Own Introduction)

  We identified Salesman as a crucial entity in this database. In the real-world context, the Salesman entity could represent employees who interact directly with customers and handle product sales.


Member 2
2. Attributes of the Salesman Entity  
   After defining the entity, we listed its relevant attributes, which describe characteristics of the salesman, such as:  
   - Employee Name  
   - Contact Number  
   - Email  
   - Date of Birth  
   - Work Placement  
   - Branch ID (for the branch where the salesman works)  
   - Department Name (where the salesman is assigned)


Member 3
3. Primary Key (PK) and Foreign Keys (FK)  
   - We designated Employee_ID as the primary key (PK). This ensures that each salesman can be uniquely identified in the system.  
   - We also introduced two foreign keys (FK): Branch_ID and Department_Name. These foreign keys establish relationships between the Salesman entity and the Branch and Department entities, ensuring data consistency across related entities.


Member 4
4. Entity Instances  
   To provide examples, we created two instances of the Salesman entity:  
   - Ridley Z. Barnes with Employee ID 00325650, working in the Electronics department at Branch 00127.  
   - Ryan C. Montero with Employee ID 00329869, working in the Cosmetics department, also at Branch 00127.

   These instances represent real-world examples of salesmen, each with their own unique attributes while still sharing common fields like the branch and department.


Member 5
Flowchart Explanation

   In addition to the ER diagram, we’ve also included a flowchart on the right side of the diagram, using Chen Notation Style. Let me explain the key shapes and their roles:

Entities (Rectangles):
   The Salesman entity is represented by a rectangle in this flowchart. This symbol is used to define objects that store data about something, such as salesmen, employees, or products.


Member 6

Attributes (Ovals):
   Each oval represents an attribute of the Salesman entity, like Employee Name, Contact Number, Email, Date of Birth, Branch ID, Department Name, and Work Placement. These attributes describe characteristics of the entity.

Primary Key (PK):  
   The primary key, Employee ID, is highlighted in a rectangle under the entity in the ER diagram and is also part of the flowchart. This shows that it’s a unique identifier for each salesman.

 Foreign Keys (FK):
   The foreign keys, Branch ID and Department Name, are shown in relation to the Salesman entity. These foreign keys connect the Salesman to the Branch and Department entities, establishing relationships in the system.

Relationships (Diamonds):
   In other ER diagrams (although not explicitly shown here), relationships between entities would be depicted using a diamond shape. This symbolizes how entities like Salesman relate to other entities, like Branch or Department.
