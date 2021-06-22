## What does this Odoo module do?

- This module reads an SO and if there are manufacturable products in line-items, it creates an MO.
- If BOMs are associated with the product, they are preloaded
- If there are BTO products (Inventory route "Manufacture") in the SaleOrder, a separate MO is created for that product.  Source is set to SO#.

The MO is left in an un-validated state. 
