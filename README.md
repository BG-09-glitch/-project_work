# -project_work
In an e-commerce website, various actors (users and systems) interact with the platform to perform specific actions (use cases). Below are the primary actors and key use cases involved in an e-commerce system.
Primary Actors:
1. Customer (Buyer)
   - The primary user who browses products, adds them to the cart, and completes the purchase.
   
2. Administrator(Admin)
   - The person responsible for managing the website, overseeing products, orders, and customer interactions.

3. Seller (Vendor)
   - If the platform supports multiple sellers (marketplace model), the seller is the individual or business listing products for sale on the site.

4. Guest User
   - A user who browses the website without creating an account or logging in. They can add items to the cart but might need to create an account for checkout.

5. Payment Gateway
   - External service responsible for handling financial transactions, including credit card payments and other online payment systems.

6. Shipping Provider
   - External service responsible for delivering the purchased items to customers.

7. Support Team
   - Provides customer service, managing issues like order disputes, returns, and inquiries.

8. Inventory Management System
   - Handles stock management and keeps track of product availability in real-time.


Use Cases:

1. Customer (Buyer) Use Cases
   - Browse Products: Customers search for products using filters (category, price, brand, etc.) and view product details.
   - View Product Details: Customers can view detailed descriptions, images, prices, and reviews of individual products.
   - Register/Sign In: Customers can create an account or log in to track orders, manage personal details, and save favorite items.
   - Add to Cart: Customers can add selected items to the shopping cart for checkout.
   - Apply Discount/Coupons: Customers can apply promotional codes or discounts to reduce the order total.
   - Checkout: The process where customers review their cart, enter shipping information, and proceed with payment.
   - Select Payment Method: Customers choose a payment method (credit card, PayPal, etc.) during checkout.
   - Track Orders: After completing a purchase, customers can track the status of their orders (processing, shipped, delivered).
   - Write Product Reviews: Customers can leave reviews or ratings for products they have purchased.
   - Return/Refund Requests: If dissatisfied with a product, customers can initiate returns or refund requests.
   - View Order History: Customers can view past orders, including details and statuses.

2. Administrator (Admin) Use Cases
   - Manage Products: Admin can add, edit, or remove products from the inventory. This includes updating product descriptions, prices, images, and stock levels.
   - Manage Categories: Admin can organize products into categories for easier navigation.
   - Manage Orders: Admin can view and update the status of customer orders (processing, shipped, delivered).
   - Manage Payments: Admin monitors payments, handles payment failures, and ensures the proper processing of funds.
   - Manage Users: Admin can view and manage customer accounts, including permissions, suspensions, or deleting users.
   - Generate Reports: Admin can generate sales reports, order summaries, and inventory reports to monitor business performance.
   - Manage Discounts/Promotions: Admin can create and manage promotional campaigns, discounts, and coupon codes.
   - Customer Support: Admin manages customer inquiries and complaints, providing solutions and support.

 3. Seller (Vendor) Use Cases (if applicable)
   - Add Products: Sellers can add their products to the website, including descriptions, images, and pricing.
   - Update Product Information: Sellers can update stock levels, prices, and product descriptions.
   - Manage Orders: Sellers can view, fulfill, and manage customer orders, including updating order status (shipped, out of stock).
   - Manage Reviews: Sellers can respond to customer reviews and address any concerns.
   - View Sales Reports: Sellers can generate reports on their sales, inventory, and customer engagement.

4. Guest User Use Cases
   - Browse Products: Guests can search and view products but cannot make a purchase unless registered or signed in.
   - Add to Cart: Guests can add items to the cart but need to log in or register to proceed with checkout.

 5. Payment Gateway Use Cases
   - Process Payments: The payment gateway handles transactions by processing payments through various methods (credit cards, PayPal, etc.).
   - Confirm Payment: After successful payment, the payment gateway confirms the transaction and notifies the system.
   - Handle Payment Failures: If a payment fails, the gateway informs the user and the system for resolution.
   
6. Shipping Provider Use Cases
   - Generate Shipping Labels: The shipping provider generates shipping labels based on the customer’s address and package details.
   - Track Shipments: Shipping providers provide tracking information to update the status of the delivery.
   - Calculate Shipping Costs: Shipping providers calculate shipping costs based on the destination, weight, and size of the order.

7. Support Team Use Cases
   - Handle Customer Queries: The support team responds to customer inquiries, including order status, product details, and returns.
   - Process Returns/Exchanges: The support team manages return or exchange requests, including validating conditions and issuing refunds.
   - Resolve Dispute: In case of issues like order discrepancies or disputes, the support team intervenes and resolves them.

8. Inventory Management System Use Cases
   - Track Stock Levels: The system automatically updates the stock levels as customers purchase products.
   - Alert Admin for Low Stock: When stock levels fall below a threshold, the system notifies the admin to restock the items.
   - Sync with Product Listings: The inventory system ensures that only available products are displayed on the website.



Summary of Actors and Use Cases:
| Actor                | Key Use Cases                                                                                                                                     |
|--------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| Customer (Buyer)      | Browse products, add to cart, register/sign in, checkout, apply discounts, track orders, write reviews, initiate returns/refunds, view order history |
| Administrator (Admin) | Manage products, categories, orders, payments, users, reports, promotions, customer support                                                           |
| Seller(Vendor)       | Add/update products, manage orders, respond to reviews, view sales reports                                                                            |
| Guest User            | Browse products, add to cart (but must register to complete checkout)                                                                               |
| Payment Gateway      | Process and confirm payments, handle payment failures                                                                                               |
| Shipping Provider   | Generate labels, track shipments, calculate shipping costs                                                                                          |
| Support Team          | Handle customer queries, process returns/exchanges, resolve disputes                                                                                |
| Inventory System      | Track stock levels, alert for low stock, sync with product listings                                                                                 |

These use cases capture the core interactions and features of an e-commerce website, ensuring a smooth experience for all stakeholders involved.
