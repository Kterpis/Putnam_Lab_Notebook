---
layout: post
title: 20220302 mtORF PCR and ethanol precipitation of Pocillopora
date: '2022-03-02'
categories: Processing
tags: PCR QC DNA
---

## mtORF PCR of Pocillopora
*Loosely based off of this [protocol](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/mtORF-protocol/).*

Diluted the genomic data 1:10 with PCR grade water in strip tubes to help reduce any inhibitors that might be in the sample. Not worried about final concentration.

Setting up 12 samples plus a negative control
**Did not use a positive control since I didn't have one**

Samples:  
  * Negative control
  * 59
  * 61
  * 63
  * 65
  * 67
  * 77
  * 105
  * 123
  * 135
  * 237
  * 245
  * 253

###### Made 14 total PCR reactions
  1. 233.24ul of Phusion High-Fidelity PCR Master Mix
  2. 205.24ul of Ultrapure PCR grade water
  3. 6.02ul of FatP6 primer
  4. 6.02ul of RORF primer
32ul of MM into each tube and 1ul of the diluted gDNA.

### Gel

- Modified from this [protocol](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/Gel-Protocol/)
- Added 0.50g of agarose and 50ml of 1x TAE to flask and microwaved for 45 seconds. This makes a 1.0% gel
- Once cool enough to touch added 1ul of gel green stain
- Swirled and poured into gel mould with comb
- Once solidified, covered with 1X TAE as a running buffer
- Added 1ul of purple loading dye to a piece of parafilm and then added 3ul of PCR product.
- Gel ran for 30 minutes at 80V
 ![20220302_gel.jpg](https://github.com/Kterpis/Putnam_Lab_Notebook/blob/master/images/gels/20220302_gel.jpg?raw=true)

### Ethanol precipitation
1. Add 3ul of 3M sodium acetate to each PCR reaction (1/10th the total voume)
2. Add 99ul of ice cold 100% ethanol to each tube (3x the total volume)
3. Transfer entire volume to a new labeled 1.5ml tube
4. Place tubes in -80 freezer for about 30 minutes
5. Spin for 30 minutes at 12,000rpm. Make sure all the tubes are facing the same way. The DNA will pellet on the back wall
6. Pipette off the liquid without disturbing the pellet. It will most likely be invisable.
7. Add 200ul of ice cold 70% Ethanol
8. Spin for 5 minutes at 12,000rmp. This is to wash the pellet. Again make sure each tube is facing the same direction
9. Pipette off the ethanol without disturbing the pellet
10. Let dry at room temperature with the caps open for about 15 minutes or until all ethanol has evaporated
11. Add 30ul of either Tris or water to the pellet and pipette up and down to resuspend

### Nanodrop

| DNA | ng/ul |
|-------------	|------------	|
|59 | 158.0|
|61 | 144.6|
|63 | 168.2|
|65 |198.8|
|67 | 150.2|
|77 | 88.3|
|105 | 165.7|
|123 | 199.5|
|135 | 177.0|
|237 | 149.0|
|245 |171.5|
|253 | 169.4|

### Sequencing  
  - had to dilue the DNA 1:10 so it would be the in correct concentratio to set it the samples up for sequencing. I did not re-nanodrop the samples after diluting
  - Intially just sequenced in one direction to make sure I was getting the correct target
