# beam
BEAM your CoAP, MQTT or REST-Message

For Arduino compatible microcontrollers like TheSpaceSatellite or Merkurboard (OSDOMOTICS):

## Config

Configure Beam

  counterpart : URL of the MQTT-Server or peer
  
  protocol : MQTT, CoAP, HTTP-REST get/post

```beam.config(counterpart, protocol);```

## Send

Send a message to the couterpart.

  topic : MQTT topic or CoAP resource
  
  payload : message (plain/text, json, XML, ...)

```beam(topic, payload);```

or

```beam(coutnerpart, protcoll, topic, payload);```


## Receive

Receive a message from the counterpart.

```message = beam(topic);```
