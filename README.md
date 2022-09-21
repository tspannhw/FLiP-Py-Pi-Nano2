# FLiP-Py-Pi-Nano2
RP4 2GB RAM with Pimoroni Breakout Garden + BME688 + MAX30105


### Sensors

* MAX30105 - Heart Rate, Oximeter, Smoke Sensor
precision optical sensor that can be used to measure heart rate, pulse oximetry (SPO2 / blood oxygen saturation), and smoke (and other particles).

* Bosch BME688 4-in-1 environmental sensor with Artificial Intelligence

* Pimoroni Breakout Garden

* Raspberry Pi 4 - 2GB

* Python 3.9


### Output

````
{'cpu': 0.0, 'diskusage': '19494.8 MB', 'endtime': '1663772286.1950016', 'host': 'nano2', 'hostname': 'nano2', 'ipaddress': '192.168.1.96', 'macaddress': 'e4:5f:01:d1:62:a3', 'memory': 16.6, 'rowid': '20220921145806_c195ad51-d1a8-4453-97c9-62b8d61ebb2f', 'runtime': 0, 'starttime': '09/21/2022 10:58:06', 'systemtime': '09/21/2022 10:58:07', 'bme680_tempc': 24.62, 'bme680_tempf': 76.32, 'bme680_pressure': 1012.18, 'bme680_humidity': 46.481, 'ts': 1663772287, 'uuid': 'nano2idrkt20220921145806', 'max30105_temp': 23.88, 'max30105_value': 21.0, 'max30105_mean': 7.5, 'max30105_delta': 0.0, 'max30105_detected': True, 'max30105timestamp': '20220921-105806-109688'}
````

### References

* https://github.com/pimoroni/bme680-python
* https://shop.pimoroni.com/products/bme688-breakout?variant=39336951709779
* https://cdn.shopify.com/s/files/1/0174/1800/files/bst-bme688-ds000.pdf?v=1620834794
* https://github.com/pimoroni/max30105-python
* https://github.com/tspannhw/FLiP-Py-BreakoutGarden
