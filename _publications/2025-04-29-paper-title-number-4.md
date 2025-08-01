---
title: "BanTH: A Multi-label Hate Speech Detection Dataset for Transliterated Bangla"
collection: publications
category: conferences
excerpt: 'As transliterated Bangla (Banglish) is one of the most common forms of online communication, detecting hate content in this form is crucial. We present BANTH, the first multi-label transliterated Bangla hate speech dataset. We also propose a novel translation-based prompting strategy with LLMs achieving superior performance over existing baselines and paving the way for more effective hate speech detection in underrepresented languages.'
date: 2025-04-29
venue: 'NAACL'
paperurl: 'https://aclanthology.org/2025.findings-naacl.403.pdf'
---
### Abstract

The proliferation of transliterated texts in digital spaces has emphasized the need for detecting and classifying hate speech in languages beyond English, particularly in low-resource languages. As online discourse can perpetuate discrimination based on target groups, e.g. gender, religion, and origin, multi-label classification of hateful content can help in understanding hate motivation and enhance content moderation. While previous efforts have focused on monolingual or binary hate classification tasks, no work has yet addressed the challenge of multi-label hate speech classification in transliterated Bangla. We introduce BANTH, the first multi-label transliterated Bangla hate speech dataset. The samples are sourced from YouTube comments, where each instance is labeled with one or more target groups, reflecting the regional demographic. We propose a novel translation-based LLM prompting strategy that translates or transliterates underresourced text to higher-resourced text before classifying the hate group(s). Experiments reveal further pre-trained encoders achieving state-of-the-art performance on the BANTH dataset while translation-based prompting outperforms other strategies in the zero-shot setting. We address a critical gap in Bangla hate speech and set the stage for further exploration into code-mixed and multi-label classification in underrepresented languages.