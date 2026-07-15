# Smart POS Billing v0.2

*A lightweight POS billing system for small businesses.*

---

## Installation

### Option 1: Windows Installer (Recommended)

1. Download `SmartPOS_Billing_Setup_v0.2.exe`
2. Double-click the installer and follow the on-screen instructions
3. Once installed, launch **Smart POS Billing** from the Start Menu or Desktop shortcut
4. A browser window will open automatically — log in with the credentials below

### Option 2: Manual Setup (Portable / No Installer)

1. Install **Python 3.10 or later** from [python.org](https://python.org) (check "Add Python to PATH")
2. Extract the application folder to your preferred location
3. Double-click `install.bat` (one-time setup — installs dependencies + creates shortcut)
4. Double-click the **"Smart POS Billing"** desktop shortcut, or run `start.bat`

---

## First-Time Login

| Field | Value |
|-------|-------|
| **Username** | `admin` |
| **Password** | `smart@123` |

Change your password immediately after login: **Settings → Change Password**

---

## Activation

The app runs in trial mode with a 5-product limit. To unlock unlimited products and all features:

1. Go to **Settings → License / Activation**
2. Enter your license key (format: `SPOS-XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX`)
3. Click **Activate**

### How to get a License Key

Contact us via email with your purchase details:

📧 **smartgemtech@gmail.com**

---

## Using the App

### Billing
- Add products to cart with quantity +/-, discount %, tax %
- Change unit price directly in the cart
- Payment methods: Cash, Card, UPI, Credit
- Credit balance tracking per customer
- Barcode/QR scanning via device camera
- Prints receipt on sale completion

### Products
- Full product list with stock tracking
- Product categories management
- Bulk upload from CSV

### Customers
- Customer list with total spent and order count
- Credit balance per customer
- Purchase history viewer

### History
- Search by bill number, customer, or date range
- Filter by payment method
- Download bills as CSV

### Settings
- Store name, address, phone, GST, tax %, bill footer
- Change password
- Data export / import (full JSON backup)
- License key activation
- Help & Support contact

---

## Support

If you encounter any issues:

- **Activation problems** — email us your purchase details
- **License key not working** — send us a screenshot of the error
- **Installation issues** — describe the problem including any error messages

📧 **smartgemtech@gmail.com**

We aim to respond within 24 hours.

---

## Tips

- Back up your data regularly: **Settings → Data tools → Export backup**
- The server auto-creates backups in the `backups/` folder on every save
- HTTPS uses a self-signed certificate (generated automatically)
- Camera scanning requires HTTPS for non-localhost connections
