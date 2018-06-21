Read this in other languages: [English](README.md), [日本語](README.ja.md)

# SiTCP Netlist for Spartan6

SiTCP Library (ngc file) for Xilinx Spartan 6.


## What is SiTCP

Simple TCP/IP implemented on an FPGA (Field Programmable Gate Array) for the purpose of transferring large amounts of data in physics experiments.

* For details, please refer to [SiTCP Library page](https://www.bbtech.co.jp/en/products/sitcp-library/).
* For other related projects, please refer to [here](https://github.com/BeeBeansTechnologies).

![SiTCP](sitcp.png)


## History

2010-08-10 Ver.4.0
* A bug for ARP fixed.

2010-12-14 Ver.4.1
* 32kbyte SiTCP buffersize reduced to 16kbyte.

2012-06-19 Ver.5.0
* A bug for 10BASE fixed.

2012-11-22 Ver.6.0
* Client mode of SiTCP added.

2012-11-26 Ver.7.0
* Expansion of the ACK reply method at the time of the reception

2013-10-18 Ver.8.0
* Added minimum IPG resistor (programmable range from 3 to 15).

2016-02-09 Ver.9.0
* Added MAC address output port

2016-10-11 Ver.10.0
* RX bug fixed

2017-05-29 Ver.11.0
* Modified for corresponding to the pause frame(IEEE802.3x flow control).
* Arp request function added in Client mode.
* SiTCP_RST modified.
* Change of ACK transmission method.
* MIF Initialization modified.
