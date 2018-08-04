# Wireless-Sensor-Network
This project is a deployment of a wireless sensor network. This network is included two sub-networks, which communicate by 433 MHz and 315 MHz frequency modules. Each sub-network included nodes(sensors) and a leader. The nodes of each network are considered to send their data to their leader (star protocol).  the leaders communicate with each other in 2.4 GHz frequency by the NRF24L01+ module. Finally, the head cluster (leader of leaders) of this network send the processed data to the Things Speak clouds by ESP8266 Wi-Fi module to monitor them. the devices are based on the Arduino nano development boards.
o Successfully designed heterogeneous WSN.
o Implemented three networks with a different frequency (ISM band).
o Developed the network with two kinds of the node for being heterogeneous.
o Used Temperature and Humidity sensor, Air Pollution detector, Pressure sensor, PIR Motion detector, and Voice detector.
