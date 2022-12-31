# Tablaeu
exercises:



Start by downloading

ISM 6419 Fall 22.xlsx

The file contains five worksheets, entitled Orders, Suppliers, Countries, Customers and Products.

The example may be a bit contrived but the general intent will be clear: The Customers and Products worksheets contain information about customers and products.  In the Products table, we have a pointer to the Supplier of this product whose full information is available in the Suppliers worksheet.  The Suppliers worksheet has the address of the supplier, including the country.  In Countries, we store in which geographical regions each country is located.  Orders obviously contains information about orders, with points to the Customer who ordered the product, the product(s) they ordered, and the quantity.  The following is a graphical depiction of the relationships between the various components:

Data Model

As you start working on this exercise, remember to save the file you are working on regularly.

The tasks are 

Build the data tables by importing the data from the Module 3 Excel spreadsheet by dragging the sheets into top pane and linking the sheets as follows:
Between Country in Suppliers, and Country Name in Countries
Between SupplierID in Suppliers and SupID in Products
Between ProdID in Products and ProductID in Orders
Between CustID in Customers and CustID in Orders.
Add the calculated fields Gross Revenue by multiplying Qty from Orders  by List Price from Products, Cost by multiplying Qty from Orders by Unit Cost from Products, and Net Revenue by subtracting Cost from Gross Revenue.
Create a visualization, that shows the Gross Revenue, Cost and Net Revenue by geographical area.  I should be able to drill down to get the information by country and by supplier in that country.  Give the sheet with the visualization a meaningful name and title.  Note: If necessary, you can re-order the fields in a hierarchy.
Create a second visualization that shows the proportion of Net Revenue generated by each supplier.  Give the sheet with the visualization a meaningful name and title.  Note: You can drag a field from within a hierarchy into the sheet.
Create a third visualization that shows the amount of Net Revenue generated in each country.







# Tablaeu 3

Create a visualization that shows, for each product, the average Qty in an order and the average Cost of an order.  The visualization should be dual axis.
Create a visualization that shows, in a single chart and by Order Month and Year, average cost, average gross revenue, and average net revenue.  I should be able to change the chart by Product Name.  Use a filter, rather than a parameter.
Create a simple visualization that shows Cost, Net Revenue and Gross Revenue by the actual Order Date.
Use a pages animation to animate the chart you created in step 2, again using OrderDate as the basis for the animation but make sure the animation shows the figures by Month. 
Use a pages animation to animate the chart you created in step 3, use OrderDate as the basis for the animation, but make sure the animation shows the figures by the actual date of the order. 
Create a visualization that shows total Net Revenue for Suppliers in China and Japan.  Give the worksheet a meaningful name.
Create a scatter graph for customers with as dimensions average gross revenue and average net revenue.  The bubbles in the scatter graph should have the name of the customer company associated with them.  I should be able to interactively change the information by order year.  Give the worksheet with this visualization a meaningful name.  
Create a scatter chart that shows for each product, average cost, average net revenue, and average order gross revenue, and the country that the product is supplied from.  The bubbles should have the name of the supplier on it.  Give the worksheet with this visualization a meaningful name.  
Create a parameter and a calculated field, Financial Measure, to allow the user to change the financial measure (Cost, Gross Revenue, Net Revenue)
Use a map that shows Financial Measure by country.  The map should also include the parameter that you used in calculating the Financial Measure so that I can change the Financial Measure that is displayed on the map.

