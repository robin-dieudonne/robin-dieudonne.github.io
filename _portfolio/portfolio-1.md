---
title: "NLP for Sign Language Translation"
excerpt: "Developed a state-of-the-art sign language translation model using transformers and the Flan-T5 architecture to improve gloss-to-text translation.<br/><img src='/images/500x300.png'>"

collection: portfolio
---

Sign Language Machine Translation (SLT) is challenged by the scarcity of annotated data. In this project, we enhance data augmentation techniques and improve gloss-to-text translation, where glosses are sequences of transcribed spoken language words ordered as they are signed. We treat gloss-to-text translation as a low-resource neural machine translation (NMT) problem. Our data augmentation approach focuses on generating glosses from text to address the shortage of professionally annotated SLT data.

Utilizing the PHOENIX-Weather 2014T corpus, we achieve a new state-of-the-art ROUGE-L score of 57.11. Our results demonstrate the potential for further advancements in SLT by jointly training encoder-decoder architectures on both text-to-gloss and gloss-to-text tasks. This combined approach not only augments the data but also improves SLT performance using the newly generated data.
