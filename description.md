Goals / description:
* uses 250v/10A relais switches to switch appliances on and off - no limitations to what kinds of devices can be connected
* capable of switching up to 8 appliances per device
* (hopefully) capable of activating door openers and other assistive devices with pushbutton connectors
* connects to ethernet
* uses some form of public/private key encryption for authentication
* uses atmega328
* uses configuration files on a microsd to configure appliances
* announces itself after a broadcast - no need to configure static ip addresses
* capable of processing both direct (switch 1 on) and function specific (lights off) commands
* can be operated with python script on pc (and connected to speech recognition)
* can be operated via android devices (iOs too if we can find the money for a developer acc)
* can be operated via any device capable of making outgoing ssh connections
* can be operated manually via pushbuttons located on the device
* NO BATTERIES
* reliable: good quality watchdog that will reboot at the first sign of trouble
* safe: every relais will have its own circuit breaker
* if we have spare money and time, gewa-like devices should be able to operate it as well (low priority, we are doing this exactly to avoid all the trouble that gewa-like devices bring with them)

Downsides:
* needs a wired ethernet connection (for reliability, and simplicity)
* 8 switches in one place means more wires in the house
* if the router goes down, so does this
* in its current design unsuitable for switching personal alarms, as there is no battery backup. UPS would fix this.
* no support for remote operated phones -> something to look into


