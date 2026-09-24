# Inverting and Non-Inverting Amplifier

## Aim

This experiment consists of designing and verifying:

1. **Inverting Amplifier** using an op-amp for a given gain of **−2**.
2. **Non-Inverting Amplifier** using an op-amp for a given gain of **2**.

## Apparatus Required

* Operational Amplifier IC 741
* Resistors: **1 kΩ and 2 kΩ**
* Breadboard / Trainer Kit
* Function Generator
* CRO (Cathode Ray Oscilloscope)
* Dual Power Supply
* Connecting Wires

The inverting amplifier setup uses IC 741, 1 kΩ and 2 kΩ resistors, a trainer kit/breadboard, CRO, and function generator.

## 1. Inverting Amplifier

### Principle

An inverting amplifier produces an output that is **amplified and 180° out of phase** with the input signal.

### Procedure

1. Connect IC 741 on the trainer kit.
2. Provide dual power supply (+Vcc and −Vcc) to the IC.
3. Make the circuit connections according to the circuit diagram.
4. Apply a sinusoidal input signal from the function generator to the inverting terminal.
5. Ground the non-inverting terminal.
6. Connect the feedback resistor between the output and inverting terminal.
7. Switch ON the power supply and CRO.
8. Observe the input and output waveforms on the CRO.
9. Verify that the output is amplified and 180° out of phase with the input.
10. Tabulate the readings.

### Observation

| S.No | Vin (V) | Vout (V) | Practical Gain | Theoretical Gain |
| ---- | ------: | -------: | -------------: | ---------------: |
| 1    |       1 |     -2.6 |           -2.6 |             -2.2 |
| 2    |       2 |       -5 |           -2.5 |             -2.2 |
| 3    |       3 |     -7.2 |           -2.4 |             -2.2 |
| 4    |       4 |     -9.4 |          -2.35 |             -2.2 |

The observation values are taken directly from the practical record.

### Result

The working of the **inverting amplifier** was studied and verified successfully.

---

## 2. Non-Inverting Amplifier

### Principle

A non-inverting amplifier produces an output that is **amplified and in phase** with the input signal.

### Procedure

1. Place IC 741 on the trainer kit.
2. Connect a dual power supply of **±12 V** to the IC.
3. Make the connections according to the circuit diagram.
4. Apply a sinusoidal input signal from the function generator to the non-inverting terminal.
5. Connect the feedback resistor (Rf) and resistor (R1) properly.
6. Switch ON the power supply and CRO.
7. Observe the input and output waveforms on the CRO.
8. Measure input voltage, output voltage, time period, and frequency.
9. Verify that the output waveform is amplified and in phase with the input.
10. Tabulate the readings.

### Observation

| S.No | Vin (V) | Vout (V) | Practical Gain | Theoretical Gain |
| ---- | ------: | -------: | -------------: | ---------------: |
| 1    |     0.5 |     1.38 |           3.76 |              2.2 |
| 2    |       1 |     2.94 |           3.94 |              2.2 |
| 3    |     1.5 |     4.73 |          4.153 |              2.2 |
| 4    |       2 |     6.26 |           4.13 |              2.2 |
| 5    |     2.5 |     7.96 |           4.18 |              2.2 |
| 6    |       3 |     9.50 |           4.16 |              2.2 |
| 7    |     3.6 |    10.57 |          3.936 |              2.2 |

The readings above are taken from the observation table in the uploaded practical.

### Result

The **non-inverting amplifier** was designed and verified successfully.

---

## Key Difference

| Feature         | Inverting Amplifier | Non-Inverting Amplifier |
| --------------- | ------------------- | ----------------------- |
| Input terminal  | Inverting (−)       | Non-inverting (+)       |
| Output phase    | 180° out of phase   | In phase                |
| Experiment Gain | −2                  | 2                       |
| Op-Amp          | IC 741              | IC 741                  |

## Conclusion

The **inverting and non-inverting amplifier circuits** were implemented using IC 741. Their input and output waveforms were observed using a CRO, and the amplifier operation was successfully verified.
