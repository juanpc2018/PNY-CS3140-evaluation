# PNY-CS3140-evaluation

M280CS31402TB-RB </br>
according to [TomsHardware](https://www.tomshardware.com/reviews/pny-xlr8-cs3140-ssd-review/2) 2TB drive has a low power efficiency. </br>
Low Power Efficiency 300MB/s per Watt = more heat vs. good drives 500MB/s Watt. </br>

Big Files = Long Write Times = More Heat. </br>

using a good external case with RTL9210- controller: [Orinco PWDM2-G2](https://www.orico.cc/us/product/detail/8037.html) </br>
USB 3.0 limits speed to 500MB/s </br>
Longer Write Times = More Heat. </br>

Drive Failed, but was a strange failure. </br>
stops being detected by the RTL9210 controller, </br>
BUT... when connected directly to PCIe with a cheap adapter [startech PEX4M2E1](https://www.startech.com/en-us/hdd/pex4m2e1)  </br>
CS3140 "works", pass all tests at 1400MB/s "1.4GB/s" Read | 1000MB/s "1GB/s" Write,
using [Thunderbolt2](https://en.wikipedia.org/wiki/Thunderbolt_(interface)#Thunderbolt_2) -> [eGpu](https://egpu.io/best-egpu-buyers-guide/) external case </br>
also works directly to Motherboard PCIe. </br>

something got damaged, but Not a total damage. </br>
external USB case / RTL9210 controller has No problem with Higher efficiency drives: Sabrent Rocket and Samsung Pro </br>

IF you live outside USA or EU, forget about the warranty, you lost the money. </br>


