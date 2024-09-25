
# Example 2: Complex Decision Making

Consider an e-commerce platform that applies discounts based on multiple criteria:

```plaintext
IF customer is "returning" THEN
    IF purchaseAmount > 100 THEN
        DISPLAY "You get a 10% discount."
    ELSE
        DISPLAY "You get a 5% discount."
    ENDIF
ELSE
    DISPLAY "Sign up for discounts."
ENDIF
