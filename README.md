# 📻 AM Radio Receiver Using BJTs

### 🔧 23ECE282 – Analog Electronics Lab Term Project

---

## 📘 Project Description

This project demonstrates the **design, simulation, and implementation of an AM radio receiver circuit** using **Bipolar Junction Transistors (BJTs)**. The objective was to receive, demodulate, and amplify AM signals to obtain a clear audio output.

---

## 🧠 Core Concepts

- **Amplitude Modulation (AM)**: Varying the amplitude of a carrier wave in accordance with the audio signal.
- **Demodulation**: Extracting the original audio signal from the modulated carrier.
- **Tuning Circuit**: Selecting the desired frequency using a resonant LC circuit.
- **Amplification**: Boosting the demodulated audio signal for output.

---

## 🛠️ Circuit Design Stages

1. **Signal Source**  
   - V3 (550 kHz carrier), V4 (1.5 kHz audio) for AM generation.

2. **Mixer Stage**  
   - Combines carrier and audio using multiplier component (B1).

3. **Tuned LC Circuit**  
   - L1 (1 µH) and C1 (400 nF) form a resonant filter tuned to 550 kHz.

4. **Demodulation**  
   - D2 (1N5817) rectifies the AM signal to extract audio.

5. **Amplifier Stage**  
   - Q1 (BC547B or 2N2222) boosts the demodulated audio signal.

6. **Filtering and Output**  
   - Capacitors and resistors filter noise and prepare signal for output.

---

## 🧪 Simulation Results

- **Input Signals**: Carrier and audio waveforms.
- **Mixed Signal**: Modulated AM waveform.
- **Demodulated Output**: Rectified audio waveform.
- **Amplified Output**: Strong, clean audio signal.

---

## 🔬 Experimental Results

- Real-world circuit built and tested.
- Audio signals successfully received and demodulated.
- Peak Gain observed: **~60.7x** at optimal tuning.

| Carrier Freq | Audio Freq | Input Vpp | Output Vpp | Gain |
|--------------|------------|-----------|------------|------|
| 550 kHz      | 1.5 kHz    | 100 mV    | 6.07 V     | 60.7 |

---

## 🎯 Conclusion

The project successfully demonstrates an AM receiver using BJTs. The circuit:
- **Tuned** accurately to AM frequencies.
- **Demodulated** signals using a diode detector.
- **Amplified** audio using a common-emitter BJT amplifier.

Further enhancements could include **variable tuning**, **multi-band support**, and **speaker integration**.

