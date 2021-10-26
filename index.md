## *nex* platform for neuroscience research

*nex* is an integrated hardware/software platform for neuroscience research, targeted at use cases requiring a small, lightweight form factor (e.g. small animal research), fully implantable packaging (e.g. chronic experiments), and closed-loop neuromodulation. The platform consists of:

* _hardware_ (nexhw): a printed circuit board (PCB) design sized for applications as small as mouse implants
* _firmware_ (nexfw): power-optimized code that runs on the implanted device, controlling a stimulation engine and transmitting recorded biosignals
* _transceiver_ (nextrx): code for a USB device to transmit/receive data between a PC and the implanted device
* _communication protocol_ (nexdp): a lightweight and ultrafast protocol for communication with data telemetry implants
* _user interface_ (nexui): an application for real-time data visualization and system control

### System functionality

* Biosignal recording
  * 4 channels, AC- or DC-coupled instrumentation amplifier w/ variable gain (100 or 200 V/V)
  * Independent references
  * 16-bit, 250ksps ADC
  * Multiplexed inputs
  * 10 kHz sample rate
* Stimulation
  * ±2.5 mA amplitude
  * ±10V compliance
  * 50 µs timing
  * Passive charge recovery/electrode discharge switch
* Wireless microcontroller (nRF52840)
* Sensor excitation
  * Precision 2.5V output for use with piezoresistive pressure transducers
* On-board sensors
  * Humidity/temperature
  * Accelerometer
* Wireless charging
  * AC rectification for magnetic resonant charging (LTC4124)
  * CC/CV LiPo charging circuit
  * Built-in LiPo protection circuit
  * Battery voltage and current monitoring

### Support or Contact

* Timir Datta-Chaudhuri (tdatta@northwell.edu)
* Jason Wright (jason@jpw.nyc)

