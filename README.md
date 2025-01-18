# OSS Inventory List
- Odoo (on-premise)
- ERPNext
- OSS Comparison
- Odoo Features
- ERPNext Features

## 1. Odoo (on-premise)

Odoo Inventory OSS is part of the Odoo ERP suite, which is modular and fully integrated. This means it can seamlessly connect with other Odoo modules like accounting, e-commerce, and CRM, providing a comprehensive business management solution[¹](https://transines.com/odoo-erp-for-inventory-management/).

### Pros
- **Customization Freedom**: The source code can be altered to meet unique business requirements[¹](https://transines.com/odoo-erp-for-inventory-management/).
- **Community Support**: Over 20,000 developers contribute to its enhancement[¹](https://transines.com/odoo-erp-for-inventory-management/).
- **Cost-Effectiveness**: It's free software with optional paid services and upgrades[¹](https://transines.com/odoo-erp-for-inventory-management/).
- **Scalability**: Suitable for both small businesses and large enterprises[¹](https://transines.com/odoo-erp-for-inventory-management/).
- **Integration Capabilities**: Easily integrates with other Odoo modules[¹](https://transines.com/odoo-erp-for-inventory-management/).
- **Flexibility**: Can be modified according to business changes[¹](https://transines.com/odoo-erp-for-inventory-management/).
- **No Vendor Lock-In**: You remain in control of your system and information[¹](https://transines.com/odoo-erp-for-inventory-management/).

### Cons
- **Complexity**: Customization and integration might require technical expertise[¹](https://transines.com/odoo-erp-for-inventory-management/).
- **Learning Curve**: Users may need time to get accustomed to the system[¹](https://transines.com/odoo-erp-for-inventory-management/).
- **Maintenance**: Regular updates and maintenance are necessary to keep the system running smoothly[¹](https://transines.com/odoo-erp-for-inventory-management/).

### Installation Complexity
Installing Odoo Inventory OSS can be straightforward if you follow the official documentation. However, it can become complex if you need extensive customization or integration with other systems. Here are the general steps:
1. **System Requirements**: Ensure your server meets the necessary requirements.
2. **Download and Install**: Obtain the Odoo source code and install it on your server.
3. **Configuration**: Configure the system according to your business needs.
4. **Customization**: Modify the source code if needed.
5. **Integration**: Connect with other Odoo modules or third-party systems.

Source: 

- (1) [ERP For Inventory Management: Features & Benefits.](https://transines.com/odoo-erp-for-inventory-management/)


NOTES:

- Purchase 
  - For dealers wanting to purchase a product
  - Can recieve initial ordered items and has options to backorder remaining items
- Inventory - For HQ admin having an access to Inventory
- Sales - Possible usage for fulfiller or sales rep creating sales order for dealers
- Modules: Inventory, Purchases, Sales, Manufacturing, Invoicing, Website, Barcode
- Odoo.sh 
  - Need subscription code
  - Use for on-premise development
  - Need to setup mail server
  - Tightly integrated in Github
  - Daily Backup is enabled (Manual/Auto)
  - We can use our own db (psql)
  - Usable if customization is needed, like adding fields or other biz logic

## 2. ERPNext

ERPNext is a comprehensive ERP system that integrates various business processes, including inventory management, into a single platform. Unlike some other inventory management systems, ERPNext offers a wide range of modules such as accounting, HR, CRM, and manufacturing, making it a holistic solution for businesses[¹](https://www.erp-information.com/erpnext-erp-guide).

### Pros
- **Comprehensive Solution**: Integrates multiple business processes into one platform[¹](https://www.erp-information.com/erpnext-erp-guide).
- **User-Friendly Interface**: Designed to be intuitive and easy to use[²](https://comparecamp.com/erpnext-review-pricing-pros-cons-features/).
- **Customizable**: Highly customizable to fit specific business needs[²](https://comparecamp.com/erpnext-review-pricing-pros-cons-features/).
- **Community Support**: Strong community support with regular updates and improvements[¹](https://www.erp-information.com/erpnext-erp-guide).
- **Cost-Effective**: Free to use with optional paid services for additional support[¹](https://www.erp-information.com/erpnext-erp-guide).
- **Scalability**: Suitable for businesses of all sizes[²](https://comparecamp.com/erpnext-review-pricing-pros-cons-features/).
- **Multi-Language Support**: Available in multiple languages, making it accessible globally[¹](https://www.erp-information.com/erpnext-erp-guide).

### Cons
- **Complexity**: Can be complex to set up and configure, especially for businesses without technical expertise[²](https://comparecamp.com/erpnext-review-pricing-pros-cons-features/).
- **Learning Curve**: Users may need time to get accustomed to the system[²](https://comparecamp.com/erpnext-review-pricing-pros-cons-features/).
- **Maintenance**: Requires regular updates and maintenance to keep the system running smoothly[¹](https://www.erp-information.com/erpnext-erp-guide).
- **Limited Advanced Features**: May lack some advanced features required by very large enterprises[²](https://comparecamp.com/erpnext-review-pricing-pros-cons-features/).

### Installation Complexity
Installing ERPNext can be straightforward if you follow the official documentation, but it can become complex if you need extensive customization or integration with other systems. Here are the general steps:
1. **System Requirements**: Ensure your server meets the necessary requirements.
2. **Download and Install**: Obtain the ERPNext source code and install it on your server.
3. **Configuration**: Configure the system according to your business needs.
4. **Customization**: Modify the source code if needed.
5. **Integration**: Connect with other applications or systems as required.

For businesses without in-house technical expertise, it might be beneficial to seek help from ERPNext partners or consultants to ensure a smooth installation and setup process[¹](https://www.erp-information.com/erpnext-erp-guide)[²](https://comparecamp.com/erpnext-review-pricing-pros-cons-features/).


Source:
- (1) [ERPNext Software Review (Modules, Pros & Cons) - ERP Information](https://www.erp-information.com/erpnext-erp-guide).
- (2) [ERPNext Review: Pricing, Pros, Cons & Features - CompareCamp.com](https://comparecamp.com/erpnext-review-pricing-pros-cons-features/).


### ------
OSS Comparison
------

### Comparison matrix between Odoo (on-prem), and ERPNext

| -  | Odoo On-premise |  ERPNext |
| -  | --------------- |  ------- |
| Has API |  ✓ |   ✓ |
| Supported Barcodes | EAN (European Article Number), UPC (Universal Product Code), Code-39, Code-93, Code-128, Codabar, ITF | UPC, EAN, Code-39, Code-93, Code-128, ITF, Codabar |
| Batch product upload | ✓ | ✓ |
| Multiple users | ✓ | ✓ |
| **Minimum System Requirements** |
| VM Size | **Small (up to 5 users):** <br>Standard B2s (2 vCPUs, 4 GB RAM). $30/month <br><br> **Medium (up to 20 users):** <br>Standard D4s v3 (4 vCPUs, 16 GB RAM). $140/month <br><br> **Large (90+ users):** Standard D8s v3 (8 vCPUs, 32 GB RAM) or larger. $280/month | Same |
| Storage | **OS Disk:** <br> Standard SSD (64 GB or more). <br><br> **Data Disk:** <br> Premium SSD (size depending on your database and backup needs, typically starting at 100 GB). |
| **Additional Recommendations** |
| Database | Use Azure Database for PostgreSQL for managed database services. | Primarily uses MariaDB but PostgreSQL is also recommended. |
| Backup | Implement Azure Backup for regular backups of your VM and database.
|  Monitoring | Use Azure Monitor to keep track of your VM’s performance and health. |
|


### Odoo Features
1. ***Storage Locations:***
  Create and manage specific storage locations like shelves, aisles, cold storage rooms, and pallet racks.

2. ***Putaway Rules:***
  Automatically route products to ideal storage locations based on real-time capacity, product storage needs, and picking accessibility.
3. ***Operations:***
  Create dedicated locations for receiving products, sorting, packing, and other warehouse operations.
4. ***Smart Removal:***
  Choose product removal strategies (FIFO, FEFO, nearest available zone, LEFO) and streamline picker paths with the right picking method (single, batch, cluster, wave).
5. ***Role-based To-Do List:***
  Dedicated dashboards to keep order fulfillment, purchasing, quality, picking, packing, and receiving teams on top of their daily tasks.
6. ***Receipts:***
  Manage incoming shipments with vendor-provided arrival dates and automatic unit of measure conversion for received quantities.
7. ***Returns:***
  Set predefined routes for return condition assessment, refurbishing, restocking, or disposal.
8. ***Pick and Pack:***
  Create smart automatic batches based on shipping carriers, serial numbers, specific quantities, and total weight for picker convenience.
  Assign barcodes to sealed packages for content tracking.
9. ***Scrap Management:***
  Scrap products in just a few clicks and get clear reports on scrap costs, reasons, and volumes.
10. ***Inventory Adjustments:***
  Schedule recurring stock counts on vital storage locations, products, or lots to keep inventory up to date.
11. ***Multi-Warehouse Management:***
  Manage all storage, stock, and replenishments for all your warehouses.
12. ***Barcode Integration:***
  Streamline warehouse operations using a barcode scanner for receipts, pickings, and inventory adjustments.
13. ***Customer Portal:***
Live web page where customers can track the status of their order, payment, and delivery.


### ERPNext Features

1. ***Stock Ledger and Valuation:***
  Provides a detailed record of all inventory transactions, including purchases, sales, transfers, and adjustments.
2. ***Batch and Serial Number Tracking:***
  Allows precise tracking of items using batch numbers and serial numbers, which is essential for quality control and regulatory compliance.
3. ***Multi-Unit of Measure (UOM):***
  Supports multiple units of measure for inventory items, making it easier to manage products sold in different quantities.
4. ***Automated Replenishment:***
  Automatically generates material requests to replenish stock when inventory levels fall below a predefined threshold.
5. ***Bin Management:***
  Helps organize inventory within warehouses by assigning specific bins to items, improving storage efficiency.
6. ***Material Requests and Transfers:***
  Facilitates the creation of material requests and internal transfers between warehouses.
7. ***Warehouse Configuration:***
  Allows setting up multiple warehouses with specific rules and configurations, suitable for businesses operating across various locations.
8. ***Item Variants:***
  Enables the creation of item variants based on attributes like size, color, and weight, simplifying inventory management.
9. ***Quality Inspections:***
  Implements quality inspections to ensure that the correct stock enters or leaves warehouses.
10. ***Stock Aging:***
  Provides insights into the age of inventory, which is crucial for managing perishable items.
11. ***Real-time Inventory Visibility:***
  Offers real-time visibility into inventory levels, movements, and costs, aiding in informed decision-making.
12. ***Advanced Inventory Control:***
  Supports advanced inventory control techniques, including reorder levels, lead times, and safety stock levels.
