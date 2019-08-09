# Node-red
Node
Configure Node Mcu with the arduino IDE by installing necessary Library files ( ESP8266 ). The default module used is  NodeMcu 1.0(ESP 12E Module) in Arduino IDE , in board manager. Take the above code to arduino IDE. Dump the code to NodeMcu. Install node.js from browser and install necessary packages. Run nodered in command prompt and open local host. Make a simple circuit by giving switch as an input and mqtt as output.

Makesure that you installed Dashboard and npm packages, you can get these tutorial about installation in this link https://nodered.org/docs/getting-started/local

Change the topic in Node-red to "ledcontrol" which is given in the arduino code. 

Subsribe to a local Mqtt broker( https://www.cloudmqtt.com/ )

After subscribing youll get all the details about mqtt userid, password, port details and i.p.address.
(These details should be updated in Arduino code)

Make a ui dashboard in node-red, so that the switch we created will be appeared in that ui dashboard.

Deploy the node-red and open ui dashboard(localhost:1880/ui)

Done! Now you can operate the led in NodeMcu using node-red.

