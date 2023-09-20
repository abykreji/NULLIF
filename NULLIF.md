## Exercise:

#### Question:


##### Show NULL when the product is not on special (0)

###### DB: Store
###### Table: products

### Solution

```python
SELECT prod_id, title, price, NULLIF(special, 0) as "special"
FROM products
```