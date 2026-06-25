# RTAL-EST-001-ESP32-Effects-Processor-for-the-TubeOhm-Jeannie
Exploring how a modern ESP32 DSP can be integrated into an existing synthesizer architecture.

RTAL-EST-001

ESP32 Effects Processor for the TubeOhm Jeannie

Engineering Study

“Exploring how a modern ESP32 DSP can be integrated into an existing synthesizer architecture.”

⸻

Engineering Study

This repository documents the design and implementation of a custom ESP32-based stereo effects processor developed for the TubeOhm Jeannie synthesizer.

The original Jeannie synthesizer is the outstanding work of Rolf Degen (TubeOhm Instruments).

This repository documents only the custom hardware, firmware and integration work developed for replacing the original FV-1 effects processor.

⸻

Background

The TubeOhm Jeannie is one of the most impressive DIY synthesizers available today.

Originally designed by Rolf Degen, the instrument combines virtual analog synthesis, wavetable synthesis, modulation, filters and effects into a compact and powerful musical instrument.

During the construction of my own Jeannie, I decided to build the complete hardware entirely on stripboard (Veroboard) using traditional wire-wrap / point-to-point wiring techniques instead of manufacturing printed circuit boards.

While preserving the original synthesizer architecture, I replaced the original FV-1 DSP effects board with a completely custom effects processor based on the ESP32.

The objective was not to redesign the synthesizer itself, but to explore the possibilities offered by modern embedded DSP technology while maintaining compatibility with the original instrument.

⸻

Project Goals

* Replace the FV-1 effects processor
* Develop a custom ESP32 DSP board
* Preserve compatibility with the original Jeannie
* Improve flexibility for future DSP algorithms
* Learn and document the complete integration process

⸻

Original Jeannie

Original Design

Rolf Degen

TubeOhm Instruments

The Jeannie synthesizer hardware and firmware are entirely the work of Rolf Degen.

This repository is not intended as a replacement for the original project.

Instead, it documents an engineering modification built around the original synthesizer.

Please visit the original project:

* TubeOhm Instruments
* Jeannie Open Source Repository

⸻

RTAL Contribution

This repository documents the following original developments.

Hardware

* Custom ESP32 DSP board
* Power supply adaptation
* Mechanical integration
* Stripboard implementation
* Wiring documentation

Firmware

* ESP32 audio firmware
* Effect integration
* Communication with Jeannie
* User interface adaptation

⸻

DSP Algorithms

Some effects implemented on the ESP32 are based on open-source DSP libraries developed by Marcel Licence.

These algorithms have been integrated, adapted and extended for this project.

Special thanks for his outstanding work in embedded audio development.

⸻

Construction

Unlike the original PCB-based implementation, this instrument was completely constructed using

* stripboard
* point-to-point wiring
* hand soldering

This repository documents the complete construction process.

⸻

Gallery

(Insert photographs here)

Suggested image sequence:

* Complete synthesizer
* Front panel
* Rear panel
* Internal overview
* Stripboard construction
* ESP32 effects board
* Wiring details
* Finished instrument

⸻

Engineering Notes

Why replace the FV-1?

The objective was not to improve the original design.

Instead, the project explores the possibilities offered by modern ESP32 processors for real-time digital audio effects.

The ESP32 platform enables significantly greater computational flexibility while providing an open development environment.

⸻

Engineering Contributions

Component	Author
Jeannie Synthesizer	Rolf Degen
Original Firmware	Rolf Degen
ESP32 Effects Hardware	Andreas Hülsmann
ESP32 Effects Firmware	Andreas Hülsmann
Mechanical Integration	Andreas Hülsmann
Stripboard Construction	Andreas Hülsmann
Selected DSP Libraries	Marcel Licence

⸻

Credits

Special thanks to

* Rolf Degen
* Marcel Licence
* Bodmer
* Paul Stoffregen
* Espressif Systems
* Arduino Community

without whose work this engineering study would not have been possible.

⸻

Engineering Heritage Collection

This repository forms part of the

RTAL Engineering Heritage Collection

which documents original hardware developments, engineering studies and embedded audio projects.

The purpose is not only to preserve hardware but also the engineering knowledge behind it.

⸻

Final Thoughts

This project demonstrates that modern embedded processors can successfully be integrated into classic synthesizer architectures while respecting and preserving the work of the original designer.

It is intended as an engineering study and as a tribute to the creativity of the DIY synthesizer community.

⸻

© 2026 RealTimeAudioLab

Engineering Heritage Collection

“Preserving Engineering — Not Just Hardware.”