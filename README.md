## 🌟 Introduction
This EasyEffects preset uses psychoacoustic principles to enhance your music listening experience. It features an 8-band multiband compressor (MBC) aligned with human hearing (Bark scale) for natural sound improvement on both headphones and speakers.

This preset uses scientifically-backed principles to enhance your listening experience:  

- **Bark Scale Alignment**: 8 frequency bands matching human auditory perception
- **Automatic Calibration**: Self-adjusting to your audio content
- **Time Constant Optimization**: Attack/release times match neural processing speeds  
- **Upward Compression**: Boosts quiet details without making loud sounds harsh  
- **Dynamic Effect**: Multiband compression creates natural tonal balance  
- **Phase Coherence**: Preserves spatial cues and instrument positioning  

## 🎚️ Sound Improvements:

- **Sub-bass (20-100Hz):** Physical rumble without distortion, no boominess
- **Bass (100-200Hz):** Tight and controlled foundation
- **Mid-range (200-3200Hz):** Natural vocal and instrument clarity
- **Highs (3200Hz+):** Detailed brilliance without harshness
- **Soundstage:** Expanded width and depth with precise imaging
- **Volume Independence:** Maintains clarity and definition even at lower listening volumes

⚠️ **Usage Notes**  
Start with **-6 dB** system volume when first enabling.  
Allow **48 hours** for your brain to fully adapt to the new sound stage.

## 🎧 For Headphone Users (Important)
Place your AutoEQ headset correction profile (if you have any) **after** the MBC:<br><br>
Source → [25Hz EQ Filter] → [8-Band MBC] → [Your AutoEQ Profile] → [Limiter] → Output

**Why This Order Matters**

- The MBC needs to analyze the original recording dynamics
- Headphone correction changes frequency response, which would alter how the MBC processes sound
- Placing correction after MBC preserves spatial cues and dynamic processing integrity

Your headphones get the full benefit of psychoacoustic processing.

## 🔍 Hearing the Difference

**Quick Test Method:**
1. Play familiar music [Song](https://www.youtube.com/watch?v=oq5X2G5qKQI) [Song](https://www.youtube.com/watch?v=V9PVRfjEBTI)
2. Toggle MBC on/off while listening
3. Notice these changes:

| Aspect              | With MBC Enabled                                | With MBC Disabled                      |
|---------------------|-------------------------------------------------|----------------------------------------|
| Bass Detail         | ✅ Deeper but tighter                           | Less defined, more blended             |
| Vocal Clarity       | ✅ Enhanced clarity, more intelligible words    | Slightly muffled                       |
| Cymbal Decay        | ✅ Smoother high-frequency decay                | Highs may sound dull or sharp, Quicker fade-out  |
| Background Details  | ✅ Subtle elements more audible                 | Harder to distinguish                  |
| Overall Fatigue     | ✅ Less listening fatigue                       | More fatigue at high volumes           |

> Note: The difference is often perceived as "removing a thin veil" rather than dramatic change. Your brain may initially interpret it as slightly quieter but clearer sound.

**Why Some Songs Show Minimal or No Change?**  
This preset reveals existing quality rather than adding effects. You'll notice:  

- **Responds to source material:** Well-recorded tracks show less change  
- **Focuses on deficiencies:** Only enhances masked frequencies  
- **Avoids over-processing:** Never adds artificial effects  
- **Prioritizes dynamics:** Changes are more apparent in dynamic passages  

**Volume-Independent Clarity**  
This preset maintains exceptional clarity even at lower volumes by:  

- Enhancing subtle details often masked at quiet levels  
- Balancing frequency response dynamically  
- Preserving spatial cues regardless of volume  
- Optimizing the ear's sensitivity curve

**To see real-time MBC processing in EasyEffects:**

1. Go to **Preferences → Experimental Features**.
2. Enable **Native Plugin Window**.
3. In the MBC plugin, click **Show Native Window** to view the real-time processing.
> Tip: In the LSP MBC window, use the **Zoom** slider (to the right of the graph) and drag it all the way down to see detailed band movements.

**Why This Matters:**

- **Headphones:** Without AutoEQ, differences are more obvious because you hear the MBC enhancing your headphones' natural response  
- **Speakers:** Benefits rooms by controlling resonances and improving clarity  
- **Brain Adaptation:** Effects become more natural sounding after 15–60 minutes of listening

## Brain Interpretation

When enabling MBC, you'll experience:

- **0–15 seconds:** Subtle "cleaning" effect 
- **15–60 seconds:** Perceived clarity enhancement 
- **1+ minute:** Natural immersion as brain accepts enhanced spatial cues

Disabling MBC will reveal:

*brain working harder more to follow music*

- Flatter dynamic range 
- Reduced spatial depth
- Less defined frequency balance

⚠️ Allow **48 hours** for your brain to fully adapt to the new sound stage.

## 🧠 Fatigue Reduction
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

This preset uses just one EQ band (**25 Hz high-pass filter**) because the 8-band compressor dynamically adjusts all frequencies in real-time, making additional EQ adjustments unnecessary and potentially disruptive to its natural sound enhancement. The high-pass filter also eases the MBC’s processing by removing unwanted low-end frequencies.

**Key Reasons:**

- 🎛️ **The MBC acts like a "Smart EQ":** It constantly fine-tunes frequencies based on the source music instantly and dynamically.  
- ⚖️ **Avoids Double-Processing:** Adding EQ would fight the compressor's natural adjustments  
- 🔊 **Headroom Protection:** The 25 Hz filter removes damaging sub-bass rumble

*Note: The EQ is set to FIR mode for better sound quality (adds some latency); switch to IIR for lower latency at a noticable trade-off in quality.*

## 🌟 **The Final Truth**  
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


