# Universal ISA Backplane

![Initial layout plan](Universal-ISA-Backplane-Light.png#gh-light-mode-only)
![Initial layout plan](Universal-ISA-Backplane-Dark.png#gh-dark-mode-only)
*Initial layout plan. Bracketed area in the top right is where normal PC I/O goes.*

This backplane is initially intended to be used with with a [PC/104 compute board](https://en.wikipedia.org/wiki/PC/104) for legacy ISA card applications. It aims to implement the complete 16-bit ISA bus specification in a microATX form factor. In future, the PCI bus could also be implemented, allowing use of PC/104-Plus (ISA and PCI), or PCI/104 (PCI only) compute boards.

This project was based on [spark2k06's Universal ITX Backplane](https://github.com/spark2k06/Universal-ITX-Backplane), but is heavily modified to focus on PC/104 support and in a microATX form factor. More information visit spark2k06's project on their [Hackaday page](https://hackaday.io/project/175340-universal-itx-backplane).

The project is mostly unfinished. No layout exists, most of the schematic is unfinished.

## Specifications

* Standard microATX board
* 2x ISA 8-/16-bit slots (1 shared with PCI slot)
* 3x 32-bit PCI slots (1 shared with ISA slot)
* 1x PC/104, PC/104+, PCI-104 connection
* Compatibility with modern ATX power supplies
* Compatibility with modern ATX computer cases
* Standard ATX I/O shield area with connectors bringing PC/104 connections to the rear of an ATX case

## Reference Documentation
* [IBM, *Personal Computer XT Hardware Technical Reference*, Apr. 1983](https://archive.org/details/IBMPCXTTechnicalReference1502237)
* [Intel, *ATX Multi Rail Desktop Power Supply Design Guide*, Revision 003, Jun. 2020](https://web.archive.org/web/20210222203819/https://d2pgu9s4sfmw1s.buttfront.net/UAM/Prod/Done/a062E00001XMVETQA5/b2f2f54c-e980-7c06-4032-9bd4e037c83b?Expires=1614026599&Key-Pair-Id=APKAJKRNIMMSNYXST6UA&Signature=iVsGBI7emsEdrFsQ67~1S2M90n5TYe3~QRV4TUX1VC-EseakcayGKQeIrDqA~ls21nyFEuSEcp9TwYA2uYXHQRfrjsYAhPvPaKLNivtX25XWNG2Bqr1eajUeZY6SobcaUhqU8I1coBOXz6TzmLMmgRiy4awrNQnBFtagJsJRME50wE8zd8HrBmgITOGB7dXv9IFX3YCMPpx1PXaubRAcfm9tsS71Sn6xf2n2rSizwWA-JjXuYK6sZhXKNNzn-7FtBtRJoyx~uOnWPtvxE2i-O1X1cFFpnhq3wDn1Kubh-qttzKiRYs0pnXElqDpH4i9TFOFBCR-g2dmtm6USEUgBBA__)
* [Intel, *ATX Specification*, Version 2.2, 2004](https://web.archive.org/web/20120725150314/http://www.formfactors.org/developer/specs/atx2_2.pdf)
* [Intel, *ISA Bus Specification and Application Notes*, Revision 2.01, 12 Sep. 1989](https://archive.org/details/bitsavers_intelbusSpep89_3342148/)
* [Intel, *microATX Motherboard Interface Specification*, Version 1.2, 2004](http://www.motherboards.org/files/techspecs/matxspe1.2.pdf)
* [PC/104 Embedded Consortium, *PC/104 Specification*, Version 2.6, 13 Oct. 2008](https://pc104.org/hardware-specifications/pc104/)
* [PC/104 Embedded Consortium, *PC/104-Plus Specification*, Version 2.3, 13 Oct. 2008](https://pc104.org/hardware-specifications/pc104-plus/)
* [Tom Shanley and Don Anderson, *ISA System Architecture*, Third Edition, 1995](https://archive.org/details/ISA_System_Architecture)
