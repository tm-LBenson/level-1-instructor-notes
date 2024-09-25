
# Example 3: Gaming Leaderboard

Construct pseudocode for maintaining a gaming leaderboard:

```plaintext
// Leaderboard update
FOR each game result in results DO
    IF result.score > leaderboard.lowestScore THEN
        REPLACE lowest score with result.score
        SORT leaderboard
    ENDIF
ENDFOR
DISPLAY "Updated leaderboard."
