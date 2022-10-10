START

SEND "Please enter the temperature' TO DISPLAY
IF temperature<18
  SEND 'Cold, the perfect temperature for sleep is 18-21 degrees.'
ELSE
  IF temperature>21
  SEND 'Perfect' TO DISPLAY
ELSE
  SEND 'No! The perfect temperature for sleep is 18-21 degrees.'
  
END
