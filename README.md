# simple-dht

Simple, Stable and Fast LaFortuna Temp & Humidity Sensors for [DHT11 etc]

1. Simple: Simple pure C code with lots of comments.
1. Stable: Strictly follow the standard DHT protocol.
1. Fast: Support 0.5HZ or 1HZ sampling rate.

Sample: 
=================================
Sample DHT11...
Sample OK: 19 *C, 31 %
=================================
Sample DHT11...
Sample OK: 19 *C, 31 %
=================================
```

> Remark: For DHT11, no more than 1 Hz sampling rate (once every second).

## Examples

This library including the following examples:

1. DHT11Default: To sample the temperature and humidity.
1. DHT11WithRawBits: To sample the temperature and humidity, output the 40 raw bits.

Code adapted for LaFortuna board from the official Arduino library. 
