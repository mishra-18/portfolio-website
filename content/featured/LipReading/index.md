---
date: '6'
title: 'LipReading With LipNet'
cover: './LIP.png'
github: "https://github.com/mishra-18/lipnet-pytorch"
external: 'https://github.com/mishra-18/lipnet-pytorch'
cta: ''
tech:
  - Pytorch
  - Opencv
---

Developed a <b>3DConv-LSTM</b> (bi-directional) to predict the spoken sentence by extracting features from the lip movements in the frames based on [End-to-End Sentence-level Lipreading](https://github.com/mishra-18/lipnet-pytorch).

Utilized CTC Loss to handle the variable length of input alignments (spoken sentence) and weights initialized with <b>He</b> (Kaiming normal) initialization to avoid blank-index predictions.