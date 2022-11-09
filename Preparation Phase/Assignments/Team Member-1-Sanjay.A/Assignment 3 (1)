//python code for blinking led
//The following code will make the led blink untill the button pressed and once the button is pressed 
//it stops blinking and continues to blink if the button is released 
//importing the button and led interface from the gpio package
from gpiozero import Button,LED
led=LED(25)
while True:
	led.blink()
	button.wait_for_press()
	led.off()
	button.wait_for_release()

	
