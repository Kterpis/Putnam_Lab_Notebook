---
layout: post
title: 20220426 RFPL and Bento Lab testing of POC E5 samples
date: '2022-04-26'
categories: Processing
tags: PCR QC DNA RFPL
---

Continuing to the test the RFLPs on POC samples from the E5 project. Looking to see if the RE match the BLAST results.

Restriction Fragment Length Polymorphism (RFLP) is a simple molecular tool that can be used to distinguish these species using restriction enzymes based on known sites. Johnston et al (2018) used this used this to distinguish POC species in [Hawaii](https://peerj.com/articles/4355/)

#### All PCRs were run on the [Bento lab](https://bento.bio/resources/manual/) and the gels were run on the [Gel Rig Enduro XL](https://hputnam.github.io/Putnam_Lab_Notebook/Gel-Rig-Test/)

### mtORF PCR

Start by setting up a mtORF PCR
(*Loosely based off of this [protocol](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/mtORF-protocol/).*)

###### Made 19 total PCR reactions
  1. 316.54ul of Phusion High-Fidelity PCR Master Mix
  2. 278.54ul of Ultrapure PCR grade water
  3. 8.17ul of 10uM FatP6 primer
  4. 8.17ul of 10uM RORF primer

  * 32ul of MM into each strip tube and 1ul of the diluted gDNA
  * Spun down tubes briefly

    * Negative control
    * 59
    * 61
    * 179



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

**I had a band in my negative for my first PCR. I threw away my water and diluted primers and set the PCR up again. The second time everything looked great and I moved forward**

### Restriction enzyme part 1

Then 15ul of the original PCR reaction goes towards one restriction enzyme, and the other 15ul goes towards another. For this test I am using AciI which confirms *Pocillopora verrucosa* from other species, and SacI which distinguishes P. eyduxia and P. meandrina from the other POC species.

Into a new labeled 0.2ml strip tube, for every sample I added 0.5ul of 1x CutSmart buffer, 0.5ul of SacI RE, and 15ul of mtORF PCR product.
Into another new labeled 0.2ml strip tube, I added 0.5ul of 1x CutSmart Buffer, 0.5ul of AciI RE, and 15ul of mtORF PCR product.

Each of these strip tubes were incubated at 37C for one hour, and then at 65C for 20 minutes to inactivate the enzyme.

3ul of the reaction from each RE were run out on a 2% TAE gel for one hour at 70V.

 ![20220314_gel.jpg](https://github.com/Kterpis/Putnam_Lab_Notebook/blob/master/images/gels/20220314_gel.jpg?raw=true)

### Histone PCR

### Restriction enzyme part 2

Pipetted 15ul of the histone PCR product into a new labeled 0.2ml strip tube, and added 0.5ul of 1x Cutsmart buffer and 0.5ul of XhoI RE. These samples were then incubated at 37C for one hour, and then at 65C for 20 minutes to inactivate the enzyme.

3ul of the reaction was run out on a 2% TAE gel for one hour at 70V.
