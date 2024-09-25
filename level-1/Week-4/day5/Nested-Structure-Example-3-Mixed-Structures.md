# Example 3: Handling User Permissions

A complex system where user permissions vary by role and department:

```plaintext
FOR each user IN userList DO
    IF user.role == "admin" THEN
        DISPLAY "Full access"
    ELSE IF user.department == "HR" THEN
        DISPLAY "HR access"
    ELSE
        DISPLAY "Basic access"
    ENDIF
ENDFOR
