# `Hindi-POS-Tagging-Using-HMM-with-Viterbi-Algo`

[![made-with-python](https://img.shields.io/badge/Made%20With-Python-red?style=for-the-badge&logo=Python)](https://www.python.org/)

Hindi Part of Speech Tagging is something that people are still doing research on as we have various techniques and libraries available for English Text and rarely for Hindi Text.POS tagging is used in various applications like parsing where word and their tags are transformed into chunks which can be combined to generate the complete parse of a text.

## Dataset

We have obtained the source dataset containing Hindi Sentences with tagged POS from Hindi (Original) sections of the universal dependencies corpus.
The source corpora, documentation, and credits can be found at http://universaldependencies.org

## POS Tags

We have 25 tags found in our dataset-
NN, RDP, RB, SYM, NEG, QO, QFC, INJ, CC, PSP, INTF, VAUX, NNP, RP, QC, UNK, PRP, WQ, PRPC, RBC, JJ, DEM, VM, QF, NST

## SAMPLE INPUT

text = 'इराक के विदेश मंत्री ने अमरीका के उस प्रस्ताव का मजाक उड़ाया है , जिसमें अमरीका ने संयुक्त राष्ट्र के प्रतिबंधों को इराकी नागरिकों के लिए कम हानिकारक बनाने के लिए कहा है ।'

## OUTPUT

[('इराक', 'NNP'), ('के', 'PSP'), ('विदेश', 'NN'), ('मंत्री', 'NNP'), ('ने', 'PSP'), ('अमरीका', 'NNP'), ('के', 'PSP'), ('उस', 'DEM'), ('प्रस्ताव', 'NN'), ('का', 'PSP'), ('मजाक', 'NN'), ('उड़ाया', 'VM'), ('है', 'VAUX'), (',', 'SYM'), ('जिसमें', 'PRP'), ('अमरीका', 'NNP'), ('ने', 'PSP'), ('संयुक्त', 'JJ'), ('राष्ट्र', 'NN'), ('के', 'PSP'), ('प्रतिबंधों', 'NN'), ('को', 'PSP'), ('इराकी', 'JJ'), ('नागरिकों', 'NN'), ('के', 'PSP'), ('लिए', 'PSP'), ('', 'SYM'), ('कम', 'QF'), ('हानिकारक', 'JJ'), ('बनाने', 'VM'), ('के', 'PSP'), ('लिए', 'PSP'), ('कहा', 'VM'), ('है', 'VAUX'), ('।', 'SYM')]

## ACCURACY

    Accuracy of our model was 94.581% for the random 20 sentences from the test Dataset and the Computing time was 585.57secs.

**REF:**
[1] Part of Speech (POS) tagging with Hidden Markov Model By Hussain Mujtaba https://www.mygreatlearning.com/blog/pos-tagging/
