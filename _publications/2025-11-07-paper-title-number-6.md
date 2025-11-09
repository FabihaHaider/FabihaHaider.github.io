---
title: "Robustness of LLMs to Transliteration Perturbations in Bangla"
collection: publications
category: under_review
authors: '<strong>Fabiha Haider</strong>, Md Farhan Ishmam, Fariha Tanjim Shifat, Md Tasmim Rahman Adib, Md Fahim, Md Farhad Alam Bhuiyan'
excerpt: 'Bangla text online often mixes Bangla script with Romanized Bangla. To handle this, language models need to be able to understand this script mixing. In this work, we test how well current LLMs and Bangla models handle different types of transliteration-based changes. We create mixed-script versions of Bangla data by replacing some words, sentences, or important keywords with their transliterated forms. Our experiments show weaknesses and interesting behaviors in these models, highlighting the need to improve robustness for real-world use.'
date: 2025-11-07
venue: 'BNP-Workshop'
---
### Abstract

Bangla text on the internet often appears in mixed scripts that combine native Bangla characters with their Romanized transliterations. To ensure practical usability, language models should be robust to naturally occurring script mixing. Our work investigates the robustness of current LLMs and Bangla language models under various transliteration-based textual perturbations, i.e., we augment portions of existing Bangla datasets using transliteration. Specifically, we replace words and sentences with their transliterated text to emulate realistic script mixing, and similarly, replace the top salient words to emulate adversarial script mixing. Our experiments reveal interesting behavioral insights and vulnerabilities to robustness in language models for Bangla, which can be crucial for deploying such models in real-world scenarios and enhancing their overall robustness.