# Product-Margin-Application
A first test launch of an windows application that is built using Python and tkinter. 

The application mainly allows bakery to record supplier information, record raw material costs, and record recipes for easy margin calculation.

A few incomplete functions to take note

- Raw material cost records the cost of each order/bulk from the supplier, and does not calculate the material cost per gram/mililitre. User would require to do some pre-calculations beforehand to manually type in the cost of material per gram (cost/g).
- The recipe only records cost of material and does not include any multiplier for selling price, labour cost, miscellaneous cost (cost of water, cost of electric, etc..) A way to solve this is by creating a customm "Supplier" to record miscellaneous cost by adding "Labour Cost", "Water Cost", "Electricity Cost", or any other that is needed as an "Ingredient" to be added during the recipe creation.
- All raw data should be accessible within the "product_margins" database file, which can be read, edit, deleted, using any sql viewer. The sql file is created using SQLite.

**IMPORTANT

The Product_Margins.exe file can only be run with the folder including the "_internal" and Data Base File together. If wanted to be accessed elsewhere, a shortcut file is to be created.
