# Data Catalog of the datasets 

## Overview
The data sets are  structured to support analytical and reporting use cases. It consists of **4 Tables** which are **Orders** **Customers** **Location** and **Product**.

---

### 1.  **Orders**
- **Purpose:** Stores Orders details enriched with demographic and sales data.


| Column Name      | Data Type     | Description                                                                                   |
|------------------|---------------|-----------------------------------------------------------------------------------------------|
| Row ID           | INT           | Unique numerical identifier assigned to each lines.                                           |
| Order ID         | INT           | Unique numerical identifier assigned to each Orders.                                          |
| Order Date       | DATE          | The date when the orders record was created in the system                                     |
| Ship Date        | DATE          | The date when the orders is  ship to the customer                                             |
| Ship Mode        | STRING        | Type of class the product is transported (ex. First class)                                    |
| Customer ID      | STRING        | Unique identifier assigned to each Customers.                                                 |
| Segment          | STRING        | The segment (ex, Home Office, Comsumer, etc)                                                  |
| Postal Code      | INT           | Postal Code                                                                                   |
| Product ID       | INT           | Unique numerical identifier assigned to each Products.                                        |
| Sales            | FLOAT         | Sales                                                                                         |
| Quantity         | INT           | Quantity sold                                                                                 |
| Discount         | FLOAT         | Discount                                                                                      |
| Profit           | FLOAT         | Prodit made                                                                                   |

---

### 1.  **Customers**
- **Purpose:** Stores Customers details such as Name and Customer ID


| Column Name      | Data Type     | Description                                                                                   |
|------------------|---------------|-----------------------------------------------------------------------------------------------|
| Customer ID      | STRING        | Unique identifier assigned to each Customers.                                                 |
| Customer Name    | STRING        | Name of the customers                                                                         |

---

### 1.  **Location**
- **Purpose:** Provides geographical information


| Column Name      | Data Type     | Description                                                                                   |
|------------------|---------------|-----------------------------------------------------------------------------------------------|
| Postal Code      | INT           | Postal Code                                                                                   |
| City             | STRING        | City                                                                                          |
| State            | STRING        | State of the city                                                                             |
| Region           | STRING        | Region of the country (ex, South )                                                            |
| Country          | STRING        | Country                                                                                       |

---

### 1.  **Product**
- **Purpose:** Provides information about the product


| Column Name      | Data Type     | Description                                                                                   |
|------------------|---------------|-----------------------------------------------------------------------------------------------|
| Product ID       | STRING        | Unique identifier assigned to the product for internal tracking and referencing.              |
| Category         | STRING        | The broader classification of the product (ex, Furniature) to group related items.            |
| Sub-Category     | STRING        | A more detailed classification of the product within the category, such as product type.      |
| Product Name     | STRING        | Descriptive name of the product.                                                              |
 


