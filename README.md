# Analog-Frequency-Based-Security-System


## Overview

The Analog Frequency Based Security System is a low-cost access control solution that uses a specific audio frequency as a security key. Unlike conventional digital authentication methods, this system relies entirely on analog electronics to detect and validate a predefined frequency.

## How It Works

1. An electret microphone captures the incoming audio signal.
2. The signal is amplified using an operational amplifier.
3. A band-pass filter allows only the target frequency (around 1 kHz) to pass.
4. A comparator verifies whether the detected signal matches the required frequency.
5. A 555 timer configured in monostable mode generates a fixed-duration output pulse.
6. The output activates a relay, LED, or buzzer to indicate successful authentication.

## Features

* Frequency-based access control
* No microcontroller required
* Low-cost and easy-to-build design
* Noise-resistant operation using analog filtering
* Educational demonstration of analog signal processing

## Components Used

* Electret Microphone
* Operational Amplifier (Op-Amp)
* Band-Pass Filter Circuit
* Comparator
* NE555 Timer IC
* Relay / LED / Buzzer
* Resistors and Capacitors
* Breadboard and Power Supply

## Applications

* Door Access Systems
* Electronic Lockers
* Anti-Theft Devices
* Educational Analog Electronics Projects

## Future Improvements

* Multiple-frequency authentication
* Increased sensitivity and detection range
* Relay-controlled electronic door lock integration
* Enhanced noise immunity
