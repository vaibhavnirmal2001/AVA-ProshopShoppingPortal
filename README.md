
# AVA-ProshopShoppingPortal

 In this project, we developed the website which is basically focused on the user who wants to purchase items from anywhere using internet.
It is an online store that enables website owners to sell their product online.
The features of this application are: 

•	It provides customer friendly and easy to understand interface. 

•	Any member can register and view available products. 

•	Only registered member can purchase multiple products regardless of quantity. 

•	There are three roles available: Visitor, User and Admin. 

• Visitor can view available products. 

• User can view and purchase products. 

• An Admin has some extra privilege including all privilege of visitor and user. 

•	It also provides payment system for the customer to pay for their bills easily. It has an admin interface to monitor the users and their activities. The Server process the customers and the items are shipped to the address submitted by them.

**User interface contains:**

1.	Home page: A search bar is present at the top which allows to make a search about any product. It contains a cart button which directs to shopping cart page, a profile button which directs to user profile page. It also contains a carousel below the nav bar which displays the trending and best seller products. The section below it contains information about the products available to be sold.

2.	Product information page: After selecting and clicking on a product on home page, user is directed on that product’s page which contains name, rating, price, description about the product, a review section where a (logged in) user can leave a review about the product (if purchased). It also contains a chart on the right-side showing price, status (in stock or not), quantity (available), and a button to add that product to users shopping cart.

3.	Shopping cart page: It contains all the information about the products added by the user to the shopping cart including its price and quantity. On the right side of the page, it shows the no. of total products in the cart and the total price of all the products in the cart. It also contains a payment checkout button which directs user to shipping page if the user is already signed in or else it directs to sign in page and after signing in user is directed to shipping page.

4.	Shipping page: User is asked to fill their personal details about the address and after clicking on continue button user is directed to place order page

5.	Place order page: It contains information about user including name, email address, address, status of the product (delivered or not), status of payment (paid or not), order items (name and quantity of items ordered) and on the right side of the page there is a chart containing the order summary including cost of item, shipping charges, tax 
charges and the total cost. The chart also contains two options for user to pay for their order i.e., by PayPal method or through debit or credit card.

6.	Payment method (using credit or debit card) page:  It contains the status of payment (paid or not), order items containing information about the items. Ther is another section for filling details about the card for user and proceeding to pay.

7.	PayPal System page: It contains a user interface with an empty field for user to fill. It contains 2 choices for user to proceed, one by email and the other by mobile no. There is also a create account button in case user doesn’t have an account on PayPal.

8.	User profile: User profile contains information about user viz. name of user, email address of user and password and a confirm password field. The user can change this information by making changes in respective field and updating the information using the update button. The user can view the orders placed and the history of his/her orders along with the status of order and payment and can check more details about the order if he/she wants to.

9.	Extra feature: The user can access to the nav bar from any page which contains a PROSHOP logo which redirects the user to the home page by just clicking on it. This nav bar also contains a search button to search of items, cart button to check cart and a profile button to visit the profile page.

**Admin interface contains:**
1.	Home page: Admin home page is just like user home page except on admin home page there is an admin button leading to user management page, product management page and order management page.
2.	User management page: In this page, the admin can see the number of users and other admins on the website. The page also contains id, name and email address of other users. The admin can edit details of and delete other users and admins, can make a user admin and vice versa.
3.	Product Management page: It contains details about all the products available on website including product’s id, name, price, category and brand. The admin also has a feature to create a new product, delete an existing product or edit the details of existing products.


4.	Order management page: It contains all the orders made by the users with the order’s detail information including id of order, name of user who ordered, date on which the product was ordered, total cost of order, status of payment and delivery of order. The user can further check for more details of a particular order.
# 2.4 MERN Stack
MERN Stack is a collection of powerful technologies and robust, used to develop scalable master web applications comprising backend, front-end, and database components. It is JavaScript that is used for the faster and easier development of full-stack web applications. MERN Stack is a technology that is a user-friendly full-stack JavaScript framework for building applications and dynamic websites.

**MERN Stack consists of four main components or can say four main technologies:**

1.	M stands for MongoDB (Database), mainly used for preparing document database and is a NoSQL (Non-Structured Query Language) Database System
2.	E stands for Express, mainly used for developing Node.js web framework
3.	R stands for React, mainly used for developing a client-side JavaScript framework
4.	N stands for js, mainly used for developing the premier JavaScript web server
Each of these four technologies plays an important role in providing an end-to-end framework for the developers. Even these four technologies play an important role in the development process of web applications.

# 2.5 Mongo DB
o	It is the most popular NoSQL (NoSQL or Non-Structured Query Language) database, an open-source document-oriented database.
o	The term 'NoSQL' typically means a non-relational database that does not require a fixed schema or proper relational tables to store the necessary data in it. MongoDB stores the data in a different format other than the relational tables, consisting of rows and columns.
o	The storage format in which the data is stored is known as BSON, which stands for Binary JavaScript Object Notation; MongoDB uses BSON when storing documents in collections.
o	It allows a highly scalable and flexible document structure.
o	It is very faster as compared to RDBMS due to its efficient storage and indexing techniques.
o	MongoDB uses JavaScript for coding as a language which is one of the great advantages.
o	It is Schema less as any data stored which is stored in a separate document.
o	MongoDB is a NoSQL database that scales by adding more and more servers and increases productivity with its flexible document model.


# 2.6 Express Js
o	Express is a JavaScript server-side framework that runs within js.
o	It is one of the best backend development JavaScript Frameworks.
o	It provides the developer with a platform to create and maintain robust servers.
o	Express is used for building and designing web and mobile applications easily and quickly.
o	Express is very easy to connect with Databases like MongoDB.
o	Based on HTTP methods and URLs, Express allows you to define the routes of your application.
o	With its built-in router, it promotes code reusability.
o	If we want to understand the architecture behind web servers and their working along with the organization, then learning Express is the best option.

# 2.7 React Js
o	React is one of the most popular open-source front-end JavaScript libraries used for building Web applications.
o	Before using react, it has some prerequisites that one should follow, that you must download Node packages in your system with their latest versions. Also, you must have an understanding of HTML, CSS and JavaScript.
o	It is used to build user interfaces, especially for a single page web application.
o	It allows us to create reusable UI (User Interface) components.
o	It allows developers to create large web applications that can easily change the data of the page even without reloading the page.
o	The main objective of reacting is that it only works on user interfaces in the application, whether mobile or web.
o	It is very fast, simple and scalable.
o	React is also used with a combination of other JavaScript libraries or frameworks.
o	There are a lot of open-source platforms that are also used to make the front-end web and mobile applications easier, like Angular js in MVC. Now, most developers are using the MERN stack in which react is used; the main reason is that it is very fast and has more advantages over other front-end frameworks.





# 2.8 Node js
o	js is an open-source server environment, and it is a cross-platform runtime environment for executing JavaScript code outside a browser.

o	js is not a programming language, and even it is not a framework.
o	It is often used for building and developing numerous backend services like net applications, mobile applications.
o	Massive corporations principally utilize it in production like Uber, PayPal, Netflix,
o	It may be a free ASCII text file platform and may be utilized by anybody.
o	It is incredibly simple to urge started with it and may even be used for agile development and prototyping.
o	It provides extremely ascendable and really quick services to the users.
o	It is incredibly consistent and may be used as an ASCII text file cleaner.
o	It continuously uses JavaScript; thus, it's ultimately helpful for a computer user to quickly create any net service or any net or mobile application.
o	It provides a massive system for any ASCII text file library.
o	It contains a non-blocking or, can say, Asynchronous nature.


# Advantages of MERN Stack
1.	For a smooth development of any web application or mobile app, it supports MVC (Model View Controller) architecture; the main purpose of this architecture is to separate the presentation details with the business logic.
2.	It covers all the web development stages starting from front-end development to backend development with JavaScript.
3.	It is an open-source framework mainly used to develop web-based or mobile applications and is supported by the community.
4.	It is very fast and efficient compared to MEAN Stack and mostly suitable for small applications, whereas MEAN Stack is suitable for developing large applications.






# 2.9 Redux
Redux is a predictable state container for JavaScript apps. It helps you write applications that behave consistently, run in different environments (client, server, and native), and are easy to test. 
Redux is an open-source JavaScript library used to manage application state. React uses Redux for building the user interface. 
Redux is the official React binding for Redux. It allows React components to read data from a Redux Store, and dispatch Actions to the Store to update data. Redux helps apps to scale by providing a sensible way to manage state through a unidirectional data flow model. React Redux is conceptually simple. It subscribes to the Redux store, checks to see if the data which your component wants have changed, and re-renders your component.
o	React Redux is the official UI bindings for react Application. It is kept up-to-date with any API changes to ensure that your React components behave as expected.
o	It encourages good 'React' architecture.
o	It implements many performance optimizations internally, which allows to components re-render only when it actually needs.

# 4.2. Future Scope
The following section discusses the work that will be implemented with future releases of the software. 
1. Detailed categories: Future work could involve adding more categories which are more detailed and have additional items.
 2. Watch/Wish List: Work can add a watch list or wish list so that users can add an item to a list to watch for item prices to go down or to see when there is a sale on any of those items. 
3. Enhanced User Interface: Work on enhancing the user interface by adding more user interactive features. 
4. Recommended Items: Add a bar that would display the most-recommended items which would depend on the number of times an item has been purchased by any users.

5. Payment Options: Add different payment options, such as Visa, MasterCard, PayPal, etc., where a user can also save the card information for later checkouts.
 6. Shipping Options: Add different types of shipping options: regular shipping, expedited shipping, international shipping, etc. 
7. Recent History: Display the user’s recently browsed items in the recent-history tab

