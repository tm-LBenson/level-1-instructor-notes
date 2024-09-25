# Example 1: Checking Inventory

Imagine programming a droid to check inventory levels in a storage facility. The droid needs to check each storage bin and report if restocking is needed:

```plaintext
FOR i FROM 1 TO 10 DO
    DISPLAY "Checking bin ", i
    IF bin[i] < 5 THEN
        DISPLAY "Bin ", i, " needs restocking."
    ELSE
        DISPLAY "Bin ", i, " is fully stocked."
    ENDIF
ENDFOR
```
# Additional Example: Displaying Product Listings

Imagine a website needs to display a list of products dynamically based on inventory data:

```plaintext
FOR i FROM 1 TO numberOfProducts DO
    DISPLAY "Product Name: ", products[i].name
    DISPLAY "Price: $", products[i].price
    DISPLAY "In Stock: ", products[i].inStock, " units"
ENDFOR

```
