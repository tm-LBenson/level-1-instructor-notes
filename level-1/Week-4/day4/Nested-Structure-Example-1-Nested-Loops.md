# Example 1: Generating a Matrix

Imagine creating a web application that displays a grid or matrix based on user input:

```plaintext
FOR i FROM 1 TO numberOfRows DO
    FOR j FROM 1 TO numberOfColumns DO
        DISPLAY "Cell (", i, ",", j, ") value: ", matrix[i][j]
    ENDFOR
ENDFOR
