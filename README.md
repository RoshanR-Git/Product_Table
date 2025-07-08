# Product Table
## Date: 08.07.2025
## Objective:

To create a structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes.

## Tasks:

### 1. Set Up the Basic HTML Structure:

Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document layout.

Include a ```<title>``` such as "Product Table".

### 2. Create a Table Element:

Use the ```<table>``` tag to begin the product table.

### 3. Add a Table Header:

Use the ```<thead>``` section with a ```<tr>``` row and three ```<th>``` elements:

Product Name

Product Price

Description

### 4. Insert Table Body Rows:

Use the ```<tbody>``` section with multiple ```<tr>``` rows.

In each row, use three ```<td>``` cells for:

The name of the product (e.g., Laptop, Phone)

The price (e.g., ₹45,000, $499)

A short description (e.g., "High-speed performance", "Budget-friendly")

### 5. Ensure Semantic Structure:

Include ```<caption>``` if needed to describe the table purpose.

Use meaningful text inside the table for clarity.

### 6. No CSS or JavaScript:

Keep the table design strictly in HTML for simplicity.
## HTML Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href = "style.css">
</head>
    <body>
        <h1>Product Table</h1>
        <table border="1" cellpadding="2">
            <thead>
                <tr>
                    <th>Product Name</th>
                    <th>Product Price</th>
                    <th>Description</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Laptop</td>
                    <td>$45,000</td>
                    <td>High-speed performance</td>
                </tr>
                <tr>
                    <td>Phone</td>
                    <td>$499</td>
                    <td>Budget-friendly</td>
                </tr>
                <tr>
                    <td>Wireless Earbuds</td>
                    <td>₹2,499</td>
                    <td>Compact design with noise cancellation</td>
                </tr>
                <tr>
                    <td>Smartwatch</td>
                    <td>₹3,999</td>
                    <td>Fitness tracking and notification alerts</td>
                </tr>
            </tbody>
        </table>
    </body>
</html>
```
##CSS Code:
```
body {
  background-color: #f9f9f9;
  font-family: 'Times New Roman', Times, serif;
}

h1 {
  text-align: center;
  margin-bottom: 20px;
}

table {
  border-collapse: collapse;
  margin: auto;
  width: 80%;
}

caption {
  caption-side: top;
  font-weight: bold;
  margin-bottom: 10px;
  text-align: center;
  font-size: 1.2rem;
}

thead th {
  background-color: #4CAF50;
  color: white;
  text-align: center;
  padding: 12px;
}

td {
  border: 1px solid #ddd;
  padding: 12px;
  text-align: center;
}

tr:hover {
  background-color: cyan;
}

tbody tr:nth-child(even) {
  background-color: #f9f9f9;
}
```
## Output:
![Screenshot 2025-07-07 223303](https://github.com/user-attachments/assets/ef098c66-3d9a-4c65-96c2-73b9860cb8e6)

![Screenshot 2025-07-08 120910](https://github.com/user-attachments/assets/ecc3346b-6bcb-4ba5-98e7-4b0abcad9d23)

## Live Web Page:
https://roshanr-git.github.io/Product_Table/

## Result:
A structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes is created successfully.
