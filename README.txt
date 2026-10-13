THE WAFFLE CO. — STATIC WEBSITE DEPLOY PACKAGE

Included:
- index.html: existing ordering prototype, preserved from the previous project.

CURRENT SETTINGS IN THE PROTOTYPE
- Fixed delivery fee: INR 50 per delivery order
- Takeaway: no delivery fee
- Delivery radius: 10 km (address must be manually verified by staff; not geofenced automatically)
- Payment choices: Cash and Online UPI preference (payment gateway is NOT connected)
- Order submission: creates a local summary in the browser only; does NOT save orders to a database or notify the shop.
- Automatic WhatsApp API notifications: NOT connected yet.

DEPLOY TO VERCEL (FREE URL FIRST)
1. Sign in to https://vercel.com/ or create an account.
2. Create a new GitHub repository named the-waffle-co-ordering.
3. Upload index.html from this package to the repository root and commit it.
4. In Vercel, choose Add New -> Project, import the GitHub repository.
5. For this static HTML prototype, no framework/build command is needed. If prompted, leave Build Command and Output Directory empty/default and deploy.
6. Open the generated *.vercel.app URL on a phone and test menu, cart, delivery/takeaway selection, and totals.

IMPORTANT BEFORE ACCEPTING REAL CUSTOMER ORDERS
This package is a front-end prototype, not a production ordering system. Do not advertise payment as working. To go live for real orders, next add a managed backend/database, server-side order validation, secure online payment gateway, and WhatsApp Business Platform integration. API secrets must be stored as server environment variables, never in index.html. The 10 km delivery limit currently requires manual staff verification.

Before launch, confirm the menu, item prices, shop contact details, delivery area, and terms are correct.
