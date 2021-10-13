---
title: "Phonetic word-finder"
excerpt: "Tool to generate lists of Bengali words matching specified phonological descriptions"
collection: portfolio
layout: splash
---

Phonetic word-finder for Bengali
==

This is a python-based command-line tool which outputs lists of words that match a given phonological description. 

For linguistic experiments, we often need sets of words that sound a certain way. For example, to study if a particular vowel is pronounced differently in two different experimental conditions, we would want a list of words containing the vowel that we will ask participants to pronounce in the different conditions. In most cases, we also want these words to be as similar as possible (e.g. have the same number of syllables, the same consonants before/after the target vowel). Coming up with words that fulfill all these conditions can take time. Alternatively, we might need words that don't have certain features. For example, in a study where we are interested in nasals, we might want filler words that don't contain nasal sounds. This tool takes a list of phonological conditions and outputs a list of words that fulfill them.

I made this to make finding items for experiments easier, but it can also be used to find rhyming words, or answer 2 AM questions like whether Bengali has any 6-syllable word that begins and ends with a nasal (hint: it does).


You can download it [here](https://github.com/auromitamitra/Bengali_Word_Finder). The page also has usage instructions and detailed documentation. 

The word-finder currently works with a Bengali corpus ([SHRUTI](http://cse.iitkgp.ac.in/~pabitra/shruti_corpus.html)), but can be modified to use with other languages. This is a work-in-progress. If you are interested in contributing to the code, making improvements, using it for other languages, or have any feedback, please reach out!