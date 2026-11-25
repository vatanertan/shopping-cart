# Shopping Cart

A desktop shopping cart management application built with Python and PyQt5. It provides an interactive graphical user interface (GUI) for managing cart items, calculating multi-tier discounts, and applying one-time promotional coupon codes.

## Features

- **Cart Item Management:** Add or remove items with real-time input validation for product names, integer quantities, and unit prices.
- **Special Offer Highlighting:** Automatically identifies and marks eligible promotional items (`*`) in the cart view.
- **Dynamic Discount Engine:**
  - **Bulk Discount:** Applies a 10% discount on items with a quantity greater than 3.
  - **Special Offer Discount:** Applies an additional 5% discount on designated special offer items.
- **One-Time Coupon System:** Supports promotional codes (`WELCOME10`, `SAVE20`, `MEGA25`) while tracking redeemed codes to prevent duplicate usage.
- **Cart Summary:** Displays unique item count, total quantity, pre-discount subtotal, and special offer item count.

## Project Structure

```text
shopping-cart/
├── shopping_cart.py
├── requirements.txt
├── .gitignore
└── README.md
```

## Prerequisites

- Python 3.x
- PyQt5

## Installation & Usage

1. Install the required dependency:
   ```bash
   pip install -r requirements.txt
   ```

2. Launch the application:
   ```bash
   python shopping_cart.py
   ```
