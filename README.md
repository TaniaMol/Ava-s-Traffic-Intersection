# Traffic Light
(Week 1):

Wiring:

<img width="770" alt="screenshot 2017-02-13 09 12 14" src="https://cloud.githubusercontent.com/assets/22894897/22891611/2c9dab42-f1cd-11e6-829d-225f646ee905.png">

Schematics:

<img width="951" alt="screenshot 2017-02-13 10 34 45" src="https://cloud.githubusercontent.com/assets/22894897/22894971/1176c082-f1d8-11e6-97c5-23aea8a8abf9.png">

Simulator: https://circuits.io/circuits/3642162-semaforo-arduino

![semaforo](https://cloud.githubusercontent.com/assets/22894897/22892687/acc32664-f1d0-11e6-973f-0ef7ccfbf4c6.gif)

# Radar
(Week 3)

Buil a sonar using arduino, a servo, and a ping and visualize it as a radar with Processing.

it deserved its own link:
https://github.com/TaniaMol/ArduinoRadar

# Ava's Traffic Intersection
(Week 4):

<img width="763" alt="screenshot 2017-02-10 10 54 37" src="https://cloud.githubusercontent.com/assets/22894897/22837781/5c92b02c-ef7f-11e6-998d-dff554c80a3c.png">

Instructions:

Vehicle circulation can be blocked by the barrier if the train appears or the pedestrian presses the button for the green light.

The green light button is activated if there is no train approaching, and enough time (9 sec) has passed since the button was last activated.

The green light is activated for 5 seconds, which is followed by an intermittent beep. Then, the green light blinks for 3 seconds and the intermittent beep becomes more frequent. After that, the red light is activated again, and the timer counts the time from 0 to 9 seconds.

If the train appears when the green light is on for pedestrians, the red signal is activated urgently and a continuous beep of a different height can be heard.

You can imagine the intersection happening like this:

<img width="1033" alt="screenshot 2017-02-10 13 37 41" src="https://cloud.githubusercontent.com/assets/22894897/22843305/2dde1c5a-ef96-11e6-85d0-09387e4598bf.png">

Black path is for cars, white & gray path is for the train and brown path is for people to cross.

While the train is passing, the switch cannot request a green light.

When the train comes again, the green light turns off and the red light turns on.

When the photoresistor is bright, that means the train is not passing but when you turn it dark, it means the train is passing. 

Wiring:

<img width="858" alt="screenshot 2017-02-12 22 09 27" src="https://cloud.githubusercontent.com/assets/22894897/22871636/f9f5580a-f16f-11e6-859c-548c69ba99ae.png">

Schematics:

<img width="1088" alt="screenshot 2017-02-13 09 48 36" src="https://cloud.githubusercontent.com/assets/22894897/22892986/a333ee02-f1d1-11e6-96b3-1d132a369e1d.png">

![avas](https://cloud.githubusercontent.com/assets/22894897/22894632/f0f684f6-f1d6-11e6-856a-ccdddac89cad.gif)

any help is welcome at the Simulator: https://circuits.io/circuits/3973783-ava-s-traffic-intersection/edit#breadboard

# Coward Robot example
(Week 5)

A robot who runs from the enemy as soon as he finds it in front of him.

Wiring:

<img width="991" alt="screenshot 2017-02-13 15 42 31" src="https://cloud.githubusercontent.com/assets/22894897/22906836/a30e75e6-f203-11e6-9e39-838de975d99c.png">

Schematics:

<img width="1135" alt="screenshot 2017-02-13 21 23 30" src="https://cloud.githubusercontent.com/assets/22894897/22915202/aee18780-f232-11e6-8754-7d3841fa9821.png">

![coward](https://cloud.githubusercontent.com/assets/22894897/22916363/4619335c-f23b-11e6-815d-a0d056923a6d.gif)

Simulator: https://circuits.io/circuits/3973784-road-robot/

