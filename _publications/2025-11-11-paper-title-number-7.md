---
title: "BANGLAPROTHA: Evaluating Vision Language Models in Underrepresented
Long-tail Cultural Contexts"
collection: publications
category: under_review
authors: 'Md Fahim, Md Sakib Ul Rahman Sourove, Akm Moshiur Rahman Mazumder, Md Farhan Ishmam, Md Tasmim Rahman Adib, Fariha Tanjim Shifat, <strong>Fabiha Haider</strong>, Md Farhad Alam Bhuiyan'
excerpt: 'We introduce BanglaProtha, a Bengali culture–focused VQA dataset designed to expose cultural biases in Vision-Language Models. By evaluating multiple VLM classes across prompting, fine-tuning, model sizes, and augmentation strategies, we uncover systematic Western-centric tendencies. Our work offers diagnostic insights for developing fairer multicultural and multilingual AI systems.'
# date: 2025-11-07
githuburl: "https://github.com/farhanishmam/BanglaProtha"
paperurl: "https://drive.google.com/file/d/1oIGI4tNQBlPPRbLR-8LBcuqaai2QNk4-/view?usp=sharing"
venue: 'WACV 2026 Conference'
---
### Abstract

The advanced multimodal processing of current vision language models (VLMs) has prompted rigorous benchmarking across multicultural settings, revealing a clear inclination toward Western culture. While the bias likely stems from the predominance of Western-centric images in the VLM pretraining data, the resulting long-tail distribution problem is only exacerbated in underrepresented cultural settings, such as Bengali. Our work explores this problem through an aspect-based evaluation of several classes of VLMs on the rich Bengali culture. Our BanglaProtha dataset is a VQA dataset, containing images that encapsulate Bengali cultural elements, questions in native Bengali, and semantically similar multiple-choice answer options. Our experiments provide behavioral insights into VLMs across prompting & fine-tuning strategies, cultural aspects, model size, and augmentation methods. Our work serves as a diagnostic tool for addressing and mitigating inequalities in multicultural and multilingual settings, thereby bringing efforts to democratize AI systems. Our code and data are available at https://github.com/farhanishmam/BanglaProtha.