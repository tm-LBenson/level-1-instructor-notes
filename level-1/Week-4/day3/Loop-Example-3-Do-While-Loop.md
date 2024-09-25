# Example 3: Sending a Distress Signal

A communications console is set to send a distress signal until an acknowledgment is received:

```plaintext
DO
    DISPLAY "Sending distress signal..."
    SET signalAcknowledged TO RECEIVE_ACKNOWLEDGMENT()
WHILE signalAcknowledged == FALSE
```



# Additional Example: User Login Attempt

A web application allows users to attempt to log in, retrying until successful or until the maximum attempt limit is reached:

```plaintext
SET attemptCount TO 0
SET loginSuccessful TO FALSE

DO
    DISPLAY "Enter username and password."
    SET loginSuccessful TO checkCredentials(username, password)
    INCREMENT attemptCount BY 1
    IF attemptCount >= 3 THEN
        DISPLAY "Maximum login attempts reached. Please try again later."
        BREAK
    ENDIF
WHILE loginSuccessful == FALSE
