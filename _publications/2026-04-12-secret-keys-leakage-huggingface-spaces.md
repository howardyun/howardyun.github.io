---
title: "A Large-Scale Empirical Study of Secret Keys Leakage in Hugging Face Spaces"
collection: publications
category: conferences
permalink: /publication/2026-04-12-secret-keys-leakage-huggingface-spaces
excerpt: 'This paper presents the first large-scale and systematic empirical study to quantify the extent of secret key leakage in Hugging Face Spaces, identifying 9,149 vulnerable repositories and 11,557 unique leaked keys.'
date: 2026-04-12
venue: 'IEEE/ACM 48th International Conference on Software Engineering (ICSE 2026)'
paperurl: '/files/2026-icse-secret-keys-leakage.pdf'
citation: 'Shaoxuan Yun, Yuchao Zhang, Zhikun Shi, Liu Wang, Yi Wang, and Yu Bai. (2026). &quot;A Large-Scale Empirical Study of Secret Keys Leakage in Hugging Face Spaces.&quot; <i>ICSE 2026</i>.'
---
Hugging Face Spaces (Spaces) has become a leading platform for hosting AI applications, offering developers seamless integration of Git-based repositories and out-of-the-box web service deployment. However, as its adoption continues to expand, security concerns have come to light. We present the first large-scale and systematic empirical study to quantify the extent of secret key leakage in Spaces. We introduce Secret Reviewer, an advanced framework that combines static analysis and Large Language Model (LLM)-assisted detection to identify leaked credentials. Applying Secret Reviewer, we identified 9,149 repositories with secret keys leakage vulnerabilities and 11,557 unique keys—76% of which from leading AI service providers such as OpenAI and Groq.
