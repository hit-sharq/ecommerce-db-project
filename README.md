# E-commerce Database Design

This project contains the design and implementation of an e-commerce database schema. The schema is designed to manage products, brands, categories, variations, attributes, and related entities for an e-commerce platform.

## Database Schema

The schema is defined in the `ecommerce.sql` file, which includes the following tables:

- `brand`: Stores brand information.
- `product_category`: Classifies products into categories.
- `product`: Stores general product details.
- `color`: Manages available color options.
- `size_category`: Groups sizes into categories.
- `size_option`: Lists specific sizes.
- `product_variation`: Links products to their variations (size, color).
- `product_item`: Represents purchasable items with stock and price.
- `product_image`: Stores product image URLs or references.
- `attribute_type`: Defines types of product attributes.
- `attribute_category`: Groups attributes into categories.
- `product_attribute`: Stores custom attributes for products.

## Usage

1. Create a new database in your SQL environment.
2. Run the `ecommerce.sql` script to create all tables and constraints.
3. Use the tables to manage your e-commerce product data.

## ERD Diagram

You can visualize the database schema using tools like [dbdiagram.io](https://dbdiagram.io) by importing the `ecommerce.sql` file.

## Collaboration

This project is designed for group collaboration on e-commerce database design and implementation.

## License

MIT License

Copyright (c) 2025 joshua mwendwa

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
