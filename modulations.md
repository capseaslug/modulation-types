
**Amplitude Modulation (AM):**

Equation:
```plaintext
x(t) = A * (1 + mi * m(t)) * cos(2 * π * fc * t)
```

Parameters:
- `A`: Amplitude of the carrier signal.
- `fc`: Carrier frequency.
- `mi`: Modulation index.
- `m(t)`: Message signal.

Additional Data:
- Modulation Type: Amplitude Modulation (AM)
- Carrier Waveform: Sinusoidal
- Modulating Waveform: Sinusoidal, Sawtooth
- Applications: AM radio broadcasting, long-distance communication
- Common Broadcasting Power: 1 kW to 50 kW
- Inverse Demodulation Equation: `m(t) = x(t) / (A * (1 + mi * m(t)))`


**Frequency Modulation (FM):**

Equation:
```plaintext
x(t) = A * cos(2 * π * fc * t + k * integral(signal, dt))
```

Parameters:
- `A`: Amplitude of the carrier signal.
- `fc`: Carrier frequency.
- `k`: Frequency modulation sensitivity.
- `signal`: Modulating signal.

Additional Data:
- Modulation Type: Frequency Modulation (FM)
- Carrier Waveform: Sinusoidal
- Modulating Waveform: Sinusoidal
- Applications: FM radio broadcasting, analog TV broadcasting
- Common Broadcasting Power: 1 kW to 100 kW
- Inverse Demodulation Equation: Demodulation of FM signals involves complex signal processing and is usually performed using FM demodulators.


**Phase Modulation (PM):**

Equation:
```plaintext
x(t) = A * cos(2 * π * fc * t + k * m(t))
```

Parameters:
- `A`: Amplitude of the carrier signal.
- `fc`: Carrier frequency.
- `k`: Phase modulation sensitivity.
- `m(t)`: Modulating signal.

Additional Data:
- Modulation Type: Phase Modulation (PM)
- Carrier Waveform: Sinusoidal
- Modulating Waveform: Sinusoidal, Digital bits
- Applications: Phase-shift keying (PSK), digital communication
- Common Broadcasting Power: N/A (mainly used for digital communication)
- Inverse Demodulation Equation: Demodulation of PM signals involves complex signal processing and is typically performed using phase detectors.


**Pulse Width Modulation (PWM):**

In Pulse Width Modulation (PWM), analog information is encoded into digital signals by altering the width of pulses within a periodic waveform. This technique finds applications in motor control, audio synthesis, and power converters.

**Equation:**
```plaintext
x(t) = PWM(t, D)
```

**Parameters:**
- `D`: Duty cycle of the PWM signal.

**Additional Data:**
- Modulation Type: Pulse Width Modulation (PWM)
- Carrier Waveform: Square
- Modulating Waveform: Analog signal
- Applications: Motor control, audio synthesis, power converters
- Common Broadcasting Power: N/A (typically used for control and synthesis)
- Inverse Demodulation Equation: Demodulation of PWM signals involves controlling actuators or devices based on the duty cycle of the signal. It's not usually demodulated in the same way as traditional modulation techniques.



**Amplitude Shift Keying (ASK):**

Equation:
```plaintext
x(t) = A * (1 + m(t)) * cos(2 * π * fc * t)
```

Parameters:
- `A`: Amplitude of the carrier signal.
- `fc`: Carrier frequency.
- `m(t)`: Digital message signal.

Additional Data:
- Modulation Type: Amplitude Shift Keying (ASK)
- Carrier Waveform: Sinusoidal
- Modulating Waveform: Digital bits
- Applications: Digital communication, RFID systems
- Common Broadcasting Power: N/A (mainly used for short-range communication)
- Inverse Demodulation Equation: `m(t) = (x(t) / A) - 1`

**Frequency Shift Keying (FSK):**

Equation:
```plaintext
x(t) = A * cos(2 * π * f1 * t + φ(m(t)))
```

Parameters:
- `A`: Amplitude of the carrier signal.
- `f1`: Frequency for binary value "1".
- `φ(m(t))`: Phase deviation based on modulating signal.

Additional Data:
- Modulation Type: Frequency Shift Keying (FSK)
- Carrier Waveform: Sinusoidal
- Modulating Waveform: Digital bits
- Applications: Digital communication, wireless remote control
- Common Broadcasting Power: N/A (mainly used for short-range communication)
- Inverse Demodulation Equation: Demodulation of FSK signals involves using frequency detectors for each binary value.


**Amplitude Shift Keying (ASK):**

Amplitude Shift Keying (ASK) is a digital modulation technique that varies the amplitude of a carrier signal to transmit digital data.

**Equation:**
```plaintext
x(t) = A * (1 + m(t)) * cos(2 * π * fc * t)
```

**Parameters:**
- `A`: Amplitude of the carrier signal.
- `fc`: Carrier frequency.
- `m(t)`: Digital message signal.

**Additional Data:**
- Modulation Type: Amplitude Shift Keying (ASK)
- Carrier Waveform: Sinusoidal
- Modulating Waveform: Digital bits
- Applications: Digital communication, RFID systems
- Common Broadcasting Power: N/A (mainly used for short-range communication)
- Inverse Demodulation Equation: `m(t) = (x(t) / A) - 1`

**Frequency Shift Keying (FSK):**

Frequency Shift Keying (FSK) is a digital modulation technique where different carrier frequencies represent different digital symbols.

**Equation:**
```plaintext
x(t) = A * cos(2 * π * f1 * t + φ(m(t)))
```

**Parameters:**
- `A`: Amplitude of the carrier signal.
- `f1`: Frequency for binary value "1".
- `φ(m(t))`: Phase deviation based on modulating signal.

**Additional Data:**
- Modulation Type: Frequency Shift Keying (FSK)
- Carrier Waveform: Sinusoidal
- Modulating Waveform: Digital bits
- Applications: Digital communication, wireless remote control
- Common Broadcasting Power: N/A (mainly used for short-range communication)
- Inverse Demodulation Equation: Demodulation of FSK signals involves using frequency detectors for each binary value.

