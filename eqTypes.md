# TECHNICAL GUIDE: EQUALIZATION TYPES AND BANDS
# Developed by Gemini 3 Flash (AI) with User Direction

This document covers the essential types of EQ processing and filter shapes used to achieve a professional Rock mix.

---

## 1. FILTER SHAPES (BANDS)
These define the geometry of how the frequency spectrum is manipulated.

### Bell (Peak)
* **Description:** The most common filter. It boosts or cuts around a center frequency.
* **Parameters:** Center Frequency, Gain, and Q (Bandwidth).
* **Rock Use:** Narrow Q for "notching out" annoying ringy frequencies in snares; Wide Q for adding musical "body" to vocals or guitars.

### Shelf (Low & High)
* **Description:** Affects all frequencies above (High Shelf) or below (Low Shelf) a set point equally.
* **Rock Use:** Use a High Shelf at 10kHz+ to add "air" to overheads and vocals. Use a Low Shelf to add consistent weight to the Bass Bus.

### Pass Filters (HPF / LPF)
* **Description:** They do not boost; they only attenuate. 
    * **High Pass Filter (HPF):** Cuts lows, lets highs pass. 
    * **Low Pass Filter (LPF):** Cuts highs, lets lows pass.
* **Rock Use:** HPF is mandatory on Guitars (80-100Hz) to clear space for the Kick. LPF is used on distorted guitars (8-10kHz) to remove harsh "fizz."

### Notch
* **Description:** An extremely narrow Bell filter with deep attenuation.
* **Rock Use:** Specifically for removing 60Hz hum from single-coil pickups or surgical resonance removal.

---

## 2. TYPES OF EQUALIZERS
The underlying technology that determines the "vibe" and precision of the tool.

### Parametric EQ (The Surgeon)
* **Characteristics:** Total control over Frequency, Gain, and Q. Usually very transparent.
* **Best For:** Corrective work, cleaning muddy frequencies, and precise filtering.
* **Common Plugin:** FabFilter Pro-Q 3 or DAW Stock EQ.

### Semi-Parametric EQ (The Musical)
* **Characteristics:** Fixed or switchable Q settings. Limited frequency choices.
* **Best For:** Fast decision-making. Forces the producer to use ears rather than eyes.
* **Common Plugin:** API 550A/550B emulations.

### Vintage / Analog Emulation (The Colorist)
* **Characteristics:** Adds harmonic distortion and "warmth." Non-linear behavior.
* **Pultec Style:** Great for the "Pultec Trick" (boosting and cutting the same low frequency) to get a massive Kick drum.
* **Neve Style (1073):** Renowned for aggressive, "crunchy" mid-range gains. Perfect for Rock Guitars.

### Dynamic EQ (The Controller)
* **Characteristics:** A hybrid between EQ and Compression. The band only activates when the signal crosses a threshold.
* **Best For:** Taming "boomy" palm-muted guitars at 200Hz or harsh vocal spikes that only happen on loud notes.

---

## 3. PHASE MODES
* **Minimum Phase:** Standard mode. Sounds "natural" but introduces slight phase shifts. Best for individual tracks.
* **Linear Phase:** Keeps phase perfectly aligned but can cause "pre-ringing" (a subtle smear before transients). Use only on the Master Bus or multi-mic setups like Drum Buses.

---

**Next Step:** Would you like a list of specific "frequency hunting" points for Rock instruments (e.g., where to find the 'snap' of a kick or the 'bite' of a guitar)?
