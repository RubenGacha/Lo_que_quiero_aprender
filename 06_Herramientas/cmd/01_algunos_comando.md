# algunos comandos


Windows:

Modelo: `wmic csproduct get name`
Serie: `wmic bios get serialnumber`
capacidad memoria ram: `wmic memphysical get MaxCapacity, MemoryDevices` (para el tipo de memoria toca usar cpu-z)

Linux: 

se debe instalar el paquete `dmidecode`
capacidad memoria ram: `sudo dmidecode -t memory`