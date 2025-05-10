# Finals-Lab-Task-5-Using-SQL-views-and-Stored-Procedures-and-Stored-Functions

In this task, we explored the use of SQL Views, Stored Procedures, and Stored Functions to manage and manipulate database records more efficiently. After reviewing the lecture and practicing sample codes using hrd.sql, we applied our understanding by executing specific SQL statements on the inventory.sql database. This includes creating views to filter and compute product and vendor information, as well as defining a stored procedure and a function to update and retrieve data based on specific parameters.

# These are the guide given by our instructor:

### 1. CREATE A VIEW that will display the vendors_code, vendors name, product description p_indate, of all products with p_indate from 2002 onwards
- SQL Query Statements
![image](https://github.com/user-attachments/assets/36927489-7ef1-4e4d-92ab-c593fdcdd98c)

- Output
  
![Screenshot 2025-05-10 214424](https://github.com/user-attachments/assets/9aa0c0f2-51d0-477f-9740-c10ec4410320)

### 2. CREATE a VIEW that will display all products whose price range is between 100-150
- SQL Query Statements
![image](https://github.com/user-attachments/assets/5f6619b2-805e-4d8c-b862-61ac1642fdd7)

- Output

![Screenshot 2025-05-10 214606](https://github.com/user-attachments/assets/3d6d44c4-3333-4a0d-bc49-b1ae1a16d46d)

### 3. Create a VIEW that will COMPUTE for the (TOTAL_PRICE) of ALL PRODUCTS by getting the (P_ONHAND x P_PRICE) Sold by vendors with the following v_code (21344, 23119 and 24288)
- SQL Query Statements
![image](https://github.com/user-attachments/assets/a8e959b8-f62a-4072-ba2b-42820f9362de)

- Output

![Screenshot 2025-05-10 214716](https://github.com/user-attachments/assets/93acade7-4322-4f7b-b9bb-ed91ea7ce8d2)

### 4. CREATE a STORED PROCEDURE that WILL take a SINGLE PARAMETER and UPDATED the Name of Vendor ‘Bryson,Inc.’ to ‘Bryson and Co’.
- SQL Query Statement
![image](https://github.com/user-attachments/assets/b9820ee0-9aea-4ebe-8178-ab848a86b79a)

- Output

![image](https://github.com/user-attachments/assets/a66922e0-0aab-4535-946b-8f432e9dd6ba)

### 5. CREATE A Function that will take 2 parameters(v_code and v_state) and display All the product description and price based on the parameters passed to the function
- SQL Query Statement
![image](https://github.com/user-attachments/assets/ec0b3473-410d-499e-800f-2e0f100a9a22)

- Output

![image](https://github.com/user-attachments/assets/6930b09f-e425-4210-b0c1-5bd025929537)
