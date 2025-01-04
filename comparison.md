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