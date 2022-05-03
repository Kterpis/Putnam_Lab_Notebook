---
layout: post
title: 20220314 RFPL and Bento Lab testing
date: '2022-03-14'
categories: Processing
tags: PCR QC DNA RFPL
---

Pocillopora of Moorea has cryptic diversity, species cannot be discerned by morphological characteristics. Even by generating a molecular barcode (ATP synthase 6), there are some species that are identical and a different gene needs to be sequenced to correctly identify these species.
It's really important to be able to tell these different species apart to make sure enough samples from each species are collected. While generating these sequence barcodes isn't difficult, it can't easily be done in the field, but what if it was?

Restriction Fragment Length Polymorphism (RFLP) is a simple molecular tool that can be used to distinguish these species using restriction enzymes based on known sites. Johnston et al (2018) used this used this to distinguish POC species in [Hawaii](https://peerj.com/articles/4355/)

#### All PCRs and gels were run on the [Bento lab](https://bento.bio/resources/manual/)

### mtORF PCR

Start by setting up a mtORF PCR
(*Loosely based off of this [protocol](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/mtORF-protocol/).*)

###### Made 5 total PCR reactions
  1. 83.3ul of Phusion High-Fidelity PCR Master Mix
  2. 73.3ul of Ultrapure PCR grade water
  3. 2.15ul of 10uM FatP6 primer
  4. 2.15ul of 10uM RORF primer

  * 32ul of MM into each strip tube and 1ul of the diluted gDNA
  * Spun down tubes briefly

    * Negative control
    * 59
    * 61
    * 179


59 and 61 are from the E5 project and 179 is an unknown *Pocillopora* sample from Danielle

### Gel
Since the PCR reactions are set up in 33ul, take either 2 or 3ul and run it out on a 1.0% gel for 30 minutes at 80V to make sure the PCR worked and there is no band in your negative control.

- Modified from this [protocol](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/Gel-Protocol/)
- Added 0.50g of agarose and 50ml of 1x TAE to flask and microwaved for 45 seconds. This makes a 1.0% gel
- Once cool enough to touch added 5ul of gel red stain
- Swirled and poured into gel mould with comb
- Once solidified, covered with 1X TAE as a running buffer
- Added 1ul of purple loading dye to a piece of parafilm and then added 3ul of PCR product.
- Gel ran for 30 minutes at 80V
I did not take a picture of this gel, but the bento box melted it. There was no band in the negative control, and you could tell that it worked.


### Restriction enzyme

Then 15ul of the original PCR reaction goes towards one restriction enzyme, and the other 15ul goes towards another. For this test I am using AciI which confirms *Pocillopora verrucosa* from other species, and SacI which distinguishes P. eyduxia and P. meandrina from the other POC species.

Into a new labeled 0.2ml strip tube, for every sample I added 0.5ul of 1x CutSmart buffer, 0.5ul of SacI RE, and 15ul of mtORF PCR product.
Into another new labeled 0.2ml strip tube, I added 0.5ul of 1x CutSmart Buffer, 0.5ul of AciI RE, and 15ul of mtORF PCR product.

Each of these stripe tubes were incubated at 37C for one hour, and then at 65C for 20 minutes to inactivate the enzyme.

3ul of the reaction from each RE were run out on a 2% TAE gel for one hour at 70V.

 ![20220314_gel.jpg](https://github.com/Kterpis/Putnam_Lab_Notebook/blob/master/images/gels/20220314_gel.jpg?raw=true)

Conclusion: the bento gel box runs wayyyyy hotter than it says it is. There is no way to tell anything from this gel.
