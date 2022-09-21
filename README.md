SET number 5
SENT "Please enter guess number" to DISPLAY
RECIEVE guess from keyboard 
IF guess <10 THEN 
SENT "too high" to DISPLAY
else
IF guess = number Then 
SEND "Correct"
else 
SENT "incorrect maybe next time"
END if 
END if
