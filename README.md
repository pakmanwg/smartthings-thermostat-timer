# smartthings-thermostat-timer
Simple thermostat timer smartapp for smartthings.

History:
To my surprise, most of the modern thermostat do not support timer function. The timer function is very populer in standalone fan, heater and window air conditioner. It is very useful when someone want to turn on the fan/heater/air conditioner for a predefined period of time and then shut it down automatically. So I decided to write a simple timer for nest using smartthings.

Usage:
- create a simulated switch device or button device in IDE
- setup the app to use the new simulated switch or button and config the time, cool and heat temperature, default cool and heat temperature.

Integration with other smartapps:
- nest can be used if you install tonesto7 nest manager app
- Either switch or button can be used. I am using switch because it can be easily integrated with Amazon dash using redloro dash smartapps.
