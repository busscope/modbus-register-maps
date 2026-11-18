# Open-Source Modbus Device Register Maps

A community-driven collection of clean, standardized Modbus register maps (`CSV` and `JSON`) for popular industrial devices, energy meters, PLCs, and VFDs.

## Available Devices
- **Energy Meters:** [Eastron SDM630](energy-meters/eastron-sdm630.csv)

## Useful Modbus Tools
- **Online Frame Decoder:** Need to quickly decode raw Modbus RTU/TCP hex frames and verify CRC/LRC? Try the free browser-based [Busscope Frame Parser](https://busscope.com).
- **Windows Testing Suite:** Poll, write, chart, and diagnose these register maps live on Windows (TCP, TLS 1.2+, RTU, ASCII) using [Busscope Master & Slave](https://busscope.com).

## Standard Format
All register maps follow a consistent column structure so they can be easily imported into scripts, SCADA systems, or Modbus testing tools:
`Address, Register_Type, Data_Type, Byte_Order, Scale, Unit, Description`

## Contributing
Pull requests are welcome! Feel free to add register maps for new devices or submit corrections via Issues.
