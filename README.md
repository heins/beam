# beam
BEAM your CoAP, MQTT or REST-Message

For Arduino compatible microcontrollers like TheSpaceSatellite or Merkurboard (OSDOMOTICS):

## Config

  counterpart : URL of the MQTT-Server or peer
  protocol : MQTT, CoAP, HTTP-REST get/post

'''beam.config(counterpart, protocol)'''

## Send

  topic : MQTT topic or CoAP resource
  payload : message (plain/text, json, XML, ...)

beam(topic, payload);

## Receive

message = beam(topic);
