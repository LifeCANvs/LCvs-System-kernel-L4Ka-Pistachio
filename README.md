# L4Ka::Pistachio microkernel

L4Ka::Pistachio is the latest L4 microkernel developed by the System Architecture Group at the University of Karlsruhe in collaboration with the DiSy group at the University of New South Wales, Australia. It is the first available kernel implementation of the L4 Version 4 kernel API (currently code-named Version X.2), which is fully 32 and 64 bit clean, provides multiprocessor support, and super-fast local IPC.

The current release of L4Ka::Pistachio is version 0.4. Read the official announcement message.

L4Ka::Pistachio is built from ground up incorporating the research results of the last seven years of microkernel and multi-server research.
The code is written in C++ with a strong focus on performance and portability.

The current release includes many of today's widely used commodity architectures:
- x86-x64 (AMD64/EM64T, K9 / P4 and higher)
- x86-x32 (IA32, Pentium and higher)
- PowerPC 32bit (IBM 440, AMCC Ebony / Blue Gene P) 

The variety of supported architctures makes L4Ka::Pistachio an ideal research and development platform for a wide variety of systems.

## Documentation

    L4 Version X.2 Reference Manual (Latest snapshot, July 19 2010)
    L4 Version X.2 Reference Manual (Rev. 6, May 4 2009)
    The reference manual serves as the defining document for the API and all ABIs. Its key point is precise definition, not explanation and illustration. Please note that Version X.2 is still in an experimental stage and the interface may change significantly. Features may be added, dropped, or modified without notice.
    L4Ka::Pistachio Whitepaper
    This document gives a broad overview of the key features of the Version 4 API and the L4Ka::Pistachio microkernel.
    L4Ka::Pistachio FAQ
    Frequently asked questions about L4Ka::Pistachio and some answers. This FAQ is maintained by the L4Ka::Pistachio user community.
    L4 System Programmer's Manual
    We plan to publish a developers manual describing design concepts and reasoning for developers using the L4 Version 4 API. This document is supposed to picture construction principles of systems on top of L4.

## Discussions

    https://lists.ira.uni-karlsruhe.de/pipermail/l4ka/ mailing list (subscribe here)
    This mailing list is intended for all L4Ka related issues, including L4Ka::Pistachio, API and architecture related topics. All core developers are actively watching this list.
    Internet Relay Chat
    Sometimes, the members of the L4Ka team and UNSW are on channel #elf|ka of irc.slashnet.org.

## Availability and licensing

L4Ka::Pistachio is available for download via remote mercurial access. The source code is open source and released under the two-clause BSD license.

