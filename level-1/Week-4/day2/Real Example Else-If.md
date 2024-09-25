
**Real Example: Navigating the Starship's Control System**
`Real-Example-Else-If.md`
```markdown
# Real Example: Navigating the Starship's Control System

Imagine you are piloting the Millennium Falcon and need to choose the correct system settings based on flight conditions:

```plaintext
IF systemStatus == "combat" THEN
    DISPLAY "Combat mode engaged. All systems prepare for battle!"
ELSE IF systemStatus == "stealth" THEN
    DISPLAY "Stealth mode activated. Running silent."
ELSE
    DISPLAY "Travel mode set. Enjoy your trip across the galaxy."
ENDIF
