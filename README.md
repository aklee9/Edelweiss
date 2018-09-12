# Edelweiss
Edelweiss for APL-Circ
I'm trying to automate a manual process, starting with Circ History, that will allow for Sierra information to be sent to Edelweiss without Scheduler.

There is a Saved Search in Sierra
Store Record Type: Item
ITEM Checkout Date between MM-DD-YYYY MM-DD-YYYY
last_checkout_gmt




Saved Export
ITEM Record Number
ITEM Barcode
BIBLIOGRAPHIC Record Number
ITEM Checkout Date
ITEM Checkout Location
ITEM Due Date
ITEM Location

item_record_id bigint OR id?
barcode varchar
bib_record_id big int
last_checkout_gmt timestamp
location_code varchar
due_gmt timestamp
location_code varchar
