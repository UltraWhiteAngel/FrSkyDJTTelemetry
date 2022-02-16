# FrSky DJT Telemetry
Decoder for "D" receiver telemetry emitted typically from an early FrSky DJT Tx Module. Code is intended for an Arduino Nno or similar. DJT modules uses +/-6V signalling and so an inverter is required.


As per Trial on v8R7-ii the Receiver does not sends back telemetry packets as per FCC- EU norms. But the Chip onboard cc2500 is well capable of Telemetry Back link, e
even with d4r2-ii firmware which is almost identical with Pinmappings and RF-FE
