## What does this Odoo module do?

- This module reads an SO and creates an MO with 
  - stockable products as line-items
  - services listed in a separate tab on the MO called "Manpower". The service line-item can be assigned to a Worker with ability to start and stop timer required by him for specific service line.
- If BOMs are associated with the product, they are preloaded
- If there are BTO products (Inventory route "Manufacture") in the SaleOrder, a separate MO is created for that product, according to the standard Odoo process.  Source is set to SO#.

The MO is left in an un-validated state. 
BTO = Built to Order
