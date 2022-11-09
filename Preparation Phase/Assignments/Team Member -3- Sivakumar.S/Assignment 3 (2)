//python code for traffic lights in ras
from gpiozero import button,TrafficLights
lights=TrafficLights(25,6,7)
button=Button(21)
while True:
	//using this all the three lights are blinked once if the button is pressed
	button.wait_for_press()
	lights.on()
	button.wait_for_release()
	lights.off()
	//using this the individual lights are made to glow
	lights.green.on()
	sleep(3)
	lights.amber.on()
	sleep(3)
	lights.red.on()
	sleep(3)
	lights.off()

	
