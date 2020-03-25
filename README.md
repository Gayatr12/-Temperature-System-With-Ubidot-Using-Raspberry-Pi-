#Temperature System With Ubidot Using Raspberry-Pi

A temperature monitoring system provides valuable insights in both commercial and industrial environments to reduce inefficiencies or maintain quality of products and their quality. What if I told you that you can monitor the temp of your self-built wine-cellar or your family's aquarium at home using the same device. Further, what if I told you that the same device could be used to monitor air and liquid temperatures of fluids at your factory too? The makers of our world have made this possible and this guide is here to help kickstart your own initiatives at home or on the shop floor.<br/>

This guide will be your tutorial for a simple DIY temperature monitoring system that is also waterproof to boot. Using a Raspberry Pi and Ubidots we'll show you how to connect your Pi and display in real-time your temperature system's metrics. Using Ubidots, you can also create emails or SMS events to ensure your "variable" (in this case, the temperature) remains within a set of defined limits assigned by you to ensure quality and efficiency of your system's conditions.<br/>

For this project we are going to use a 1-wire pre-wired and waterproof version of the DS18B20 sensor. What is 1-wire? It's a communication protocol that makes connecting your IoT sensors simpler by aggregating all cabling into is a single wire (...well actually it's three, two are ground and power connections for energy, the third being the 1-wire for data transmission).

