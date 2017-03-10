# Simple shopping cart system
•	Our system will contain a web application with its supporting database
•	The database will have several tables according to the database diagram
•	The backend will use extensive object oriented programing to allow easy modifications, and interaction between components (product, user, cart, etc.)
•	A MVC design pattern will be used and enforced since the system will be accessed from the web and mobile applications at least and code duplication is not an option
•	We will use a caching system for pages like the product detail except the section related to the product availability which will be dynamic according to real data
•	Secure connections will be used as soon as we are in the checkout process or profile information
•	On the main page, we will show a list of the featured products and options to browse the rest by categories and a search field. There will be also the possibility to login for extra options related to the user. If the user is authenticated, we could show a list of items based on the last purchases.
•	The product detail page will have options to add items to the shopping cart either by incrementing what’s already in the cart for that item or by specifying a quantity. A product could be “followed” by an authenticated user to receive notifications if the item is on sale, if the inventory changes, etc.
•	If the user is not authenticated a session based shopping cart will be used and all the information (products, quantity, etc.) will be persisted in the user’s browser through cookies or a similar alternative
•	If the user is authenticated the cart will be persisted for this user on the database
•	If the user is authenticated, the user page will be available and it will contain options such as purchase history, order status, profile management, etc.
•	The shopping cart page will list all the items and the quantity specified by the user
•	At every step of the checkout process we check the inventory to alert the client if there’s no stock for certain items
