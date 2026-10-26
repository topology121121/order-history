# Request: choose a layout for "My orders" on phones

**From:** Product team
**To:** Frontend

Our "My orders" screen is moving to the mobile web app, and we have two candidate layouts on separate branches:

- `layout/scroll-table`: a compact table that scrolls sideways
- `layout/stacked-cards`: one card per order

Please test both and recommend one. Write the decision up in `layout-decision.md` on `main` so design and support can refer to it.

## What matters most (from support tickets)
1. **Order status.** Most calls are "where is my order?". Customers need to see the status of each order without hunting for it.
2. **Long IDs.** Customers read out order IDs to support and copy tracking numbers into courier websites, so IDs must be readable in full and selectable.
3. **Small phones.** Many customers use small or older Android phones. Please check at **320px, 375px and 414px** wide.

The screen shows a customer's 8 most recent orders. All data in both branches is synthetic.
