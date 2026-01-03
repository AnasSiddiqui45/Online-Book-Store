📘 SQL Bookstore Database 
🔹 Basic Queries
1. Show books where genre is fiction

Definition: Filters records based on a specific category.
Description: Retrieves all books classified under the fiction genre to analyze category-specific inventory.

2. Find books published after the year 1950

Definition: Uses conditional filtering on numeric/date fields.
Description: Fetches books released after 1950 to analyze modern publications.

3. List all customers from Canada

Definition: Filters customer data by geographic location.
Description: Identifies customers residing in Canada for region-based analysis.

4. Show orders placed in November 2023

Definition: Uses date range filtering with BETWEEN.
Description: Extracts all orders placed within a specific month to analyze monthly sales.

5. Retrieve total stock of books available

Definition: Uses aggregate function SUM.
Description: Calculates the total number of books currently available in inventory.

6. Find details of the most expensive book

Definition: Uses sorting with ORDER BY.
Description: Identifies the highest-priced book to analyze premium pricing.

7. Show customers who ordered more than one book

Definition: Uses JOIN with conditional filtering.
Description: Displays customers who purchased multiple quantities, indicating high demand behavior.

8. Show orders where total amount exceeds $20

Definition: Filters numeric values using conditions.
Description: Identifies high-value orders for revenue analysis.

9. List all genres in the books table

Definition: Uses DISTINCT to remove duplicates.
Description: Retrieves all unique book genres available in the database.

10. Find the book with the lowest stock

Definition: Sorting and limiting results.
Description: Identifies low-stock items to assist in inventory replenishment.

11. Calculate total revenue generated from all orders

Definition: Aggregation using SUM.
Description: Computes overall sales revenue from all customer orders.

🔹 Advanced Queries
12. Retrieve total number of books sold for each genre

Definition: Aggregation with GROUP BY and JOIN.
Description: Calculates total quantity sold per genre to understand category performance.

13. Find the average price of Fantasy books

Definition: Uses AVG aggregate function.
Description: Determines average pricing within the Fantasy genre.

14. List customers who placed at least two orders

Definition: Uses GROUP BY with HAVING.
Description: Identifies repeat customers based on order frequency.

15. Find the most frequently ordered book

Definition: Uses counting and sorting.
Description: Determines the book with the highest number of orders.

16. Show top 3 most expensive Fantasy books

Definition: Filtering, sorting, and limiting results.
Description: Lists premium Fantasy books based on price.

17. Retrieve total quantity of books sold by each author

Definition: Aggregation with joins.
Description: Calculates total sales per author to analyze author popularity.

18. List cities where customers spent over $30

Definition: Uses JOIN, filtering, and DISTINCT.
Description: Identifies high-spending customer locations.

19. Find customers who spent the most

Definition: Aggregation and ranking.
Description: Identifies top customers based on total spending.

20. Calculate remaining stock after fulfilling all orders

Definition: Uses LEFT JOIN, COALESCE, and arithmetic operations.
Description: Computes remaining inventory after deducting all fulfilled orders.
