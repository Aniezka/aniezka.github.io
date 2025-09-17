---
layout: single
classes: wide
author_profile: true
title: "Projects"
---
---
# 🚧 Under Development 🚧

> ### 🚨 RuHateBe: Russian Hate Speech Benchmark for Dialogue Systems
> 
> Led development of the first Russian-language benchmark dataset for hate speech detection in dialogue systems. This research project created a comprehensive evaluation framework to assess the propensity of conversational AI models to generate inappropriate content, revealing systematic biases in state-of-the-art models and providing insights for responsible AI development.
> 
> **Key Features:**
> - Novel benchmark dataset with 10,382 data points targeting 7 social groups (women, LGBTQ+, migrants, men, born place and skin color, children, others) identified based on Russian sociocultural context
> - Automated toxicity filtering (probability >0.97) combined with morphological analysis for hate speech identification using 160+ identifiers per group
> - Comprehensive evaluation of state-of-the-art Russian dialogue models (RuBERT, Conversational RuBERT, RuGPT3 Large/XL)
> - Systematic bias detection revealing GPT-3 models choosing toxic responses ~40% of the time across all target groups
> - First study examining Russian dialogue models for hate speech toward specific social groups
> - Multi-source data collection from toxic forums (ProDota, Dvach) and everyday communication (Open Subtitles, Fiction corpus)
> 
> **Technologies:** Python, PyTorch, re, pandas, pymorphy2, numpy, transformers, NLTK, Beautiful Soup, API integration, matplotlib
> 
> **Links:** [GitHub](https://github.com/Aniezka/hatespeech-russian)
> 
> **Date:** 2022
> 
---

> ### 💬 VKontakte Sentiment Analysis Tool
> 
> A Python3 library for sentiment analysis of comments from toxic and non-toxic VKontakte communities. The project addresses the gap in existing solutions by combining automated comment collection with sentiment analysis specifically optimized for highly toxic or non-toxic communities. Designed for VK community administrators and researchers who need automated sentiment monitoring.
> 
> **Key Features:**
> - Custom sentiment analysis dataset with 14,680 manually annotated comments
> - Multi-class classification (positive, negative, neutral, skip, speech) following RuSentiment guidelines
> - Automated comment collection from VK groups
> - Community-level sentiment indices (positivity/neutrality/negativity scores)
> - 192 preprocessing variants with comprehensive text normalization
> - Best configuration: 0.78 F1-score (vs. Dostoevsky baseline: 0.55 F1)
> 
> **Technologies:** Python, scikit-learn, pymorphy2, TF-IDF, XGBoost, SGDClassifier, LogisticRegression, RandomForestClassifier, MultinomialNB
> 
> **Links:** [GitHub](https://github.com/polyankaglade/vkToxic)
> 
> **Date:** 2020
> 
---

> ### 🎭 Russian SuperGLUE: Metaphor-Based Diagnostic Tasks
> 
> Development of linguistic test methodology and diagnostic tasks for evaluating NLP models on Russian language understanding. Following the Russian SuperGLUE benchmark approach, this project created specialized diagnostic tasks based on Russian metaphors, providing researchers with data to assess model comprehension of figurative language and semantic relationships.
> 
> **Key Features:**
> - Linguistic markup and annotation methodology design
> - Diagnostic tasks specifically targeting Russian metaphor comprehension
> - Contribution to Russian language NLP evaluation standards
> 
> **Technologies:** Linguistic annotation tools
> 
> **Date:** 2020
> 
---

> ### 🌍 Universal Dependencies - Belarusian Treebank Contributions
> 
> A computational linguistics project focused on developing and enhancing the Belarusian language treebank for the Universal Dependencies framework. This work involved creating high-quality syntactic annotations and morphological tags through automated processing followed by manual verification and correction to support NLP research for the Belarusian language.
> 
> **Key Features:**
> - Syntactic dependency parsing and annotation
> - Comprehensive morphological analysis and tagging
> - Adherence to Universal Dependencies annotation standards
> - Contribution to open-source linguistic resources
> 
> **Technologies:** UDPipe, Mystem, Arborator
> 
> **Links:** [Universal Dependencies Project](https://universaldependencies.org/)
> 
> **Date:** 2017-2018
> 
---
