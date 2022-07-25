---
title: "Vowel harmony and coarticulation in Khalkha Mongolian"
excerpt: "This project compares patterns of coarticulation in harmonic vs. non-harmonic vowel sequences to understand how a low-level phonetic process interacts with phonological constraints."
layout: splash
collection: research
permalink: /research/mongolian
---

Vowel harmony and coarticulation in Khalkha Mongolian
==

This is an ongoing project with Prof. Indranil Dutta at the [Speech Dynamics lab](https://duttalab.github.io), Jadavpur University, Kolkata.

While speaking, sounds are not produced discretely, one after the other. Instead, while producing a sound our articulators are still affected by the previous vowel/consonant, and already starting to plan for the next, resulting in overlapping articulatory gestures. This kind of *coarticulation* causes acoustic variation, which means that the same phoneme might have different acoustic properties (and thus potentially sound different) when it occurs in different phonetic environments. Vowel-to-vowel (V-to-V) coarticulation is where the quality of a vowel is affected by a preceding or following vowel. Coarticulation can be both *mechanico-inertial* (the gestures of an earlier vowel perturb a later vowel) and *anticipatory*, (planning of the following vowel perturbs the former).

Khalkha Mongolian has a robust and regular vowel harmony system: vowels in polysyllabic words must share certain phonological features. Specifically, in most words the features [ATR] and [round] of non-initial vowels must match those of the initial vowel. This is a grammatical constraint of the language. Some vowels block vowel harmony, which gives non-harmonic vowel sequences (words in which the vowels have different values for [ATR] and/or [round]). 

In this project, we want to understand how the low-level phonetic process of coarticulation interacts with this kind of grammatical knowledge. To do this, we are comparing coarticulation in harmonic (words where vowel harmony is seen) vs. non-harmonic (words where vowel harmony is blocked) sequences in the speech of Khalkha Mongolian speakers, to see if/how these differ.

As part of this project, we trained an acoustic model on our own corpus of Khalka Mongolian speech and used this to force-align and annotate the data. The acoustic model can be downloaded [here](https://github.com/auromitamitra/Mongolian_Acoustic_Model).

The data for this study can be found [here](https://github.com/auromitamitra/mongolian_vowel_harmony/tree/main/formant_data). [These](https://github.com/auromitamitra/mongolian_vowel_harmony/tree/main/scripts) are the Praat and R scripts used for data processing, annotation, and acoustic analyses. 

Preliminary analyses suggest that the direction of coarticulation in non-harmonic sequences is primarily anticipatory (right-to-left), opposite to the direction of vowel harmony. This is unlike harmonic sequences, where coarticulation is primarity mechanico-inertial (left-to-right), the same as that of vowel harmony. 

----

**Mitra, A.**, Dutta, I. (2022) Asymmetries in V-to-V coarticulation among harmonic and non-harmonic sequences in Khalkha Mongolian. Poster presented at Laboratory Phonology 18, virtual, June 23-25 2022. [presentation](https://youtu.be/brornwZ64Ec)|<a href="/files/labphon18_slides_mongolian.pdf" target="_blank">slides</a>