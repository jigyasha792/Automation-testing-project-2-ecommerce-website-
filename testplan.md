Test Plan: Add to Cart and Checkout Automation practise
1.Objective
To ensure that customers can add products to the cart, manage the items in the cart and checkout properly on this demo ecommerce website: https://automationexercise.com/

2.Scope
-Adding single/multiple products to cart
-Updating product quantity in cart
-Removing products from cart
-Cart persistence across pages
-Checkout flow for logged-in and guest users
-Order summary and price calculation accuracy
-Placing an order

3. Out of scope
-payment gateway
-product filtering
-login/register workflow

5. Environment
Application URL: https://automationexercise.com
Browser(s): Chrome (primary), Firefox (secondary, if time allows)
Test data: Dummy accounts and dummy address/payment info only

6. Test Strategy
-manual Functional testing first as exploratory testing
-Automated regression testing(playwright)
-Bug report for bugs found

8. Tools Used
-Manual execution: browser
-Bug tracking: GitHub Issues
-API testing: Postman, Playwright (API testing)
-Automation: Playwright + JavaScript
-Data validation: SQLite + SQL queries

9.Assumptions & Risks
-Site is a public demo/training site — behavior may change without notice
-No real payment processing will be tested
-Some features (e.g. persistent cart across sessions) may behave differently than a production app

