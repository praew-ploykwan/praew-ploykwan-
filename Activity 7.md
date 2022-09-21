SET correct_number to 7
SEND 'Please enter a number that is not higher than 10' TO DISPLAY
RECIEVE guess FROM KEYBOARD
IF guess >10 THEN 
  SEND "Too high! Please try again, your guess must be between 1 to 10" TO DISPLAY
ELSE
IF guess =correct_number THEN
  SEND "7 is the correct number! Welldone!" TO DISPLAY
ELSE
SEND "That is not the correct number, better luck next time!" TO DISPLAY
END IF
END IF
