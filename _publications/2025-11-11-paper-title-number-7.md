---
title: "BANGLAPROTHA: Evaluating Vision Language Models in Underrepresented
Long-tail Cultural Contexts"
collection: publications
category: under_review
authors: 'Md Fahim, Md Sakib Ul Rahman Sourove, Akm Moshiur Rahman Mazumder, Md Farhan Ishmam, Md Tasmim Rahman Adib, Fariha Tanjim Shifat, <strong>Fabiha Haider</strong>, Md Farhad Alam Bhuiyan'
excerpt: 'Bangla text online often mixes Bangla script with Romanized Bangla. To handle this, language models need to be able to understand this script mixing. In this work, we test how well current LLMs and Bangla models handle different types of transliteration-based changes. We create mixed-script versions of Bangla data by replacing some words, sentences, or important keywords with their transliterated forms. Our experiments show weaknesses and interesting behaviors in these models, highlighting the need to improve robustness for real-world use.'
# date: 2025-11-07
githuburl: "https://github.com/farhanishmam/BanglaProtha"
venue: 'WACV 2026 Conference'
---
### Abstract

The advanced multimodal processing of current vision language models (VLMs) has prompted rigorous benchmarking across multicultural settings, revealing a clear inclination toward Western culture. While the bias likely stems from the predominance of Western-centric images in the VLM pretraining data, the resulting long-tail distribution problem is only exacerbated in underrepresented cultural settings, such as Bengali. Our work explores this problem through an aspect-based evaluation of several classes of VLMs on the rich Bengali culture. Our BanglaProtha dataset is a VQA dataset, containing images that encapsulate Bengali cultural elements, questions in native Bengali, and semantically similar multiple-choice answer options. Our experiments provide behavioral insights into VLMs across prompting & fine-tuning strategies, cultural aspects, model size, and augmentation methods. Our work serves as a diagnostic tool for addressing and mitigating inequalities in multicultural and multilingual settings, thereby bringing efforts to democratize AI systems. Our code and data are available at https://github.com/farhanishmam/BanglaProtha.