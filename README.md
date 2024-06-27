# Odoo-iSuperaps-Integration
iSuperaps integration for Odoo

iSuperaps is a free Advanced Planning and Scheduling software. This project was built to integrate iSuperaps with  Odoo

1 Export data from Odoo to iSuperaps.

1.1 Odoo integration program export basic data tables mrp. workcenter, product. product, mrp. bom, mrp. routing, resource.calendars, sale.order to APS

2 Generate the plan in iSuperaps.

3 Import the manufacturing orders / purchase orders / outsourcing orders from iSuperaps to Odoo.

3.1 APS work orders, purchase orders, and outsourcing orders must have ERPno and status fields in their tables

3.2 The Odoo integration program will create a new document purchase.order/mrp.production based on the data in the corresponding APS table, and write back the erpno and status fields

4 Sync the inv between Odoo and iSuperaps.

4.1 Odoo real-time inventory quantity table is onhand

5 Sync the status of manufacturing orders / purchase orders / outsourcing orders between Odoo and iSuperaps.

5.1 Odoo integration program write back the status field of the APS corresponding table
