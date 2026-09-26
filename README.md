# StockSense — Final Fixed Prototype

Inventory Management System prototype for the Odoo × LPU Hackathon.

## Run
Open `client/index.html` in a modern browser.

## Core workflows
- Authentication, signup and demo OTP password reset
- Dashboard KPIs and inventory alerts
- Product management
- Receipts with Save Draft / Validate Receipt
- Delivery Orders with Save Draft / Validate Delivery
- Internal Transfers with Save Draft / Validate Transfer
- Inventory Adjustments
- Stock Ledger / Move History
- Warehouses and locations
- SKU search and filters
- Reordering rules

## Receipt validation
Use **Operations → Receipts → New Receipt**. Enter supplier, product, quantity and destination, then click **✓ Validate Receipt**. The selected location stock increases immediately and a ledger movement is created.

The prototype stores demo data in browser LocalStorage; it is intended for hackathon demonstration and is not a production backend.
