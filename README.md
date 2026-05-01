📡 Project PAGE Emulator

Project PAGE Emulator is a research and development platform for emulating a P25 SmartConnect®-compatible environment, allowing subscriber radios to establish secure connections and interact with a simulated trunked system over IP.

The project focuses on:

Emulating SmartConnect® TLS session handling
Reproducing radio authentication workflows
Delivering system information and control channel context
Observing and analyzing radio behavior during affiliation and system interaction
This platform is designed for protocol research, interoperability testing, and educational exploration of P25 network behavior — particularly how subscriber units interact with IP-based system extensions.



⚙️ Foundation & Acknowledgment

This project builds upon the excellent work of the DVMProject (Digital Voice Modem Project).

Specifically, it leverages:

DVMHost for system/channel management
DVMFNE for network authentication and peer handling
These tools provide the core infrastructure for P25 system emulation, and this project extends them by introducing a SmartConnect® bridge layer to interface directly with subscriber radios over TLS.

Full credit goes to the DVMProject contributors for their foundational work enabling this system.



🔍 Project Scope

The emulator currently supports:

TLS-based SmartConnect® session establishment
Radio authentication (RPTL / RPTK / RPTC workflows)
System Info delivery to subscriber units
Session lifecycle handling and cleanup
Packet capture and protocol-level analysis
Ongoing development is focused on:

Decoding and responding to radio-originated application messages
Completing full affiliation workflows
Improving system realism and control channel simulation


⚠️ Disclaimer

This project is intended for:

Research and development
Educational use
Protocol analysis in controlled environments
It is not intended for use on live production radio systems or any unauthorized networks.

Users are responsible for complying with all applicable laws, regulations, and licensing requirements.



🔐 Security Note

Sensitive components such as:

Private keys and certificates
System configurations
Network identifiers
are intentionally excluded from this repository.



📛 Trademark Notice

Motorola® and SmartConnect® are registered trademarks of Motorola Solutions, Inc.

All other product names, trademarks, and registered trademarks are the property of their respective owners.

This project is not affiliated with, endorsed by, or sponsored by Motorola Solutions, Inc.



🚧 Status

Active development — progressing toward full SmartConnect® session emulation and subscriber affiliation support.
