# Noise-Cognition-Experiment

A PsychoPy-based experimental study investigating the effect of background noise on human reaction time.

---

## Overview

This project explores how ambient background noise (simulated café environment) influences cognitive performance, specifically **reaction time** to visual stimuli.

Contrary to common assumptions, the results suggest that moderate noise may actually **improve reaction speed**.

---

## Research Objective

To determine whether background noise:

* Slows down reaction time (as distraction)
* Or enhances performance through increased arousal

---

## Experiment Design

* **Design Type:** Within-Subjects (Repeated Measures)
* **Independent Variable:** Audio Condition

  * Silence
  * Noise (café sound)
* **Dependent Variable:** Reaction Time (seconds)

---

## Tools & Technologies

* PsychoPy (v2026.1.3)
* Python (backend execution)
* CSV (data collection)

---

## Project Structure

```
Noise-Cognition-Experiment/
│
├── noise_study.psyexp        # PsychoPy experiment file
├── cafe_noise.wav            # Audio stimulus
├── conditions.xlsx           # experiment file conditions
├── data/                     # Collected participant data (CSV files)
├── Report.txt                # Full research report

```

---

## Participants

* 3 participants (convenience sampling)
* IDs: `test1`, `test2`, `test3`

---

## Key Findings

* All participants showed **faster reaction times in noise**
* One participant showed **statistically significant improvement**
* Suggests moderate noise increases **alertness and focus**

---

## Results Summary

| Condition | Effect                |
| --------- | --------------------- |
| Silence   | Slower reaction times |
| Noise     | Faster reaction times |

---

## Conclusion

This study challenges the assumption that noise always impairs performance. Instead, it supports the **Arousal Theory**, showing that moderate background noise can enhance simple cognitive tasks.

---

## Limitations

* Small sample size (n = 3)
* Minor data inconsistencies (missed trials)
* Audio timing precision limitations

---

## How to Run the Experiment

1. Install PsychoPy
2. Open `noise_study.psyexp`
3. Ensure `cafe_noise.wav` is in the same directory
4. Run the experiment

---

## Future Improvements

* Increase sample size
* Use high-precision audio hardware
* Test different types of noise (music, white noise, etc.)

---

## License

This project is for academic and educational purposes.

---

## Acknowledgment

Developed as part of a cognitive psychology / AI lab experiment using PsychoPy.
