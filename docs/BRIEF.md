# Phase array antenna

Design a 28 GHz 5G NR FR2 phased-array MIMO antenna board for beamforming and beam-steering applications.

Requirements:
• Operating frequency: 27.5 GHz to 29.5 GHz (center frequency 28 GHz)
• Antenna architecture: 8x8 planar phased array (64 elements)
• Antenna type: Microstrip patch array with corporate feed network
• Element spacing: 0.5λ at 28 GHz (~5.35 mm center-to-center)
• Polarization: Dual-polarized (+45° / −45°)
• Beam steering range: ±60° in azimuth and elevation
• Peak array gain: >24 dBi
• Sidelobe level: < -13 dB
• Input impedance: 50 Ω
• Return loss: S11 < -10 dB across band
• Isolation between polarizations: >20 dB
• MIMO functionality with independent beamforming paths
• Support 5G NR bands n257, n258, and n261

RF Front End:
• 64 transmit/receive channels
• Integrated phase shifters with 6-bit phase resolution
• Per-element power amplifier and low-noise amplifier
• Beamforming IC interfaces through SPI control bus
• RF power monitoring test points

PCB Requirements:
• Board size approximately 120 mm × 120 mm
• 6-8 layer RF PCB
• Low-loss substrate (Rogers RO4350B or RO3003)
• Controlled impedance RF traces
• Via-fence shielding around RF paths
• Solid RF ground plane
• Thermal vias under beamformer ICs and PAs

Interfaces:
• SMA or 2.92 mm K-connectors for RF test access
• USB-C for control and firmware update
• Ethernet interface for beamforming control
• Status LEDs for power, transmit, receive, and fault indication
• 12 V DC input

Performance Targets:
• Array EIRP > 50 dBm
• Receiver NF < 5 dB
• Bandwidth ≥ 1 GHz
• Scan loss < 3 dB at ±45°
• Support simultaneous multi-user MIMO beamforming

Mechanical Constraints:
• Provision for RF shield can
• Edge mounting holes for enclosure integration
• Heat spreader attachment points for thermal management
• Suitable for outdoor small-cell or 5G research platform deployment

Deliverables:
• Complete schematic
• PCB layout
• Gerber files
• Beamforming control interface
• Antenna simulation reports (S-parameters, gain, radiation patterns, beam steering analysis)
• Manufacturing-ready design documentation
