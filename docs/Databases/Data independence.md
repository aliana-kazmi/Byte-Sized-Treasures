# Data independence
Data independence means a **change of data at one level should not affect another level.** Two types of data independence are present in this architecture: 

1. **Physical Data Independence:** **Any change in the physical location of tables and indexes should not affect the conceptual level or external view of data.** This data independence is easy to achieve and implemented by most of the DBMS. 

2. **Conceptual Data Independence**: The data at conceptual level schema and external level schema must be independent. This means, **change in conceptual schema should not affect external schema.** e.g.; **Adding or deleting attributes of a table should not affect the user’s view of table.** But this type of independence is *difficult to achieve as compared to physical data independence because the changes in conceptual schema are reflected in user’s view.*