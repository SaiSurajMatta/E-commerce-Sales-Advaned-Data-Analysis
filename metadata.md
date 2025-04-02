# Dataset Metadata

## 1. `products.csv`

- **Description**: Contains product catalog data.
- **Number of Rows**: 70  
- **Number of Columns**: 6  
- **Columns**:
  - `Product_ID` *(int)* – Unique identifier for each product
  - `Product_Name` *(str)* – Name of the product
  - `Category` *(str)* – Type/category of the product (e.g., Soft Toys, Plants)
  - `Price (INR)` *(int)* – Price in Indian Rupees
  - `Occasion` *(str)* – Occasion the product is suited for
  - `Description` *(str)* – Short description of the product
- **Sample**:
  ```json
  [
    {"Product_ID": 1, "Product_Name": "Magnam Set", "Category": "Soft Toys", "Price (INR)": 1935, "Occasion": "All Occasions", "Description": "Quam numquam iste sunt nemo."}
  ]
  ```

---

## 2. `orders.csv`

- **Description**: Contains transactional order data.
- **Number of Rows**: 1000  
- **Number of Columns**: 10  
- **Columns**:
  - `Order_ID` *(int)* – Unique identifier for each order
  - `Customer_ID` *(str)* – ID of the customer who placed the order
  - `Product_ID` *(int)* – Product being ordered
  - `Quantity` *(int)* – Number of units ordered
  - `Order_Date` *(str)* – Date of order (DD-MM-YYYY)
  - `Order_Time` *(str)* – Time of order (HH:MM:SS)
  - `Delivery_Date` *(str)* – Scheduled delivery date
  - `Delivery_Time` *(str)* – Scheduled delivery time
  - `Location` *(str)* – Delivery location
  - `Occasion` *(str)* – Occasion associated with the order
- **Sample**:
  ```json
  [
    {"Order_ID": 1, "Customer_ID": "C037", "Product_ID": 67, "Quantity": 5, "Order_Date": "24-02-2023", "Delivery_Date": "05-03-2023", "Location": "Bardhaman", "Occasion": "Anniversary"}
  ]
  ```

---

## 3. `customers.csv`

- **Description**: Contains information about customers.
- **Number of Rows**: 100  
- **Number of Columns**: 7  
- **Columns**:
  - `Customer_ID` *(str)* – Unique identifier for each customer
  - `Name` *(str)* – Customer’s full name
  - `City` *(str)* – City of residence
  - `Contact_Number` *(int)* – Phone number
  - `Email` *(str)* – Email address
  - `Gender` *(str)* – Gender of the customer
  - `Address` *(str)* – Full address
- **Sample**:
  ```json
  [
    {"Customer_ID": "C001", "Name": "Tara Krishnan", "City": "Panchkula", "Contact_Number": 917193971454, "Email": "mandrati@chad.org", "Gender": "Female"}
  ]
  ```
