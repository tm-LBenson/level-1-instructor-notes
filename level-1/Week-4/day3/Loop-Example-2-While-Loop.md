
# Example 2: Fueling Up

A maintenance droid is tasked with fueling spacecraft until the fuel reserve is depleted:

```plaintext
SET fuelReserve TO 100

WHILE fuelReserve > 0 DO
    DECREMENT fuelReserve BY 10
    DISPLAY "Fueling spacecraft. Remaining reserve: ", fuelReserve, " units."
ENDWHILE
```

**Additional Example for Fueling Up (While Loop)**

A blog post page needs to load user comments dynamically as the user scrolls:

```plaintext
SET commentsLoaded TO 0
SET totalComments TO fetchTotalComments()

WHILE commentsLoaded < totalComments DO
    DISPLAY "Loading comment ", commentsLoaded + 1
    INCREMENT commentsLoaded BY 1
    IF commentsLoaded MOD 10 == 0 THEN
        DISPLAY "Load more comments?"
        BREAK // Temporarily stop loading until user action
    ENDIF
ENDWHILE
