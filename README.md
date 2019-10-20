# nRF HAL -- port for Arduino #

This is a port of Nordic Semiconductor's **nRF24L01** transceiver **HAL** _(Hardware Abstraction Layer)_ **API** _(ie:
the **nRF HAL API**)_ for the [Arduino][1] platform.
All of the original **HAL** function prototypes have been preserved; some _additions_ were introduced, as well _(mostly
**"getters"** for existing **"setters""**)_.

The **HAL API** provides an easy and flexible way to utilize the full power of the **nRF24** transceiver, abstracting
the access methods for the device's low level registers, communication protocol, etc.
The API set consists of _about **70**_ rather simple functions, performing basic actions on the transceiver _(like
opening an RX pipe, setting TX/RX addresses, setting TX output power, checking various statuses, reading/writing the
data payload, etc..)_.

See the `./src/nrf_hal.h` header file for the API specification and `./examples` for some examples.


## Related Projects ##

Looking for an **NRF HAL API** port for Raspberry Pi? Check out the [librasp][2] library:



## License ##

Nordic Semiconductor Standard Software Development Kit License Agreement




[1]:	<https://arduino.cc>
[2]:	<https://github.com/pstolarz/librasp>
