# DAX Measures — Retail Sales Dashboard

These are the custom DAX measures written for the Power BI sales dashboard.
Assisted and validated using Microsoft Copilot during development.

---

## Revenue Measures

### Total Revenue
```DAX
Total Revenue = SUMX(order_items, order_items[quantity] * order_items[unit_price])
