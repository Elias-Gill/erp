In the given document are present all the requirements for the ERP system.

1. [Inventory](#inventory)
   * [Requirements](#requirements)
     * [Notes](#notes)
2. [Sales](#sales)
   * [Requirements](#requirements)
3. [Security](#security)
   * [Requirements](#requirements)
4. [Providers](#providers)
   * [Requirements](#requirements)
5. [Employees](#employees)
6. [Finances](#finances)

****

# General requirements

- Easy to use.
- Expose robust api's for building external tools.
- "Easy" to extend in a source code level.
- Support a simple web UI.

# Modules

The system has to support 4 modules:

## Inventory

Module to manage the inventory on warehouse and sales center

### Requirements

- Support for multiple warehouses and sales centers and branchs.
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

### Requirements

- Manage pricing of the products
- Support for barcodes.
- Have support for special promotions, discounts and combos.
- Support paymethods:
  credit cards and cash.

## Security

Module to manage security acces, roles and passwords for employees.

### Requirements

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

NOTE:
orders don't affect finances directly, because the orders may change until the products arrive.
It is used as a "placeholder"

### Requirements

- Support for cataloges of providers
- Manage providers data
- Unsuscribe providers.
- Manage orders

## Employees

Module to manage employees data, salary, contract and simple productivity stats.
payment date, orders arrival, etc).

NOTE:
the system does not controles ins and outs of work.

- Manage employees data such as salary and contract.
- Fire employees
- Manage employee charges and roles
- Manage basic employees statistics such as faults, vacations, 

## Finances

TODO: // 
