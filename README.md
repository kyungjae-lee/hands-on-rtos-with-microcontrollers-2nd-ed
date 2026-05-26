# hands-on-rtos-with-microcontrollers-2nd-ed
A collection of example projects and experiments for studying "Hands-On RTOS with Microcontrollers (2nd Edition)".



## Notes

### Chapter 03

* [SEGGER SystemView] Target | Recorder Configuration | J-Link will not show the pop-up window for further configuration if [J-Link Software and Documentation Pack](https://www.segger.com/downloads/jlink/#J-LinkSoftwareAndDocumentationPack) is not installed. (v8.30 is used.)

### Chapter 05

* Read/write atomicity is typically guaranteed only when the following two conditions are met:
  1. Variable size must not exceed the native memory access width (i.e., the processor word size).
  2. The variable must be naturally aligned (e.g., on a 32-bit architecture, a 32-bit variable should be aligned to a 4-byte boundary).
