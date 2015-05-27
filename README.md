# PRU Bridge
The PRU Bridge framework enables two-way data and event communication between the ARM and PRU subsystem on the Beaglebone Black (powered by the TI AM335x ARM Cortex-A8 SoC). 

## The SoC

## PRUSS Subsystem

## The framework
    (why, how, etc.)

## API 
### 1. ARM to PRU
```python
import pru_bridge
pru = pru_bridge(0); #the pru cpu number
pru.send_event(event_no)
pru.write(channel, data)
pru.read(channel, num_of_bytes)
```
## extensions and future work
    (what SDKs can be built over this)
