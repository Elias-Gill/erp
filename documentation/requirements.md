In the given document are present all the requirements for the ERP system.

1. [Inventory](#inventory)
    * [Notes](#notes)
2. [Sales](#sales)
3. [Security](#security)
4. [Providers](#providers)
5. [Employees](#employees)
6. [Finances](#finances)


****

# General requirements

- Support for multiple branch offices.
- Easy to use.
- Expose robust api's for building external tools.
- "Easy" to extend in a source code level.
- Support a simple web UI.

# Modules

The system has to support 4 modules:

## Inventory

Module to manage the inventory on warehouse and sales center

- Support for multiple warehouses, sales centers and branch offices.
- Support for building customized repots (as cataloges)
- Support for product images.
- Make reports of the current stock from warehouse and sales center
- Support recieving more products to the warehouses.
- Support recieving more products to the sales center directly.
- Support moving inventory from warehouses to sales center.
- Support for lots(lotes) of products.
- Support to do inventory on a section or departament level.
- Unsuscribe products from inventory.
- Search tools for searching specific products.
- Add new products, sections and departaments.
- List all products filtering by levels and stock.

#### Notes

- The inventory module does not support pricing of the products or providers.

## Sales

Module to manage sales, pricing of the products, promotions, etc.

- Manage pricing of the products
- Support for barcodes.
- Have support for special promotions, discounts and combos.
- Support paymethods:
  credit cards and cash.

## Security

Module to manage security acces, roles and passwords for employees.

- Support for managing roles and fine grade tunning of permissions. 
- Manage passwords, encryption and security meassures.
- Loging, logout and 
- Register every user's actions (actions and operations, config.
  changes, logins and logouts).
  With log files or inside the database (or both).
- User data input validation.

## Providers

Module to manage providers data and manage orders at a fine level (payment method, orders date,
payment date, orders arrival, etc).

- Support for cataloges of providers
- Manage providers data
- Unsuscribe providers.
- Manage orders

NOTE:
orders don't affect finances directly, because the orders may change until the products arrive.
It is used as a "placeholder"

## Employees

Module to manage employees data, salary, contract and simple productivity stats.
payment date, orders arrival, etc).

- Manage employees data such as salary and contract.
- Fire employees
- Manage employee charges and roles
- Manage basic employees statistics such as faults and vacation days

NOTE:
the system does not controles ins and outs times (for automatic "faults").

## Finances

- Support for accounting entries, ledger and journal (libro mayor y diario).
- Support various payment styles such as checks, credit cards and cash.
- Register every financial movement from the other modules.
- Divide for accounts.
- Custom reports by date, type of movement, branch office, etc.
- Export reports to pdf.
- Simple electronic billing.
- Support for billing numbers for the current fiscal year (according to the law).
- Manage financial entries.

****
