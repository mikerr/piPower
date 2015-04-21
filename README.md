# piPower
Monitor input power of the raspberry pi 

- Supports recent Pi models A+, B+ , Pi-2  - not older A/B

ledcheck.py  - logs status of powerLED remotely, warns if voltage is under 4.63v, shuts down if low for 4+ seconds.
consoleLED.py - shows LED status in the console (e.g. over SSH)
