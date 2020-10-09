# pocadassubscriber

## POC Adas Subscriber

This is test MQTT client/subscriber that is meant to run on Raspberry Pi. The raspberry pi would be connected to Windows PC (simulate Super Computer).

Setup needs following:

* Install MQTT library for Python 3
    * sudo pip3 install paho-mqtt
* In AdasSubscriber.py, constant MQTT_SERVER equals IP for ethernet port on Windows PC. (172.162.4.202 in this project)
* See pocadas project for instructions for port configuration and Windows publisher code setup.
