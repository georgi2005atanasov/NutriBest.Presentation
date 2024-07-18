# NutriBest.Presentation
A web application for selling fitness supplements, developed using C# ASP.NET Web API and React.

<h2>Admin Panel Functionalities</h2>

<h3>CRUD Operations</h3>
<ul>
    <li><strong>Products:</strong> Create, read, update, and delete product entries.</li>
    <li><strong>Promotions:</strong> Manage promotional campaigns and offers.</li>
    <li><strong>Promo Codes:</strong> Generate and delete discount codes.</li>
    <li><strong>Flavours:</strong> Add and remove flavor options.</li>
    <li><strong>Categories:</strong> Organize and manage product categories.</li>
    <li><strong>Brands:</strong> Manage brand information and relationships.</li>
    <li><strong>Shipping Discounts:</strong> Set and manage discounts on shipping.</li>
</ul>

<h3>Reports and Analytics</h3>
<ul>
    <li><strong>Order-Based Reports:</strong> Visualize top categories, products, brands, and flavours through interactive charts.</li>
    <li><strong>Date Filtering:</strong> Apply start and end date filters to refine report data.</li>
    <li><strong>Demographic Reports:</strong> Analyze best-selling towns and countries with date filters for precise insights.</li>
</ul>

<h3>User Monitoring</h3>
<ul>
    <li><strong>Live User Tracking:</strong> View real-time user activity across different routes within the application.</li>
</ul>

<h3>Notifications via SignalR</h3>
<ul>
    <li><strong>Order Notifications:</strong> Receive alerts when an order is made or confirmed.</li>
    <li><strong>Inventory Alerts:</strong> Get notified when product quantities are low (notifications stored).</li>
    <li><strong>Newsletter:</strong> Get notified when user signs up for the Newsletter.</li>
</ul>

<h3>Simple Layouts for Management</h3>
<ul>
    <li><strong>Categories, Brands, Flavours:</strong> Manage these entities through straightforward interfaces.</li>
</ul>

<h3>Order Management Layout</h3>
<ul>
    <li><strong>Filters:</strong> Filter orders by date, status (finished, shipped, confirmed, paid), and search by order ID, phone number, or customer name.</li>
</ul>

<h3>User Management Layout</h3>
<ul>
    <li><strong>Filters:</strong> Sort users by all, with orders, or without orders.</li>
    <li><strong>Search Bar:</strong> Search by email, city, name, phone number, username, or user role.</li>
    <li><strong>Role Assignment:</strong> Grant users different roles, such as employee.</li>
    <li><strong>User Details:</strong> View detailed user activity, total money spent, order count, and send promo codes.</li>
    <li><strong>User Deletion:</strong> Remove user profiles as needed.</li>
    <li><strong>Restoring Profiles:</strong>Deleted profiles can be restored.</li>
</ul>

<h3>Export Functionality</h3>
<ul>
    <li><strong>CSV Export:</strong> Export data for categories, products, flavours, packages, reports, brands, newsletter list, profiles, orders, promotions, promo codes, and shipping discounts.</li>
</ul>

<h3>Newsletter Management Layout</h3>
<ul>
    <li><strong>Filters:</strong> Filter users by those with orders, without orders, or anonymous users.</li>
    <li><strong>Search Bar:</strong> Search by order ID, phone, or customer name.</li>
    <li><strong>Email Sending:</strong> Send emails or promo codes to all users or specific groups.</li>
</ul>

<h3>Email Notifications</h3>
<ul>
    <li><strong>Admin Alerts:</strong> Receive emails when an order is made or confirmed.</li>
</ul>


<h2>User Functionalities</h2>

<ul>
    <li><strong>Login and Registration:</strong> Register, login, logout, and reset password via email.</li>
    <li><strong>Profile Management:</strong> Set profile details (email, name, username, age, gender) and address for automatic order form filling.</li>
    <li><strong>Shopping Cart:</strong> Add, remove, and set products in the cart.</li>
    <li><strong>Cart Management:</strong> Adjust product quantities and apply promo codes.</li>
    <li><strong>Order Creation:</strong> Create orders.</li>
    <li><strong>Shipping Discounts:</strong> Pop-up container with products to fulfill shipping discount minimum price.</li>
    <li><strong>Newsletter Subscription:</strong> Sign up for the newsletter and receive promo codes.</li>
    <li><strong>Product Details:</strong> View product details with related products.</li>
    <li><strong>Product Filters:</strong> Filter products by category, price, alphabetical order, brand, flavour, grams, and search text.</li>
    <li><strong>Home Page:</strong> Includes About Us, Contact Us, Newest Products, and Shop Now sections.</li>
    <li><strong>Brand and Category Layouts:</strong> Display different brands and categories.</li>
    <li><strong>Order Management:</strong> Create orders with invoice options and two payment methods (Cash on Delivery, Bank Transfer).</li>
    <li><strong>Order Details Page:</strong> View order details, including address, name, phone number, payment method, order status, purchased products, and their count.</li>
    <li><strong>Order Confirmation:</strong> Confirm order through email.</li>
    <li><strong>Anonymous Orders:</strong> Store orders as cookies for anonymous users and display in <strong>My Orders</strong> for authenticated users.</li>
</ul>

<h2>Additional Points</h2>
<ul>
    <li><strong>Pagination:</strong> Implemented where needed for efficient data navigation.</li>
    <li><strong>Caching:</strong> Cache on the home page has been applied.</li>
</ul>
