------
title: OSS Comparison

------

### Comparison matrix between Odoo (on-prem), Inventree, and ERPNext

| -  | Odoo On-premise | Inventree | ERPNext |
| -  | --------------- | --------- | ------- |
| Has API |  ✓ |  ✓ |   ✓ |
| Supported Barcodes | EAN (European Article Number), UPC (Universal Product Code), Code-39, Code-93, Code-128, Codabar, ITF | Code-39, Code-93, Code-128, ITF | UPC, EAN, Code-39, Code-93, Code-128, ITF, Codabar |
| Batch product upload | ✓ | ✓ | ✓ |
| Multiple users | ✓ | ✓ | ✓ |
| **Minimum System Requirements** |
| VM Size | **Small (up to 5 users):** <br>Standard B2s (2 vCPUs, 4 GB RAM). <br><br> **Medium (up to 20 users):** <br>Standard D4s v3 (4 vCPUs, 16 GB RAM). <br><br> **Large (90+ users):** Standard D8s v3 (8 vCPUs, 32 GB RAM) or larger. | Same | Same |
| Storage | **OS Disk:** <br> Standard SSD (64 GB or more). <br><br> **Data Disk:** <br> Premium SSD (size depending on your database and backup needs, typically starting at 100 GB). |
| **Additional Recommendations** |
| Database | Use Azure Database for PostgreSQL for managed database services. | Primary uses PostgeSQL and can use SQLite for testing and development purposes. | Primarily uses MariaDB but PostgreSQL is also recommended. |
| Backup | Implement Azure Backup for regular backups of your VM and database.
|  Monitoring | Use Azure Monitor to keep track of your VM’s performance and health. |
|


### Odoo On Premise Features
1. Storage Locations:
  Create and manage specific storage locations like shelves, aisles, cold storage rooms, and pallet racks.
2. Putaway Rules:
  Automatically route products to ideal storage locations based on real-time capacity, product storage needs, and picking accessibility.
3. Operations:
  Create dedicated locations for receiving products, sorting, packing, and other warehouse operations.
4. Smart Removal:
  Choose product removal strategies (FIFO, FEFO, nearest available zone, LEFO) and streamline picker paths with the right picking method (single, batch, cluster, wave).
5. Role-based To-Do List:
  Dedicated dashboards to keep order fulfillment, purchasing, quality, picking, packing, and receiving teams on top of their daily tasks.
6. Receipts:
  Manage incoming shipments with vendor-provided arrival dates and automatic unit of measure conversion for received quantities.
7. Returns:
  Set predefined routes for return condition assessment, refurbishing, restocking, or disposal.
8. Pick and Pack:
  Create smart automatic batches based on shipping carriers, serial numbers, specific quantities, and total weight for picker convenience.
  Assign barcodes to sealed packages for content tracking.
9. Scrap Management:
  Scrap products in just a few clicks and get clear reports on scrap costs, reasons, and volumes.
10. Inventory Adjustments:
  Schedule recurring stock counts on vital storage locations, products, or lots to keep inventory up to date.
11. Multi-Warehouse Management:
  Manage all storage, stock, and replenishments for all your warehouses.
12. Barcode Integration:
  Streamline warehouse operations using a barcode scanner for receipts, pickings, and inventory adjustments.
13. Customer Portal:
Live web page where customers can track the status of their order, payment, and delivery.


### ERPNext Features

1. Stock Ledger and Valuation:
  Provides a detailed record of all inventory transactions, including purchases, sales, transfers, and adjustments.
2. Batch and Serial Number Tracking:
  Allows precise tracking of items using batch numbers and serial numbers, which is essential for quality control and regulatory compliance.
3. Multi-Unit of Measure (UOM):
  Supports multiple units of measure for inventory items, making it easier to manage products sold in different quantities.
4. Automated Replenishment:
  Automatically generates material requests to replenish stock when inventory levels fall below a predefined threshold.
5. Bin Management:
  Helps organize inventory within warehouses by assigning specific bins to items, improving storage efficiency.
6. Material Requests and Transfers:
  Facilitates the creation of material requests and internal transfers between warehouses.
7. Warehouse Configuration:
  Allows setting up multiple warehouses with specific rules and configurations, suitable for businesses operating across various locations.
8. Item Variants:
  Enables the creation of item variants based on attributes like size, color, and weight, simplifying inventory management.
9. Quality Inspections:
  Implements quality inspections to ensure that the correct stock enters or leaves warehouses.
10. Stock Aging:
  Provides insights into the age of inventory, which is crucial for managing perishable items.
11. Real-time Inventory Visibility:
  Offers real-time visibility into inventory levels, movements, and costs, aiding in informed decision-making.
12. Advanced Inventory Control:
  Supports advanced inventory control techniques, including reorder levels, lead times, and safety stock levels.
