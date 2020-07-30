Pager is a project to develop a simple and small personal pager device which works in LTE NB-IoT mobile network. The main idea is just to receive text or short status messages and have an ability to easily send by one button an acknoledgement for sender that the message has been received and readed.

One existing a very excellent model about this is Airbus P8GR -device (use Google!) which is based on TETRA-network and has been meant to use for ie. firemen, first responders, healthcare and many other critical groups who have to be urgently reached as soon as possible and all at the same moment. Many ideas shall be copied from this concept. At this moment no similar device is available for commercial mobile networks.

At this point someone might ask why not to do this with a regular mobile phone? There are a couple of reasons. First, there is no need to carry a big smartphone if a person is on hobbies or in a place where handling a phone is not easily possible, or does not want to be disturbed except in emergency situation. Next, it is possible to send an acknoledgement my pressing one key without any extra hassle with touch-screen phone. Thirdly, LTE NB-IoT technology guarantees the best possible connection to the network even in really harsh network conditions where a regular cellphone simply won't work anymore (this is a very essential thing due to increased reliability).

LTE NB-IoT is a network technology which allows very minimal power consumption for devices but also a very modest connection to mobile network so it is very ideal selection for network at this point. Due to small consumption the battery can be such small but still it can last very long.

Although all ideas and proposals are definitely welcome I'll describe here a few key points where to start:

* The core of the device is SimCom SIM7080G LTE-module which supports only NB-IoT and LTE-M network technologies. LTE-M will not be used since it does not give any value for this device. The selection is based on such cheap price, simplicity, low power consumption and very minimal need for external components. It also supports a large number of LTE-bands which is a big advantage comparing to similar NB-IoT modules in the current market.
* The CPU will very probably be Atmel ATmega-series microcontroller. There are many reasons which are essential. Simplicity, cheap price, prevalence, easy programming, good development tools, a large number of experienced programmers, very small power consumption on small clock speed, small size and many, many others.
* The screen should be clear and bright OLED-display due to readability in different circumstances and environments. Also power consumption is the key advantage.

The device can/will be about in same size than traditional pagers has usually been. Charging could be done with USB-C -cable. The antenna will be an internal PCB-antenna and luckily ready constructions/drawings are already available so there is no need to innovate this again, though.

Although it will be possible to send messages (SMS) to these devices from whatever mobile device there is still a plan for cloud-based services for organizations where is possible to build groups of pagers where to send an alarm or a message with one click from dispatcher. If talking about volunteer firemen everyone in the group will get the fire alarm and immediately click a button whether accepting or declining to participate. Hereby the dispatcher sees in real time who are arriving to the duty.

Now we need YOUR help! If you feel you are familiar with technical prototyping, like to work around with Arduinos, KiCad schematics and PCB planning is in your hands, you like coding, you've full of ideas or whatever, JOIN US! :) Everybody are definitely welcome! :)
