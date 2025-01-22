| Entity Name          | Entity Type   | Unit    | Example       | Description                                                      |
|----------------------|---------------|---------|---------------|------------------------------------------------------------------|
| saveeyeDeviceSerialNumber |               | String  | ABCD1234      | Unique serial number of the SaveEye device                       |
| meterType            |               | String  | /LGF5E360     | Type or model name of the meter                                  |
| meterSerialNumber    |               | String  | ABC123        | Serial number of the meter if available                          |
| timestamp            |               | String  | 2023-10-12T09:05:35Z | Timestamp when the reading is captured (ISO 8601 format)        |
| wifiRssi             |               | Number  | dBm           | -67                                                             | WiFi signal strength indicator in dBm                           |
| activeActualConsumption | total         | Number  | W             | 666                                                              | Instantaneous active power consumption across all lines          |
|                      | L1            | Number  | W             | 111                                                              | Instantaneous active power consumption for line 1                 |
|                      | L2            | Number  | W             | 222                                                              | Instantaneous active power consumption for line 2                 |
|                      | L3            | Number  | W             | 333                                                              | Instantaneous active power consumption for line 3                 |
| activeActualProduction | total         | Number  | W             | 667                                                              | Instantaneous active power production across all lines            |
|                      | L1            | Number  | W             | 112                                                              | Instantaneous active power production for line 1                  |
|                      | L2            | Number  | W             | 223                                                              | Instantaneous active power production for line 2                  |
|                      | L3            | Number  | W             | 334                                                              | Instantaneous active power production for line 3                  |
| activeTotalConsumption | total         | Number  | W/h           | 668                                                              | Cumulative active energy consumption across all lines             |
|                      | L1            | Number  | W/h           | 113                                                              | Cumulative active energy consumption for line 1                   |
|                      | L2            | Number  | W/h           | 224                                                              | Cumulative active energy consumption for line 2                   |
|                      | L3            | Number  | W/h           | 335                                                              | Cumulative active energy consumption for line 3                   |
| activeTotalProduction | total         | Number  | W/h           | 669                                                              | Cumulative active energy production across all lines              |
|                      | L1            | Number  | W/h           | 114                                                              | Cumulative active energy production for line 1                    |
|                      | L2            | Number  | W/h           | 225                                                              | Cumulative active energy production for line 2                    |
|                      | L3            | Number  | W/h           | 336                                                              | Cumulative active energy production for line 3                    |
| reactiveActualConsumption | total        | Number  | Var           | 670                                                              | Instantaneous reactive power consumption across all lines         |
|                      | L1            | Number  | Var           | 115                                                              | Instantaneous reactive power consumption for line 1               |
|                      | L2            | Number  | Var           | 226                                                              | Instantaneous reactive power consumption for line 2               |
|                      | L3            | Number  | Var           | 337                                                              | Instantaneous reactive power consumption for line 3               |
| reactiveActualProduction | total        | Number  | Var           | 671                                                              | Instantaneous reactive power production across all lines          |
|                      | L1            | Number  | Var           | 116                                                              | Instantaneous reactive power production for line 1                |
|                      | L2            | Number  | Var           | 227                                                              | Instantaneous reactive power production for line 2                |
|                      | L3            | Number  | Var           | 338                                                              | Instantaneous reactive power production for line 3                |
| reactiveTotalConsumption | total        | Number  | Varh          | 672                                                              | Cumulative reactive energy consumption across all lines           |
|                      | L1            | Number  | Varh          | 117                                                              | Cumulative reactive energy consumption for line 1                 |
|                      | L2            | Number  | Varh          | 228                                                              | Cumulative reactive energy consumption for line 2                 |
|                      | L3            | Number  | Varh          | 339                                                              | Cumulative reactive energy consumption for line 3                 |
| reactiveTotalProduction | total        | Number  | Varh          | 673                                                              | Cumulative reactive energy production across all lines            |
|                      | L1            | Number  | Varh          | 118                                                              | Cumulative reactive energy production for line 1                  |
|                      | L2            | Number  | Varh          | 229                                                              | Cumulative reactive energy production for line 2                  |
|                      | L3            | Number  | Varh          | 340                                                              | Cumulative reactive energy production for line 3                  |
| rmsVoltage           | L1            | Number  | V             | 229                                                              | RMS voltage for line 1 (in volts)                                 |
|                      | L2            | Number  | V             | 230                                                              | RMS voltage for line 2 (in volts)                                 |
|                      | L3            | Number  | V             | 231                                                              | RMS voltage for line 3 (in volts)                                 |
| rmsCurrent           | L1            | Number  | mA            | 100                                                              | RMS current for line 1 (in milliamperes)                          |
|                      | L2            | Number  | mA            | 120                                                              | RMS current for line 2 (in milliamperes)                          |
|                      | L3            | Number  | mA            | 300                                                              | RMS current for line 3 (in milliamperes)                          |
| powerFactor          | total         | Number  | %             | 98                                                               | Power factor (total) as a percentage                              |
|                      | L1            | Number  | %             | 99                                                               | Power factor for line 1 as a percentage                            |
|                      | L2            | Number  | %             | 98                                                               | Power factor for line 2 as a percentage                            |
|                      | L3            | Number  | %             | 97                                                               | Power factor for line 3 as a percentage                            |
| ExtendersData (array) |               |         |               |                                                                  |                                                                  |
|                      | extenderDeviceId | String  | -             | E247FD61                                                         | Serial number of the extender device                              |
|                      | extenderPulses | Number  | -             | 42                                                               | Number of pulses counted by the extender                           |
|                      | extenderTimestamp | Number  | S             | 1741913085                                                       | UNIX timestamp when data was sent by the extender                  |
|                      | extenderVcc   | Number  | -             | 98                                                               | Extender's voltage supply level                                    |
|                      | extenderadvType | Number  | -             | 2                                                                | Advertising type of the extender                                   |
|                      | extenderRssi  | Number  | dBm           | -64                                                              | Signal strength of the extender in dBm                             |
|                      | activeActualConsumption | Number  | W/h         | 10                                                               | Current active power consumption calculated on the device side    |
|                      | activeTotalConsumption | Number  | W             | 3000                                                             | Total active energy consumed by the extender                       |
