# InventoryShelfCheck
Smooth little 1 page application that you use  look up what products are on a specific shelf to print a list for manual inventory cycle counts. Uses google sheets & forms as a database for the back end.

Copy this google spreadsheets to your own google drive:

Inventory Location - https://docs.google.com/spreadsheets/d/1zpr9EPaNJ_2FOCCV7ca0iAjjeIV9H59tI6gVNso28qE

(the form should be automatically generated and accessable through the Inventory Location Spreadsheet)

Replace the variables values on their respective lines in the inventory.html file using the strings from your google spreadsheets URL's on lines 21 - 23.

Open up the form, copy the field_id's for each entry field, and paste them in to the appropriate fields in the inventory.html file. Starts on line 222.

Save to your webserver and launch! Enjoy entering various items and being able to look them up using the google sheet or the app.
