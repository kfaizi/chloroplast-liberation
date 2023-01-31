---
status: Accepted
reason: 
---

# 2022-08-18 chloroplast life support (run 2)

## Purpose
This experiment is to assess the viability of chloroplasts _ex vivo_ by tracking chlorophyll fluorescence over time. 

## Materials
### Organisms
| **Organism** | **Strain** | **Genotype** |
| :--: | :--: | :--: |
| _Chlamydomonas reinhardtii_ | cc-400 | cw-15 |

### Plate layout
| **Wells** | **Sample** | **Volume (uL)** | **Notes** |
| :--: | :--: | :--: | :--: |
| A1-3 | Whole cells in TP | 100 | positive control |
| A4 | Chloroplasts in TP | 100 | normal chloroplast survival _ex vivo_ |
| A5-6 | Chloroplasts in TP + cytoplasmic extract (1:1) | 200 | life support condition |
| B1-3 | Cytoplasmic extract | 100 | negative control (hopefully) |
| C1-3 | TP medium | 100 | negative control |
| D1-3 | Chloroplast isolation buffer (CIB) | 100 | negative control (hopefully) |
| E1-3 | CIB + TP | 200 | negative control (included to assess dilution effects) |
| E4-6 | CIB + TP | 100 | negative control (included to assess dilution effects) |

### Instrument settings
| Instrument | BioTek Synergy H1 Microplate Reader |
|:--:| :--:|
| Plate Type | 96 well with lid |
| Temperature | 25°C |
| Run Type | kinetic |
| Shaking Mode | orbital (continuous) |
| Run Duration | 10h |
| Read Interval | 2m |
| Read Speed | normal |
| Read Type | fluorescence (440 nm, 680 nm) | 
| Optics Type | bottom |

## Notes and Observations
This is my last life support run before the summer is over --- and the chloroplast isolation finally worked!

I noticed that glutathione calls for refrigeration, so I moved it into the cold room, but it has been at RT up to now. From a quick search online, this might have compromised its quality, but I'm unsure how important this will ultimately be for my purposes. Noting for future me.

I made my Percoll gradients in 15 mL round-bottom tubes this time, rather than 50 mL Falcon tubes. This felt more difficult, but I reasoned that by making the fractions thicker, this should improve their resolution (longer travel distance for my unseparated samples). I only got 1 decent column out of 4 attempts, working very slowly with a P1000 so as not to disturb the gradients.

Around 6 pm, I quanted my cc-400 culture ($7 \times 10^{5}$ cells/mL, 800 mL total), and spun it down in a bunch of 50 mL Falcons. Decanted supe and added 45 mL of HEPES-KOH for the first 5 minute wash. `NOTE: I forgot to resuspend the pellet first, so I combined the pellets after centrifuging and did them instead.`

Into the cold room now, I added 8 mL CIB to the consolidated resuspended pellet (perhaps $10^9$ cells, minus any losses during the wash) and passed everything through the needle. I've found a useful trick is to place the syringe snugly inside a clean 50 mL Falcon by squeezing the sides as needed, which acts as a brace for achieving smooth, even flow.

Resuspending the pellet with the brush took a few minutes. I slowly layered 1 mL on top of my nicest gradient from earlier, and the remaining ~1 mL on my second-best one. Spun down for 18 minutes, and I got the most beautiful bands! Finally, a clear thylakoid band, and a clear CP band (if the protocol is to be believed). CP band looks clumpy and dotted, rather than like a smooth green gradient. It was straightforward to retrieve it with a P1000.

I centrifuged the chloroplast pellets twice to remove the Percoll, since after the first round, the pellet was too easy to disturb.

For the positive control wells, I spun down ~45 mL of my initial culture (about $10^7$ cells) for 10 min at 3220 rcf. Resuspending in 2 mL of fresh cool TP, which should give about $5 \times 10^5$ cells in each 100 uL aliquot.

The plate reader settings are largely the same as last time, but:
- I'm taking reads every 2 minutes, instead of every 1.
- Going for 10 hours, rather than 2.
- Using bottom optics, instead of top, to avoid confounding by condensation on the lid.
- Preset temp to set point before protocol, so the device was ready as soon as I needed it.

There was a delay of about 20 minutes between isolating the chloroplasts and starting the plate read.

## Summary of Results
The results from this experiment are the ones shown in Figure 4 of my tech report.