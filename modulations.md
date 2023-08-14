
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

