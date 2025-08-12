## 🌟 Introduction
This EasyEffects preset uses psychoacoustic principles to enhance your audio experience. It features an 8-band multiband compressor (MBC) aligned with human hearing (Bark scale) for natural sound improvement on both headphones and speakers.

This preset uses scientifically-backed principles to enhance your listening experience:  

- **Bark Scale Alignment**: 8 frequency bands matching human auditory perception  
- **Time Constant Optimization**: Attack/release times match neural processing speeds  
- **Upward Compression**: Boosts quiet details without making loud sounds harsh  
- **Dynamic Effect**: Multiband compression creates natural tonal balance  
- **Phase Coherence**: Preserves spatial cues and instrument positioning  

## 🎚️ Sound Improvements:

- **Bass:** Powerful yet controlled, no boominess
- **Midrange:** Natural instrument reproduction
- **Vocals:** Clear and natural
- **Highs:** Detailed but not harsh
- **Soundstage:** Wider and spatial

**System-Wide Benefits**
- 🎧 Headphones: Enhanced spatial cues, reduced listening fatigue  
- 🔈 Speakers: Improved room interaction, tighter bass response  
- 🎛 All Systems: Consistent tonal balance across content types

⚠️ **Usage Notes**  
Start with **-6 dB** system volume when first enabling.  
Allow **48 hours** for your brain to fully adapt to the new sound stage.

## 🎧 For Headphone Users (Important)
Place your AutoEQ headset correction profile (if you have any) **after** the MBC:<br><br>
Source → [25Hz EQ Filter] → [8-Band MBC] → [Your AutoEQ Profile] → [Limiter] → Output

- Let psychoacoustic processing enhance your headphones' natural response  
- Prevent EQ corrections from being altered by compression  
- Maintain precise frequency correction  

Your headphones get the full benefit of psychoacoustic processing

## 🔍 Hearing the Difference

**Quick Test Method:**
1. Play familiar music
2. Toggle MBC on/off while listening
3. Notice these changes:

| Enabled | Disabled |
|---------|----------|
| Bass sounds deeper but tighter | Bass may sound weaker or boomy |
| Enhanced vocal clarity | Vocals get buried in instruments |
| Smoother high-frequency decay | Highs may sound dull or sharp |
| Sound feels more natural and "spatial" | Soundstage feels flatter |

**Why This Matters:**

- **Headphones:** Without AutoEQ, differences are more obvious because you hear the MBC enhancing your headphones' natural response  
- **Speakers:** Benefits rooms by controlling resonances and improving clarity  
- **Brain Adaptation:** Effects become more natural sounding after 15–60 minutes of listening

## Brain Interpretation

When enabling MBC, you'll experience:

- **0–15 seconds:** Subtle "cleaning" effect *(brain adjusting to noise reduction)*
- **15–60 seconds:** Perceived bass enhancement *(upward compression working)*
- **1+ minute:** Natural immersion as brain accepts enhanced spatial cues

Disabling MBC will reveal:

- Compressed dynamic range *(especially in complex passages)*
- Reduced spatial depth
- Less defined frequency balance

⚠️ Allow **48 hours** for your brain to fully adapt to the new sound stage.

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

## Why Only 1 EQ Band? (High-Pass Filter)

This preset uses just one EQ band (**25 Hz high-pass filter**) because the 8-band compressor dynamically adjusts all frequencies in real-time, making additional EQ adjustments unnecessary and potentially disruptive to its natural sound enhancement.

**Key Reasons:**

- 🎛️ **The MBC is a "Smart EQ":** It constantly fine-tunes frequencies based on what you're hearing  
- ⚖️ **Avoids Double-Processing:** Adding EQ would fight the compressor's natural adjustments  
- 🔊 **Headroom Protection:** The 25 Hz filter removes damaging sub-bass rumble

🌟 **The Final Truth**  
This isn't EQ – it's dynamic range optimization using hearing science. Like cleaning a window.  
The result? Your music sounds more like itself – just clearer, more balanced, and easier to enjoy for hours.  
No magic, just science.

## Multiband Compressor Parameters (V3)

| Band | Frequency range (Hz) | Split (upper) Hz | Sidechain low (Hz) | Sidechain high (Hz) | Mode     | Attack Thresh (dB) | Attack (ms) | Release (ms) | Ratio |
| ---- | -------------------: | ---------------: | -----------------: | ------------------: | -------- | -----------------: | ----------: | -----------: | ----: |
| 1    |              0 – 100 |              100 |               25.0 |               100.0 | Upward   |             -42.00 |       100.0 |        400.0 |  1.12 |
| 2    |            100 – 200 |              200 |              100.0 |               200.0 | Downward |             -20.00 |        60.0 |        180.0 |  1.85 |
| 3    |            200 – 400 |              400 |              200.0 |               400.0 | Downward |             -18.00 |        40.0 |        160.0 |  1.65 |
| 4    |            400 – 800 |              800 |              400.0 |               800.0 | Downward |             -16.00 |        30.0 |        140.0 |  1.55 |
| 5    |           800 – 1600 |             1600 |              800.0 |              1600.0 | Downward |             -15.00 |        25.0 |        120.0 |  1.45 |
| 6    |          1600 – 3200 |             3200 |             1600.0 |              3200.0 | Downward |             -14.00 |        20.0 |        100.0 |  1.35 |
| 7    |          3200 – 8000 |             8000 |             3200.0 |              8000.0 | Upward   |             -28.00 |        10.0 |         80.0 |  1.06 |
| 8    |         8000 – 20000 |      20000 (top) |             8000.0 |             20000.0 | Upward   |             -32.00 |         5.0 |         60.0 |  1.04 |

(AI assisted writing)

