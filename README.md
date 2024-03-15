# ModBus

# Các loại giao thức ModBus
- ModBus RTU
- ModBus ASCII
- ModBus TCP/IP

## Cấu trúc khung ModBus RTU
  [Slave Address] [Function Code] [Data]  [CRC]

## Cấu trúc khung ModBus ASCII
  [Start(0x3A)] [Address] [Function Code] [Data] [LRC] ['\r'] ['\n']

## Cấu trúc khung ModBus TCP/IP
Transaction Identifier: 2 bytes
Protocol Identifier: 2 bytes
Length: 2 bytes
Unit Identifier: 1 byte

![image](https://github.com/tranhien1612/modBus/assets/69721832/a3e12cb7-7ba3-4c24-8c2f-ccf695223f4c)

