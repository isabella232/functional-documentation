# Back-office shop metrics & data

## Description

Back-office shop metrics & data are a collection of informations found among multiple pages in the back-office of PrestaShop software. They provide data & pre-calculated metrics on various topics such as customers, products or orders.

## Metrics & data

### Customers

#### Main country

Displays the country from which most customers order on the shop over a specific timeframe

> example : If 10 out of 15 customers' order are from France over the last 30 days, displays **France**

#### Customer main gender

Displays the main gender of the shop's customers as a percentage

> example : if 70 out of 100 customers are female, displays **70% female customers**

#### Average customer age

Displays the average age of the shop's customers. This metric doesn't take in account customers whom haven't input a birthdate.

> example : if a shop has 5 customers, 3 having input their respective ages of 20, 30 and 40, and 2 without an age, displays the average of the 3 ages : **30** **years**

#### Newsletter registration

Displays the total number of customers subscribed to the shop's newsletter

> example : if a shop has 10 customers but only 5 subscribed to the newsletter, displays **5**&#x20;

#### Order per customer

Displays the average number of order per active customers on the shop.\
Only orders with the following status are counted toward this metric :&#x20;

* Processing in progress
* Payment accepted
* Remote payment accepted
* Shipped
* Delivered

> example : if 5 orders were delivered and the shop has 10 customers, displays **0.5**

### Customer relationship

#### Pending message

Displays the total number of unanswered customer messages.

> example : if 5 customer have sent a message relative to their orders and the shop admin has answered 3 of them, displays **2**&#x20;

#### Average message response time

Displays the average response time to customers' messages over a specific timeframe. Response time are calculated by looking at the timestamp difference between a customer's message and the following shop admin's message.

> example : if customers sent 3 messages over the last 30 days and the shop admin took 1 hour, 2 hours and 3 hours to answer each of them respectively, displays **2 hours**

#### Message per thread

Displays the average number of messages per closed thread over a specific timeframe.

> example : if 3 messages threads were closed over the last 30 days, with 5, 10 and 15 messages respectively, displays **10**

### Carts and orders

#### Conversion rate

Displays the percentage of visits that ended in an order for a specific timeframe. The formula is :&#x20;

```php
100*nbOrders/nbVisitors
```

Only orders with the following statuts are counted for this metric :&#x20;

* Processing in progress
* Payment accepted
* Remote payment accepted
* Shipped
* Delivered

> example : if there was a total of 10 visitors over the last 30 days and a total of 4 orders over the same period of time, displays **40%**

#### Abandonned cart

Displays the number of abandonned cart over a specific timeframe. A cart is considered abandonned if a visitor created a cart but did not complete the order by end of the timeframe.

> example : if a visitor put a pair of socks in their cart but did not complete the order and left the shop, displays **1**&#x20;

#### **Netprofit visit**

Displays the average net profit per visitors over a specific timeframe.

> example : if the shop has a total net profit of 100€ over the last 30 days and a total of 10 visitors over the same period of time, displays **€10**&#x20;

#### **Average order value**

Displays the average monetary value of orders over a specific timeframe. Unlike other metrics, this one does not take the status of the orders into account.

> example : if the shop has 3 orders with respective monetary values of €30, €50 and €100, displays **€60**

### **Products and categories**

#### **Product per category**

Displays the average number of products per category of the shop.

> example : if the shop has a 100 products and 5 categories, displays **20**

#### **Disabled products**

Displays the percentage of disabled products relative to the total number of products in the shop.

> example : if the shop has 10 products and 4 of those are disabled, displays **40%**

**Disabled categories**

Displays the number of disabled product categories of the shop.

> example : if the shop has 10 product categories and 3 of those are disabled, displays **3**.

#### Empty categories

Displays the number of empty product categories of the shop.

> example : if the shop has 10 product categories and 3 of those are disabled, displays **3**.

#### Top category

Displays the category with the best sales over a specific timeframe

> example : if the shop's product category with the best sales over the last 30 days is Art, displays **Art**

### Shop and modules

#### Enabled languages

Displays the number of active languages of a shop

> example : if a shop has french and english as active languages, displays **2**

#### Installed modules

Displays the number of installed modules on the shop, counting enabled and disabled modules alike.

> example : if a shop has 10 enabled modules and 5 disabled modules, displays **15**

#### Disabled modules

Displays the number of disabled modules on the shop.

> example : if a shop has 10 enabled modules and 5 disabled modules, displays **5**

#### Update modules

Displays the number of module to update on the shop.

> example : if a shop has 15 enabled modules and 8 modules can be updated, displays **8**
