## 🌟 Introduction
This EasyEffects preset uses psychoacoustic principles to enhance your audio experience. It features an 8-band multiband compressor (MBC) aligned with human hearing (Bark scale) for natural sound improvement on both headphones and speakers.

This preset uses scientifically-backed principles to enhance your listening experience:  

- **Bark Scale Alignment**: 8 frequency bands matching human auditory perception  
- **Time Constant Optimization (τ)**: Attack/release times match neural processing speeds  
- **Upward Compression**: Boosts quiet details without making loud sounds harsh  
- **Dynamic Effect**: Multiband compression creates natural tonal balance  
- **Phase Coherence**: Preserves spatial cues and instrument positioning  

## 🎚️ What This Preset Does
Bass: Full but controlled (no boominess)<br>
Vocals: Clear and natural<br>
Highs: Detailed but not harsh<br>
Soundstage: Wider and spatial

## 🎧 For Headphone Users (Important)
Place your AutoEQ headset correction profile **after** the MBC:<br>
Source → [25Hz EQ Filter] → [8-Band MBC] → [Your AutoEQ Profile] → [Limiter] → Output

- Let psychoacoustic processing enhance your headphones' natural response  
- Prevent EQ corrections from being altered by compression  
- Maintain precise frequency correction  

Your headphones get the full benefit of psychoacoustic processing

## 🧠 Fatigue Reduction - Brain-Friendly Time Constants
This preset uses precision-timed processing (tau values) that match how your brain processes sound.
The MBC significantly reduces listening fatigue during long sessions because:

→ Compression timing matches neural processing speeds<br>
→ Transients arrive in sync across frequencies<br>
→ No timing conflicts to mentally resolve<br>
→ Upward compression gently reveals details (no harsh boosting)<br>
→ Downward compression prevents "frequency fatigue" in critical ranges<br>
→ Consistent dynamics prevent subconscious straining to hear<br>

Result: Music feels more natural to follow, with less ear fatigue.


## Multiband Compressor Parameters (V3)

| Band | Split Frequency (Hz) | Sidechain Lowcut (Hz) | Sidechain Highcut (Hz) | Mode     | Attack Thresh (dB) | Attack Time (ms) | Release Time (ms) | Ratio | Knee (dB) |
| ---- | -------------------- | --------------------- | ---------------------- | -------- | ------------------ | ---------------- | ----------------- | ----- | --------- |
| 1    | —                    | 25.0                  | 100.0                  | Upward   | -42.00             | 100.0            | 400.0             | 1.12  | 0.0       |
| 2    | 100.0                | 100.0                 | 200.0                  | Downward | -20.00             | 60.0             | 180.0             | 1.85  | -12.0     |
| 3    | 200.0                | 200.0                 | 400.0                  | Downward | -18.00             | 40.0             | 160.0             | 1.65  | -8.0      |
| 4    | 400.0                | 400.0                 | 800.0                  | Downward | -16.00             | 30.0             | 140.0             | 1.55  | -6.0      |
| 5    | 800.0                | 800.0                 | 1600.0                 | Downward | -15.00             | 25.0             | 120.0             | 1.45  | -4.0      |
| 6    | 1600.0               | 1600.0                | 3200.0                 | Downward | -14.00             | 20.0             | 100.0             | 1.35  | -3.0      |
| 7    | 3200.0               | 3200.0                | 8000.0                 | Upward   | -28.00             | 10.0             | 80.0              | 1.06  | -4.0      |
| 8    | 8000.0               | 8000.0                | 20000.0                | Upward   | -32.00             | 5.0              | 60.0              | 1.04  | 0.0       |
