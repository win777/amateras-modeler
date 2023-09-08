# Amateras Modeler

Lightweight UML and ER-diagram editor for Eclipse. Former AmaterasUML and AmaterasERD.

- UML
  - Class diagram graphical editing
  - Sequence diagram graphical editing
  - Activity diagram graphical editing
  - Import and export java code
- ER
  - ER diagram  graphical editing
  - Import tables from existing database
  - Generate DDL from diagram
  - Export table definition as HTML

Installation
--------
Install from the update site: https://takezoe.github.io/amateras-update-site/

For users who use Eclipse on Java 16 or later, add the following to eclipse.ini.

```
--add-opens=java.desktop/java.beans=ALL-UNNAMED
```

For developers
--------------
Install the following eclipse plugins:
- Eclipse SDK or PDE
- UML2 Extender SDK

License
--------
[Eclipse Public License 1.0](http://opensource.org/licenses/eclipse-1.0.php)

History
--------
| **Release date**  | **Product name** | **Version** | **Update description** |
| ------------------- | ------------- | ------------- | ------------- |
|2021/08/22  | AmaterasModeler  | 2.1.0 | - Support zoom by CTRL + Mouse scroll |
|2020/10/18  | AmaterasModeler  | 2.0.0 | - Java11 Support |
|2017/03/29  | AmaterasModeler  | 1.1.0 | - Java Enum support in class diagram <br> - Some icon decorators such as abstract, static and final <br> - Synchronization of class diagram against Java source <br> - Option to turn on / off aggregation links on java import |
|2012/07/16| AmaterasUML | 1.3.4 | - Fixed the issue on Java7. |
|2012/06/13| AmaterasERD | 1.0.9 | - Displays unique indices on the diagram.<br>- Switching display mode (logical or physical) by CTRL+D.<br>- Improvement of PostgreSQLDialect, MySQLDialect and OracleDialect.<br>- Refreshing imported tables.<br>- The dictionary which is used for name conversion became customizable.<br>|
|2011/08/13|AmaterasUML |1.3.3|- Improvement of constructor in the class diagram<br>- Improvement of Java generics support<br>- Quick Filter ("Show only Public" and "Show All")<br>- Refresh the class diagram from Java source<br>- Copy the diagram as image<br> |
|2011/02/12|AmaterasERD|1.0.8|- Sybase support<br>- In importing and exporting, table and column comments are mapped to logical name (Oracle and Sybase only)<br>- Copy As Image from the context menu<br>- Quick Outline ([CTRL]+[O])<br>- Diagram font configuration<br>- HTML generation tool from *.erd file which could be used in command-line<br> |
|2010/01/03|AmaterasERD |1.0.7|- H2 Support<br>- Switching dialect after creating a diagram<br>- Improved foreign key creation behavior<br>- Improved HTML report<br>- Convert table / column name from context menu<br>- Show NOT NULL constraint in the diagram<br>- Show and snap to Grid, snap to other figure<br>- SQL Highlighting<br> |
|2009/05/05|AmaterasERD |1.0.6|- Note is available on the diagram<br>- Additional SQL (such as inserting initial data) of each table<br>- Auto diagram reloading when the file is updated such as SVN update|
|2009/04/19|AmaterasUML|1.3.2|- New appearance settings of class diagram / sequence diagram<br>- Auto diagram reloading when the file is updated such as SVN update<br>|
|2008/12/10|AmaterasERD |1.0.5|- Show selected tables DDL from the context menu<br>- Table background color has been configurable<br>- Incremental search in the JDBC importing wizard<br>|
|2008/09/03 |AmaterasERD |1.0.4.1|- MySQL reverse engineering issue has been fixed.|
|2008/08/21|AmaterasERD |1.0.4|- SQL comment generation in DDL<br>- CREATE TABLE with SCHEMA option<br>- Diagram Validation<br>- Linked Table<br>- Table copy and paste|
|2008/06/07|AmaterasERD |1.0.3|- PostgreSQL and Oracle support<br>- Table re-importing improved<br>- Foreign keys decoration in the diagram<br>- Default column value support<br>- Outline view<br>- New DDL generate option to generate constraints as ALTER TABLE<br>- Index designing support<br>- Domain (Generic data type definition) support<br>- HTML report improved<br>|
|2008/02/14|AmaterasUML |1.3.1|- Auto layout in the class diagram editor.<br>- Java model importing supports aggregation.|
|2008/02/07|AmaterasERD |1.0.2|**New actions are available at the ER diagram context menu** <br>- Save as Image and Print<br>- Export table definition as HTML<br>- Auto layout<br> **Table definition dialog improved** <br>- Table / Column description<br>- Auto increment column<br> **New extension point (net.java.amateras.db.generators)** <br>|
|2007/10/07|AmaterasUML |1.3.0|- Eclipse 3.3 Support (This version can't work with Eclipse 3.2.x)<br>- Copy & Pase in the class diagram, the usecase diagram and the activity diagram.<br>- Brand new visual theme for diagrams.|<br>
|2007/07/19|AmaterasERD |1.0.1|- Apache Derby support<br>- Logical database design support|
|2007/04/22|AmaterasUML |1.2.2|- Activity diagram is available.<br>- Connection routers which exclude BendpoinConnectionRouter are not supported.<br>- Bendpoint moves according to the entity dragging.<br>- Note: This version hasn't compatibility with old versions.<br>|
|2006/12/31|AmaterasERD|1.0.0|- Initial Release|
|2006/08/31|AmaterasUML|1.2.1|**Class Diagram**<br>- Enable to drag two or more classes at a time.<br>- Enable auto connect to Generalization/Realization connection.<br>- Enable to drop the classes in jar entry.<br>**Extension**<br>- XMI import/export extension is available.<br>|
|2006/06/10|AmaterasUML|1.2.0|**Common**<br>- Enable to switch show/hide diagram grid.<br>**Class Diagram**<br>- Enable to hide fields/methods by context menu.<br>**Usecase Diagram**<br>- New feature<br>|
|2006/05/13|AmaterasUML|1.1.2|**Common**<br>- Enable to hide icons.<br>- Enable to change background/foreground color.<br> **Class Diagram** <br>- Enable to align diagram element.<br>- Add new connection router.<br> **Sequence Diagram** <br>- Change presentation of instance.<br>- Add Sequence API and sample plugin.<br> **Java support** <br>- Enable to open Java editor from class diagram.<br> **Limitation** <br>- Sorry, Sequence diagram editor can't edit *.sqd files created by older version. <br>|
|2006/04/22|AmaterasUML|1.1.1|**Add drag-and-drop**<br>- both class and sequence<br>- drap Java file in package exploler view.<br>**Enable to delete and create Return message.** <br>- Auto return message creation swtich in AmaterasUML preference<br> **Add code compiletion feature to edit message.** <br>|
|2006/04/09|AmaterasUML|1.1.0|- Add sequence diagram editor.<br>- Add Note for class diagram editor|
|2005/12/31|AmaterasUML|1.0.0|- This is the initial public release.|
