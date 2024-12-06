# DDL-project
# Unique Apparels Sales Data Mart

## Dataset Explanation

The dataset consists of transaction data for Unique Apparels, a clothing brand. It includes detailed information about transactions, products, stores, discounts, special events, and dates. The main tables are:

### Transactions Table
- **TransactionID**: Unique identifier for each transaction.
- **Date**: Date of the transaction.
- **Time**: Time of the transaction.
- **CustomerID**: Unique identifier for each customer.
- **StoreID**: Unique identifier for each store.
- **StoreName**: Name of the store.
- **City**: City where the store is located.
- **Province**: Province where the store is located.
- **ProductID**: Unique identifier for each product.
- **ProductName**: Name of the product.
- **Category**: Category of the product.
- **Color**: Color of the product.
- **Size**: Size of the product.
- **Gender**: Gender for which the product is intended.
- **Quantity**: Quantity of the product sold.
- **CostPrice**: Cost price of the product.
- **SellingPrice**: Selling price of the product.
- **Discount**: Discount applied to the product.
- **AdditionalDiscountType**: Additional discount type applied.
- **Season**: Season during which the product is sold.
- **TotalCost**: Total cost of the transaction (calculated as Quantity * Selling Price).
- **ProfitMargin**: Profit margin for the transaction (calculated as TotalCost - (Quantity * CostPrice)).

### Product Lookup Table
- **ProductID**: Unique identifier for each product.
- **ProductName**: Name of the product.
- **Category**: Category of the product.
- **Color**: Color of the product.
- **Size**: Size of the product.
- **CostPrice**: Cost price of the product.
- **SellingPrice**: Selling price of the product.

### Store Lookup Table
- **StoreID**: Unique identifier for each store.
- **City**: City where the store is located.
- **Province**: Province where the store is located.

### Additional Discount Lookup Table
- **DiscountType**: Type of the additional discount.
- **DiscountPercentage**: Percentage of the additional discount.

### Special Events Lookup Table
- **EventDate**: Date of the special event.
- **EventName**: Name of the special event.

### Date Lookup Table
- **Date**: Unique list of dates extracted from the transactions for date-related analysis.
