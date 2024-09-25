# Example 1: E-commerce Checkout System

Design a comprehensive pseudocode to handle an e-commerce checkout process:

```plaintext
// User authentication
IF user is logged in THEN
    DISPLAY "Proceed to checkout."
ELSE
    DISPLAY "Please log in to continue."
ENDIF

// Product selection
FOR each product in cart DO
    DISPLAY "Product: ", product.name, " Price: $", product.price
ENDFOR

// Calculate total
SET total TO 0
FOR each product in cart DO
    ADD product.price TO total
ENDFOR
DISPLAY "Total: $", total

// Payment processing
IF payment is successful THEN
    DISPLAY "Thank you for your purchase!"
ELSE
    DISPLAY "Payment failed. Please try again."
ENDIF
