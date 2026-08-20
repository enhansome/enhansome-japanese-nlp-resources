# awesome-japanese-nlp-resources with stars

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/taishi-i/awesome-japanese-nlp-resources) ⭐ 1,006 | 🐛 1 | 📅 2026-08-17
[![RRs](https://img.shields.io/badge/PRs-welcome-brightgreen)](https://github.com/taishi-i/awesome-japanese-nlp-resources/pulls) ⭐ 1,006 | 🐛 1 | 📅 2026-08-17
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

A curated list of resources dedicated to Python libraries, llms, dictionaries, and corpora of NLP for Japanese

* Listed information on [897 GitHub repositories](https://github.com/taishi-i/awesome-japanese-nlp-resources/blob/main/docs/README.full.md) ⭐ 1,006 | 🐛 1 | 📅 2026-08-17
* Listed information on [354 Hugging Face repositories](https://github.com/taishi-i/awesome-japanese-nlp-resources/blob/main/docs/huggingface.md) ⭐ 1,006 | 🐛 1 | 📅 2026-08-17 (models and datasets)
* 🎉 We are excited to announce the release of [awesome-japanese-nlp-slides](https://github.com/taishi-i/awesome-japanese-nlp-slides) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-08-20, a curated list of presentation slides for Japanese NLP, on August 9, 2026!

## Claude Code Plugin

Search, discover, and track Japanese NLP resources directly from [Claude Code](https://claude.ai/code) using the `awesome-japanese-nlp-resources` plugin.

```shell
# Add the marketplace and install
/plugin marketplace add taishi-i/awesome-japanese-nlp-resources
/plugin install awesome-japanese-nlp-resources@awesome-japanese-nlp-resources
/reload-plugins
```

The plugin ships five skills:

| Skill                                                        | Purpose                                                                                          |
| ------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| `/awesome-japanese-nlp-resources:search <query>`             | Search the bundled 1,200+ resource dataset                                                       |
| `/awesome-japanese-nlp-resources:similar-resources <repo>`   | Given a repo/tool, find ones that do the same or related processing                              |
| `/awesome-japanese-nlp-resources:find-new-resources <topic>` | Discover GitHub repos and Hugging Face models/datasets NOT yet in the list — contribution helper |
| `/awesome-japanese-nlp-resources:research-trends <topic>`    | Survey the dataset + latest web research for a trend report                                      |
| `/awesome-japanese-nlp-resources:research-issues <topic>`    | Investigate current challenges, limitations, and proposed solutions for a topic                  |

All skills detect the query language and respond in kind — English by default, Japanese when the query contains Japanese characters.

**`search` example:**

```shell
/awesome-japanese-nlp-resources:search What tutorials are recommended for beginners learning Japanese NLP?
```

Output includes a **Use-case Selection Guide** table:

| Use case                                   | Recommended                                                                                                   | Popularity | Why                                                                              |
| ------------------------------------------ | ------------------------------------------------------------------------------------------------------------- | ---------- | -------------------------------------------------------------------------------- |
| Learn modern NLP/LLM concepts from scratch | [llm-book](https://github.com/ghmagazine/llm-book) ⭐ 474 \| 🐛 5 \| 🌐 Jupyter Notebook \| 📅 2025-12-31      | ⭐387       | Most popular intro; covers LLMs end-to-end with practical Japanese code examples |
| Build practical skills through exercises   | [nlp100v2025](https://github.com/upura/nlp100v2025) ⭐ 90 \| 🐛 0 \| 🌐 Python \| 📅 2025-04-21                | ⭐82        | Classic "100 Knock" challenge series; best way to learn by doing                 |
| Learn BERT and transformer-based NLP       | [bert-book](https://github.com/stockmarkteam/bert-book) ⭐ 265 \| 🐛 8 \| 🌐 Jupyter Notebook \| 📅 2024-02-13 | ⭐262       | Hands-on BERT programming with clear explanations for Japanese NLP beginners     |

For full documentation, see the [plugin README](https://github.com/taishi-i/awesome-japanese-nlp-resources/blob/main/plugins/awesome-japanese-nlp-resources/README.md) ⭐ 1,006 | 🐛 1 | 📅 2026-08-17.

[English](https://github.com/taishi-i/awesome-japanese-nlp-resources/blob/main/docs/README.en.md) ⭐ 1,006 | 🐛 1 | 📅 2026-08-17 | [日本語 (Japanese) ](https://github.com/taishi-i/awesome-japanese-nlp-resources/blob/main/docs/README.ja.md) ⭐ 1,006 | 🐛 1 | 📅 2026-08-17 | [繁體中文 (Chinese) ](https://github.com/taishi-i/awesome-japanese-nlp-resources/blob/main/docs/README.zh-hant.md) ⭐ 1,006 | 🐛 1 | 📅 2026-08-17 | [简体中文 (Chinese) ](https://github.com/taishi-i/awesome-japanese-nlp-resources/blob/main/docs/README.zh-hans.md) ⭐ 1,006 | 🐛 1 | 📅 2026-08-17

## 🎉 The latest additions

**Corpus**

* [pfgen-bench](https://github.com/pfnet-research/pfgen-bench) ⭐ 107 | 🐛 1 | 🌐 Python | 📅 2026-08-07 - Preferred Generation Benchmark
* [jfbench](https://github.com/pfnet-research/jfbench) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2026-08-06 - JFBench: Japanese instruction Following Benchmark
* [j-tau-bench](https://github.com/sbintuitions/j-tau-bench) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2026-08-13 - J-tau: A Japanese tau-bench for Benchmarking Tool-Agent-User Interaction in Real-World Domains
* [bbh-ja](https://github.com/pfnet-research/bbh-ja) ⭐ 5 | 🐛 0 | 📅 2025-07-08 - Japanese Translation of BIG-Bench-Hard (<https://github.com/suzgunmirac/BIG-Bench-Hard/> ⭐ 569 | 🐛 11 | 📅 2024-06-25)

*Updated on Aug 18, 2026*

## Contents

* [Hugging Face](https://github.com/taishi-i/awesome-japanese-nlp-resources/blob/main/docs/huggingface.md) ⭐ 1,006 | 🐛 1 | 📅 2026-08-17
  * [Models](https://github.com/taishi-i/awesome-japanese-nlp-resources/blob/main/docs/huggingface.md#models) ⭐ 1,006 | 🐛 1 | 📅 2026-08-17
  * [Datasets](https://github.com/taishi-i/awesome-japanese-nlp-resources/blob/main/docs/huggingface.md#datasets) ⭐ 1,006 | 🐛 1 | 📅 2026-08-17
* [Python library](#python-library)
  * [Morphology analysis](#morphology-analysis)
  * [Parsing](#parsing)
  * [Converter](#converter)
  * [Preprocessor](#preprocessor)
  * [Sentence splitter](#sentence-splitter)
  * [Sentiment analysis](#sentiment-analysis)
  * [Machine translation](#machine-translation)
  * [Named entity recognition](#named-entity-recognition)
  * [OCR](#ocr)
  * [Tool for pretrained models](#tool-for-pretrained-models)
  * [Others](#others)
* [C++](#c)
  * [Morphology analysis](#morphology-analysis-1)
  * [Parsing](#parsing-1)
  * [Others](#others-1)
* [Rust crate](#rust-crate)
  * [Morphology analysis](#morphology-analysis-2)
  * [Converter](#converter-1)
  * [Search engine library](#search-engine-library)
  * [Others](#others-2)
* [JavaScript](#javascript)
  * [Morphology analysis](#morphology-analysis-3)
  * [Converter](#converter-2)
  * [Others](#others-3)
* [Go](#go)
  * [Morphology analysis](#morphology-analysis-4)
  * [Others](#others-4)
* [Java](#java)
  * [Morphology analysis](#morphology-analysis-5)
  * [Others](#others-5)
* [Pretrained model](#pretrained-model)
  * [Word2Vec](#word2vec)
  * [Transformer based models](#transformer-based-models)
* [ChatGPT](#chatgpt)
* [Dictionary and IME](#dictionary-and-ime)
* [Corpus](#corpus)
  * [Part-of-speech tagging / Named entity recognition](#part-of-speech-tagging--named-entity-recognition)
  * [Parallel corpus](#parallel-corpus)
  * [Dialog corpus](#dialog-corpus)
  * [Others](#others-6)
* [Tutorial](#tutorial)
* [Research summary](#research-summary)
* [Reference](#reference)
* [Contributors](#contributors)

## Python library

### Morphology analysis

Libraries that split Japanese text into words or morphemes and assign part-of-speech and base forms

* [Janome](https://github.com/mocobeta/janome) ⭐ 914 | 🐛 17 | 🌐 Python | 📅 2026-06-07 - Japanese morphological analysis engine written in pure Python
* [mecab-python3](https://github.com/SamuraiT/mecab-python3) ⭐ 584 | 🐛 2 | 🌐 C++ | 📅 2025-11-25 - mecab-python. you can find original version here:<http://taku910.github.io/mecab/>
* [fugashi](https://github.com/polm/fugashi) ⭐ 536 | 🐛 11 | 🌐 C++ | 📅 2025-10-24 - A Cython MeCab wrapper for fast, pythonic Japanese tokenization and morphological analysis.
* [sudachi.rs](https://github.com/WorksApplications/sudachi.rs) ⭐ 469 | 🐛 35 | 🌐 Rust | 📅 2026-06-29 - SudachiPy 0.6\* and above are developed as Sudachi.rs.
* [nagisa](https://github.com/taishi-i/nagisa) ⭐ 419 | 🐛 2 | 🌐 Python | 📅 2026-07-06 - A Japanese tokenizer based on recurrent neural networks
* [mecab](https://github.com/ikegami-yukino/mecab) ⚠️ Archived - This repository is for building Windows 64-bit MeCab binary and improving MeCab Python binding.
* [konoha](https://github.com/himkt/konoha) ⭐ 263 | 🐛 0 | 🌐 Python | 📅 2026-07-19 - Konoha: Simple wrapper of Japanese Tokenizers
* [natto-py](https://github.com/buruzaemon/natto-py) ⭐ 95 | 🐛 7 | 🌐 Python | 📅 2024-06-06 - natto-py combines the Python programming language with MeCab, the part-of-speech and morphological analyzer for the Japanese language.
* [pyknp](https://github.com/ku-nlp/pyknp) ⚠️ Archived - A Python Module for JUMAN++/KNP
* [python-vibrato](https://github.com/daac-tools/python-vibrato) ⭐ 46 | 🐛 0 | 🌐 Rust | 📅 2026-05-30 -  Viterbi-based accelerated tokenizer (Python wrapper)
* [rhoknp](https://github.com/ku-nlp/rhoknp) ⭐ 40 | 🐛 6 | 🌐 Python | 📅 2026-08-03 - Yet another Python binding for Juman++/KNP
* [Mecari](https://github.com/zbller/Mecari) ⭐ 40 | 🐛 0 | 🌐 Python | 📅 2025-10-21 - Mecari (Japanese Morphological Analysis with Graph Neural Networks)
* [Mykytea-python](https://github.com/chezou/Mykytea-python) ⭐ 36 | 🐛 1 | 🌐 C++ | 📅 2026-03-30 - Python wrapper for KyTea
* [dango](https://github.com/mkartawijaya/dango) ⭐ 26 | 🐛 3 | 🌐 Python | 📅 2021-11-21 - An easy to use tokenizer for Japanese text, aimed at language learners and non-linguists
* [rakutenma-python](https://github.com/ikegami-yukino/rakutenma-python) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2017-05-22 - Rakuten MA (Python version)
* [python-vaporetto](https://github.com/daac-tools/python-vaporetto) ⭐ 21 | 🐛 0 | 🌐 Rust | 📅 2026-05-30 -  Vaporetto is a fast and lightweight pointwise prediction based tokenizer. This is a Python wrapper for Vaporetto.
* [jagger-python](https://github.com/lighttransport/jagger-python) ⭐ 13 | 🐛 0 | 🌐 C++ | 📅 2025-12-16 - Python binding for Jagger(C++ implementation of Pattern-based Japanese Morphological Analyzer)

| Name                                                                                                                 | downloads/week | total downloads | stars | last commit       |
| -------------------------------------------------------------------------------------------------------------------- | -------------- | --------------- | ----- | ----------------- |
| 🔗 [SudachiPy](https://github.com/WorksApplications/SudachiPy) ⚠️ Archived                                           | 📥 369k        | 📦 72M          | ⭐ 443 | 🔴 october 2022   |
| 🔗 [Janome](https://github.com/mocobeta/janome) ⭐ 914 \| 🐛 17 \| 🌐 Python \| 📅 2026-06-07                         | 📥 71k         | 📦 13M          | ⭐ 914 | 🟢 june           |
| 🔗 [mecab-python3](https://github.com/SamuraiT/mecab-python3) ⭐ 584 \| 🐛 2 \| 🌐 C++ \| 📅 2025-11-25               | 📥 219k        | 📦 41M          | ⭐ 584 | 🟡 november 2025  |
| 🔗 [mecab](https://github.com/ikegami-yukino/mecab/tree/master/mecab/python) ⚠️ Archived                             | 📥 230k        | 📦 2M           | ⭐ 274 | 🔴 october 2024   |
| 🔗 [fugashi](https://github.com/polm/fugashi) ⭐ 536 \| 🐛 11 \| 🌐 C++ \| 📅 2025-10-24                              | 📥 177k        | 📦 17M          | ⭐ 536 | 🟡 october 2025   |
| 🔗 [nagisa](https://github.com/taishi-i/nagisa) ⭐ 419 \| 🐛 2 \| 🌐 Python \| 📅 2026-07-06                          | 📥 65k         | 📦 10M          | ⭐ 419 | 🟢 july           |
| 🔗 [pyknp](https://github.com/ku-nlp/pyknp) ⚠️ Archived                                                              | 📥 540         | 📦 3M           | ⭐ 93  | 🟡 january        |
| 🔗 [Mykytea-python](https://github.com/chezou/Mykytea-python) ⭐ 36 \| 🐛 1 \| 🌐 C++ \| 📅 2026-03-30                | 📥 457         | 📦 584k         | ⭐ 36  | 🟡 march          |
| 🔗 [konoha](https://github.com/himkt/konoha) ⭐ 263 \| 🐛 0 \| 🌐 Python \| 📅 2026-07-19                             | 📥 54k         | 📦 6M           | ⭐ 263 | 🟢 july           |
| 🔗 [natto-py](https://github.com/buruzaemon/natto-py) ⭐ 95 \| 🐛 7 \| 🌐 Python \| 📅 2024-06-06                     | 📥 7k          | 📦 34M          | ⭐ 95  | 🔴 november 2023  |
| 🔗 [rakutenma-python](https://github.com/ikegami-yukino/rakutenma-python) ⭐ 23 \| 🐛 0 \| 🌐 Python \| 📅 2017-05-22 | 📥 14          | 📦 27k          | ⭐ 23  | 🔴 may 2017       |
| 🔗 [python-vaporetto](https://github.com/daac-tools/python-vaporetto) ⭐ 21 \| 🐛 0 \| 🌐 Rust \| 📅 2026-05-30       | 📥 571         | 📦 188k         | ⭐ 21  | 🟡 may            |
| 🔗 [dango](https://github.com/mkartawijaya/dango) ⭐ 26 \| 🐛 3 \| 🌐 Python \| 📅 2021-11-21                         | 📥 55          | 📦 27k          | ⭐ 26  | 🔴 november 2021  |
| 🔗 [rhoknp](https://github.com/ku-nlp/rhoknp) ⭐ 40 \| 🐛 6 \| 🌐 Python \| 📅 2026-08-03                             | 📥 21k         | 📦 1M           | ⭐ 40  | 🟡 may            |
| 🔗 [python-vibrato](https://github.com/daac-tools/python-vibrato) ⭐ 46 \| 🐛 0 \| 🌐 Rust \| 📅 2026-05-30           | 📥 423         | 📦 126k         | ⭐ 46  | 🟡 may            |
| 🔗 [jagger-python](https://github.com/lighttransport/jagger-python) ⭐ 13 \| 🐛 0 \| 🌐 C++ \| 📅 2025-12-16          | 📥 726         | 📦 328k         | ⭐ 13  | 🔴 march 2024     |
| 🔗 [Mecari](https://github.com/zbller/Mecari) ⭐ 40 \| 🐛 0 \| 🌐 Python \| 📅 2025-10-21                             | -              | -               | ⭐ 40  | 🟡 september 2025 |

### Parsing

Libraries that analyze syntactic and dependency structures of Japanese sentences

* [ginza](https://github.com/megagonlabs/ginza) ⭐ 867 | 🐛 12 | 🌐 Python | 📅 2026-07-10 - A Japanese NLP Library using spaCy as framework based on Universal Dependencies
* [camphr](https://github.com/PKSHATechnology-Research/camphr) ⭐ 336 | 🐛 4 | 🌐 Python | 📅 2022-12-09 - Camphr - NLP libary for creating pipeline components
* [depccg](https://github.com/masashi-y/depccg) ⭐ 102 | 🐛 1 | 🌐 C | 📅 2026-08-15 - A\* CCG Parser with a Supertag and Dependency Factored Model
* [esupar](https://github.com/KoichiYasuoka/esupar) ⭐ 55 | 🐛 1 | 🌐 Python | 📅 2026-02-28 - Tokenizer POS-Tagger and Dependency-parser with BERT/RoBERTa/DeBERTa models for Japanese and other languages
* [UniDic2UD](https://github.com/KoichiYasuoka/UniDic2UD) ⭐ 38 | 🐛 1 | 🌐 Python | 📅 2025-12-29 - Tokenizer POS-tagger Lemmatizer and Dependency-parser for modern and contemporary Japanese
* [yomikata](https://github.com/passaglia/yomikata) ⭐ 35 | 🐛 3 | 🌐 Python | 📅 2023-10-03 - Heteronym disambiguation library using a fine-tuned BERT model.
* [lightblue](https://github.com/daisukebekki/lightblue) ⭐ 29 | 🐛 86 | 🌐 Haskell | 📅 2026-07-16 - A CCG parser for Japanese with DTS-representations
* [bertknp](https://github.com/ku-nlp/bertknp) ⭐ 23 | 🐛 4 | 🌐 Python | 📅 2022-10-26 - A Japanese dependency parser based on BERT
* [SuPar-UniDic](https://github.com/KoichiYasuoka/SuPar-UniDic) ⭐ 21 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2026-02-28 - Tokenizer POS-tagger Lemmatizer and Dependency-parser for modern and contemporary Japanese with BERT models
* [cabocha](https://github.com/ikegami-yukino/cabocha) ⭐ 7 | 🐛 0 | 🌐 C++ | 📅 2022-08-17 - Yet Another Japanese Dependency Structure Analyzer
* [natsume-simple](https://github.com/borh-lab/natsume-simple) ⭐ 5 | 🐛 5 | 🌐 Python | 📅 2025-02-04 - natsume-simpleは日本語の係り受け関係検索システム
* [jdepp-python](https://github.com/lighttransport/jdepp-python) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2024-02-14 - Python binding for J.DepP(C++ implementation of Japanese Dependency Parsers)
* [jdeppy](https://github.com/matsurih/jdeppy) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2022-02-07 - Python wrapper for J.DepP, fast Japanese Dependency Parser

| Name                                                                                                                  | downloads/week | total downloads | stars | last commit      |
| --------------------------------------------------------------------------------------------------------------------- | -------------- | --------------- | ----- | ---------------- |
| 🔗 [ginza](https://github.com/megagonlabs/ginza) ⭐ 867 \| 🐛 12 \| 🌐 Python \| 📅 2026-07-10                         | 📥 17k         | 📦 2M           | ⭐ 867 | 🟢 july          |
| 🔗 [cabocha](https://github.com/ikegami-yukino/cabocha/tree/master/python) ⭐ 7 \| 🐛 0 \| 🌐 C++ \| 📅 2022-08-17     | 📥 109         | 📦 56k          | ⭐ 7   | 🔴 august 2022   |
| 🔗 [UniDic2UD](https://github.com/KoichiYasuoka/UniDic2UD) ⭐ 38 \| 🐛 1 \| 🌐 Python \| 📅 2025-12-29                 | 📥 240         | 📦 338k         | ⭐ 38  | 🟡 december 2025 |
| 🔗 [camphr](https://github.com/PKSHATechnology-Research/camphr) ⭐ 336 \| 🐛 4 \| 🌐 Python \| 📅 2022-12-09           | 📥 1k          | 📦 278k         | ⭐ 336 | 🔴 august 2021   |
| 🔗 [SuPar-UniDic](https://github.com/KoichiYasuoka/SuPar-UniDic) ⭐ 21 \| 🐛 1 \| 🌐 Jupyter Notebook \| 📅 2026-02-28 | 📥 120         | 📦 123k         | ⭐ 21  | 🟡 february      |
| 🔗 [depccg](https://github.com/masashi-y/depccg) ⭐ 102 \| 🐛 1 \| 🌐 C \| 📅 2026-08-15                               | 📥 2k          | 📦 50k          | ⭐ 102 | 🟢 last saturday |
| 🔗 [bertknp](https://github.com/ku-nlp/bertknp) ⭐ 23 \| 🐛 4 \| 🌐 Python \| 📅 2022-10-26                            | -              | -               | ⭐ 23  | 🔴 october 2021  |
| 🔗 [esupar](https://github.com/KoichiYasuoka/esupar) ⭐ 55 \| 🐛 1 \| 🌐 Python \| 📅 2026-02-28                       | 📥 220         | 📦 182k         | ⭐ 55  | 🟡 february      |
| 🔗 [yomikata](https://github.com/passaglia/yomikata) ⭐ 35 \| 🐛 3 \| 🌐 Python \| 📅 2023-10-03                       | 📥 89          | 📦 50k          | ⭐ 35  | 🔴 october 2023  |
| 🔗 [jdepp-python](https://github.com/lighttransport/jdepp-python) ⭐ 4 \| 🐛 0 \| 🌐 C++ \| 📅 2024-02-14              | 📥 1k          | 📦 311k         | ⭐ 4   | 🔴 february 2024 |
| 🔗 [lightblue](https://github.com/daisukebekki/lightblue) ⭐ 29 \| 🐛 86 \| 🌐 Haskell \| 📅 2026-07-16                | -              | -               | ⭐ 29  | 🟡 march         |
| 🔗 [natsume-simple](https://github.com/borh-lab/natsume-simple) ⭐ 5 \| 🐛 5 \| 🌐 Python \| 📅 2025-02-04             | -              | -               | ⭐ 5   | 🔴 february 2025 |
| 🔗 [jdeppy](https://github.com/matsurih/jdeppy) ⭐ 3 \| 🐛 0 \| 🌐 Python \| 📅 2022-02-07                             | 📥 16          | 📦 12k          | ⭐ 3   | 🔴 february 2022 |

### Converter

Libraries that convert between character types such as kana, romaji, and full-width/half-width forms

* [pykakasi](https://github.com/miurahr/pykakasi) ⭐ 462 | 🐛 3 | 🌐 Python | 📅 2026-07-17 - Lightweight converter from Japanese Kana-kanji sentences into Kana-Roman.
* [cutlet](https://github.com/polm/cutlet) ⭐ 382 | 🐛 5 | 🌐 Python | 📅 2026-07-01 - Japanese to romaji converter in Python
* [kanjize](https://github.com/nagataaaas/kanjize) ⭐ 67 | 🐛 1 | 🌐 Python | 📅 2025-06-14 - Kanjize(カンジャイズ): Easy converter between Kanji-Number and Integer
* [Convert-Numbers-to-Japanese](https://github.com/Greatdane/Convert-Numbers-to-Japanese) ⭐ 51 | 🐛 1 | 🌐 Python | 📅 2020-11-26 - Converts Arabic numerals, or 'western' style numbers, to a Japanese context.
* [mozcpy](https://github.com/ikegami-yukino/mozcpy) ⭐ 49 | 🐛 0 | 🌐 Python | 📅 2025-02-14 - Mozc for Python: Kana-Kanji converter
* [alkana.py](https://github.com/zomysan/alkana.py) ⭐ 35 | 🐛 0 | 🌐 Python | 📅 2021-10-07 - A tool to get the katakana reading of an alphabetical string.
* [jntajis-python](https://github.com/opencollector/jntajis-python) ⭐ 21 | 🐛 0 | 🌐 C | 📅 2026-03-11 - A fast character conversion and transliteration library based on the scheme defined for Japan National Tax Agency (国税庁) 's
* [e2k](https://github.com/Patchethium/e2k) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2026-07-05 - A tool for automatic English to Katakana conversion
* [kanjiconv](https://github.com/sea-turt1e/kanjiconv) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2026-08-08 - Kanji Converter to Hiragana, Katakana, Roman alphabet.
* [alphabet2kana](https://github.com/shihono/alphabet2kana) ⭐ 15 | 🐛 6 | 🌐 Python | 📅 2026-08-01 - Convert English alphabet to Katakana
* [text2phoneme](https://github.com/korguchi/text2phoneme) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2023-05-16 - 日本語文を音素列へ変換するスクリプト
* [Jusho](https://github.com/nagataaaas/Jusho) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2024-06-04 - Easy wrapper for the postal code data of Japan
* [jamorasep](https://github.com/tachi-hi/jamorasep) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2026-02-16 - Japanese text parser to separate Hiragana/Katakana string into morae (syllables).
* [pynormalizenumexp](https://github.com/tkscode/pynormalizenumexp) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2024-04-28 - 数量表現や時間表現の抽出・正規化を行うNormalizeNumexpのPython実装
* [mecab-text-cleaner](https://github.com/34j/mecab-text-cleaner) ⭐ 7 | 🐛 14 | 🌐 Python | 📅 2026-08-17 - Simple Python package (CLI/Python API) for getting japanese readings (yomigana) and accents using MeCab.
* [yurenizer](https://github.com/sea-turt1e/yurenizer) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2025-03-16 - Japanese text normalizer that resolves spelling inconsistencies. （日本語表記揺れ解消ツール）
* [englishtokanaconverter](https://github.com/actlaboratory/englishtokanaconverter) ⭐ 4 | 🐛 3 | 🌐 Python | 📅 2026-08-20 - 英語文字列をカタカナに変換するプログラム
* [wiredify](https://github.com/eggplants/wiredify) ⚠️ Archived - Convert japanese kana from ba-bi-bu-be-bo into va-vi-vu-ve-vo

| Name                                                                                                                                  | downloads/week | total downloads | stars | last commit      |
| ------------------------------------------------------------------------------------------------------------------------------------- | -------------- | --------------- | ----- | ---------------- |
| 🔗 [pykakasi](https://github.com/miurahr/pykakasi) ⭐ 462 \| 🐛 3 \| 🌐 Python \| 📅 2026-07-17                                        | 📥 312k        | 📦 37M          | ⭐ 462 | 🟢 july          |
| 🔗 [cutlet](https://github.com/polm/cutlet) ⭐ 382 \| 🐛 5 \| 🌐 Python \| 📅 2026-07-01                                               | 📥 19k         | 📦 2M           | ⭐ 382 | 🟢 july          |
| 🔗 [alphabet2kana](https://github.com/shihono/alphabet2kana) ⭐ 15 \| 🐛 6 \| 🌐 Python \| 📅 2026-08-01                               | 📥 145         | 📦 63k          | ⭐ 15  | 🟡 february      |
| 🔗 [Convert-Numbers-to-Japanese](https://github.com/Greatdane/Convert-Numbers-to-Japanese) ⭐ 51 \| 🐛 1 \| 🌐 Python \| 📅 2020-11-26 | -              | -               | ⭐ 51  | 🔴 november 2020 |
| 🔗 [mozcpy](https://github.com/ikegami-yukino/mozcpy) ⭐ 49 \| 🐛 0 \| 🌐 Python \| 📅 2025-02-14                                      | 📥 262         | 📦 18k          | ⭐ 49  | 🔴 february 2025 |
| 🔗 [jamorasep](https://github.com/tachi-hi/jamorasep) ⭐ 11 \| 🐛 0 \| 🌐 Python \| 📅 2026-02-16                                      | 📥 20          | 📦 11k          | ⭐ 11  | 🟡 february      |
| 🔗 [text2phoneme](https://github.com/korguchi/text2phoneme) ⭐ 13 \| 🐛 0 \| 🌐 Python \| 📅 2023-05-16                                | -              | -               | ⭐ 13  | 🔴 may 2023      |
| 🔗 [jntajis-python](https://github.com/opencollector/jntajis-python) ⭐ 21 \| 🐛 0 \| 🌐 C \| 📅 2026-03-11                            | 📥 1k          | 📦 141k         | ⭐ 21  | 🟡 march         |
| 🔗 [wiredify](https://github.com/eggplants/wiredify) ⚠️ Archived                                                                      | 📥 32          | 📦 7k           | ⭐ 3   | 🟡 december 2025 |
| 🔗 [mecab-text-cleaner](https://github.com/34j/mecab-text-cleaner) ⭐ 7 \| 🐛 14 \| 🌐 Python \| 📅 2026-08-17                         | 📥 17          | 📦 5k           | ⭐ 7   | 🟡 february      |
| 🔗 [pynormalizenumexp](https://github.com/tkscode/pynormalizenumexp) ⭐ 8 \| 🐛 0 \| 🌐 Python \| 📅 2024-04-28                        | 📥 11          | 📦 15k          | ⭐ 8   | 🔴 april 2024    |
| 🔗 [Jusho](https://github.com/nagataaaas/Jusho) ⭐ 12 \| 🐛 0 \| 🌐 Python \| 📅 2024-06-04                                            | 📥 433         | 📦 65k          | ⭐ 12  | 🔴 june 2024     |
| 🔗 [yurenizer](https://github.com/sea-turt1e/yurenizer) ⭐ 6 \| 🐛 0 \| 🌐 Python \| 📅 2025-03-16                                     | 📥 99          | 📦 21k          | ⭐ 6   | 🔴 march 2025    |
| 🔗 [e2k](https://github.com/Patchethium/e2k) ⭐ 20 \| 🐛 0 \| 🌐 Python \| 📅 2026-07-05                                               | 📥 946         | 📦 37k          | ⭐ 20  | 🟡 march         |
| 🔗 [alkana.py](https://github.com/zomysan/alkana.py) ⭐ 35 \| 🐛 0 \| 🌐 Python \| 📅 2021-10-07                                       | -              | -               | ⭐ 35  | 🔴 october 2021  |
| 🔗 [englishtokanaconverter](https://github.com/actlaboratory/englishtokanaconverter) ⭐ 4 \| 🐛 3 \| 🌐 Python \| 📅 2026-08-20        | -              | -               | ⭐ 4   | 🟢 last saturday |
| 🔗 [kanjiconv](https://github.com/sea-turt1e/kanjiconv) ⭐ 20 \| 🐛 0 \| 🌐 Python \| 📅 2026-08-08                                    | 📥 2k          | 📦 21k          | ⭐ 20  | 🟢 august        |
| 🔗 [kanjize](https://github.com/nagataaaas/kanjize) ⭐ 67 \| 🐛 1 \| 🌐 Python \| 📅 2025-06-14                                        | 📥 27k         | 📦 2M           | ⭐ 67  | 🔴 june 2025     |

### Preprocessor

Libraries that normalize and clean text before analysis

* [jaconv](https://github.com/ikegami-yukino/jaconv) ⭐ 350 | 🐛 5 | 🌐 Python | 📅 2026-07-20 - Pure-Python Japanese character interconverter for Hiragana, Katakana, Hankaku, and Zenkaku
* [neologdn](https://github.com/ikegami-yukino/neologdn) ⭐ 289 | 🐛 0 | 🌐 Cython | 📅 2026-05-06 - Japanese text normalizer for mecab-neologd
* [mojimoji](https://github.com/studio-ousia/mojimoji) ⭐ 152 | 🐛 3 | 🌐 Cython | 📅 2024-01-12 - A fast converter between Japanese hankaku and zenkaku characters
* [HojiChar](https://github.com/HojiChar/HojiChar) ⭐ 128 | 🐛 6 | 🌐 Python | 📅 2026-08-15 - 複数の前処理を構成して管理するテキスト前処理ツール
* [text-cleaning](https://github.com/ku-nlp/text-cleaning) ⭐ 12 | 🐛 2 | 🌐 Python | 📅 2024-01-20 - A powerful text cleaner for Japanese web texts
* [python-habachen](https://github.com/Hizuru3/python-habachen) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2025-10-26 - Yet Another Fast Japanese String Converter
* [kairyou](https://github.com/bikatr7/kairyou) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2025-06-24 - Quickly preprocesses Japanese text using NLP/NER from SpaCy for Japanese translation or other NLP tasks.
* [utsuho](https://github.com/juno-rmks/utsuho) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2026-03-29 - Utsuho is a Python module that facilitates bidirectional conversion between half-width katakana and full-width katakana in Japanese.

| Name                                                                                                   | downloads/week | total downloads | stars | last commit      |
| ------------------------------------------------------------------------------------------------------ | -------------- | --------------- | ----- | ---------------- |
| 🔗 [neologdn](https://github.com/ikegami-yukino/neologdn) ⭐ 289 \| 🐛 0 \| 🌐 Cython \| 📅 2026-05-06  | 📥 9k          | 📦 2M           | ⭐ 289 | 🟡 may           |
| 🔗 [jaconv](https://github.com/ikegami-yukino/jaconv) ⭐ 350 \| 🐛 5 \| 🌐 Python \| 📅 2026-07-20      | 📥 684k        | 📦 79M          | ⭐ 350 | 🟡 february      |
| 🔗 [mojimoji](https://github.com/studio-ousia/mojimoji) ⭐ 152 \| 🐛 3 \| 🌐 Cython \| 📅 2024-01-12    | 📥 66k         | 📦 13M          | ⭐ 152 | 🔴 january 2024  |
| 🔗 [text-cleaning](https://github.com/ku-nlp/text-cleaning) ⭐ 12 \| 🐛 2 \| 🌐 Python \| 📅 2024-01-20 | -              | -               | ⭐ 12  | 🔴 november 2022 |
| 🔗 [HojiChar](https://github.com/HojiChar/HojiChar) ⭐ 128 \| 🐛 6 \| 🌐 Python \| 📅 2026-08-15        | 📥 4k          | 📦 1M           | ⭐ 128 | 🟢 last saturday |
| 🔗 [utsuho](https://github.com/juno-rmks/utsuho) ⭐ 5 \| 🐛 1 \| 🌐 Python \| 📅 2026-03-29             | 📥 183         | 📦 25k          | ⭐ 5   | 🟡 march         |
| 🔗 [python-habachen](https://github.com/Hizuru3/python-habachen) ⭐ 6 \| 🐛 0 \| 🌐 C \| 📅 2025-10-26  | 📥 33k         | 📦 2M           | ⭐ 6   | 🟡 october 2025  |
| 🔗 [kairyou](https://github.com/bikatr7/kairyou) ⭐ 6 \| 🐛 0 \| 🌐 Python \| 📅 2025-06-24             | 📥 132         | 📦 34k          | ⭐ 6   | 🔴 june 2025     |

### Sentence splitter

Libraries that automatically detect sentence boundaries and split text

* [budoux](https://github.com/google/budoux) ⭐ 1,766 | 🐛 10 | 🌐 Python | 📅 2026-08-20 - Standalone. Small. Language-neutral. BudouX is the successor to Budou, the machine learning powered line break organizer tool.
* [Bunkai](https://github.com/megagonlabs/bunkai) ⭐ 200 | 🐛 18 | 🌐 Python | 📅 2024-03-26 - Sentence boundary disambiguation tool for Japanese texts (日本語文境界判定器)
* [ja\_sentence\_segmenter](https://github.com/wwwcojp/ja_sentence_segmenter) ⭐ 76 | 🐛 1 | 🌐 Python | 📅 2026-08-15 - japanese sentence segmentation library for python
* [fast-bunkai](https://github.com/hotchpotch/fast-bunkai) ⭐ 76 | 🐛 0 | 🌐 Rust | 📅 2025-10-14 - Japanese sentence splitting(日本語文境界判定器), 40–250× faster via a Rust-accelerated Python library with near-perfect API compatibility with megagonlabs/bunkai.
* [sengiri](https://github.com/ikegami-yukino/sengiri) ⭐ 24 | 🐛 2 | 🌐 Python | 📅 2025-11-27 - Yet another sentence-level tokenizer for the Japanese text
* [japanese-sentence-breaker](https://github.com/hppRC/japanese-sentence-breaker) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2021-06-06 - Japanese Sentence Breaker
* [ja-senter-benchmark](https://github.com/hkiyomaru/ja-senter-benchmark) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2023-02-27 - Comparison of Japanese Sentence Segmentation Tools
* [hasami](https://github.com/mkartawijaya/hasami) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2021-02-21 - A tool to perform sentence segmentation on Japanese text
* [kuzukiri](https://github.com/alinear-corp/kuzukiri) ⭐ 6 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2025-06-28 - Japanese Text Segmenter for Python written in Rust

| Name                                                                                                                          | downloads/week | total downloads | stars  | last commit      |
| ----------------------------------------------------------------------------------------------------------------------------- | -------------- | --------------- | ------ | ---------------- |
| 🔗 [bunkai](https://github.com/megagonlabs/bunkai) ⭐ 200 \| 🐛 18 \| 🌐 Python \| 📅 2024-03-26                               | 📥 660         | 📦 122k         | ⭐ 200  | 🔴 august 2023   |
| 🔗 [japanese-sentence-breaker](https://github.com/hppRC/japanese-sentence-breaker) ⭐ 14 \| 🐛 1 \| 🌐 Python \| 📅 2021-06-06 | 📥 7           | 📦 6k           | ⭐ 14   | 🔴 february 2021 |
| 🔗 [sengiri](https://github.com/ikegami-yukino/sengiri) ⭐ 24 \| 🐛 2 \| 🌐 Python \| 📅 2025-11-27                            | 📥 67          | 📦 138k         | ⭐ 24   | 🟡 november 2025 |
| 🔗 [budoux](https://github.com/google/budoux) ⭐ 1,766 \| 🐛 10 \| 🌐 Python \| 📅 2026-08-20                                  | 📥 16k         | 📦 708k         | ⭐ 1.8k | 🟢 today         |
| 🔗 [ja\_sentence\_segmenter](https://github.com/wwwcojp/ja_sentence_segmenter) ⭐ 76 \| 🐛 1 \| 🌐 Python \| 📅 2026-08-15     | 📥 2k          | 📦 262k         | ⭐ 76   | 🟢 july          |
| 🔗 [hasami](https://github.com/mkartawijaya/hasami) ⭐ 6 \| 🐛 0 \| 🌐 Python \| 📅 2021-02-21                                 | 📥 256         | 📦 45k          | ⭐ 6    | 🔴 february 2021 |
| 🔗 [kuzukiri](https://github.com/alinear-corp/kuzukiri) ⭐ 6 \| 🐛 1 \| 🌐 Jupyter Notebook \| 📅 2025-06-28                   | 📥 105         | 📦 30k          | ⭐ 6    | 🔴 june 2025     |
| 🔗 [ja-senter-benchmark](https://github.com/hkiyomaru/ja-senter-benchmark) ⭐ 10 \| 🐛 0 \| 🌐 Python \| 📅 2023-02-27         | -              | -               | ⭐ 10   | 🔴 february 2023 |
| 🔗 [fast-bunkai](https://github.com/hotchpotch/fast-bunkai) ⭐ 76 \| 🐛 0 \| 🌐 Rust \| 📅 2025-10-14                          | 📥 171         | 📦 9k           | ⭐ 75   | 🟡 october 2025  |

### Sentiment analysis

Libraries that detect emotions or polarity in text

* [asari](https://github.com/Hironsan/asari) ⭐ 153 | 🐛 3 | 🌐 Python | 📅 2024-02-15 - Japanese sentiment analyzer implemented in Python.
* [negapoji](https://github.com/liaoziyang/negapoji) ⭐ 152 | 🐛 0 | 🌐 Python | 📅 2017-08-20 - Japanese negative positive classification.日本語文書のネガポジを判定。
* [pymlask](https://github.com/ikegami-yukino/pymlask) ⭐ 118 | 🐛 1 | 🌐 Python | 📅 2024-07-25 - Emotion analyzer for Japanese text
* [oseti](https://github.com/ikegami-yukino/oseti) ⭐ 99 | 🐛 1 | 🌐 Python | 📅 2025-08-02 - Dictionary based Sentiment Analysis for Japanese
* [kotobacore](https://github.com/ekiyo55/kotobacore) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-08-18 - Japanese semantic understanding engine for LLM, RAG, SNS analysis, and AI agents ? dependency-free tokenizer + Plutchik emotion + intent + RAG keywords.

| Name                                                                                                | downloads/week | total downloads | stars | last commit     |
| --------------------------------------------------------------------------------------------------- | -------------- | --------------- | ----- | --------------- |
| 🔗 [oseti](https://github.com/ikegami-yukino/oseti) ⭐ 99 \| 🐛 1 \| 🌐 Python \| 📅 2025-08-02      | 📥 137         | 📦 173k         | ⭐ 99  | 🔴 august 2025  |
| 🔗 [negapoji](https://github.com/liaoziyang/negapoji) ⭐ 152 \| 🐛 0 \| 🌐 Python \| 📅 2017-08-20   | -              | -               | ⭐ 152 | 🔴 august 2017  |
| 🔗 [pymlask](https://github.com/ikegami-yukino/pymlask) ⭐ 118 \| 🐛 1 \| 🌐 Python \| 📅 2024-07-25 | 📥 29          | 📦 67k          | ⭐ 118 | 🔴 july 2024    |
| 🔗 [asari](https://github.com/Hironsan/asari) ⭐ 153 \| 🐛 3 \| 🌐 Python \| 📅 2024-02-15           | 📥 79          | 📦 82k          | ⭐ 153 | 🔴 october 2022 |
| 🔗 [kotobacore](https://github.com/ekiyo55/kotobacore) ⭐ 0 \| 🐛 0 \| 🌐 Python \| 📅 2026-08-18    | -              | -               | ⭐ 0   | 🟢 august       |

### Machine translation

Libraries that automatically translate text between languages

* [plamo-translate-cli](https://github.com/pfnet/plamo-translate-cli) ⭐ 351 | 🐛 1 | 🌐 Python | 📅 2026-04-15 - A command-line interface for translation using the plamo-2-translate model with local execution.
* [jparacrawl-finetune](https://github.com/MorinoseiMorizo/jparacrawl-finetune) ⭐ 104 | 🐛 2 | 🌐 Shell | 📅 2021-04-29 - An example usage of JParaCrawl pre-trained Neural Machine Translation (NMT) models.
* [PheMT](https://github.com/cl-tohoku/PheMT) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2021-02-18 - A phenomenon-wise evaluation dataset for Japanese-English machine translation robustness. The dataset is based on the MTNT dataset, with additional annotations of four linguistic phenomena; Proper Noun, Abbreviated Noun, Colloquial Expression, and Variant. COLING 2020.
* [JASS](https://github.com/Mao-KU/JASS) ⭐ 16 | 🐛 0 | 📅 2022-01-25 - JASS: Japanese-specific Sequence to Sequence Pre-training for Neural Machine Translation (LREC2020) & Linguistically Driven Multi-Task Pre-Training for Low-Resource Neural Machine Translation (ACM TALLIP)
* [VISA](https://github.com/ku-nlp/VISA) ⭐ 14 | 🐛 0 | 📅 2022-10-17 - An ambiguous subtitles dataset for visual scene-aware machine translation

| Name                                                                                                                        | downloads/week | total downloads | stars | last commit      |
| --------------------------------------------------------------------------------------------------------------------------- | -------------- | --------------- | ----- | ---------------- |
| 🔗 [jparacrawl-finetune](https://github.com/MorinoseiMorizo/jparacrawl-finetune) ⭐ 104 \| 🐛 2 \| 🌐 Shell \| 📅 2021-04-29 | -              | -               | ⭐ 104 | 🔴 april 2021    |
| 🔗 [JASS](https://github.com/Mao-KU/JASS) ⭐ 16 \| 🐛 0 \| 📅 2022-01-25                                                     | -              | -               | ⭐ 16  | 🔴 january 2022  |
| 🔗 [PheMT](https://github.com/cl-tohoku/PheMT) ⭐ 19 \| 🐛 0 \| 🌐 Python \| 📅 2021-02-18                                   | -              | -               | ⭐ 19  | 🔴 february 2021 |
| 🔗 [VISA](https://github.com/ku-nlp/VISA) ⭐ 14 \| 🐛 0 \| 📅 2022-10-17                                                     | -              | -               | ⭐ 14  | 🔴 october 2022  |
| 🔗 [plamo-translate-cli](https://github.com/pfnet/plamo-translate-cli) ⭐ 351 \| 🐛 1 \| 🌐 Python \| 📅 2026-04-15          | -              | -               | ⭐ 351 | 🟡 april         |

### Named entity recognition

Libraries that extract names of people, places, and organizations from text

* [namaco](https://github.com/chakki-works/namaco) ⭐ 40 | 🐛 5 | 🌐 Python | 📅 2018-04-03 - Character Based Named Entity Recognition.
* [pygeonlp](https://github.com/geonlp-platform/pygeonlp) ⭐ 22 | 🐛 4 | 🌐 Python | 📅 2026-03-24 - pygeonlp, A python module for geotagging Japanese texts.
* [huggingface-finetune-japanese](https://github.com/tsmatz/huggingface-finetune-japanese) ⭐ 16 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2023-10-06 - Examples to finetune encoder-only and encoder-decoder transformers for Japanese language (Hugging Face) Resources
* [entitypedia](https://github.com/chakki-works/entitypedia) ⭐ 13 | 🐛 11 | 🌐 Jupyter Notebook | 📅 2022-12-07 - Entitypedia is an Extended Named Entity Dictionary from Wikipedia.
* [bert-japanese-ner-finetuning](https://github.com/ken11/bert-japanese-ner-finetuning) ⭐ 11 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2022-06-19 - Code to perform finetuning of the BERT model. BERTモデルのファインチューニングで固有表現抽出用タスクのモデルを作成・使用するサンプルです
* [noyaki](https://github.com/ken11/noyaki) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2022-08-25 - Converts character span label information to tokenized text-based label information.
* [bert-ner-japanese](https://github.com/jurabiinc/bert-ner-japanese) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2022-09-26 - BERTによる日本語固有表現抽出のファインチューニング用プログラム
* [novelanalysisbyner](https://github.com/lychee1223/novelanalysisbyner) ⭐ 2 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-06-28 - BERTのfine-tuningによる固有表現抽出
* [joint-information-extraction-hs](https://github.com/aih-uth/joint-information-extraction-hs) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2021-11-17 - 詳細なアノテーション基準に基づく症例報告コーパスからの固有表現及び関係の抽出精度の推論を行うコード

| Name                                                                                                                                             | downloads/week | total downloads | stars | last commit       |
| ------------------------------------------------------------------------------------------------------------------------------------------------ | -------------- | --------------- | ----- | ----------------- |
| 🔗 [namaco](https://github.com/chakki-works/namaco) ⭐ 40 \| 🐛 5 \| 🌐 Python \| 📅 2018-04-03                                                   | -              | -               | ⭐ 40  | 🔴 february 2018  |
| 🔗 [entitypedia](https://github.com/chakki-works/entitypedia) ⭐ 13 \| 🐛 11 \| 🌐 Jupyter Notebook \| 📅 2022-12-07                              | -              | -               | ⭐ 13  | 🔴 december 2018  |
| 🔗 [noyaki](https://github.com/ken11/noyaki) ⭐ 5 \| 🐛 0 \| 🌐 Python \| 📅 2022-08-25                                                           | 📥 102         | 📦 24k          | ⭐ 5   | 🔴 august 2022    |
| 🔗 [bert-japanese-ner-finetuning](https://github.com/ken11/bert-japanese-ner-finetuning) ⭐ 11 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2022-06-19    | -              | -               | ⭐ 11  | 🔴 june 2022      |
| 🔗 [joint-information-extraction-hs](https://github.com/aih-uth/joint-information-extraction-hs) ⭐ 1 \| 🐛 0 \| 🌐 Python \| 📅 2021-11-17       | -              | -               | ⭐ 1   | 🔴 november 2021  |
| 🔗 [pygeonlp](https://github.com/geonlp-platform/pygeonlp) ⭐ 22 \| 🐛 4 \| 🌐 Python \| 📅 2026-03-24                                            | 📥 259         | 📦 27k          | ⭐ 22  | 🟡 march          |
| 🔗 [bert-ner-japanese](https://github.com/jurabiinc/bert-ner-japanese) ⭐ 5 \| 🐛 1 \| 🌐 Python \| 📅 2022-09-26                                 | -              | -               | ⭐ 5   | 🔴 september 2022 |
| 🔗 [huggingface-finetune-japanese](https://github.com/tsmatz/huggingface-finetune-japanese) ⭐ 16 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2023-10-06 | -              | -               | ⭐ 16  | 🔴 october 2023   |
| 🔗 [novelanalysisbyner](https://github.com/lychee1223/novelanalysisbyner) ⭐ 2 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2024-06-28                    | -              | -               | ⭐ 2   | 🔴 june 2024      |

### OCR

Libraries that recognize and extract text from images

* [donut](https://github.com/clovaai/donut) ⭐ 6,914 | 🐛 211 | 🌐 Python | 📅 2024-07-11 - Official Implementation of OCR-free Document Understanding Transformer (Donut) and Synthetic Document Generator (SynthDoG), ECCV 2022
* [Manga OCR](https://github.com/kha-white/manga-ocr) ⭐ 2,755 | 🐛 43 | 🌐 Python | 📅 2026-07-19 - About Optical character recognition for Japanese text, with the main focus being Japanese manga
* [mokuro](https://github.com/kha-white/mokuro) ⭐ 1,705 | 🐛 34 | 🌐 HTML | 📅 2026-07-20 - Read Japanese manga inside browser with selectable text.
* [yomitoku](https://github.com/kotaro-kinoshita/yomitoku) ⭐ 1,578 | 🐛 6 | 🌐 Python | 📅 2026-08-18 - Yomitoku is an AI-powered document image analysis package designed specifically for the Japanese language.
* [ndlocr\_cli](https://github.com/ndl-lab/ndlocr_cli) ⭐ 680 | 🐛 2 | 🌐 Python | 📅 2026-01-05 - NDLOCRのアプリケーション
* [meikipop](https://github.com/rtr46/meikipop) ⭐ 633 | 🐛 7 | 🌐 Python | 📅 2026-08-17 - universal japanese ocr popup dictionary for windows, linux and macos
* [Poricom](https://github.com/blueaxis/Poricom) ⭐ 440 | 🐛 32 | 🌐 Python | 📅 2023-11-23 - Optical character recognition in manga images. Manga OCR desktop application
* [owocr](https://github.com/aurorawright/owocr) ⭐ 287 | 🐛 19 | 🌐 Python | 📅 2026-06-03 - Optical character recognition for Japanese text
* [OCR\_Japanease](https://github.com/tanreinama/OCR_Japanease) ⭐ 251 | 🐛 2 | 🌐 Python | 📅 2021-08-07 - 日本語OCR
* [Kindai-OCR](https://github.com/ducanh841988/Kindai-OCR) ⭐ 153 | 🐛 4 | 🌐 Python | 📅 2026-07-14 - OCR system for recognizing modern Japanese magazines
* [meikiocr](https://github.com/rtr46/meikiocr) ⭐ 89 | 🐛 0 | 🌐 Python | 📅 2026-04-27 - high-speed, high-accuracy, local ocr for japanese video games
* [JMTrans](https://github.com/ttop32/JMTrans) ⭐ 88 | 🐛 5 | 🌐 Python | 📅 2021-01-16 - manga translator - get japanese manga from url to translate manga image
* [findtextcenternet](https://github.com/lithium0003/findtextcenternet) ⭐ 64 | 🐛 2 | 🌐 Python | 📅 2025-08-02 - Japanese OCR with CenterNet
* [MangaOCR](https://github.com/gnurt2041/MangaOCR) ⭐ 39 | 🐛 1 | 🌐 Python | 📅 2024-05-12 - A lightweight OCR model for Japanese text, especially in Manga
* [handwritten-japanese-ocr](https://github.com/yas-sim/handwritten-japanese-ocr) ⭐ 37 | 🐛 0 | 🌐 Python | 📅 2022-04-05 - Handwritten Japanese OCR demo using touch panel to draw the input text using Intel OpenVINO toolkit
* [paddleocr-vl-sft-for-japanese-manga-on-rtx-3060](https://github.com/openvino-book/paddleocr-vl-sft-for-japanese-manga-on-rtx-3060) ⭐ 15 | 🐛 1 | 🌐 Python | 📅 2025-12-07 - Fine-tune PaddleOCR-VL on the Manga109s dataset for Japanese manga text recognition. The base model struggles with vertical Japanese text reading order in manga. After fine-tuning, the model correctly handles manga-specific text layouts.
* [text\_recognition](https://github.com/ndl-lab/text_recognition) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2023-07-10 - NDLOCR用テキスト認識モジュール
* [simple-ocr-for-manga](https://github.com/yisusdev2005/simple-ocr-for-manga) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2025-03-10 - A simple OCR for manga (Japanese traditional and Japanese vertical)
* [jp-ocr-evaluation](https://github.com/yoshino/jp-ocr-evaluation) ⭐ 1 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-03-09 - 日本語の文章画像に対するOCRの性能を評価

| Name                                                                                                                                                                              | downloads/week | total downloads | stars  | last commit       |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------- | --------------- | ------ | ----------------- |
| 🔗 [manga-ocr](https://github.com/kha-white/manga-ocr) ⭐ 2,755 \| 🐛 43 \| 🌐 Python \| 📅 2026-07-19                                                                             | 📥 5k          | 📦 372k         | ⭐ 2.8k | 🟢 july           |
| 🔗 [mokuro](https://github.com/kha-white/mokuro) ⭐ 1,705 \| 🐛 34 \| 🌐 HTML \| 📅 2026-07-20                                                                                     | 📥 847         | 📦 111k         | ⭐ 1.7k | 🟢 july           |
| 🔗 [handwritten-japanese-ocr](https://github.com/yas-sim/handwritten-japanese-ocr) ⭐ 37 \| 🐛 0 \| 🌐 Python \| 📅 2022-04-05                                                     | -              | -               | ⭐ 37   | 🔴 april 2022     |
| 🔗 [OCR\_Japanease](https://github.com/tanreinama/OCR_Japanease) ⭐ 251 \| 🐛 2 \| 🌐 Python \| 📅 2021-08-07                                                                      | -              | -               | ⭐ 251  | 🔴 april 2021     |
| 🔗 [ndlocr\_cli](https://github.com/ndl-lab/ndlocr_cli) ⭐ 680 \| 🐛 2 \| 🌐 Python \| 📅 2026-01-05                                                                               | -              | -               | ⭐ 680  | 🟡 september 2025 |
| 🔗 [donut](https://github.com/clovaai/donut) ⭐ 6,914 \| 🐛 211 \| 🌐 Python \| 📅 2024-07-11                                                                                      | 📥 268         | 📦 204k         | ⭐ 6.9k | 🔴 july 2023      |
| 🔗 [JMTrans](https://github.com/ttop32/JMTrans) ⭐ 88 \| 🐛 5 \| 🌐 Python \| 📅 2021-01-16                                                                                        | -              | -               | ⭐ 88   | 🔴 january 2021   |
| 🔗 [Kindai-OCR](https://github.com/ducanh841988/Kindai-OCR) ⭐ 153 \| 🐛 4 \| 🌐 Python \| 📅 2026-07-14                                                                           | -              | -               | ⭐ 153  | 🟢 july           |
| 🔗 [text\_recognition](https://github.com/ndl-lab/text_recognition) ⭐ 8 \| 🐛 0 \| 🌐 Python \| 📅 2023-07-10                                                                     | -              | -               | ⭐ 8    | 🔴 july 2023      |
| 🔗 [Poricom](https://github.com/blueaxis/Poricom) ⭐ 440 \| 🐛 32 \| 🌐 Python \| 📅 2023-11-23                                                                                    | -              | -               | ⭐ 439  | 🔴 june 2023      |
| 🔗 [owocr](https://github.com/aurorawright/owocr) ⭐ 287 \| 🐛 19 \| 🌐 Python \| 📅 2026-06-03                                                                                    | -              | -               | ⭐ 287  | 🟡 march          |
| 🔗 [yomitoku](https://github.com/kotaro-kinoshita/yomitoku) ⭐ 1,578 \| 🐛 6 \| 🌐 Python \| 📅 2026-08-18                                                                         | 📥 2k          | 📦 123k         | ⭐ 1.6k | 🟢 last friday    |
| 🔗 [findtextcenternet](https://github.com/lithium0003/findtextcenternet) ⭐ 64 \| 🐛 2 \| 🌐 Python \| 📅 2025-08-02                                                               | -              | -               | ⭐ 64   | 🔴 august 2025    |
| 🔗 [simple-ocr-for-manga](https://github.com/yisusdev2005/simple-ocr-for-manga) ⭐ 7 \| 🐛 0 \| 🌐 Python \| 📅 2025-03-10                                                         | -              | -               | ⭐ 7    | 🔴 march 2025     |
| 🔗 [jp-ocr-evaluation](https://github.com/yoshino/jp-ocr-evaluation) ⭐ 1 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2024-03-09                                                          | -              | -               | ⭐ 1    | 🔴 march 2024     |
| 🔗 [paddleocr-vl-sft-for-japanese-manga-on-rtx-3060](https://github.com/openvino-book/paddleocr-vl-sft-for-japanese-manga-on-rtx-3060) ⭐ 15 \| 🐛 1 \| 🌐 Python \| 📅 2025-12-07 | -              | -               | ⭐ 15   | 🟡 december 2025  |
| 🔗 [MangaOCR](https://github.com/gnurt2041/MangaOCR) ⭐ 39 \| 🐛 1 \| 🌐 Python \| 📅 2024-05-12                                                                                   | -              | -               | ⭐ 39   | 🔴 may 2024       |
| 🔗 [meikiocr](https://github.com/rtr46/meikiocr) ⭐ 89 \| 🐛 0 \| 🌐 Python \| 📅 2026-04-27                                                                                       | 📥 1k          | 📦 46k          | ⭐ 89   | 🟡 april          |
| 🔗 [meikipop](https://github.com/rtr46/meikipop) ⭐ 633 \| 🐛 7 \| 🌐 Python \| 📅 2026-08-17                                                                                      | -              | -               | ⭐ 596  | 🟢 june           |

### Tool for pretrained models

Libraries that utilize pretrained models to improve accuracy and efficiency

* [JGLUE](https://github.com/yahoojapan/JGLUE) ⭐ 347 | 🐛 4 | 🌐 Python | 📅 2025-03-31 - JGLUE: Japanese General Language Understanding Evaluation
* [llm-jp-eval](https://github.com/llm-jp/llm-jp-eval) ⭐ 166 | 🐛 3 | 🌐 Python | 📅 2026-07-31 - このツールは、複数のデータセットを横断して日本語の大規模言語モデルを自動評価するものです．
* [jp-stable](https://github.com/Stability-AI/lm-evaluation-harness/tree/jp-stable) ⭐ 154 | 🐛 10 | 🌐 Python | 📅 2024-09-13 - JP Language Model Evaluation Harness
* [llm-lora-classification](https://github.com/hppRC/llm-lora-classification) ⭐ 98 | 🐛 1 | 🌐 Python | 📅 2023-07-22 - llm-lora-classification
* [japanese-lm-fin-harness](https://github.com/pfnet-research/japanese-lm-fin-harness) ⭐ 79 | 🐛 2 | 🌐 Shell | 📅 2026-06-17 - Japanese Language Model Financial Evaluation Harness
* [llm-jp-sft](https://github.com/llm-jp/llm-jp-sft) ⭐ 62 | 🐛 2 | 🌐 Python | 📅 2024-06-13 - This repository contains the code for supervised fine-tuning of LLM-jp models.
* [japanese-llm-ranking](https://github.com/yuzu-ai/japanese-llm-ranking) ⭐ 50 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2024-04-10 - This repository supports YuzuAI's Rakuda leaderboard of Japanese LLMs, which is a Japanese-focused analogue of LMSYS' Vicuna eval.
* [llm-jp-tokenizer](https://github.com/llm-jp/llm-jp-tokenizer) ⭐ 49 | 🐛 2 | 🌐 Python | 📅 2026-03-30 - LLM勉強会（LLM-jp）で開発しているLLM用のトークナイザー関連をまとめたリポジトリです．
* [Japanese-BPEEncoder](https://github.com/tanreinama/Japanese-BPEEncoder) ⭐ 42 | 🐛 1 | 🌐 Python | 📅 2021-09-12 - Japanese-BPEEncoder
* [Japanese-BPEEncoder\_V2](https://github.com/tanreinama/Japanese-BPEEncoder_V2) ⭐ 41 | 🐛 1 | 🌐 Python | 📅 2023-01-15 - Japanese-BPEEncoder Version 2
* [japanese-llm-roleplay-benchmark](https://github.com/oshizo/japanese-llm-roleplay-benchmark) ⭐ 41 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2023-11-03 - このリポジトリは日本語LLMのキャラクターロールプレイに関する性能を評価するために作成しました。
* [ja-vicuna-qa-benchmark](https://github.com/ku-nlp/ja-vicuna-qa-benchmark) ⭐ 33 | 🐛 2 | 🌐 Python | 📅 2024-07-31 - Japanese Vicuna QA Benchmark
* [swallow-evaluation-instruct](https://github.com/swallow-llm/swallow-evaluation-instruct) ⭐ 31 | 🐛 0 | 🌐 Python | 📅 2026-05-08 - Swallowプロジェクト 事後学習ずみ大規模言語モデル 評価フレームワーク
* [transformer-copy](https://github.com/youichiro/transformer-copy) ⭐ 29 | 🐛 4 | 🌐 Python | 📅 2022-06-22 - 日本語文法誤り訂正ツール
* [swallow-evaluation](https://github.com/swallow-llm/swallow-evaluation) ⭐ 25 | 🐛 2 | 🌐 Python | 📅 2025-09-17 - Swallowプロジェクト 大規模言語モデル 評価スクリプト
* [pretrained\_doc2vec\_ja](https://github.com/yagays/pretrained_doc2vec_ja) ⭐ 25 | 🐛 1 | 🌐 Python | 📅 2019-01-25 - pretrained doc2vec models on Japanese Wikipedia
* [pl-bert-ja](https://github.com/kyamauchi1023/pl-bert-ja) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2023-12-16 - A repository of Japanese Phoneme-Level BERT
* [gector-ja](https://github.com/jonnyli1125/gector-ja) ⭐ 19 | 🐛 1 | 🌐 Python | 📅 2023-08-04 - BERT-based GEC tagging for Japanese
* [rinna\_gpt-neox\_ggml-lora](https://github.com/yukaryavka/rinna_gpt-neox_ggml-lora) ⚠️ Archived - The repository contains scripts and merge scripts that have been modified to adapt an Alpaca-Lora adapter for LoRA tuning when assuming the use of the "rinna/japanese-gpt-neox..." \[gpt-neox] model converted to ggml.
* [JGLUE-benchmark](https://github.com/nobu-g/JGLUE-benchmark) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2026-08-05 - Training and evaluation scripts for JGLUE, a Japanese language understanding benchmark
* [ginza-transformers](https://github.com/megagonlabs/ginza-transformers) ⭐ 16 | 🐛 2 | 🌐 Python | 📅 2022-08-09 - Use custom tokenizers in spacy-transformers
* [allennlp-shiba-model](https://github.com/shunk031/allennlp-shiba-model) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2021-06-26 - AllenNLP integration for Shiba: Japanese CANINE model
* [evaluate\_japanese\_w2v](https://github.com/shihono/evaluate_japanese_w2v) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2024-11-04 - script to evaluate pre-trained Japanese word2vec model on Japanese similarity dataset
* [japanese\_text\_classification](https://github.com/Masao-Taketani/japanese_text_classification) ⭐ 9 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2020-01-15 - To investigate various DNN text classifiers including MLP, CNN, RNN, BERT approaches.
* [compare-ja-tokenizer](https://github.com/hitachi-nlp/compare-ja-tokenizer) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2023-06-16 - How do different tokenizers perform on downstream tasks in scriptio continua languages?: A case study in Japanese-ACL SRW 2023
* [jmlm\_scoring](https://github.com/minhpqn/jmlm_scoring) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2024-01-30 - Masked Language Model-based Scoring for Japanese and Vietnamese
* [nagisa\_bert](https://github.com/taishi-i/nagisa_bert) ⭐ 5 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-02-25 - A BERT model for nagisa
* [jptranstokenizer](https://github.com/retarfi/jptranstokenizer) ⭐ 5 | 🐛 2 | 🌐 Python | 📅 2024-02-02 - Japanese Tokenizer for transformers library
* [t5\_japanese\_dialogue\_generation](https://github.com/Jinyamyzk/t5_japanese_dialogue_generation) ⭐ 3 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2021-11-28 - T5による会話生成
* [Japanese-BERT-Sentiment-Analyzer](https://github.com/izuna385/Japanese-BERT-Sentiment-Analyzer) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2021-04-19 - Deploying sentiment analysis server with FastAPI and BERT
* [lm-evaluation-harness-jp-stable](https://github.com/tdc-yamada-ya/lm-evaluation-harness-jp-stable) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2023-06-20 - A framework for few-shot evaluation of autoregressive language models.
* [japanese-stable-diffusion](https://github.com/rinnakk/japanese-stable-diffusion) - Japanese Stable Diffusion is a Japanese specific latent text-to-image diffusion model capable of generating photo-realistic images given any text input.
* [prefix-tuning-gpt](https://github.com/rinnakk/prefix-tuning-gpt) - Example code for prefix-tuning GPT/GPT-NeoX models and for inference with trained prefixes

| Name                                                                                                                                                      | downloads/week | total downloads | stars            | last commit       |
| --------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------- | --------------- | ---------------- | ----------------- |
| 🔗 [JGLUE](https://github.com/yahoojapan/JGLUE) ⭐ 347 \| 🐛 4 \| 🌐 Python \| 📅 2025-03-31                                                               | -              | -               | ⭐ 347            | 🔴 march 2025     |
| 🔗 [ginza-transformers](https://github.com/megagonlabs/ginza-transformers) ⭐ 16 \| 🐛 2 \| 🌐 Python \| 📅 2022-08-09                                     | 📥 325         | 📦 276k         | ⭐ 16             | 🔴 august 2022    |
| 🔗 [t5\_japanese\_dialogue\_generation](https://github.com/Jinyamyzk/t5_japanese_dialogue_generation) ⭐ 3 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2021-11-28 | -              | -               | ⭐ 3              | 🔴 november 2021  |
| 🔗 [japanese\_text\_classification](https://github.com/Masao-Taketani/japanese_text_classification) ⭐ 9 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2020-01-15   | -              | -               | ⭐ 9              | 🔴 january 2020   |
| 🔗 [Japanese-BERT-Sentiment-Analyzer](https://github.com/izuna385/Japanese-BERT-Sentiment-Analyzer) ⭐ 2 \| 🐛 0 \| 🌐 Python \| 📅 2021-04-19             | -              | -               | ⭐ 2              | 🔴 april 2021     |
| 🔗 [jmlm\_scoring](https://github.com/minhpqn/jmlm_scoring) ⭐ 5 \| 🐛 0 \| 🌐 Python \| 📅 2024-01-30                                                     | -              | -               | ⭐ 5              | 🔴 february 2022  |
| 🔗 [allennlp-shiba-model](https://github.com/shunk031/allennlp-shiba-model) ⭐ 12 \| 🐛 0 \| 🌐 Python \| 📅 2021-06-26                                    | 📥 47          | 📦 23k          | ⭐ 12             | 🔴 june 2021      |
| 🔗 [evaluate\_japanese\_w2v](https://github.com/shihono/evaluate_japanese_w2v) ⭐ 12 \| 🐛 0 \| 🌐 Python \| 📅 2024-11-04                                 | -              | -               | ⭐ 12             | 🔴 november 2024  |
| 🔗 [gector-ja](https://github.com/jonnyli1125/gector-ja) ⭐ 19 \| 🐛 1 \| 🌐 Python \| 📅 2023-08-04                                                       | -              | -               | ⭐ 19             | 🔴 june 2021      |
| 🔗 [Japanese-BPEEncoder](https://github.com/tanreinama/Japanese-BPEEncoder) ⭐ 42 \| 🐛 1 \| 🌐 Python \| 📅 2021-09-12                                    | -              | -               | ⭐ 42             | 🔴 september 2021 |
| 🔗 [Japanese-BPEEncoder\_V2](https://github.com/tanreinama/Japanese-BPEEncoder_V2) ⭐ 41 \| 🐛 1 \| 🌐 Python \| 📅 2023-01-15                             | -              | -               | ⭐ 41             | 🔴 january 2023   |
| 🔗 [transformer-copy](https://github.com/youichiro/transformer-copy) ⭐ 29 \| 🐛 4 \| 🌐 Python \| 📅 2022-06-22                                           | -              | -               | ⭐ 29             | 🔴 september 2020 |
| 🔗 [japanese-stable-diffusion](https://github.com/rinnakk/japanese-stable-diffusion)                                                                      | -              | -               | ⭐ repo not found | 🔴 repo not found |
| 🔗 [nagisa\_bert](https://github.com/taishi-i/nagisa_bert) ⭐ 5 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2026-02-25                                            | 📥 48          | 📦 63k          | ⭐ 5              | 🟡 february       |
| 🔗 [prefix-tuning-gpt](https://github.com/rinnakk/prefix-tuning-gpt)                                                                                      | -              | -               | ⭐ repo not found | 🔴 repo not found |
| 🔗 [JGLUE-benchmark](https://github.com/nobu-g/JGLUE-benchmark) ⭐ 18 \| 🐛 0 \| 🌐 Python \| 📅 2026-08-05                                                | -              | -               | ⭐ 18             | 🟢 august         |
| 🔗 [jptranstokenizer](https://github.com/retarfi/jptranstokenizer) ⭐ 5 \| 🐛 2 \| 🌐 Python \| 📅 2024-02-02                                              | 📥 82          | 📦 31k          | ⭐ 5              | 🔴 february 2024  |
| 🔗 [jp-stable](https://github.com/Stability-AI/lm-evaluation-harness/tree/jp-stable) ⭐ 154 \| 🐛 10 \| 🌐 Python \| 📅 2024-09-13                         | -              | -               | ⭐ 154            | 🔴 november 2023  |
| 🔗 [compare-ja-tokenizer](https://github.com/hitachi-nlp/compare-ja-tokenizer) ⭐ 6 \| 🐛 0 \| 🌐 Python \| 📅 2023-06-16                                  | -              | -               | ⭐ 6              | 🔴 june 2023      |
| 🔗 [lm-evaluation-harness-jp-stable](https://github.com/tdc-yamada-ya/lm-evaluation-harness-jp-stable) ⭐ 1 \| 🐛 0 \| 🌐 Python \| 📅 2023-06-20          | -              | -               | ⭐ 1              | 🔴 june 2023      |
| 🔗 [llm-lora-classification](https://github.com/hppRC/llm-lora-classification) ⭐ 98 \| 🐛 1 \| 🌐 Python \| 📅 2023-07-22                                 | -              | -               | ⭐ 98             | 🔴 july 2023      |
| 🔗 [rinna\_gpt-neox\_ggml-lora](https://github.com/yukaryavka/rinna_gpt-neox_ggml-lora) ⚠️ Archived                                                       | -              | -               | ⭐ 19             | 🔴 may 2023       |
| 🔗 [japanese-llm-roleplay-benchmark](https://github.com/oshizo/japanese-llm-roleplay-benchmark) ⭐ 41 \| 🐛 1 \| 🌐 Jupyter Notebook \| 📅 2023-11-03      | -              | -               | ⭐ 41             | 🔴 november 2023  |
| 🔗 [japanese-llm-ranking](https://github.com/yuzu-ai/japanese-llm-ranking) ⭐ 50 \| 🐛 2 \| 🌐 Jupyter Notebook \| 📅 2024-04-10                           | -              | -               | ⭐ 50             | 🔴 march 2024     |
| 🔗 [llm-jp-eval](https://github.com/llm-jp/llm-jp-eval) ⭐ 166 \| 🐛 3 \| 🌐 Python \| 📅 2026-07-31                                                       | -              | -               | ⭐ 166            | 🟢 july           |
| 🔗 [llm-jp-sft](https://github.com/llm-jp/llm-jp-sft) ⭐ 62 \| 🐛 2 \| 🌐 Python \| 📅 2024-06-13                                                          | -              | -               | ⭐ 62             | 🔴 june 2024      |
| 🔗 [llm-jp-tokenizer](https://github.com/llm-jp/llm-jp-tokenizer) ⭐ 49 \| 🐛 2 \| 🌐 Python \| 📅 2026-03-30                                              | -              | -               | ⭐ 48             | 🟡 march          |
| 🔗 [japanese-lm-fin-harness](https://github.com/pfnet-research/japanese-lm-fin-harness) ⭐ 79 \| 🐛 2 \| 🌐 Shell \| 📅 2026-06-17                         | -              | -               | ⭐ 79             | 🟢 june           |
| 🔗 [ja-vicuna-qa-benchmark](https://github.com/ku-nlp/ja-vicuna-qa-benchmark) ⭐ 33 \| 🐛 2 \| 🌐 Python \| 📅 2024-07-31                                  | -              | -               | ⭐ 33             | 🔴 june 2024      |
| 🔗 [swallow-evaluation](https://github.com/swallow-llm/swallow-evaluation) ⭐ 25 \| 🐛 2 \| 🌐 Python \| 📅 2025-09-17                                     | -              | -               | ⭐ 25             | 🟡 september 2025 |
| 🔗 [swallow-evaluation-instruct](https://github.com/swallow-llm/swallow-evaluation-instruct) ⭐ 31 \| 🐛 0 \| 🌐 Python \| 📅 2026-05-08                   | -              | -               | ⭐ 31             | 🟡 may            |
| 🔗 [pretrained\_doc2vec\_ja](https://github.com/yagays/pretrained_doc2vec_ja) ⭐ 25 \| 🐛 1 \| 🌐 Python \| 📅 2019-01-25                                  | -              | -               | ⭐ 25             | 🔴 january 2019   |
| 🔗 [pl-bert-ja](https://github.com/kyamauchi1023/pl-bert-ja) ⭐ 24 \| 🐛 0 \| 🌐 Python \| 📅 2023-12-16                                                   | -              | -               | ⭐ 24             | 🔴 december 2023  |

### Others

General-purpose tools supporting Japanese language processing

* [mozc-devices](https://github.com/google/mozc-devices) ⭐ 2,709 | 🐛 0 | 🌐 C++ | 📅 2025-11-07 - Automatically exported from code.google.com/p/mozc-morse
* [voicevox\_engine](https://github.com/VOICEVOX/voicevox_engine) ⭐ 1,751 | 🐛 89 | 🌐 Python | 📅 2026-08-20 - 無料で使える中品質なテキスト読み上げソフトウェア、VOICEVOXの音声合成エンジン
* [N46Whisper](https://github.com/Ayanaminn/N46Whisper) ⭐ 1,709 | 🐛 44 | 🌐 Jupyter Notebook | 📅 2025-02-23 - Whisper based Japanese subtitle generator
* [Irodori-TTS](https://github.com/Aratako/Irodori-TTS) ⭐ 1,201 | 🐛 16 | 🌐 Python | 📅 2026-08-11 - A Flow Matching-based Text-to-Speech Model with Emoji-driven Style Control
* [OneCompression](https://github.com/FujitsuResearch/OneCompression) ⭐ 416 | 🐛 11 | 🌐 Python | 📅 2026-08-06 -  富士通研究所による LLM 向け後学習量子化 (PTQ) パイプライン。QEP (NeurIPS 2025)、ILP 混合精度、回転前処理、vLLM プラグインを統合。論文: [arXiv:2603.28845](https://arxiv.org/abs/2603.28845)。
* [pdf-translator](https://github.com/discus0434/pdf-translator) ⭐ 342 | 🐛 6 | 🌐 Python | 📅 2024-05-07 - pdf-translator translates English PDF files into Japanese, preserving the original layout.
* [accel-brain-code](https://github.com/accel-brain/accel-brain-code) ⭐ 327 | 🐛 1 | 🌐 Python | 📅 2023-12-26 - The purpose of this repository is to make prototypes as case study in the context of proof of concept(PoC) and research and development(R\&D) that I have written in my website. The main research topics are Auto-Encoders in relation to the representation learning, the statistical machine learning for energy-based models, adversarial generation net…
* [j-moshi](https://github.com/nu-dialogue/j-moshi) ⭐ 318 | 🐛 1 | 🌐 JavaScript | 📅 2025-06-04 - J-Moshi: A Japanese Full-duplex Spoken Dialogue System
* [HotPepperGourmetDialogue](https://github.com/Hironsan/HotPepperGourmetDialogue) ⭐ 276 | 🐛 4 | 🌐 Python | 📅 2017-10-01 - Restaurant Search System through Dialogue in Japanese.
* [tacotron2-japanese](https://github.com/CjangCjengh/tacotron2-japanese) ⭐ 267 | 🐛 9 | 🌐 Jupyter Notebook | 📅 2022-09-04 - Tacotron2 implementation of Japanese
* [akaza](https://github.com/tokuhirom/akaza) ⭐ 259 | 🐛 24 | 🌐 Rust | 📅 2026-06-08 - Yet another Japanese IME for IBus/Linux
* [pyopenjtalk](https://github.com/r9y9/pyopenjtalk) ⭐ 258 | 🐛 30 | 🌐 Cython | 📅 2025-04-08 - Python wrapper for OpenJTalk
* [namedivider-python](https://github.com/rskmoi/namedivider-python) ⭐ 252 | 🐛 1 | 🌐 Python | 📅 2025-11-03 - A tool for dividing the Japanese full name into a family name and a given name.
* [nlplot](https://github.com/takapy0210/nlplot) ⭐ 238 | 🐛 6 | 🌐 Python | 📅 2022-09-21 - Visualization Module for Natural Language Processing
* [easynovelassistant](https://github.com/zuntan03/easynovelassistant) ⭐ 233 | 🐛 14 | 🌐 Python | 📅 2024-07-05 - 軽量で規制も検閲もない日本語ローカル LLM『LightChatAssistant-TypeB』による、簡単なノベル生成アシスタントです。ローカル特権の永続生成 Generate forever で、当たりガチャを積み上げます。読み上げにも対応。
* [posuto](https://github.com/polm/posuto) ⭐ 226 | 🐛 3 | 🌐 Python | 📅 2026-08-01 -  Japanese postal code data.
* [piper-plus](https://github.com/ayutaz/piper-plus) ⭐ 197 | 🐛 12 | 🌐 Python | 📅 2026-08-20 - Enhanced Piper TTS with Japanese support, WebAssembly, multi-GPU training, and quality improvements.
* [JapaneseEmbeddingEval](https://github.com/oshizo/JapaneseEmbeddingEval) ⭐ 184 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-10-09 - JapaneseEmbeddingEval
* [neural\_japanese\_transliterator](https://github.com/Kyubyong/neural_japanese_transliterator) ⭐ 178 | 🐛 2 | 🌐 Python | 📅 2017-09-17 - Can neural networks transliterate Romaji into Japanese correctly?
* [dictation-kit](https://github.com/julius-speech/dictation-kit) ⭐ 166 | 🐛 5 | 🌐 Python | 📅 2019-04-18 - Japanese dictation kit using Julius
* [kwja](https://github.com/ku-nlp/kwja) ⭐ 146 | 🐛 1 | 🌐 Python | 📅 2026-07-31 - A unified language analyzer for Japanese
* [shuwa](https://github.com/google/shuwa) ⚠️ Archived - Extend GNOME On-Screen Keyboard for Input Methods
* [ja-timex](https://github.com/yagays/ja-timex) ⭐ 140 | 🐛 2 | 🌐 Python | 📅 2025-02-27 - 自然言語で書かれた時間情報表現を抽出/規格化するルールベースの解析器
* [JapaneseTokenizers](https://github.com/Kensuke-Mitsuzawa/JapaneseTokenizers) ⭐ 138 | 🐛 8 | 🌐 Python | 📅 2019-03-25 - A set of metrics for feature selection from text data
* [manga109api](https://github.com/manga109/manga109api) ⭐ 130 | 🐛 0 | 🌐 Python | 📅 2022-03-04 - Simple python API to read annotation data of Manga109
* [toiro](https://github.com/taishi-i/toiro) ⭐ 122 | 🐛 1 | 🌐 Python | 📅 2025-11-09 - A comparison tool of Japanese tokenizers
* [kanjikana-model](https://github.com/digital-go-jp/kanjikana-model) ⭐ 119 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2026-04-28 - 氏名漢字カナ突合モデル
* [t5-japanese](https://github.com/sonoisa/t5-japanese) ⭐ 118 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-09-15 - 日本語T5モデル
* [JLM](https://github.com/jiali-ms/JLM) ⭐ 112 | 🐛 0 | 🌐 Python | 📅 2019-06-04 - A fast LSTM Language Model for large vocabulary language like Japanese and Chinese
* [kanjivg-radical](https://github.com/yagays/kanjivg-radical) ⭐ 107 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2018-08-07 - kanjivg-radical
* [moshi-finetune](https://github.com/nu-dialogue/moshi-finetune) ⭐ 105 | 🐛 2 | 🌐 Python | 📅 2026-01-05 - Fine-tuning Moshi/J-Moshi on your own spoken dialogue data
* [jageocoder](https://github.com/t-sagara/jageocoder) ⭐ 103 | 🐛 1 | 🌐 Python | 📅 2026-04-21 - Pure Python Japanese address geocoder
* [novel2hermes\_jp](https://github.com/kgmkm/novel2hermes_jp) ⭐ 97 | 🐛 1 | 🌐 Python | 📅 2026-06-27 - メモリ機能が強力なhermes-agentと、日本語検索に強い外部メモリvecmemoriを活かし、長文に耐える小説を企画/プロッティング/執筆するためのskills.md
* [llm-leaderboard](https://github.com/wandb/llm-leaderboard) ⭐ 94 | 🐛 4 | 🌐 Python | 📅 2026-07-26 - Project of llm evaluation to Japanese tasks
* [cihai](https://github.com/cihai/cihai) ⭐ 93 | 🐛 14 | 🌐 Python | 📅 2026-08-16 - Python library for CJK (Chinese, Japanese, and Korean) language dictionary
* [jmteb](https://github.com/sbintuitions/jmteb) ⭐ 93 | 🐛 8 | 🌐 Python | 📅 2026-07-31 - The evaluation scripts of JMTEB (Japanese Massive Text Embedding Benchmark)
* [vits](https://github.com/zassou65535/vits) ⭐ 93 | 🐛 0 | 🌐 Python | 📅 2023-02-02 - VITSによるテキスト読み上げ器&ボイスチェンジャー
* [ibus-hiragana](https://github.com/esrille/ibus-hiragana) ⭐ 81 | 🐛 4 | 🌐 Python | 📅 2026-03-22 - ひらがなIME for IBus
* [sarashina2.2-tts](https://github.com/sbintuitions/sarashina2.2-tts) ⭐ 81 | 🐛 3 | 🌐 Python | 📅 2026-06-29 - Sarashina2.2-TTS is a Japanese-centric text-to-speech system built on a large language model, developed by SB Intuitions.
* [5ch-analysis](https://github.com/GINK03/5ch-analysis) ⭐ 74 | 🐛 2 | 🌐 Python | 📅 2018-11-11 - 5chの過去ログをスクレイピングして、過去流行った単語(ex, 香具師, orz)などを追跡調査
* [TinySegmenterMaker](https://github.com/shogo82148/TinySegmenterMaker) ⭐ 73 | 🐛 0 | 🌐 Python | 📅 2022-09-30 - TinySegmenter用の学習モデルを自作するためのツール．
* [ASRDeepSpeech](https://github.com/JeanMaximilienCadic/ASRDeepSpeech) ⭐ 69 | 🐛 0 | 🌐 Python | 📅 2026-08-20 - Automatic Speech Recognition with deepspeech2 model in pytorch with support from Zakuro AI.
* [simple-simcse-ja](https://github.com/hpprc/simple-simcse-ja) ⭐ 69 | 🐛 0 | 🌐 Python | 📅 2023-10-31 - Exploring Japanese SimCSE
* [neural\_ime](https://github.com/yohokuno/neural_ime) ⭐ 67 | 🐛 0 | 🌐 Python | 📅 2016-12-27 - Neural IME: Neural Input Method Engine
* [nlp-recipes-ja](https://github.com/upura/nlp-recipes-ja) ⭐ 66 | 🐛 2 | 🌐 Python | 📅 2023-08-24 - Samples codes for natural language processing in Japanese
* [tsukasa-speech](https://github.com/respaired/tsukasa-speech) ⭐ 65 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2025-05-15 - a Frontier Japanese Speech Generation net
* [daaja](https://github.com/kajyuuen/daaja) ⭐ 64 | 🐛 11 | 🌐 Python | 📅 2023-02-16 - This repository has implementations of data augmentation for NLP for Japanese.
* [LLaVA-JP](https://github.com/tosiyuki/LLaVA-JP) ⭐ 64 | 🐛 3 | 🌐 Python | 📅 2024-07-03 - LLaVA-JP is a Japanese VLM trained by LLaVA method
* [fugumt](https://github.com/s-taka/fugumt) ⭐ 63 | 🐛 2 | 🌐 Python | 📅 2021-02-28 - ぷるーふおぶこんせぷと で公開した機械翻訳エンジンを利用する翻訳環境です。 フォームに入力された文字列の翻訳、PDFの翻訳が可能です。
* [pyopenjtalk-plus](https://github.com/tsukumijima/pyopenjtalk-plus) ⭐ 60 | 🐛 0 | 🌐 Python | 📅 2026-08-11 - pyopenjtalk-plus: A Python wrapper for OpenJTalk with additional improvements
* [llm-jp-judge](https://github.com/llm-jp/llm-jp-judge) ⭐ 58 | 🐛 3 | 🌐 Python | 📅 2026-08-19 - 生成自動評価を行うためのPythonツール
* [chikkarpy](https://github.com/WorksApplications/chikkarpy) ⭐ 55 | 🐛 2 | 🌐 Python | 📅 2022-02-07 - Japanese synonym library
* [rime-jaroomaji](https://github.com/lazyfoxchan/rime-jaroomaji) ⭐ 55 | 🐛 2 | 🌐 Python | 📅 2026-08-20 - Japanese rōmaji input schema for Rime IME
* [tinysegmenter](https://github.com/SamuraiT/tinysegmenter) ⭐ 53 | 🐛 2 | 🌐 Python | 📅 2021-04-20 - tokenizer specified for Japanese
* [YouyakuMan](https://github.com/neilctwu/YouyakuMan) ⭐ 52 | 🐛 2 | 🌐 Python | 📅 2020-09-02 - Extractive summarizer using BertSum as summarization model
* [bert-abstractive-text-summarization](https://github.com/iwasakiyuuki/bert-abstractive-text-summarization) ⭐ 49 | 🐛 0 | 🌐 Python | 📅 2023-05-09 - Japanese Sentence Summarization with BERT
* [fasttext-vs-word2vec-on-twitter-data](https://github.com/GINK03/fasttext-vs-word2vec-on-twitter-data) ⭐ 48 | 🐛 15 | 🌐 Python | 📅 2022-11-22 - fasttextとword2vecの比較と、実行スクリプト、学習スクリプトです
* [akari\_chatgpt\_bot](https://github.com/akarigroup/akari_chatgpt_bot) ⭐ 48 | 🐛 0 | 🌐 Python | 📅 2025-10-16 - 音声認識、文章生成、音声合成を使って対話するチャットボットアプリ
* [xvector\_jtubespeech](https://github.com/sarulab-speech/xvector_jtubespeech) ⭐ 47 | 🐛 0 | 🌐 Python | 📅 2023-11-05 - xvector model on jtubespeech
* [Retrieval-based-Voice-Conversion-WebUI-JP-localization](https://github.com/yantaisa11/Retrieval-based-Voice-Conversion-WebUI-JP-localization) ⭐ 47 | 🐛 0 | 🌐 Python | 📅 2023-04-11 - jp-localization
* [jatts](https://github.com/unilight/jatts) ⭐ 44 | 🐛 1 | 🌐 Python | 📅 2026-03-13 - JATTS: Japanese TTS (for research)
* [llm-jp-eval-mm](https://github.com/llm-jp/llm-jp-eval-mm) ⭐ 43 | 🐛 2 | 🌐 Python | 📅 2026-04-20 - This tool automatically evaluates Japanese multi-modal large language models across multiple datasets.
* [vits-japros-webui](https://github.com/litagin02/vits-japros-webui) ⚠️ Archived - 日本語TTS（VITS）の学習と音声合成のGradio WebUI
* [EN-JP-ML-Lexicon](https://github.com/Machine-Learning-Tokyo/EN-JP-ML-Lexicon) ⭐ 41 | 🐛 1 | 📅 2021-03-13 - This is a English-Japanese lexicon for Machine Learning and Deep Learning terminology.
* [make-meidai-dialogue](https://github.com/knok/make-meidai-dialogue) ⭐ 40 | 🐛 0 | 🌐 Python | 📅 2017-09-28 - Get Japanese dialogue corpus
* [pydomino](https://github.com/dwangomediavillage/pydomino) ⭐ 40 | 🐛 0 | 🌐 C++ | 📅 2025-08-19 - 日本語音声に対して音素ラベルをアラインメントするためのツールです
* [mecab-web-api](https://github.com/bungoume/mecab-web-api) ⭐ 40 | 🐛 94 | 🌐 Python | 📅 2026-02-12 - MeCabを利用した日本語形態素解析WebAPI
* [marine](https://github.com/6gsn/marine) ⭐ 38 | 🐛 5 | 🌐 Python | 📅 2022-09-20 - MARINE : Multi-task leaRnIng-based JapaNese accent Estimation
* [ja-tokenizer-docker-py](https://github.com/p-geon/ja-tokenizer-docker-py) ⭐ 36 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2022-05-10 - Mecab + NEologd + Docker + Python3
* [shisa-v2](https://github.com/shisa-ai/shisa-v2) ⭐ 35 | 🐛 0 | 🌐 Python | 📅 2025-12-23 - Japanese / English Bilingual LLM
* [Japanera](https://github.com/nagataaaas/Japanera) ⭐ 35 | 🐛 0 | 🌐 Python | 📅 2025-06-23 - Easy Tools for Japanese Era System
* [python-npylm](https://github.com/musyoku/python-npylm) ⭐ 34 | 🐛 4 | 🌐 C++ | 📅 2023-10-16 - ベイズ階層言語モデルによる教師なし形態素解析
* [furigana4epub](https://github.com/Mumumu4/furigana4epub) ⭐ 33 | 🐛 0 | 🌐 Python | 📅 2021-09-11 - A Python script for adding furigana to Japanese epub books using Mecab and Unidic.
* [whisper-asr-finetune](https://github.com/sarulab-speech/whisper-asr-finetune) ⭐ 32 | 🐛 5 | 🌐 Python | 📅 2022-12-04 - Finetuning Whisper ASR model
* [mozcdic-ut-jawiki](https://github.com/utuhiro78/mozcdic-ut-jawiki) ⭐ 31 | 🐛 0 | 📅 2026-08-09 - Mozc UT Jawiki Dictionary is a dictionary generated from the Japanese Wikipedia for Mozc.
* [text2dataset](https://github.com/llm-jp/text2dataset) ⭐ 31 | 🐛 6 | 🌐 Python | 📅 2025-01-20 - Easily turn large English text datasets into Japanese text datasets using open LLMs.
* [vv\_core\_inference](https://github.com/hiroshiba/vv_core_inference) ⭐ 31 | 🐛 6 | 🌐 Python | 📅 2025-12-03 - VOICEVOXのコア内で用いられているディープラーニングモデルの推論コード
* [Japanese\_nlp\_scripts](https://github.com/olsgaard/Japanese_nlp_scripts) ⭐ 27 | 🐛 0 | 🌐 Python | 📅 2019-06-30 - Small example scripts for working with Japanese texts in Python
* [yomigana-ebook](https://github.com/rabbit19981023/yomigana-ebook) ⭐ 27 | 🐛 0 | 🌐 Python | 📅 2024-02-20 - Make learning Japanese easier by adding readings for every kanji in the eBook
* [manga-translator](https://github.com/georgescutelnicu/manga-translator) ⭐ 27 | 🐛 0 | 🌐 Python | 📅 2026-04-14 - Translate text found within speech bubbles in manga images.
* [Grongish](https://github.com/shogo82148/Grongish) ⭐ 26 | 🐛 4 | 🌐 Python | 📅 2026-03-02 - 日本語とグロンギ語の相互変換スクリプト
* [nksnd](https://github.com/yoriyuki/nksnd) ⭐ 26 | 🐛 0 | 🌐 Python | 📅 2018-05-16 - New kana-kanji conversion engine
* [kudasai](https://github.com/bikatr7/kudasai) ⭐ 26 | 🐛 2 | 🌐 Python | 📅 2025-06-24 - Streamlining Japanese-English Translation with Advanced Preprocessing and Integrated Translation Technologies
* [easyllasa](https://github.com/zuntan03/easyllasa) ⭐ 26 | 🐛 0 | 🌐 Python | 📅 2025-09-29 - EasyLlasa は 5～15秒の日本語音声と日本語テキストから日本語音声を生成する TSTS (TextSpeechToSpeech) です。
* [ja-law-parser](https://github.com/takuyaa/ja-law-parser) ⭐ 25 | 🐛 2 | 🌐 Python | 📅 2024-01-25 - A Japanese law parser
* [llm-jp-moshi](https://github.com/llm-jp/llm-jp-moshi) ⭐ 24 | 🐛 0 | 🌐 HTML | 📅 2026-03-17 - LLM-jp-Moshi: Japanese Full-duplex Spoken Dialogue Models
* [python\_asa](https://github.com/Takeuchi-Lab-LM/python_asa) ⭐ 22 | 🐛 3 | 🌐 Python | 📅 2022-11-11 - python版日本語意味役割付与システム（ASA）
* [kyujipy](https://github.com/drturnon/kyujipy) ⭐ 22 | 🐛 1 | 🌐 Python | 📅 2026-02-11 - A Python library to convert Japanese texts from Shinjitai (新字体) to Kyujitai (舊字體) and vice versa
* [rake-ja](https://github.com/kanjirz50/rake-ja) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2018-10-11 - Rapid Automatic Keyword Extraction algorithm for Japanese
* [japanese-numbers-python](https://github.com/takumakanari/japanese-numbers-python) ⭐ 21 | 🐛 2 | 🌐 Python | 📅 2020-04-04 - A parser for Japanese number (Kanji, arabic) in the natural language.
* [llm-translator](https://github.com/hpprc/llm-translator) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2025-01-06 - Mixtral-based Ja-En (En-Ja) Translation model
* [mecab\_controller](https://github.com/ajatt-tools/mecab_controller) ⭐ 21 | 🐛 1 | 🌐 Python | 📅 2026-06-29 - Mecab wrapper to generate furigana readings.
* [darts-clone-python](https://github.com/rixwew/darts-clone-python) ⭐ 20 | 🐛 3 | 🌐 Cython | 📅 2022-04-23 - Darts-clone python binding
* [furiganapad](https://github.com/esrille/furiganapad) ⭐ 20 | 🐛 3 | 🌐 Python | 📅 2025-04-14 - ふりがなパッド
* [whisper-transcription](https://github.com/fumifumi0831/whisper-transcription) ⭐ 20 | 🐛 1 | 🌐 Python | 📅 2026-01-02 - Pythonを使用したWhisperモデルによる音声文字起こしツール
* [text-generation](https://github.com/discus0434/text-generation) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2025-08-26 - Easy-to-use scripts to fine-tune GPT-2-JA with your own texts, to generate sentences, and to tweet them automatically.
* [minimal-search-engine](https://github.com/GINK03/minimal-search-engine) ⭐ 19 | 🐛 3 | 🌐 Python | 📅 2023-05-22 - 最小のサーチエンジン/PageRank/tf-idf
* [medical-paper-summarizer-public](https://github.com/yush02084/medical-paper-summarizer-public) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2026-04-18 - 毎日PubMedから最新の循環器内科論文を自動収集・AI要約してGmailに届けるシステム
* [manga-translator](https://github.com/Detopall/manga-translator) ⭐ 19 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-06-18 - A manga translator created using Yolov8, manga\_ocr and deep-translator.
* [MedNER-J](https://github.com/sociocom/MedNER-J) ⭐ 18 | 🐛 2 | 🌐 Python | 📅 2022-05-17 - Latest version of MedEX/J (Japanese disease name extractor)
* [termextract](https://github.com/kanjirz50/termextract) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2018-09-26 - - 専門用語抽出アルゴリズムの実装の練習
* [jglue-evaluation-scripts](https://github.com/nobu-g/jglue-evaluation-scripts) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2026-08-05 - Training and evaluation scripts for JGLUE, a Japanese language understanding benchmark
* [chainer\_nic](https://github.com/yuyay/chainer_nic) ⭐ 17 | 🐛 1 | 🌐 Python | 📅 2018-12-14 - Neural Image Caption (NIC) on chainer, its pretrained models on English and Japanese image caption datasets.
* [japanese\_llm\_simple\_webui](https://github.com/noir55/japanese_llm_simple_webui) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2024-05-12 - Rinna-3.6B、OpenCALM等の日本語対応LLM(大規模言語モデル)用の簡易Webインタフェースです
* [gpt4-autoeval](https://github.com/northern-system-service/gpt4-autoeval) ⭐ 17 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-06-06 - GPT-4 を用いて、言語モデルの応答を自動評価するスクリプト
* [AIO2\_DPR\_baseline](https://github.com/cl-tohoku/AIO2_DPR_baseline) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2022-08-04 - <https://www.nlp.ecei.tohoku.ac.jp/projects/aio/>
* [unsupervised-pos-tagging](https://github.com/musyoku/unsupervised-pos-tagging) ⭐ 16 | 🐛 3 | 🌐 C++ | 📅 2018-03-22 - 教師なし品詞タグ推定
* [japanese\_spelling\_correction](https://github.com/phkhanhtrinh23/japanese_spelling_correction) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2023-09-19 - Japanese Spelling Correction
* [negima](https://github.com/cocodrips/negima) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2018-08-20 - Negima is a Python package to extract phrases in Japanese text by using the part-of-speeches based rules you defined.
* [bertjsc](https://github.com/er-ri/bertjsc) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2024-08-03 - Japanese Spelling Error Corrector using BERT(Masked-Language Model). BERTに基づいて日本語校正
* [BLIP2-Japanese](https://github.com/ZhaoPeiduo/BLIP2-Japanese) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2025-09-12 - Modifying LAVIS' BLIP2 Q-former with models pretrained on Japanese datasets.
* [pl-bert-vits2](https://github.com/tonnetonne814/pl-bert-vits2) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2023-12-17 - VITS2 using Phoneme-Level Japanese BERT
* [ndc\_predictor](https://github.com/ndl-lab/ndc_predictor) ⭐ 14 | 🐛 0 | 📅 2021-08-04 - NDCPredictorの機械学習モデル（書誌情報から日本十進分類を推測するfastTextの学習済みモデル）
* [NTM](https://github.com/m3yrin/NTM) ⭐ 13 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2019-07-24 - Testing of Neural Topic Modeling for Japanese articles
* [PyKatsuyou](https://github.com/SmashinFries/PyKatsuyou) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2025-03-10 - Japanese verb/adjective inflections tool
* [ClipCap-for-Japanese](https://github.com/Japanese-Image-Captioning/ClipCap-for-Japanese) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2022-10-04 - \[PyTorch] ClipCap for Japanese
* [clip-japanese](https://github.com/sonoisa/clip-japanese) ⭐ 13 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-09-15 - 日本語データセットでのqlora instruction tuning学習サンプルコード
* [jtransbench](https://github.com/webbigdata-jp/jtransbench) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2025-10-11 - A tool to easily benchmark Japanese translation skills
* [deep-openreview-research-ja](https://github.com/tb-yasu/deep-openreview-research-ja) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2025-11-29 - OpenReview論文を自動で発見・分析する日本語対応AIエージェント
* [jel](https://github.com/izuna385/jel) ⭐ 12 | 🐛 3 | 🌐 Python | 📅 2021-07-25 - Japanese Entity Linker.
* [wikipedia-passages-jawiki-embeddings-utils](https://github.com/hotchpotch/wikipedia-passages-jawiki-embeddings-utils) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2024-03-28 - wikipedia 日本語の文を、各種日本語の embeddings や faiss index へと変換するスクリプト等。
* [deep-question-generation](https://github.com/sonoisa/deep-question-generation) ⭐ 12 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2023-03-12 - 深層学習を用いたクイズ自動生成（日本語T5モデル）
* [asa-python](https://github.com/ikegami-yukino/asa-python) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2019-02-16 - A curated list of resources dedicated to Python libraries of NLP for Japanese
* [python-npycrf](https://github.com/musyoku/python-npycrf) ⭐ 11 | 🐛 0 | 🌐 C++ | 📅 2018-03-22 - 条件付確率場とベイズ階層言語モデルの統合による半教師あり形態素解析
* [aozora\_classification](https://github.com/shibuiwilliam/aozora_classification) ⭐ 11 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2017-09-03 - This project aims to classify Japanese sentence to how well similar to some Japanese classical writers, such as Soseki Natsume, Ogai Mori, Ryunosuke Akutagawa and so on.
* [snark](https://github.com/hiraokusky/snark) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2020-03-11 - 日本語ワードネットを利用したDBアクセスライブラリ
* [kyoto-reader](https://github.com/ku-nlp/kyoto-reader) ⚠️ Archived - A processor for KyotoCorpus, KWDLC, and AnnotatedFKCCorpus
* [zunda-python](https://github.com/ikegami-yukino/zunda-python) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2019-11-30 - Zunda: Japanese Enhanced Modality Analyzer client for Python.
* [japanese\_summarizer](https://github.com/ryuryukke/japanese_summarizer) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2022-08-01 - A summarizer for Japanese articles.
* [WordCloud-Japanese](https://github.com/aocattleya/WordCloud-Japanese) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2020-01-01 - WordCloudでの日本語文章をMecab（形態素解析エンジン）を使用せずに形態素解析チックな表示を実現するスクリプト
* [radicalchar](https://github.com/yamamaya/radicalchar) ⭐ 10 | 🐛 0 | 🌐 C# | 📅 2022-12-29 - 部首文字正規化ライブラリ
* [RAG-Japanese](https://github.com/AkimParis/RAG-Japanese) ⭐ 10 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2025-05-12 - Open source RAG with Llama Index for Japanese LLM in low resource settting
* [rag-japanese](https://github.com/akimfromparis/rag-japanese) ⭐ 10 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2025-05-12 - Open source RAG with Llama Index for Japanese LLM in low resource settting
* [pocket-researcher](https://github.com/u-masao/pocket-researcher) ⭐ 10 | 🐛 4 | 🌐 Python | 📅 2025-04-07 - LLMを活用した自律調査エージェント。手軽に情報収集、概要把握。
* [llm-jp-vila](https://github.com/llm-jp/llm-jp-vila) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2025-08-26 - This repository contains the code for training llm-jp/llm-jp-3-vila-14b, modified from VILA repository.
* [igakuqa119](https://github.com/docto-rin/igakuqa119) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2026-06-10 - Evaluating LLMs on the 119th Japanese Medical Licensing Examination
* [DNorm-J](https://github.com/sociocom/DNorm-J) ⭐ 9 | 🐛 1 | 🌐 Python | 📅 2022-06-30 - Japanese version of DNorm
* [pyknp-eventgraph](https://github.com/ku-nlp/pyknp-eventgraph) ⭐ 9 | 🐛 2 | 🌐 Python | 📅 2022-12-08 - EventGraph is a development platform for high-level NLP applications in Japanese.
* [JaMIE](https://github.com/racerandom/JaMIE) ⭐ 9 | 🐛 1 | 🌐 Python | 📅 2026-03-08 - A Japanese Medical Information Extraction Toolkit
* [JaSPICE](https://github.com/keio-smilab23/JaSPICE) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2026-06-12 - JaSPICE: Automatic Evaluation Metric Using Predicate-Argument Structures for Image Captioning Models
* [llm-jp-asr](https://github.com/tosiyuki/llm-jp-asr) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2024-09-07 - Whisperのデコーダをllm-jp-1.3b-v1.0に置き換えた音声認識モデルを学習させるためのコード
* [pfmt-bench-fin-ja](https://github.com/pfnet-research/pfmt-bench-fin-ja) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2025-03-19 - pfmt-bench-fin-ja: Preferred Multi-turn Benchmark for Finance in Japanese
* [marine-plus](https://github.com/tsukumijima/marine-plus) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2026-03-22 - MARINE : Multi-task leaRnIng-based JapaNese accent Estimation (Also supported Windows)
* [moine](https://github.com/tagucci/moine) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2026-08-03 - Romanization-aware string comparison for Japanese and Mandarin Chinese.
* [kantan](https://github.com/itayperl/kantan) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2024-10-08 - Lookup japanese words by radical patterns
* [aozora-corpus-generator](https://github.com/borh/aozora-corpus-generator) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2025-06-12 - Generates plain or tokenized text files from the Aozora Bunko
* [magpie-nemotron](https://github.com/aratako/magpie-nemotron) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2024-07-05 - Magpieという手法とNemotron-4-340B-Instructを用いて合成対話データセットを作るコード
* [chirptext](https://github.com/letuananh/chirptext) ⭐ 7 | 🐛 6 | 🌐 Python | 📅 2022-11-09 - ChirpText is a collection of text processing tools for Python.
* [AugLy-jp](https://github.com/chck/AugLy-jp) ⭐ 7 | 🐛 4 | 🌐 Python | 📅 2021-09-30 - Data Augmentation for Japanese Text on AugLy
* [julius4seg](https://github.com/Hiroshiba/julius4seg) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2021-08-22 - Juliusを使ったセグメンテーション支援ツール
* [monaka](https://github.com/komiya-lab/monaka) ⭐ 7 | 🐛 1 | 🌐 Python | 📅 2026-02-23 - A Japanese Parser (including historical Japanese)
* [ja-tokenizer-benchmark](https://github.com/polm/ja-tokenizer-benchmark) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2022-02-24 - Compare the speed of various Japanese tokenizers in Python.
* [yat](https://github.com/yagays/yat) ⭐ 7 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2018-06-19 - yat: Yet Another Tokenizer for Japanese NLP
* [jp-llm-corpus-pii-filter](https://github.com/matsuolab/jp-llm-corpus-pii-filter) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2025-03-25 - 本コードは，大規模言語モデル（LLM）の学習用コーパスから，個人情報の中でも特に配慮が求められる「要配慮個人情報」をフィルタリングするためのものです.
* [showcase](https://github.com/cl-tohoku/showcase) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2018-06-26 - A PyTorch implementation of the Japanese Predicate-Argument Structure (PAS) analyser presented in the paper of Matsubayashi & Inui (2018) with some improvements.
* [desuwa](https://github.com/megagonlabs/desuwa) ⚠️ Archived - Feature annotator to morphemes and phrases based on KNP rule files (pure-Python)
* [jawiki-cleaner](https://github.com/hppRC/jawiki-cleaner) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2021-06-06 - Japanese Wikipedia Cleaner
* [mixture-of-unigram-model](https://github.com/KentoW/mixture-of-unigram-model) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2017-06-16 - Mixture of Unigram Model and Infinite Mixture of Unigram Model in Python. (混合ユニグラムモデルと無限混合ユニグラムモデル)
* [mlm-scoring-transformers](https://github.com/Ryutaro-A/mlm-scoring-transformers) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2023-07-09 - Reproduced package based on Masked Language Model Scoring (ACL2020).
* [japanese-nli-model](https://github.com/CyberAgentAILab/japanese-nli-model) ⚠️ Archived - This repository provides the code for Japanese NLI model, a fine-tuned masked language model.
* [heron-vlm-leaderboard](https://github.com/wandb/heron-vlm-leaderboard) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2024-12-25 - This project is a benchmarking tool for evaluating and comparing the performance of various Vision Language Models (VLMs). It uses two datasets: LLaVA-Bench-In-the-Wild and Japanese HERON Bench to measure model performance.
* [fastrtc-jp](https://github.com/route250/fastrtc-jp) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2025-06-10 - fastrtc用の日本語TTSとSTT追加キット
* [py-kaomoji](https://github.com/shibuiwilliam/py-kaomoji) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2018-12-09 - python kaomoji
* [japanese-luw-tokenizer](https://github.com/koichiyasuoka/japanese-luw-tokenizer) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2021-12-21 - Japanese Long-Unit-Word Tokenizer with RemBertTokenizerFast of Transformers
* [himotoki](https://github.com/msr2903/himotoki) ⭐ 6 | 🐛 2 | 🌐 HTML | 📅 2026-07-12 - A Python-based Japanese Tokenizer, Dictionary, Morphological Analyzer and Romanization Tool. Based on JMDict for Language Learning.
* [jp-tl-bench](https://github.com/shisa-ai/jp-tl-bench) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-04-23 - Anchored Pairwise LLM Evaluation for Bidirectional Japanese-English Translation
* [hidden-markov-model](https://github.com/KentoW/hidden-markov-model) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2017-06-16 - Hidden Markov Model (HMM) and Infinite Hidden Markov Model (iHMM) in Python. (隠れマルコフモデルと無限隠れマルコフモデル)
* [Ngram-language-model](https://github.com/KentoW/Ngram-language-model) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2017-12-05 - Ngram language model in Python. (Nグラム言語モデル)
* [tra-fugu](https://github.com/tos-kamiya/tra-fugu) ⚠️ Archived - A tool for Japanese-English translation and English-Japanese translation by using FuguMT
* [japanese\_llm\_eval](https://github.com/lightblue-tech/japanese_llm_eval) ⭐ 5 | 🐛 1 | 🌐 HTML | 📅 2024-04-22 - A repo for evaluating Japanese LLMs　・　日本語LLMを評価するレポ
* [ja-icd10](https://github.com/yagays/ja-icd10) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2021-07-09 - ICD-10 国際疾病分類の日本語情報を扱うためのPythonパッケージ
* [simple-evals-mm](https://github.com/llm-jp/simple-evals-mm) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-08-20 - A lightweight library for evaluating vision language models on English and Japanese benchmarks.
* [toEmoji](https://github.com/mkan0141/toEmoji) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2018-04-15 - 日本語文を絵文字だけの文に変換するなにか
* [jinf](https://github.com/hkiyomaru/jinf) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2022-12-27 - A Japanese inflection converter
* [substring-word-finder](https://github.com/toufu-24/substring-word-finder) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2025-11-24 - 連続部分文字列の単語判定を行います
* [jitenbot](https://github.com/konstantindjairo/jitenbot) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2024-12-05 - Web crawler for creating personal copies of Japanese dictionaries
* [ibus-jig](https://github.com/y-koj/ibus-jig) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2023-12-10 - ibus-jig: Japanese-language Input-method using GPT-4
* [jp-stopword-filter](https://github.com/BrambleXu/jp-stopword-filter) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-06-20 - A lightweight Python library designed to filter stopwords from Japanese text based on customizable rules.
* [medvoice-jp-asr](https://github.com/nikotora/medvoice-jp-asr) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-06-27 - MedVoice-JP LoRA60: 日本語医療特化ASR (whisper-small + LoRA, 60話者) と国内初の医療ASRベンチマーク (フルFT版 FT60 も収録)
* [jrte-corpus\_example](https://github.com/megagonlabs/jrte-corpus_example) ⚠️ Archived - Example codes for Japanese Realistic Textual Entailment Corpus
* [yubin](https://github.com/alvations/yubin) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2019-10-27 - Japanese Address Munger
* [mbart-finetuning](https://github.com/ken11/mbart-finetuning) ⭐ 3 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2021-10-13 - Code to perform finetuning of the mBART model.
* [tweet\_extructor](https://github.com/tatHi/tweet_extructor) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2022-08-28 - Twitter日本語評判分析データセットのためのツイートダウンローダ
* [jp-translate.cloud](https://github.com/matthewbieda/jp-translate.cloud) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2024-09-05 - A state-of-the-art open-source Japanese <--> English machine translation system based on the latest NMT research.
* [add-dictionary](https://github.com/massao000/add-dictionary) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-10-08 - OpenJTalkのユーザ辞書をGUIで追加するアプリ
* [japanese-wordnet-visualization](https://github.com/HemingwayLee/japanese-wordnet-visualization) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2024-02-07 - This project visualizes the Japanese Wordnet (日本語ワードネット) with web application built by Django
* [yasumail](https://github.com/terallite/yasumail) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-01-24 - Synthetic Japanese business email generator for ML training data
* [eval\_vertical\_ja](https://github.com/llm-jp/eval_vertical_ja) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2026-05-24 - Evaluating Multimodal Large Language Models on Vertically Written Japanese Text
* [ishi](https://github.com/ku-nlp/ishi) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2020-05-15 - Ishi: A volition classifier for Japanese
* [unihan-lm](https://github.com/JetRunner/unihan-lm) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2020-11-06 - The official repository for "UnihanLM: Coarse-to-Fine Chinese-Japanese Language Model Pretraining with the Unihan Database", AACL-IJCNLP 2020
* [japanese-word-aggregation](https://github.com/hkiyomaru/japanese-word-aggregation) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2018-08-19 - Aggregating Japanese words based on Juman++ and ConceptNet5.5
* [SAT-for-Japanese](https://github.com/Japanese-Image-Captioning/SAT-for-Japanese) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2022-10-04 - \[PyTorch] Show, Attend and Tell for Japanese
* [mecab-visualizer](https://github.com/sophiefy/mecab-visualizer) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2023-09-23 - MeCabの形態素解析結果を可視化するツール
* [symptom-expression-search](https://github.com/po3rin/symptom-expression-search) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2021-02-17 - ElasticsearchやGiNZA、患者表現辞書を使った患者表現揺れ吸収する意味構造検索を試した
* [pitchbench](https://github.com/shewiiii/pitchbench) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-02-21 - Experimental Japanese pitch accent based LLM Benchmark
* [mini-transformer-from-scratch](https://github.com/zuofanf/mini-transformer-from-scratch) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-11-30 - English to Japanese Transformer from scratch
* [japanese2phoneme](https://github.com/iory/japanese2phoneme) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2022-02-24 - A python library to convert Japanese to phoneme.
* [anlp\_nlp2021\_d3-1](https://github.com/arusl/anlp_nlp2021_d3-1) ⭐ 1 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2022-03-08 - This repository contains codes related to the experiments in "An Experimental Evaluation of Japanese Tokenizers for Sentiment-Based Text Classification"
* [JDT-with-KenLM-scoring](https://github.com/TUT-SLP-lab/JDT-with-KenLM-scoring) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2022-07-01 - Japanese-Dialog-Transformerの応答候補に対して、KenLMによるN-gram言語モデルでスコアリングし、フィルタリング若しくはリランキングを行う。
* [japanese\_qa\_demo\_with\_haystack\_and\_es](https://github.com/Shingo-Kamata/japanese_qa_demo_with_haystack_and_es) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2022-12-18 - Haystack + Elasticsearch + wikipedia(ja) を用いた、日本語の質問応答システムのサンプル
* [qlora\_ja](https://github.com/sosuke115/qlora_ja) ⭐ 1 | 🐛 1 | 🌐 Python | 📅 2024-07-13 - 日本語データセットでのqlora instruction tuning学習サンプルコード
* [asagi-vlm-colaboratory-sample](https://github.com/kazuhito00/asagi-vlm-colaboratory-sample) ⭐ 1 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-03-01 - Colaboratory上でAsagi(合成データセットを活用した大規模日本語VLM)をお試しするサンプル
* [open-zeimu-mcp](https://github.com/zeimu-ai/open-zeimu-mcp) ⭐ 1 | 🐛 6 | 🌐 TypeScript | 📅 2026-06-22 - OSS MCP server for Japanese tax primary sources (法令・通達・タックスアンサー・質疑応答事例・文書回答事例・裁決事例)
* [diafill-toolkit](https://github.com/sbintuitions/diafill-toolkit) ⭐ 0 | 🐛 2 | 🌐 Python | 📅 2026-01-27 - A toolkit for synthesizing filler-rich, short-utterance Japanese dialogue scripts for speech-based interaction using Large Language Models (LLMs) This project is designed to generate data in two phases: Seed Generation (metadata creation) and Dialogue Generation (script creation).
* [Novel2DialCorpus](https://github.com/ganbon/Novel2DialCorpus) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-02-10 - 小説テキストから雑談対話コーパスを構築する手法
* [shirabe-address-api](https://github.com/techwell-inc-jp/shirabe-address-api) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-17 - Shirabe Address API — Japanese address normalization for AI agents (Cloudflare Workers + Fly.io NRT, abr-geocoder backed)
* [shirabe-sdk-python](https://github.com/techwell-inc-jp/shirabe-sdk-python) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-07-17 - Official Python SDK for the Shirabe Japan data APIs — ready-made LangChain / OpenAI Agents SDK tools for Japanese name reading (JMnedict-backed candidates), name splitting, address normalization, corporate number lookup, and calendar (rokuyo). Zero-dependency core.
* [fuseji](https://github.com/sserada/fuseji) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2026-07-19 - 日本語特化のPII検出・マスキングミドルウェア（LLMオブザーバビリティ向け）
* [japanese\_chatbot](https://github.com/CjangCjengh/japanese_chatbot) - A PyTorch Implementation of japanese chatbot using BERT and Transformer's decoder
* [natsume](https://github.com/faruzan0820/natsume) - A Japanese text frontend processing toolkit
* [wikipedia-japanese-open-rag](https://github.com/lawofcycles/wikipedia-japanese-open-rag) - Wikipediaの日本語記事を元に、ユーザの質問に回答するGradioベースのRAGのサンプル

| Name                                                                                                                                                                                         | downloads/week | total downloads | stars            | last commit       |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------- | --------------- | ---------------- | ----------------- |
| 🔗 [namedivider-python](https://github.com/rskmoi/namedivider-python) ⭐ 252 \| 🐛 1 \| 🌐 Python \| 📅 2025-11-03                                                                            | 📥 903         | 📦 101k         | ⭐ 252            | 🟡 november 2025  |
| 🔗 [asa-python](https://github.com/ikegami-yukino/asa-python) ⭐ 11 \| 🐛 0 \| 🌐 Python \| 📅 2019-02-16                                                                                     | 📥 24          | 📦 32k          | ⭐ 11             | 🔴 february 2019  |
| 🔗 [python\_asa](https://github.com/Takeuchi-Lab-LM/python_asa) ⭐ 22 \| 🐛 3 \| 🌐 Python \| 📅 2022-11-11                                                                                   | -              | -               | ⭐ 22             | 🔴 january 2020   |
| 🔗 [toiro](https://github.com/taishi-i/toiro) ⭐ 122 \| 🐛 1 \| 🌐 Python \| 📅 2025-11-09                                                                                                    | 📥 61          | 📦 28k          | ⭐ 122            | 🟡 november 2025  |
| 🔗 [ja-timex](https://github.com/yagays/ja-timex) ⭐ 140 \| 🐛 2 \| 🌐 Python \| 📅 2025-02-27                                                                                                | 📥 3k          | 📦 125k         | ⭐ 140            | 🔴 november 2023  |
| 🔗 [JapaneseTokenizers](https://github.com/Kensuke-Mitsuzawa/JapaneseTokenizers) ⭐ 138 \| 🐛 8 \| 🌐 Python \| 📅 2019-03-25                                                                 | -              | -               | ⭐ 138            | 🔴 march 2019     |
| 🔗 [daaja](https://github.com/kajyuuen/daaja) ⭐ 64 \| 🐛 11 \| 🌐 Python \| 📅 2023-02-16                                                                                                    | 📥 43          | 📦 27k          | ⭐ 64             | 🔴 february 2023  |
| 🔗 [accel-brain-code](https://github.com/accel-brain/accel-brain-code) ⭐ 327 \| 🐛 1 \| 🌐 Python \| 📅 2023-12-26                                                                           | 📥 198         | 📦 155k         | ⭐ 327            | 🔴 december 2023  |
| 🔗 [kyoto-reader](https://github.com/ku-nlp/kyoto-reader) ⚠️ Archived                                                                                                                        | 📥 833         | 📦 60k          | ⭐ 10             | 🔴 june 2024      |
| 🔗 [nlplot](https://github.com/takapy0210/nlplot) ⭐ 238 \| 🐛 6 \| 🌐 Python \| 📅 2022-09-21                                                                                                | 📥 87          | 📦 117k         | ⭐ 238            | 🔴 september 2022 |
| 🔗 [rake-ja](https://github.com/kanjirz50/rake-ja) ⭐ 21 \| 🐛 0 \| 🌐 Python \| 📅 2018-10-11                                                                                                | -              | -               | ⭐ 21             | 🔴 october 2018   |
| 🔗 [jel](https://github.com/izuna385/jel) ⭐ 12 \| 🐛 3 \| 🌐 Python \| 📅 2021-07-25                                                                                                         | 📥 13          | 📦 8k           | ⭐ 12             | 🔴 july 2021      |
| 🔗 [MedNER-J](https://github.com/sociocom/MedNER-J) ⭐ 18 \| 🐛 2 \| 🌐 Python \| 📅 2022-05-17                                                                                               | -              | -               | ⭐ 18             | 🔴 may 2022       |
| 🔗 [zunda-python](https://github.com/ikegami-yukino/zunda-python) ⭐ 10 \| 🐛 1 \| 🌐 Python \| 📅 2019-11-30                                                                                 | 📥 6           | 📦 6k           | ⭐ 10             | 🔴 november 2019  |
| 🔗 [AIO2\_DPR\_baseline](https://github.com/cl-tohoku/AIO2_DPR_baseline) ⭐ 16 \| 🐛 1 \| 🌐 Python \| 📅 2022-08-04                                                                          | -              | -               | ⭐ 16             | 🔴 january 2022   |
| 🔗 [showcase](https://github.com/cl-tohoku/showcase) ⭐ 6 \| 🐛 0 \| 🌐 Python \| 📅 2018-06-26                                                                                               | 📥 3           | 📦 8k           | ⭐ 6              | 🔴 june 2018      |
| 🔗 [darts-clone-python](https://github.com/rixwew/darts-clone-python) ⭐ 20 \| 🐛 3 \| 🌐 Cython \| 📅 2022-04-23                                                                             | 📥 3k          | 📦 9M           | ⭐ 20             | 🔴 april 2022     |
| 🔗 [jrte-corpus\_example](https://github.com/megagonlabs/jrte-corpus_example) ⚠️ Archived                                                                                                    | -              | -               | ⭐ 3              | 🔴 november 2021  |
| 🔗 [desuwa](https://github.com/megagonlabs/desuwa) ⚠️ Archived                                                                                                                               | 📥 17          | 📦 11k          | ⭐ 6              | 🔴 may 2022       |
| 🔗 [HotPepperGourmetDialogue](https://github.com/Hironsan/HotPepperGourmetDialogue) ⭐ 276 \| 🐛 4 \| 🌐 Python \| 📅 2017-10-01                                                              | -              | -               | ⭐ 276            | 🔴 may 2016       |
| 🔗 [nlp-recipes-ja](https://github.com/upura/nlp-recipes-ja) ⭐ 66 \| 🐛 2 \| 🌐 Python \| 📅 2023-08-24                                                                                      | -              | -               | ⭐ 66             | 🔴 april 2021     |
| 🔗 [Japanese\_nlp\_scripts](https://github.com/olsgaard/Japanese_nlp_scripts) ⭐ 27 \| 🐛 0 \| 🌐 Python \| 📅 2019-06-30                                                                     | -              | -               | ⭐ 27             | 🔴 june 2019      |
| 🔗 [DNorm-J](https://github.com/sociocom/DNorm-J) ⭐ 9 \| 🐛 1 \| 🌐 Python \| 📅 2022-06-30                                                                                                  | -              | -               | ⭐ 9              | 🔴 june 2022      |
| 🔗 [pyknp-eventgraph](https://github.com/ku-nlp/pyknp-eventgraph) ⭐ 9 \| 🐛 2 \| 🌐 Python \| 📅 2022-12-08                                                                                  | 📥 19          | 📦 68k          | ⭐ 9              | 🔴 september 2022 |
| 🔗 [ishi](https://github.com/ku-nlp/ishi) ⭐ 2 \| 🐛 0 \| 🌐 Python \| 📅 2020-05-15                                                                                                          | 📥 3           | 📦 7k           | ⭐ 2              | 🔴 may 2020       |
| 🔗 [python-npylm](https://github.com/musyoku/python-npylm) ⭐ 34 \| 🐛 4 \| 🌐 C++ \| 📅 2023-10-16                                                                                           | -              | -               | ⭐ 34             | 🔴 january 2019   |
| 🔗 [python-npycrf](https://github.com/musyoku/python-npycrf) ⭐ 11 \| 🐛 0 \| 🌐 C++ \| 📅 2018-03-22                                                                                         | -              | -               | ⭐ 11             | 🔴 march 2018     |
| 🔗 [unsupervised-pos-tagging](https://github.com/musyoku/unsupervised-pos-tagging) ⭐ 16 \| 🐛 3 \| 🌐 C++ \| 📅 2018-03-22                                                                   | -              | -               | ⭐ 16             | 🔴 october 2017   |
| 🔗 [negima](https://github.com/cocodrips/negima) ⭐ 14 \| 🐛 0 \| 🌐 Python \| 📅 2018-08-20                                                                                                  | 📥 23          | 📦 17k          | ⭐ 14             | 🔴 august 2018    |
| 🔗 [YouyakuMan](https://github.com/neilctwu/YouyakuMan) ⭐ 52 \| 🐛 2 \| 🌐 Python \| 📅 2020-09-02                                                                                           | -              | -               | ⭐ 52             | 🔴 september 2020 |
| 🔗 [japanese-numbers-python](https://github.com/takumakanari/japanese-numbers-python) ⭐ 21 \| 🐛 2 \| 🌐 Python \| 📅 2020-04-04                                                             | 📥 370         | 📦 2M           | ⭐ 21             | 🔴 april 2020     |
| 🔗 [kantan](https://github.com/itayperl/kantan) ⭐ 8 \| 🐛 0 \| 🌐 Python \| 📅 2024-10-08                                                                                                    | -              | -               | ⭐ 8              | 🔴 october 2024   |
| 🔗 [make-meidai-dialogue](https://github.com/knok/make-meidai-dialogue) ⭐ 40 \| 🐛 0 \| 🌐 Python \| 📅 2017-09-28                                                                           | -              | -               | ⭐ 40             | 🔴 september 2017 |
| 🔗 [japanese\_summarizer](https://github.com/ryuryukke/japanese_summarizer) ⭐ 10 \| 🐛 0 \| 🌐 Python \| 📅 2022-08-01                                                                       | -              | -               | ⭐ 10             | 🔴 august 2022    |
| 🔗 [chirptext](https://github.com/letuananh/chirptext) ⭐ 7 \| 🐛 6 \| 🌐 Python \| 📅 2022-11-09                                                                                             | 📥 7k          | 📦 337k         | ⭐ 7              | 🔴 october 2022   |
| 🔗 [yubin](https://github.com/alvations/yubin) ⭐ 3 \| 🐛 0 \| 🌐 Python \| 📅 2019-10-27                                                                                                     | 📥 6           | 📦 3k           | ⭐ 3              | 🔴 october 2019   |
| 🔗 [jawiki-cleaner](https://github.com/hppRC/jawiki-cleaner) ⭐ 6 \| 🐛 1 \| 🌐 Python \| 📅 2021-06-06                                                                                       | 📥 33          | 📦 26k          | ⭐ 6              | 🔴 february 2021  |
| 🔗 [japanese2phoneme](https://github.com/iory/japanese2phoneme) ⭐ 1 \| 🐛 0 \| 🌐 Python \| 📅 2022-02-24                                                                                    | 📥 9           | 📦 4k           | ⭐ 1              | 🔴 february 2022  |
| 🔗 [anlp\_nlp2021\_d3-1](https://github.com/arusl/anlp_nlp2021_d3-1) ⭐ 1 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2022-03-08                                                                     | -              | -               | ⭐ 1              | 🔴 march 2022     |
| 🔗 [aozora\_classification](https://github.com/shibuiwilliam/aozora_classification) ⭐ 11 \| 🐛 1 \| 🌐 Jupyter Notebook \| 📅 2017-09-03                                                     | -              | -               | ⭐ 11             | 🔴 september 2017 |
| 🔗 [aozora-corpus-generator](https://github.com/borh/aozora-corpus-generator) ⭐ 8 \| 🐛 0 \| 🌐 Python \| 📅 2025-06-12                                                                      | -              | -               | ⭐ 8              | 🔴 june 2025      |
| 🔗 [JLM](https://github.com/jiali-ms/JLM) ⭐ 112 \| 🐛 0 \| 🌐 Python \| 📅 2019-06-04                                                                                                        | -              | -               | ⭐ 112            | 🔴 june 2019      |
| 🔗 [NTM](https://github.com/m3yrin/NTM) ⭐ 13 \| 🐛 1 \| 🌐 Jupyter Notebook \| 📅 2019-07-24                                                                                                 | -              | -               | ⭐ 13             | 🔴 july 2019      |
| 🔗 [EN-JP-ML-Lexicon](https://github.com/Machine-Learning-Tokyo/EN-JP-ML-Lexicon) ⭐ 41 \| 🐛 1 \| 📅 2021-03-13                                                                              | -              | -               | ⭐ 41             | 🔴 march 2021     |
| 🔗 [text-generation](https://github.com/discus0434/text-generation) ⭐ 19 \| 🐛 0 \| 🌐 Python \| 📅 2025-08-26                                                                               | -              | -               | ⭐ 19             | 🔴 august 2025    |
| 🔗 [chainer\_nic](https://github.com/yuyay/chainer_nic) ⭐ 17 \| 🐛 1 \| 🌐 Python \| 📅 2018-12-14                                                                                           | -              | -               | ⭐ 17             | 🔴 december 2018  |
| 🔗 [unihan-lm](https://github.com/JetRunner/unihan-lm) ⭐ 2 \| 🐛 0 \| 🌐 Python \| 📅 2020-11-06                                                                                             | -              | -               | ⭐ 2              | 🔴 november 2020  |
| 🔗 [mbart-finetuning](https://github.com/ken11/mbart-finetuning) ⭐ 3 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2021-10-13                                                                         | -              | -               | ⭐ 3              | 🔴 october 2021   |
| 🔗 [xvector\_jtubespeech](https://github.com/sarulab-speech/xvector_jtubespeech) ⭐ 47 \| 🐛 0 \| 🌐 Python \| 📅 2023-11-05                                                                  | -              | -               | ⭐ 47             | 🔴 november 2023  |
| 🔗 [TinySegmenterMaker](https://github.com/shogo82148/TinySegmenterMaker) ⭐ 73 \| 🐛 0 \| 🌐 Python \| 📅 2022-09-30                                                                         | -              | -               | ⭐ 73             | 🔴 september 2022 |
| 🔗 [Grongish](https://github.com/shogo82148/Grongish) ⭐ 26 \| 🐛 4 \| 🌐 Python \| 📅 2026-03-02                                                                                             | -              | -               | ⭐ 26             | 🟡 december 2025  |
| 🔗 [WordCloud-Japanese](https://github.com/aocattleya/WordCloud-Japanese) ⭐ 10 \| 🐛 0 \| 🌐 Python \| 📅 2020-01-01                                                                         | -              | -               | ⭐ 10             | 🔴 january 2020   |
| 🔗 [snark](https://github.com/hiraokusky/snark) ⭐ 11 \| 🐛 0 \| 🌐 Python \| 📅 2020-03-11                                                                                                   | -              | -               | ⭐ 11             | 🔴 march 2020     |
| 🔗 [toEmoji](https://github.com/mkan0141/toEmoji) ⭐ 4 \| 🐛 0 \| 🌐 Python \| 📅 2018-04-15                                                                                                  | -              | -               | ⭐ 4              | 🔴 april 2018     |
| 🔗 [termextract](https://github.com/kanjirz50/termextract) ⭐ 18 \| 🐛 0 \| 🌐 Python \| 📅 2018-09-26                                                                                        | -              | -               | ⭐ 18             | 🔴 september 2018 |
| 🔗 [JDT-with-KenLM-scoring](https://github.com/TUT-SLP-lab/JDT-with-KenLM-scoring) ⭐ 1 \| 🐛 0 \| 🌐 Python \| 📅 2022-07-01                                                                 | -              | -               | ⭐ 1              | 🔴 july 2022      |
| 🔗 [mixture-of-unigram-model](https://github.com/KentoW/mixture-of-unigram-model) ⭐ 6 \| 🐛 1 \| 🌐 Python \| 📅 2017-06-16                                                                  | -              | -               | ⭐ 6              | 🔴 june 2017      |
| 🔗 [hidden-markov-model](https://github.com/KentoW/hidden-markov-model) ⭐ 5 \| 🐛 0 \| 🌐 Python \| 📅 2017-06-16                                                                            | -              | -               | ⭐ 5              | 🔴 june 2017      |
| 🔗 [Ngram-language-model](https://github.com/KentoW/Ngram-language-model) ⭐ 5 \| 🐛 0 \| 🌐 Python \| 📅 2017-12-05                                                                          | -              | -               | ⭐ 5              | 🔴 december 2017  |
| 🔗 [ASRDeepSpeech](https://github.com/JeanMaximilienCadic/ASRDeepSpeech) ⭐ 69 \| 🐛 0 \| 🌐 Python \| 📅 2026-08-20                                                                          | -              | -               | ⭐ 69             | 🟢 july           |
| 🔗 [neural\_ime](https://github.com/yohokuno/neural_ime) ⭐ 67 \| 🐛 0 \| 🌐 Python \| 📅 2016-12-27                                                                                          | -              | -               | ⭐ 67             | 🔴 december 2016  |
| 🔗 [neural\_japanese\_transliterator](https://github.com/Kyubyong/neural_japanese_transliterator) ⭐ 178 \| 🐛 2 \| 🌐 Python \| 📅 2017-09-17                                                | -              | -               | ⭐ 178            | 🔴 september 2017 |
| 🔗 [tinysegmenter](https://github.com/SamuraiT/tinysegmenter) ⭐ 53 \| 🐛 2 \| 🌐 Python \| 📅 2021-04-20                                                                                     | 📥 143k        | 📦 179k         | ⭐ repo not found | 🔴 november 2015  |
| 🔗 [AugLy-jp](https://github.com/chck/AugLy-jp) ⭐ 7 \| 🐛 4 \| 🌐 Python \| 📅 2021-09-30                                                                                                    | 📥 71          | 📦 32k          | ⭐ 7              | 🔴 september 2021 |
| 🔗 [furigana4epub](https://github.com/Mumumu4/furigana4epub) ⭐ 33 \| 🐛 0 \| 🌐 Python \| 📅 2021-09-11                                                                                      | 📥 6           | 📦 13k          | ⭐ 33             | 🔴 september 2021 |
| 🔗 [PyKatsuyou](https://github.com/SmashinFries/PyKatsuyou) ⭐ 13 \| 🐛 0 \| 🌐 Python \| 📅 2025-03-10                                                                                       | 📥 77          | 📦 23k          | ⭐ 13             | 🔴 march 2025     |
| 🔗 [jageocoder](https://github.com/t-sagara/jageocoder) ⭐ 103 \| 🐛 1 \| 🌐 Python \| 📅 2026-04-21                                                                                          | 📥 3k          | 📦 444k         | ⭐ 103            | 🟡 march          |
| 🔗 [nksnd](https://github.com/yoriyuki/nksnd) ⭐ 26 \| 🐛 0 \| 🌐 Python \| 📅 2018-05-16                                                                                                     | -              | -               | ⭐ 26             | 🔴 may 2018       |
| 🔗 [JaMIE](https://github.com/racerandom/JaMIE) ⭐ 9 \| 🐛 1 \| 🌐 Python \| 📅 2026-03-08                                                                                                    | -              | -               | ⭐ 9              | 🟡 march          |
| 🔗 [fasttext-vs-word2vec-on-twitter-data](https://github.com/GINK03/fasttext-vs-word2vec-on-twitter-data) ⭐ 48 \| 🐛 15 \| 🌐 Python \| 📅 2022-11-22                                        | -              | -               | ⭐ 48             | 🔴 august 2017    |
| 🔗 [minimal-search-engine](https://github.com/GINK03/minimal-search-engine) ⭐ 19 \| 🐛 3 \| 🌐 Python \| 📅 2023-05-22                                                                       | -              | -               | ⭐ 19             | 🔴 july 2019      |
| 🔗 [5ch-analysis](https://github.com/GINK03/5ch-analysis) ⭐ 74 \| 🐛 2 \| 🌐 Python \| 📅 2018-11-11                                                                                         | -              | -               | ⭐ 74             | 🔴 november 2018  |
| 🔗 [tweet\_extructor](https://github.com/tatHi/tweet_extructor) ⭐ 3 \| 🐛 0 \| 🌐 Python \| 📅 2022-08-28                                                                                    | -              | -               | ⭐ 3              | 🔴 august 2022    |
| 🔗 [japanese-word-aggregation](https://github.com/hkiyomaru/japanese-word-aggregation) ⭐ 2 \| 🐛 0 \| 🌐 Python \| 📅 2018-08-19                                                             | -              | -               | ⭐ 2              | 🔴 august 2018    |
| 🔗 [jinf](https://github.com/hkiyomaru/jinf) ⭐ 4 \| 🐛 1 \| 🌐 Python \| 📅 2022-12-27                                                                                                       | 📥 103         | 📦 65k          | ⭐ 4              | 🔴 december 2022  |
| 🔗 [kwja](https://github.com/ku-nlp/kwja) ⭐ 146 \| 🐛 1 \| 🌐 Python \| 📅 2026-07-31                                                                                                        | 📥 249         | 📦 63k          | ⭐ 146            | 🔴 august 2025    |
| 🔗 [mlm-scoring-transformers](https://github.com/Ryutaro-A/mlm-scoring-transformers) ⭐ 6 \| 🐛 1 \| 🌐 Python \| 📅 2023-07-09                                                               | -              | -               | ⭐ 6              | 🔴 december 2022  |
| 🔗 [ClipCap-for-Japanese](https://github.com/Japanese-Image-Captioning/ClipCap-for-Japanese) ⭐ 13 \| 🐛 1 \| 🌐 Python \| 📅 2022-10-04                                                      | -              | -               | ⭐ 13             | 🔴 october 2022   |
| 🔗 [SAT-for-Japanese](https://github.com/Japanese-Image-Captioning/SAT-for-Japanese) ⭐ 2 \| 🐛 0 \| 🌐 Python \| 📅 2022-10-04                                                               | -              | -               | ⭐ 2              | 🔴 october 2022   |
| 🔗 [cihai](https://github.com/cihai/cihai) ⭐ 93 \| 🐛 14 \| 🌐 Python \| 📅 2026-08-16                                                                                                       | 📥 786         | 📦 225k         | ⭐ 93             | 🟢 yesterday      |
| 🔗 [marine](https://github.com/6gsn/marine) ⭐ 38 \| 🐛 5 \| 🌐 Python \| 📅 2022-09-20                                                                                                       | 📥 89          | 📦 17k          | ⭐ 38             | 🔴 september 2022 |
| 🔗 [whisper-asr-finetune](https://github.com/sarulab-speech/whisper-asr-finetune) ⭐ 32 \| 🐛 5 \| 🌐 Python \| 📅 2022-12-04                                                                 | -              | -               | ⭐ 32             | 🔴 december 2022  |
| 🔗 [japanese\_chatbot](https://github.com/CjangCjengh/japanese_chatbot)                                                                                                                      | -              | -               | ⭐ repo not found | 🔴 repo not found |
| 🔗 [radicalchar](https://github.com/yamamaya/radicalchar) ⭐ 10 \| 🐛 0 \| 🌐 C# \| 📅 2022-12-29                                                                                             | -              | -               | ⭐ 10             | 🔴 december 2022  |
| 🔗 [akaza](https://github.com/tokuhirom/akaza) ⭐ 259 \| 🐛 24 \| 🌐 Rust \| 📅 2026-06-08                                                                                                    | -              | -               | ⭐ 259            | 🟢 june           |
| 🔗 [posuto](https://github.com/polm/posuto) ⭐ 226 \| 🐛 3 \| 🌐 Python \| 📅 2026-08-01                                                                                                      | 📥 7k          | 📦 853k         | ⭐ 226            | 🟢 august         |
| 🔗 [tacotron2-japanese](https://github.com/CjangCjengh/tacotron2-japanese) ⭐ 267 \| 🐛 9 \| 🌐 Jupyter Notebook \| 📅 2022-09-04                                                             | -              | -               | ⭐ 267            | 🔴 september 2022 |
| 🔗 [ibus-hiragana](https://github.com/esrille/ibus-hiragana) ⭐ 81 \| 🐛 4 \| 🌐 Python \| 📅 2026-03-22                                                                                      | -              | -               | ⭐ 81             | 🟡 march          |
| 🔗 [furiganapad](https://github.com/esrille/furiganapad) ⭐ 20 \| 🐛 3 \| 🌐 Python \| 📅 2025-04-14                                                                                          | -              | -               | ⭐ 20             | 🔴 april 2025     |
| 🔗 [chikkarpy](https://github.com/WorksApplications/chikkarpy) ⭐ 55 \| 🐛 2 \| 🌐 Python \| 📅 2022-02-07                                                                                    | 📥 241         | 📦 67k          | ⭐ 55             | 🔴 february 2022  |
| 🔗 [ja-tokenizer-docker-py](https://github.com/p-geon/ja-tokenizer-docker-py) ⭐ 36 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2022-05-10                                                           | -              | -               | ⭐ 36             | 🔴 may 2022       |
| 🔗 [JapaneseEmbeddingEval](https://github.com/oshizo/JapaneseEmbeddingEval) ⭐ 184 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2024-10-09                                                            | -              | -               | ⭐ 184            | 🔴 october 2024   |
| 🔗 [shuwa](https://github.com/google/shuwa) ⚠️ Archived                                                                                                                                      | -              | -               | ⭐ 146            | 🔴 december 2022  |
| 🔗 [japanese-nli-model](https://github.com/CyberAgentAILab/japanese-nli-model) ⚠️ Archived                                                                                                   | -              | -               | ⭐ 6              | 🔴 october 2022   |
| 🔗 [tra-fugu](https://github.com/tos-kamiya/tra-fugu) ⚠️ Archived                                                                                                                            | -              | -               | ⭐ 5              | 🔴 march 2023     |
| 🔗 [fugumt](https://github.com/s-taka/fugumt) ⭐ 63 \| 🐛 2 \| 🌐 Python \| 📅 2021-02-28                                                                                                     | -              | -               | ⭐ 63             | 🔴 february 2021  |
| 🔗 [JaSPICE](https://github.com/keio-smilab23/JaSPICE) ⭐ 9 \| 🐛 0 \| 🌐 Python \| 📅 2026-06-12                                                                                             | 📥 3           | 📦 2k           | ⭐ 9              | 🟢 june           |
| 🔗 [Retrieval-based-Voice-Conversion-WebUI-JP-localization](https://github.com/yantaisa11/Retrieval-based-Voice-Conversion-WebUI-JP-localization) ⭐ 47 \| 🐛 0 \| 🌐 Python \| 📅 2023-04-11 | -              | -               | ⭐ 47             | 🔴 april 2023     |
| 🔗 [pyopenjtalk](https://github.com/r9y9/pyopenjtalk) ⭐ 258 \| 🐛 30 \| 🌐 Cython \| 📅 2025-04-08                                                                                           | 📥 18k         | 📦 2M           | ⭐ 257            | 🔴 april 2025     |
| 🔗 [yomigana-ebook](https://github.com/rabbit19981023/yomigana-ebook) ⭐ 27 \| 🐛 0 \| 🌐 Python \| 📅 2024-02-20                                                                             | 📥 32          | 📦 8k           | ⭐ 27             | 🔴 february 2024  |
| 🔗 [N46Whisper](https://github.com/Ayanaminn/N46Whisper) ⭐ 1,709 \| 🐛 44 \| 🌐 Jupyter Notebook \| 📅 2025-02-23                                                                            | -              | -               | ⭐ 1.7k           | 🔴 february 2025  |
| 🔗 [japanese\_llm\_simple\_webui](https://github.com/noir55/japanese_llm_simple_webui) ⭐ 17 \| 🐛 0 \| 🌐 Python \| 📅 2024-05-12                                                            | -              | -               | ⭐ 17             | 🔴 may 2024       |
| 🔗 [pdf-translator](https://github.com/discus0434/pdf-translator) ⭐ 342 \| 🐛 6 \| 🌐 Python \| 📅 2024-05-07                                                                                | -              | -               | ⭐ 342            | 🔴 may 2024       |
| 🔗 [japanese\_qa\_demo\_with\_haystack\_and\_es](https://github.com/Shingo-Kamata/japanese_qa_demo_with_haystack_and_es) ⭐ 1 \| 🐛 0 \| 🌐 Python \| 📅 2022-12-18                           | -              | -               | ⭐ 1              | 🔴 december 2022  |
| 🔗 [mozc-devices](https://github.com/google/mozc-devices) ⭐ 2,709 \| 🐛 0 \| 🌐 C++ \| 📅 2025-11-07                                                                                         | -              | -               | ⭐ 2.7k           | 🟡 november 2025  |
| 🔗 [natsume](https://github.com/faruzan0820/natsume)                                                                                                                                         | 📥 0           | 📦 3k           | ⭐ repo not found | 🔴 repo not found |
| 🔗 [vits-japros-webui](https://github.com/litagin02/vits-japros-webui) ⚠️ Archived                                                                                                           | -              | -               | ⭐ 42             | 🔴 january 2024   |
| 🔗 [ja-law-parser](https://github.com/takuyaa/ja-law-parser) ⭐ 25 \| 🐛 2 \| 🌐 Python \| 📅 2024-01-25                                                                                      | -              | -               | ⭐ 25             | 🔴 january 2024   |
| 🔗 [dictation-kit](https://github.com/julius-speech/dictation-kit) ⭐ 166 \| 🐛 5 \| 🌐 Python \| 📅 2019-04-18                                                                               | -              | -               | ⭐ 166            | 🔴 april 2019     |
| 🔗 [julius4seg](https://github.com/Hiroshiba/julius4seg) ⭐ 7 \| 🐛 0 \| 🌐 Python \| 📅 2021-08-22                                                                                           | -              | -               | ⭐ 7              | 🔴 august 2021    |
| 🔗 [voicevox\_engine](https://github.com/VOICEVOX/voicevox_engine) ⭐ 1,751 \| 🐛 89 \| 🌐 Python \| 📅 2026-08-20                                                                            | -              | -               | ⭐ 1.8k           | 🟢 august         |
| 🔗 [LLaVA-JP](https://github.com/tosiyuki/LLaVA-JP) ⭐ 64 \| 🐛 3 \| 🌐 Python \| 📅 2024-07-03                                                                                               | -              | -               | ⭐ 64             | 🔴 june 2024      |
| 🔗 [RAG-Japanese](https://github.com/AkimParis/RAG-Japanese) ⭐ 10 \| 🐛 1 \| 🌐 Jupyter Notebook \| 📅 2025-05-12                                                                            | -              | -               | ⭐ 10             | 🔴 may 2025       |
| 🔗 [bertjsc](https://github.com/er-ri/bertjsc) ⭐ 14 \| 🐛 1 \| 🌐 Python \| 📅 2024-08-03                                                                                                    | -              | -               | ⭐ 14             | 🔴 august 2024    |
| 🔗 [llm-leaderboard](https://github.com/wandb/llm-leaderboard) ⭐ 94 \| 🐛 4 \| 🌐 Python \| 📅 2026-07-26                                                                                    | -              | -               | ⭐ 94             | 🟡 may            |
| 🔗 [jglue-evaluation-scripts](https://github.com/nobu-g/jglue-evaluation-scripts) ⭐ 18 \| 🐛 0 \| 🌐 Python \| 📅 2026-08-05                                                                 | -              | -               | ⭐ 18             | 🟢 august         |
| 🔗 [BLIP2-Japanese](https://github.com/ZhaoPeiduo/BLIP2-Japanese) ⭐ 14 \| 🐛 0 \| 🌐 Python \| 📅 2025-09-12                                                                                 | -              | -               | ⭐ 14             | 🟡 september 2025 |
| 🔗 [wikipedia-passages-jawiki-embeddings-utils](https://github.com/hotchpotch/wikipedia-passages-jawiki-embeddings-utils) ⭐ 12 \| 🐛 0 \| 🌐 Python \| 📅 2024-03-28                         | -              | -               | ⭐ 12             | 🔴 march 2024     |
| 🔗 [simple-simcse-ja](https://github.com/hpprc/simple-simcse-ja) ⭐ 69 \| 🐛 0 \| 🌐 Python \| 📅 2023-10-31                                                                                  | -              | -               | ⭐ 69             | 🔴 october 2023   |
| 🔗 [wikipedia-japanese-open-rag](https://github.com/lawofcycles/wikipedia-japanese-open-rag)                                                                                                 | -              | -               | ⭐ repo not found | 🔴 repo not found |
| 🔗 [gpt4-autoeval](https://github.com/northern-system-service/gpt4-autoeval) ⭐ 17 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2024-06-06                                                            | -              | -               | ⭐ 17             | 🔴 june 2024      |
| 🔗 [t5-japanese](https://github.com/sonoisa/t5-japanese) ⭐ 118 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2025-09-15                                                                               | -              | -               | ⭐ 118            | 🟡 september 2025 |
| 🔗 [japanese\_llm\_eval](https://github.com/lightblue-tech/japanese_llm_eval) ⭐ 5 \| 🐛 1 \| 🌐 HTML \| 📅 2024-04-22                                                                        | -              | -               | ⭐ 5              | 🔴 april 2024     |
| 🔗 [jmteb](https://github.com/sbintuitions/jmteb) ⭐ 93 \| 🐛 8 \| 🌐 Python \| 📅 2026-07-31                                                                                                 | -              | -               | ⭐ 93             | 🟡 march          |
| 🔗 [pydomino](https://github.com/dwangomediavillage/pydomino) ⭐ 40 \| 🐛 0 \| 🌐 C++ \| 📅 2025-08-19                                                                                        | -              | -               | ⭐ 40             | 🔴 august 2025    |
| 🔗 [easynovelassistant](https://github.com/zuntan03/easynovelassistant) ⭐ 233 \| 🐛 14 \| 🌐 Python \| 📅 2024-07-05                                                                         | -              | -               | ⭐ 233            | 🔴 july 2024      |
| 🔗 [clip-japanese](https://github.com/sonoisa/clip-japanese) ⭐ 13 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2025-09-15                                                                            | -              | -               | ⭐ 13             | 🟡 september 2025 |
| 🔗 [rime-jaroomaji](https://github.com/lazyfoxchan/rime-jaroomaji) ⭐ 55 \| 🐛 2 \| 🌐 Python \| 📅 2026-08-20                                                                                | -              | -               | ⭐ 55             | 🟢 last thursday  |
| 🔗 [deep-question-generation](https://github.com/sonoisa/deep-question-generation) ⭐ 12 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2023-03-12                                                      | -              | -               | ⭐ 12             | 🔴 march 2023     |
| 🔗 [magpie-nemotron](https://github.com/aratako/magpie-nemotron) ⭐ 8 \| 🐛 0 \| 🌐 Python \| 📅 2024-07-05                                                                                   | -              | -               | ⭐ 8              | 🔴 july 2024      |
| 🔗 [qlora\_ja](https://github.com/sosuke115/qlora_ja) ⭐ 1 \| 🐛 1 \| 🌐 Python \| 📅 2024-07-13                                                                                              | -              | -               | ⭐ 1              | 🔴 july 2024      |
| 🔗 [mozcdic-ut-jawiki](https://github.com/utuhiro78/mozcdic-ut-jawiki) ⭐ 31 \| 🐛 0 \| 📅 2026-08-09                                                                                         | -              | -               | ⭐ 31             | 🟢 august         |
| 🔗 [shisa-v2](https://github.com/shisa-ai/shisa-v2) ⭐ 35 \| 🐛 0 \| 🌐 Python \| 📅 2025-12-23                                                                                               | -              | -               | ⭐ 35             | 🟡 december 2025  |
| 🔗 [llm-translator](https://github.com/hpprc/llm-translator) ⭐ 21 \| 🐛 0 \| 🌐 Python \| 📅 2025-01-06                                                                                      | -              | -               | ⭐ 21             | 🔴 january 2025   |
| 🔗 [llm-jp-asr](https://github.com/tosiyuki/llm-jp-asr) ⭐ 9 \| 🐛 0 \| 🌐 Python \| 📅 2024-09-07                                                                                            | -              | -               | ⭐ 9              | 🔴 september 2024 |
| 🔗 [rag-japanese](https://github.com/akimfromparis/rag-japanese) ⭐ 10 \| 🐛 1 \| 🌐 Jupyter Notebook \| 📅 2025-05-12                                                                        | -              | -               | ⭐ 10             | 🔴 may 2025       |
| 🔗 [monaka](https://github.com/komiya-lab/monaka) ⭐ 7 \| 🐛 1 \| 🌐 Python \| 📅 2026-02-23                                                                                                  | -              | -               | ⭐ 7              | 🔴 january 2025   |
| 🔗 [jp-translate.cloud](https://github.com/matthewbieda/jp-translate.cloud) ⭐ 3 \| 🐛 0 \| 🌐 Python \| 📅 2024-09-05                                                                        | -              | -               | ⭐ 3              | 🔴 september 2024 |
| 🔗 [substring-word-finder](https://github.com/toufu-24/substring-word-finder) ⭐ 4 \| 🐛 0 \| 🌐 Python \| 📅 2025-11-24                                                                      | -              | -               | ⭐ 4              | 🟡 november 2025  |
| 🔗 [heron-vlm-leaderboard](https://github.com/wandb/heron-vlm-leaderboard) ⭐ 6 \| 🐛 0 \| 🌐 Python \| 📅 2024-12-25                                                                         | -              | -               | ⭐ 6              | 🔴 december 2024  |
| 🔗 [text2dataset](https://github.com/llm-jp/text2dataset) ⭐ 31 \| 🐛 6 \| 🌐 Python \| 📅 2025-01-20                                                                                         | -              | -               | ⭐ 31             | 🔴 january 2025   |
| 🔗 [mecab-web-api](https://github.com/bungoume/mecab-web-api) ⭐ 40 \| 🐛 94 \| 🌐 Python \| 📅 2026-02-12                                                                                    | -              | -               | ⭐ 40             | 🔴 july 2022      |
| 🔗 [mecab\_controller](https://github.com/ajatt-tools/mecab_controller) ⭐ 21 \| 🐛 1 \| 🌐 Python \| 📅 2026-06-29                                                                           | -              | -               | ⭐ 21             | 🟢 june           |
| 🔗 [vits](https://github.com/zassou65535/vits) ⭐ 93 \| 🐛 0 \| 🌐 Python \| 📅 2023-02-02                                                                                                    | -              | -               | ⭐ 93             | 🔴 february 2023  |
| 🔗 [akari\_chatgpt\_bot](https://github.com/akarigroup/akari_chatgpt_bot) ⭐ 48 \| 🐛 0 \| 🌐 Python \| 📅 2025-10-16                                                                         | -              | -               | ⭐ 48             | 🟡 october 2025   |
| 🔗 [kudasai](https://github.com/bikatr7/kudasai) ⭐ 26 \| 🐛 2 \| 🌐 Python \| 📅 2025-06-24                                                                                                  | -              | -               | ⭐ 26             | 🔴 june 2025      |
| 🔗 [mecab-visualizer](https://github.com/sophiefy/mecab-visualizer) ⭐ 2 \| 🐛 0 \| 🌐 Python \| 📅 2023-09-23                                                                                | -              | -               | ⭐ 2              | 🔴 september 2023 |
| 🔗 [add-dictionary](https://github.com/massao000/add-dictionary) ⭐ 3 \| 🐛 0 \| 🌐 Python \| 📅 2025-10-08                                                                                   | -              | -               | ⭐ 3              | 🟡 october 2025   |
| 🔗 [j-moshi](https://github.com/nu-dialogue/j-moshi) ⭐ 318 \| 🐛 1 \| 🌐 JavaScript \| 📅 2025-06-04                                                                                         | -              | -               | ⭐ 318            | 🔴 june 2025      |
| 🔗 [jatts](https://github.com/unilight/jatts) ⭐ 44 \| 🐛 1 \| 🌐 Python \| 📅 2026-03-13                                                                                                     | -              | -               | ⭐ 44             | 🟡 march          |
| 🔗 [tsukasa-speech](https://github.com/respaired/tsukasa-speech) ⭐ 65 \| 🐛 2 \| 🌐 Jupyter Notebook \| 📅 2025-05-15                                                                        | -              | -               | ⭐ 65             | 🔴 may 2025       |
| 🔗 [symptom-expression-search](https://github.com/po3rin/symptom-expression-search) ⭐ 2 \| 🐛 0 \| 🌐 Python \| 📅 2021-02-17                                                                | -              | -               | ⭐ 2              | 🔴 february 2021  |
| 🔗 [llm-jp-judge](https://github.com/llm-jp/llm-jp-judge) ⭐ 58 \| 🐛 3 \| 🌐 Python \| 📅 2026-08-19                                                                                         | -              | -               | ⭐ 58             | 🟢 july           |
| 🔗 [asagi-vlm-colaboratory-sample](https://github.com/kazuhito00/asagi-vlm-colaboratory-sample) ⭐ 1 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2025-03-01                                          | -              | -               | ⭐ 1              | 🔴 march 2025     |
| 🔗 [llm-jp-eval-mm](https://github.com/llm-jp/llm-jp-eval-mm) ⭐ 43 \| 🐛 2 \| 🌐 Python \| 📅 2026-04-20                                                                                     | -              | -               | ⭐ 43             | 🟡 april          |
| 🔗 [manga109api](https://github.com/manga109/manga109api) ⭐ 130 \| 🐛 0 \| 🌐 Python \| 📅 2022-03-04                                                                                        | 📥 84          | 📦 48k          | ⭐ 130            | 🔴 march 2022     |
| 🔗 [fastrtc-jp](https://github.com/route250/fastrtc-jp) ⭐ 6 \| 🐛 1 \| 🌐 Python \| 📅 2025-06-10                                                                                            | -              | -               | ⭐ 6              | 🔴 may 2025       |
| 🔗 [whisper-transcription](https://github.com/fumifumi0831/whisper-transcription) ⭐ 20 \| 🐛 1 \| 🌐 Python \| 📅 2026-01-02                                                                 | -              | -               | ⭐ 20             | 🟡 january        |
| 🔗 [pocket-researcher](https://github.com/u-masao/pocket-researcher) ⭐ 10 \| 🐛 4 \| 🌐 Python \| 📅 2025-04-07                                                                              | -              | -               | ⭐ 10             | 🔴 april 2025     |
| 🔗 [jtransbench](https://github.com/webbigdata-jp/jtransbench) ⭐ 13 \| 🐛 0 \| 🌐 Python \| 📅 2025-10-11                                                                                    | -              | -               | ⭐ 13             | 🟡 october 2025   |
| 🔗 [easyllasa](https://github.com/zuntan03/easyllasa) ⭐ 26 \| 🐛 0 \| 🌐 Python \| 📅 2025-09-29                                                                                             | -              | -               | ⭐ 26             | 🟡 september 2025 |
| 🔗 [kanjikana-model](https://github.com/digital-go-jp/kanjikana-model) ⭐ 119 \| 🐛 1 \| 🌐 Jupyter Notebook \| 📅 2026-04-28                                                                 | -              | -               | ⭐ 119            | 🟡 april          |
| 🔗 [deep-openreview-research-ja](https://github.com/tb-yasu/deep-openreview-research-ja) ⭐ 13 \| 🐛 0 \| 🌐 Python \| 📅 2025-11-29                                                          | -              | -               | ⭐ 13             | 🟡 november 2025  |
| 🔗 [pitchbench](https://github.com/shewiiii/pitchbench) ⭐ 2 \| 🐛 0 \| 🌐 Python \| 📅 2026-02-21                                                                                            | -              | -               | ⭐ 2              | 🟡 february       |
| 🔗 [mini-transformer-from-scratch](https://github.com/zuofanf/mini-transformer-from-scratch) ⭐ 2 \| 🐛 0 \| 🌐 Python \| 📅 2025-11-30                                                       | -              | -               | ⭐ 2              | 🟡 november 2025  |
| 🔗 [vv\_core\_inference](https://github.com/hiroshiba/vv_core_inference) ⭐ 31 \| 🐛 6 \| 🌐 Python \| 📅 2025-12-03                                                                          | -              | -               | ⭐ 31             | 🟡 december 2025  |
| 🔗 [pyopenjtalk-plus](https://github.com/tsukumijima/pyopenjtalk-plus) ⭐ 60 \| 🐛 0 \| 🌐 Python \| 📅 2026-08-11                                                                            | 📥 10k         | 📦 611k         | ⭐ 60             | 🟢 last tuesday   |
| 🔗 [japanese\_spelling\_correction](https://github.com/phkhanhtrinh23/japanese_spelling_correction) ⭐ 16 \| 🐛 0 \| 🌐 Python \| 📅 2023-09-19                                               | -              | -               | ⭐ 16             | 🔴 september 2023 |
| 🔗 [py-kaomoji](https://github.com/shibuiwilliam/py-kaomoji) ⭐ 6 \| 🐛 0 \| 🌐 Python \| 📅 2018-12-09                                                                                       | 📥 12          | 📦 38k          | ⭐ 6              | 🔴 december 2018  |
| 🔗 [llm-jp-vila](https://github.com/llm-jp/llm-jp-vila) ⭐ 10 \| 🐛 1 \| 🌐 Python \| 📅 2025-08-26                                                                                           | -              | -               | ⭐ 10             | 🔴 august 2025    |
| 🔗 [kanjivg-radical](https://github.com/yagays/kanjivg-radical) ⭐ 107 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2018-08-07                                                                        | -              | -               | ⭐ 107            | 🔴 august 2018    |
| 🔗 [japanese-wordnet-visualization](https://github.com/HemingwayLee/japanese-wordnet-visualization) ⭐ 3 \| 🐛 1 \| 🌐 Python \| 📅 2024-02-07                                                | -              | -               | ⭐ 3              | 🔴 november 2022  |
| 🔗 [piper-plus](https://github.com/ayutaz/piper-plus) ⭐ 197 \| 🐛 12 \| 🌐 Python \| 📅 2026-08-20                                                                                           | -              | -               | ⭐ 196            | 🟢 august         |
| 🔗 [Japanera](https://github.com/nagataaaas/Japanera) ⭐ 35 \| 🐛 0 \| 🌐 Python \| 📅 2025-06-23                                                                                             | 📥 3k          | 📦 438k         | ⭐ 35             | 🔴 june 2025      |
| 🔗 [bert-abstractive-text-summarization](https://github.com/iwasakiyuuki/bert-abstractive-text-summarization) ⭐ 49 \| 🐛 0 \| 🌐 Python \| 📅 2023-05-09                                     | -              | -               | ⭐ 49             | 🔴 december 2019  |
| 🔗 [kyujipy](https://github.com/drturnon/kyujipy) ⭐ 22 \| 🐛 1 \| 🌐 Python \| 📅 2026-02-11                                                                                                 | 📥 38          | 📦 24k          | ⭐ 22             | 🟡 january        |
| 🔗 [jitenbot](https://github.com/konstantindjairo/jitenbot) ⭐ 4 \| 🐛 0 \| 🌐 Python \| 📅 2024-12-05                                                                                        | -              | -               | ⭐ 4              | 🔴 december 2024  |
| 🔗 [ja-icd10](https://github.com/yagays/ja-icd10) ⭐ 5 \| 🐛 1 \| 🌐 Python \| 📅 2021-07-09                                                                                                  | -              | -               | ⭐ 5              | 🔴 july 2021      |
| 🔗 [pl-bert-vits2](https://github.com/tonnetonne814/pl-bert-vits2) ⭐ 14 \| 🐛 1 \| 🌐 Python \| 📅 2023-12-17                                                                                | -              | -               | ⭐ 14             | 🔴 december 2023  |
| 🔗 [ndc\_predictor](https://github.com/ndl-lab/ndc_predictor) ⭐ 14 \| 🐛 0 \| 📅 2021-08-04                                                                                                  | -              | -               | ⭐ 14             | 🔴 august 2021    |
| 🔗 [pfmt-bench-fin-ja](https://github.com/pfnet-research/pfmt-bench-fin-ja) ⭐ 9 \| 🐛 0 \| 🌐 Python \| 📅 2025-03-19                                                                        | -              | -               | ⭐ 9              | 🔴 march 2025     |
| 🔗 [marine-plus](https://github.com/tsukumijima/marine-plus) ⭐ 9 \| 🐛 0 \| 🌐 Python \| 📅 2026-03-22                                                                                       | 📥 134         | 📦 14k          | ⭐ 9              | 🟡 march          |
| 🔗 [ja-tokenizer-benchmark](https://github.com/polm/ja-tokenizer-benchmark) ⭐ 7 \| 🐛 0 \| 🌐 Python \| 📅 2022-02-24                                                                        | -              | -               | ⭐ 7              | 🔴 february 2022  |
| 🔗 [yat](https://github.com/yagays/yat) ⭐ 7 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2018-06-19                                                                                                  | -              | -               | ⭐ 7              | 🔴 june 2018      |
| 🔗 [igakuqa119](https://github.com/docto-rin/igakuqa119) ⭐ 10 \| 🐛 0 \| 🌐 Python \| 📅 2026-06-10                                                                                          | -              | -               | ⭐ 10             | 🔴 may 2025       |
| 🔗 [japanese-luw-tokenizer](https://github.com/koichiyasuoka/japanese-luw-tokenizer) ⭐ 6 \| 🐛 0 \| 🌐 Python \| 📅 2021-12-21                                                               | -              | -               | ⭐ 6              | 🔴 december 2021  |
| 🔗 [ibus-jig](https://github.com/y-koj/ibus-jig) ⭐ 4 \| 🐛 1 \| 🌐 Python \| 📅 2023-12-10                                                                                                   | -              | -               | ⭐ 4              | 🔴 december 2023  |
| 🔗 [jp-stopword-filter](https://github.com/BrambleXu/jp-stopword-filter) ⭐ 4 \| 🐛 0 \| 🌐 Python \| 📅 2026-06-20                                                                           | 📥 29          | 📦 7k           | ⭐ 4              | 🟢 june           |
| 🔗 [yasumail](https://github.com/terallite/yasumail) ⭐ 3 \| 🐛 0 \| 🌐 Python \| 📅 2026-01-24                                                                                               | -              | -               | ⭐ 3              | 🟡 january        |
| 🔗 [himotoki](https://github.com/msr2903/himotoki) ⭐ 6 \| 🐛 2 \| 🌐 HTML \| 📅 2026-07-12                                                                                                   | 📥 28          | 📦 6k           | ⭐ 6              | 🟢 july           |
| 🔗 [diafill-toolkit](https://github.com/sbintuitions/diafill-toolkit) ⭐ 0 \| 🐛 2 \| 🌐 Python \| 📅 2026-01-27                                                                              | -              | -               | ⭐ 0              | 🟡 january        |
| 🔗 [eval\_vertical\_ja](https://github.com/llm-jp/eval_vertical_ja) ⭐ 3 \| 🐛 1 \| 🌐 Python \| 📅 2026-05-24                                                                                | -              | -               | ⭐ 3              | 🟡 may            |
| 🔗 [jp-llm-corpus-pii-filter](https://github.com/matsuolab/jp-llm-corpus-pii-filter) ⭐ 7 \| 🐛 0 \| 🌐 Python \| 📅 2025-03-25                                                               | -              | -               | ⭐ 7              | 🔴 march 2025     |
| 🔗 [Novel2DialCorpus](https://github.com/ganbon/Novel2DialCorpus) ⭐ 0 \| 🐛 0 \| 🌐 Python \| 📅 2026-02-10                                                                                  | -              | -               | ⭐ 0              | 🟡 february       |
| 🔗 [OneCompression](https://github.com/FujitsuResearch/OneCompression) ⭐ 416 \| 🐛 11 \| 🌐 Python \| 📅 2026-08-06                                                                          | -              | -               | ⭐ 416            | 🟢 august         |
| 🔗 [manga-translator](https://github.com/georgescutelnicu/manga-translator) ⭐ 27 \| 🐛 0 \| 🌐 Python \| 📅 2026-04-14                                                                       | -              | -               | ⭐ 27             | 🟡 april          |
| 🔗 [shirabe-address-api](https://github.com/techwell-inc-jp/shirabe-address-api) ⭐ 0 \| 🐛 0 \| 🌐 TypeScript \| 📅 2026-07-17                                                               | -              | -               | ⭐ 0              | 🟢 july           |
| 🔗 [medical-paper-summarizer-public](https://github.com/yush02084/medical-paper-summarizer-public) ⭐ 19 \| 🐛 0 \| 🌐 Python \| 📅 2026-04-18                                                | -              | -               | ⭐ 19             | 🟡 april          |
| 🔗 [Irodori-TTS](https://github.com/Aratako/Irodori-TTS) ⭐ 1,201 \| 🐛 16 \| 🌐 Python \| 📅 2026-08-11                                                                                      | -              | -               | ⭐ 1.2k           | 🟢 last tuesday   |
| 🔗 [sarashina2.2-tts](https://github.com/sbintuitions/sarashina2.2-tts) ⭐ 81 \| 🐛 3 \| 🌐 Python \| 📅 2026-06-29                                                                           | -              | -               | ⭐ 81             | 🟢 june           |
| 🔗 [manga-translator](https://github.com/Detopall/manga-translator) ⭐ 19 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2026-06-18                                                                     | -              | -               | ⭐ 19             | 🟢 june           |
| 🔗 [jp-tl-bench](https://github.com/shisa-ai/jp-tl-bench) ⭐ 6 \| 🐛 0 \| 🌐 Python \| 📅 2026-04-23                                                                                          | -              | -               | ⭐ 6              | 🟡 february       |
| 🔗 [novel2hermes\_jp](https://github.com/kgmkm/novel2hermes_jp) ⭐ 97 \| 🐛 1 \| 🌐 Python \| 📅 2026-06-27                                                                                   | -              | -               | ⭐ 97             | 🟢 june           |
| 🔗 [moshi-finetune](https://github.com/nu-dialogue/moshi-finetune) ⭐ 105 \| 🐛 2 \| 🌐 Python \| 📅 2026-01-05                                                                               | -              | -               | ⭐ 106            | 🟡 january        |
| 🔗 [simple-evals-mm](https://github.com/llm-jp/simple-evals-mm) ⭐ 5 \| 🐛 0 \| 🌐 Python \| 📅 2026-08-20                                                                                    | -              | -               | ⭐ 5              | 🟡 may            |
| 🔗 [medvoice-jp-asr](https://github.com/nikotora/medvoice-jp-asr) ⭐ 4 \| 🐛 0 \| 🌐 Python \| 📅 2026-06-27                                                                                  | -              | -               | ⭐ 4              | 🟢 june           |
| 🔗 [open-zeimu-mcp](https://github.com/zeimu-ai/open-zeimu-mcp) ⭐ 1 \| 🐛 6 \| 🌐 TypeScript \| 📅 2026-06-22                                                                                | -              | -               | ⭐ 1              | 🟢 june           |
| 🔗 [llm-jp-moshi](https://github.com/llm-jp/llm-jp-moshi) ⭐ 24 \| 🐛 0 \| 🌐 HTML \| 📅 2026-03-17                                                                                           | -              | -               | ⭐ 24             | 🟡 march          |
| 🔗 [shirabe-sdk-python](https://github.com/techwell-inc-jp/shirabe-sdk-python) ⭐ 0 \| 🐛 0 \| 🌐 Python \| 📅 2026-07-17                                                                     | -              | -               | ⭐ 0              | 🟢 july           |
| 🔗 [fuseji](https://github.com/sserada/fuseji) ⭐ 0 \| 🐛 1 \| 🌐 Python \| 📅 2026-07-19                                                                                                     | -              | -               | ⭐ 0              | 🟢 june           |
| 🔗 [moine](https://github.com/tagucci/moine) ⭐ 9 \| 🐛 0 \| 🌐 Rust \| 📅 2026-08-03                                                                                                         | -              | -               | ⭐ 9              | 🟢 august         |

## C++

### Morphology analysis

High-performance libraries for Japanese morphological analysis

* [mecab](https://github.com/taku910/mecab) ⭐ 1,106 | 🐛 53 | 🌐 C++ | 📅 2025-02-22 - Yet another Japanese morphological analyzer
* [jumanpp](https://github.com/ku-nlp/jumanpp) ⭐ 415 | 🐛 30 | 🌐 C++ | 📅 2026-04-17 - Juman++ (a Morphological Analyzer Toolkit)
* [kytea](https://github.com/neubig/kytea) ⭐ 216 | 🐛 8 | 🌐 C++ | 📅 2020-04-03 - The Kyoto Text Analysis Toolkit for word segmentation and pronunciation estimation, etc.
* [juman](https://github.com/ku-nlp/juman) ⭐ 12 | 🐛 0 | 🌐 C | 📅 2021-12-09 - Japanese Morphological Analysis System JUMAN

| Name                                                                                      | downloads/week | total downloads | stars  | last commit      |
| ----------------------------------------------------------------------------------------- | -------------- | --------------- | ------ | ---------------- |
| 🔗 [mecab](https://github.com/taku910/mecab) ⭐ 1,106 \| 🐛 53 \| 🌐 C++ \| 📅 2025-02-22  | -              | -               | ⭐ 1.1k | 🔴 february 2025 |
| 🔗 [jumanpp](https://github.com/ku-nlp/jumanpp) ⭐ 415 \| 🐛 30 \| 🌐 C++ \| 📅 2026-04-17 | -              | -               | ⭐ 415  | 🟡 april         |
| 🔗 [kytea](https://github.com/neubig/kytea) ⭐ 216 \| 🐛 8 \| 🌐 C++ \| 📅 2020-04-03      | -              | -               | ⭐ 215  | 🔴 april 2020    |
| 🔗 [juman](https://github.com/ku-nlp/juman) ⭐ 12 \| 🐛 0 \| 🌐 C \| 📅 2021-12-09         | -              | -               | ⭐ 12   | 🔴 december 2021 |

### Parsing

Libraries for dependency and syntactic parsing of Japanese sentences

* [cabocha](https://github.com/taku910/cabocha) ⭐ 121 | 🐛 5 | 🌐 C++ | 📅 2025-02-22 - Yet Another Japanese Dependency Structure Analyzer
* [knp](https://github.com/ku-nlp/knp) ⭐ 35 | 🐛 7 | 🌐 C | 📅 2023-11-01 - A Japanese Parser

| Name                                                                                      | downloads/week | total downloads | stars | last commit      |
| ----------------------------------------------------------------------------------------- | -------------- | --------------- | ----- | ---------------- |
| 🔗 [cabocha](https://github.com/taku910/cabocha) ⭐ 121 \| 🐛 5 \| 🌐 C++ \| 📅 2025-02-22 | -              | -               | ⭐ 121 | 🔴 february 2025 |
| 🔗 [knp](https://github.com/ku-nlp/knp) ⭐ 35 \| 🐛 7 \| 🌐 C \| 📅 2023-11-01             | -              | -               | ⭐ 35  | 🔴 november 2023 |

### Others

Other Japanese NLP and text processing libraries

* [mozc](https://github.com/google/mozc) ⭐ 2,966 | 🐛 27 | 🌐 C++ | 📅 2026-08-14 - Mozc - a Japanese Input Method Editor designed for multi-platform
* [mozuku](https://github.com/t3tra-dev/mozuku) ⭐ 418 | 🐛 4 | 🌐 C++ | 📅 2026-04-03 - 日本語文章の解析・校正を行う LSP サーバー。
* [aquaskk](https://github.com/codefirst/aquaskk) ⭐ 373 | 🐛 29 | 🌐 C++ | 📅 2025-09-10 - An input method without morphological analysis.
* [corvusskk](https://github.com/nathancorvussolis/corvusskk) ⭐ 373 | 🐛 1 | 🌐 C | 📅 2026-08-14 - ▽▼ SKK-like Japanese Input Method Editor for Windows
* [resembla](https://github.com/tuem/resembla) ⭐ 74 | 🐛 4 | 🌐 C++ | 📅 2025-08-03 - Resembla: Word-based Japanese similar sentence search library
* [jsc](https://github.com/yohokuno/jsc) ⭐ 15 | 🐛 0 | 🌐 C++ | 📅 2012-12-19 - Joint source channel model for Japanese Kana Kanji conversion, Chinese pinyin input and CJE mixed input.
* [trimatch](https://github.com/tuem/trimatch) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2026-02-06 - Trimatch: An (Exact|Prefix|Approximate) String Matching Library

| Name                                                                                                  | downloads/week | total downloads | stars | last commit      |
| ----------------------------------------------------------------------------------------------------- | -------------- | --------------- | ----- | ---------------- |
| 🔗 [jsc](https://github.com/yohokuno/jsc) ⭐ 15 \| 🐛 0 \| 🌐 C++ \| 📅 2012-12-19                     | -              | -               | ⭐ 15  | 🔴 december 2012 |
| 🔗 [aquaskk](https://github.com/codefirst/aquaskk) ⭐ 373 \| 🐛 29 \| 🌐 C++ \| 📅 2025-09-10          | -              | -               | ⭐ 372 | 🔴 july 2023     |
| 🔗 [mozc](https://github.com/google/mozc) ⭐ 2,966 \| 🐛 27 \| 🌐 C++ \| 📅 2026-08-14                 | -              | -               | ⭐ 3k  | 🟢 last friday   |
| 🔗 [trimatch](https://github.com/tuem/trimatch) ⭐ 2 \| 🐛 0 \| 🌐 C++ \| 📅 2026-02-06                | -              | -               | ⭐ 2   | 🟡 february      |
| 🔗 [resembla](https://github.com/tuem/resembla) ⭐ 74 \| 🐛 4 \| 🌐 C++ \| 📅 2025-08-03               | -              | -               | ⭐ 74  | 🔴 august 2025   |
| 🔗 [corvusskk](https://github.com/nathancorvussolis/corvusskk) ⭐ 373 \| 🐛 1 \| 🌐 C \| 📅 2026-08-14 | -              | -               | ⭐ 372 | 🟢 last friday   |
| 🔗 [mozuku](https://github.com/t3tra-dev/mozuku) ⭐ 418 \| 🐛 4 \| 🌐 C++ \| 📅 2026-04-03             | -              | -               | ⭐ 418 | 🟡 april         |

## Rust crate

### Morphology analysis

Fast Japanese morphological analysis crates written in Rust

* [lindera](https://github.com/lindera-morphology/lindera) ⭐ 660 | 🐛 9 | 🌐 Rust | 📅 2026-08-20 - A morphological analysis library.
* [vibrato](https://github.com/daac-tools/vibrato) ⭐ 419 | 🐛 7 | 🌐 Rust | 📅 2026-07-20 - vibrato: Viterbi-based accelerated tokenizer
* [vaporetto](https://github.com/daac-tools/vaporetto) ⭐ 297 | 🐛 6 | 🌐 Rust | 📅 2026-07-20 - Vaporetto: Very Accelerated POintwise pREdicTion based TOkenizer
* [kanpyo](https://github.com/togatoga/kanpyo) ⭐ 109 | 🐛 5 | 🌐 Rust | 📅 2026-07-26 - Japanese Morphological Analyzer written in Rust
* [goya](https://github.com/Leko/goya) ⭐ 84 | 🐛 3 | 🌐 Rust | 📅 2021-12-30 - Japanese Morphological Analysis written in Rust
* [mecab-rs](https://github.com/tsurai/mecab-rs) ⭐ 72 | 🐛 2 | 🌐 Rust | 📅 2023-09-03 - Safe Rust bindings for mecab a part-of-speech and morphological analyzer library
* [yoin](https://github.com/agatan/yoin) ⭐ 26 | 🐛 2 | 🌐 Rust | 📅 2019-10-25 - A Japanese Morphological Analyzer written in pure Rust
* [awabi](https://github.com/nakagami/awabi) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2025-11-16 - A morphological analyzer using mecab dictionary
* [mecrab](https://github.com/cool-japan/mecrab) ⭐ 6 | 🐛 1 | 🌐 Rust | 📅 2026-08-13 - A pure Rust implementation of a morphological analyzer compatible with MeCab dictionaries (IPADIC format).

| Name                                                                                                  | downloads/week | total downloads | stars | last commit       |
| ----------------------------------------------------------------------------------------------------- | -------------- | --------------- | ----- | ----------------- |
| 🔗 [lindera](https://github.com/lindera-morphology/lindera) ⭐ 660 \| 🐛 9 \| 🌐 Rust \| 📅 2026-08-20 | -              | 📦 1.9M         | ⭐ 658 | 🟢 yesterday      |
| 🔗 [vaporetto](https://github.com/daac-tools/vaporetto) ⭐ 297 \| 🐛 6 \| 🌐 Rust \| 📅 2026-07-20     | -              | 📦 278k         | ⭐ 297 | 🟢 july           |
| 🔗 [goya](https://github.com/Leko/goya) ⭐ 84 \| 🐛 3 \| 🌐 Rust \| 📅 2021-12-30                      | -              | 📦 12k          | ⭐ 84  | 🔴 december 2021  |
| 🔗 [vibrato](https://github.com/daac-tools/vibrato) ⭐ 419 \| 🐛 7 \| 🌐 Rust \| 📅 2026-07-20         | -              | 📦 82k          | ⭐ 418 | 🟢 july           |
| 🔗 [yoin](https://github.com/agatan/yoin) ⭐ 26 \| 🐛 2 \| 🌐 Rust \| 📅 2019-10-25                    | -              | 📦 3.1k         | ⭐ 26  | 🔴 october 2017   |
| 🔗 [mecab-rs](https://github.com/tsurai/mecab-rs) ⭐ 72 \| 🐛 2 \| 🌐 Rust \| 📅 2023-09-03            | -              | 📦 41k          | ⭐ 72  | 🔴 september 2023 |
| 🔗 [awabi](https://github.com/nakagami/awabi) ⭐ 11 \| 🐛 0 \| 🌐 Rust \| 📅 2025-11-16                | -              | 📦 27k          | ⭐ 11  | 🟡 november 2025  |
| 🔗 [kanpyo](https://github.com/togatoga/kanpyo) ⭐ 109 \| 🐛 5 \| 🌐 Rust \| 📅 2026-07-26             | -              | 📦 2.5k         | ⭐ 109 | 🟡 february       |
| 🔗 [mecrab](https://github.com/cool-japan/mecrab) ⭐ 6 \| 🐛 1 \| 🌐 Rust \| 📅 2026-08-13             | -              | -               | ⭐ 6   | 🟡 january        |

### Converter

Crates for script and character conversion in Japanese text

* [wana\_kana\_rust](https://github.com/PSeitz/wana_kana_rust) ⭐ 90 | 🐛 6 | 🌐 Rust | 📅 2026-05-08 - Utility library for checking and converting between Japanese characters - Hiragana, Katakana - and Romaji
* [yosina](https://github.com/yosina-lib/yosina) ⭐ 26 | 🐛 0 | 🌐 Rust | 📅 2026-04-18 - Yosina is a transliteration library deals with the letters and symbols used in Japanese writing.
* [kanaria](https://github.com/samunohito/kanaria) ⭐ 21 | 🐛 2 | 🌐 Rust | 📅 2026-02-14 - このライブラリは、ひらがな・カタカナ、半角・全角の相互変換や判別を始めとした機能を提供します。
* [unicode-jp-rs](https://github.com/gemmarx/unicode-jp-rs) ⭐ 19 | 🐛 2 | 🌐 Rust | 📅 2024-03-11 - A Rust library to convert Japanese Half-width-kana\[半角ｶﾅ] and Wide-alphanumeric\[全角英数] into normal ones
* [ja-furigana](https://github.com/RyuuNeko1107/ja-furigana) ⭐ 19 | 🐛 6 | 🌐 Rust | 📅 2026-08-17 - 日本語フリガナ (ルビ) を扱う Rust 製ライブラリ + ローカル HTTP サーバー。ルールはすべてデータ駆動 (TOML)。
* [japanese-address-parser](https://github.com/yuukitoriyama/japanese-address-parser) ⭐ 13 | 🐛 49 | 🌐 Rust | 📅 2026-07-14 - 日本の住所を都道府県/市区町村/町名/その他に分割するライブラリです
* [kana](https://github.com/gbrlsnchs/kana) ⭐ 12 | 🐛 1 | 🌐 Zig | 📅 2023-02-10 - \[Mirror] CLI program for transliterating romaji text to either hiragana or katakana
* [haqumei](https://github.com/o24s/haqumei) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2026-08-20 - A Japanese Grapheme-to-Phoneme (G2P) library.
* [mojimoji-rs](https://github.com/europeanplaice/mojimoji-rs) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2022-11-14 - Rust implementation of a fast converter between Japanese hankaku and zenkaku characters, mojimoji.

| Name                                                                                                                             | downloads/week | total downloads | stars | last commit       |
| -------------------------------------------------------------------------------------------------------------------------------- | -------------- | --------------- | ----- | ----------------- |
| 🔗 [wana\_kana\_rust](https://github.com/PSeitz/wana_kana_rust) ⭐ 90 \| 🐛 6 \| 🌐 Rust \| 📅 2026-05-08                         | -              | 📦 559k         | ⭐ 90  | 🟡 may            |
| 🔗 [unicode-jp-rs](https://github.com/gemmarx/unicode-jp-rs) ⭐ 19 \| 🐛 2 \| 🌐 Rust \| 📅 2024-03-11                            | -              | 📦 68k          | ⭐ 19  | 🔴 april 2020     |
| 🔗 [kana](https://github.com/gbrlsnchs/kana) ⭐ 12 \| 🐛 1 \| 🌐 Zig \| 📅 2023-02-10                                             | -              | -               | ⭐ 12  | 🔴 january 2023   |
| 🔗 [kanaria](https://github.com/samunohito/kanaria) ⭐ 21 \| 🐛 2 \| 🌐 Rust \| 📅 2026-02-14                                     | -              | -               | ⭐ 21  | 🟡 february       |
| 🔗 [japanese-address-parser](https://github.com/yuukitoriyama/japanese-address-parser) ⭐ 13 \| 🐛 49 \| 🌐 Rust \| 📅 2026-07-14 | -              | -               | ⭐ 13  | 🟢 june           |
| 🔗 [yosina](https://github.com/yosina-lib/yosina) ⭐ 26 \| 🐛 0 \| 🌐 Rust \| 📅 2026-04-18                                       | -              | -               | ⭐ 26  | 🟡 april          |
| 🔗 [mojimoji-rs](https://github.com/europeanplaice/mojimoji-rs) ⭐ 4 \| 🐛 0 \| 🌐 Rust \| 📅 2022-11-14                          | -              | -               | ⭐ 4   | 🔴 november 2022  |
| 🔗 [haqumei](https://github.com/o24s/haqumei) ⭐ 7 \| 🐛 0 \| 🌐 Rust \| 📅 2026-08-20                                            | -              | -               | ⭐ 7   | 🟢 today          |
| 🔗 [ja-furigana](https://github.com/RyuuNeko1107/ja-furigana) ⭐ 19 \| 🐛 6 \| 🌐 Rust \| 📅 2026-08-17                           | -              | -               | ⭐ 19  | 🟢 last wednesday |

### Search engine library

Libraries for Japanese full-text search and indexing

* [lindera-tantivy](https://github.com/lindera-morphology/lindera-tantivy) ⭐ 70 | 🐛 1 | 🌐 Rust | 📅 2026-08-07 - Lindera tokenizer for Tantivy.
* [lindera-sqlite](https://github.com/lindera/lindera-sqlite) ⭐ 22 | 🐛 0 | 🌐 Rust | 📅 2026-08-08 - Lindera for SQLite FTS5 extention
* [sqlite-vaporetto](https://github.com/hotchpotch/sqlite-vaporetto) ⭐ 20 | 🐛 0 | 🌐 Rust | 📅 2026-04-30 - SQLite FTS5 extension for fast Japanese full-text search with 🛥Vaporetto / Vaporetto による高速な日本語全文検索を SQLite FTS5 で実現する拡張機能
* [duckdb-vaporetto](https://github.com/hotchpotch/duckdb-vaporetto) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2026-04-30 - DuckDB extension for Japanese full-text search with 🛥Vaporetto / Vaporetto による DuckDB + 日本語全文検索拡張機能
* [tantivy-vibrato](https://github.com/akr4/tantivy-vibrato) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2026-04-29 - A Tantivy tokenizer using Vibrato.

| Name                                                                                                                 | downloads/week | total downloads | stars | last commit |
| -------------------------------------------------------------------------------------------------------------------- | -------------- | --------------- | ----- | ----------- |
| 🔗 [lindera-tantivy](https://github.com/lindera-morphology/lindera-tantivy) ⭐ 70 \| 🐛 1 \| 🌐 Rust \| 📅 2026-08-07 | -              | 📦 214k         | ⭐ 70  | 🟢 august   |
| 🔗 [tantivy-vibrato](https://github.com/akr4/tantivy-vibrato) ⭐ 3 \| 🐛 0 \| 🌐 Rust \| 📅 2026-04-29                | -              | 📦 1.6k         | ⭐ 3   | 🟡 april    |
| 🔗 [sqlite-vaporetto](https://github.com/hotchpotch/sqlite-vaporetto) ⭐ 20 \| 🐛 0 \| 🌐 Rust \| 📅 2026-04-30       | -              | -               | ⭐ 20  | 🟡 april    |
| 🔗 [duckdb-vaporetto](https://github.com/hotchpotch/duckdb-vaporetto) ⭐ 11 \| 🐛 0 \| 🌐 Rust \| 📅 2026-04-30       | -              | -               | ⭐ 11  | 🟡 april    |
| 🔗 [lindera-sqlite](https://github.com/lindera/lindera-sqlite) ⭐ 22 \| 🐛 0 \| 🌐 Rust \| 📅 2026-08-08              | -              | -               | ⭐ 22  | 🟢 august   |

### Others

Supplementary crates for Japanese text and IME processing

* [koharu](https://github.com/mayocream/koharu) ⭐ 5,330 | 🐛 73 | 🌐 Rust | 📅 2026-08-20 - Automated manga translation tool with LLM, written in Rust.
* [voicevox\_core](https://github.com/VOICEVOX/voicevox_core) ⭐ 1,131 | 🐛 153 | 🌐 Rust | 📅 2026-08-19 - 無料で使える中品質なテキスト読み上げソフトウェア、VOICEVOXのコア
* [daachorse](https://github.com/daac-tools/daachorse) ⭐ 276 | 🐛 0 | 🌐 Rust | 📅 2026-08-18 - A fast implementation of the Aho-Corasick algorithm using the compact double-array data structure in Rust.
* [akaza](https://github.com/akaza-im/akaza) ⭐ 259 | 🐛 24 | 🌐 Rust | 📅 2026-06-08 - Yet another Japanese IME for IBus/Linux
* [vime](https://github.com/algon-320/vime) ⭐ 229 | 🐛 2 | 🌐 Rust | 📅 2022-12-03 - Using Vim as an input method for X11 apps
* [Jotoba](https://github.com/WeDontPanic/Jotoba) ⭐ 209 | 🐛 6 | 🌐 Rust | 📅 2024-01-22 - A free online, self-hostable, multilang Japanese dictionary.
* [cskk](https://github.com/naokiri/cskk) ⭐ 85 | 🐛 22 | 🌐 Rust | 📅 2026-07-20 - SKK (Simple Kana Kanji henkan) library
* [hujiang\_dictionary](https://github.com/asutorufa/hujiang_dictionary) ⭐ 72 | 🐛 11 | 🌐 Rust | 📅 2026-08-11 - 日本語辞書 by Rust, support Telegram bot, AWS Lambda and Cloudflare Workers. Support LLM and search RAG.
* [find-simdoc](https://github.com/legalforce-research/find-simdoc) ⭐ 62 | 🐛 1 | 🌐 Rust | 📅 2025-03-13 - Finding all pairs of similar documents time- and memory-efficiently
* [yomine](https://github.com/mcgrizzz/yomine) ⭐ 60 | 🐛 4 | 🌐 Rust | 📅 2026-08-19 - A Japanese vocabulary mining tool designed to help language learners mine new words and expressions.
* [jpreprocess](https://github.com/jpreprocess/jpreprocess) ⭐ 59 | 🐛 26 | 🌐 Rust | 📅 2026-08-16 - Japanese text preprocessor for Text-to-Speech applications (OpenJTalk rewrite in rust language)
* [dvorakjp-romantable](https://github.com/shinespark/dvorakjp-romantable) ⭐ 58 | 🐛 1 | 🌐 Rust | 📅 2026-08-18 - Google 日本語入力用DvorakJPローマ字テーブル / DvorakJP Roman Table for Google Japanese Input
* [crawdad](https://github.com/daac-tools/crawdad) ⭐ 38 | 🐛 0 | 🌐 Rust | 📅 2026-08-12 - Rust library of natural language dictionaries using character-wise double-array tries.
* [kanalizer](https://github.com/voicevox/kanalizer) ⭐ 31 | 🐛 15 | 🌐 Rust | 📅 2026-05-04 - 英単語から読みを推測するライブラリ。
* [matsuba](https://github.com/mrpicklepinosaur/matsuba) ⭐ 19 | 🐛 24 | 🌐 Rust | 📅 2023-03-23 - lightweight japanese ime written in rust
* [jisho](https://github.com/eagleflo/jisho) ⭐ 18 | 🐛 5 | 🌐 Rust | 📅 2026-04-02 - Jisho is a CLI tool & Rust library that provides a Japanese-English dictionary.
* [niinii](https://github.com/Netdex/niinii) ⭐ 16 | 🐛 0 | 🌐 Rust | 📅 2026-06-25 -  Japanese glossator for assisted reading of text using Ichiran
* [listup\_precedent](https://github.com/japanese-law-analysis/listup_precedent) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2026-07-01 - 裁判例のデータ一覧を裁判所のホームページ(<https://www.courts.go.jp/index.html>) をスクレイピングして生成するソフトウェア
* [jp-deinflector](https://github.com/btrkeks/jp-deinflector) ⭐ 7 | 🐛 2 | 🌐 Rust | 📅 2026-07-29 - A high-performance Rust crate for deinflecting Japanese words using perfect hash tables
* [tokenizer-speed-bench](https://github.com/legalforce-research/tokenizer-speed-bench) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2023-03-07 -  Comparison code of various tokenizers
* [stringmatch-bench](https://github.com/legalforce-research/stringmatch-bench) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2022-09-30 - Here provides benchmark tools to compare the performance of data structures for string matching.
* [japanki](https://github.com/tysonwu/japanki) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2023-10-16 - Learn Japanese vocabs 🇯🇵 by doing quizzes on CLI!
* [mecab-dic-converter](https://github.com/tomokane/mecab-dic-converter) ⭐ 1 | 🐛 2 | 🌐 Rust | 📅 2026-05-29 - MeCab 用のコンパイル済み辞書を読み取り、解析・再構成し、最終的に Vibrato や Lindera のようなMecab互換 tokenizer が使える辞書へ変換するための Rust crate です。

| Name                                                                                                                             | downloads/week | total downloads | stars  | last commit       |
| -------------------------------------------------------------------------------------------------------------------------------- | -------------- | --------------- | ------ | ----------------- |
| 🔗 [daachorse](https://github.com/daac-tools/daachorse) ⭐ 276 \| 🐛 0 \| 🌐 Rust \| 📅 2026-08-18                                | -              | 📦 3.7M         | ⭐ 275  | 🟢 last thursday  |
| 🔗 [find-simdoc](https://github.com/legalforce-research/find-simdoc) ⭐ 62 \| 🐛 1 \| 🌐 Rust \| 📅 2025-03-13                    | -              | 📦 29k          | ⭐ 62   | 🔴 march 2025     |
| 🔗 [crawdad](https://github.com/daac-tools/crawdad) ⭐ 38 \| 🐛 0 \| 🌐 Rust \| 📅 2026-08-12                                     | -              | 📦 90k          | ⭐ 38   | 🟢 last wednesday |
| 🔗 [tokenizer-speed-bench](https://github.com/legalforce-research/tokenizer-speed-bench) ⭐ 4 \| 🐛 0 \| 🌐 Rust \| 📅 2023-03-07 | -              | -               | ⭐ 4    | 🔴 march 2023     |
| 🔗 [stringmatch-bench](https://github.com/legalforce-research/stringmatch-bench) ⭐ 3 \| 🐛 0 \| 🌐 Rust \| 📅 2022-09-30         | -              | -               | ⭐ 3    | 🔴 september 2022 |
| 🔗 [vime](https://github.com/algon-320/vime) ⭐ 229 \| 🐛 2 \| 🌐 Rust \| 📅 2022-12-03                                           | -              | -               | ⭐ 229  | 🔴 november 2022  |
| 🔗 [voicevox\_core](https://github.com/VOICEVOX/voicevox_core) ⭐ 1,131 \| 🐛 153 \| 🌐 Rust \| 📅 2026-08-19                     | -              | -               | ⭐ 1.1k | 🟢 last saturday  |
| 🔗 [akaza](https://github.com/akaza-im/akaza) ⭐ 259 \| 🐛 24 \| 🌐 Rust \| 📅 2026-06-08                                         | -              | -               | ⭐ 259  | 🟢 june           |
| 🔗 [Jotoba](https://github.com/WeDontPanic/Jotoba) ⭐ 209 \| 🐛 6 \| 🌐 Rust \| 📅 2024-01-22                                     | -              | -               | ⭐ 209  | 🔴 january 2024   |
| 🔗 [dvorakjp-romantable](https://github.com/shinespark/dvorakjp-romantable) ⭐ 58 \| 🐛 1 \| 🌐 Rust \| 📅 2026-08-18             | -              | -               | ⭐ 58   | 🟢 last tuesday   |
| 🔗 [niinii](https://github.com/Netdex/niinii) ⭐ 16 \| 🐛 0 \| 🌐 Rust \| 📅 2026-06-25                                           | -              | -               | ⭐ 16   | 🟢 june           |
| 🔗 [cskk](https://github.com/naokiri/cskk) ⭐ 85 \| 🐛 22 \| 🌐 Rust \| 📅 2026-07-20                                             | -              | -               | ⭐ 84   | 🟢 july           |
| 🔗 [japanki](https://github.com/tysonwu/japanki) ⭐ 3 \| 🐛 0 \| 🌐 Rust \| 📅 2023-10-16                                         | -              | -               | ⭐ 3    | 🔴 october 2023   |
| 🔗 [jpreprocess](https://github.com/jpreprocess/jpreprocess) ⭐ 59 \| 🐛 26 \| 🌐 Rust \| 📅 2026-08-16                           | -              | -               | ⭐ 59   | 🟢 june           |
| 🔗 [listup\_precedent](https://github.com/japanese-law-analysis/listup_precedent) ⭐ 7 \| 🐛 0 \| 🌐 Rust \| 📅 2026-07-01        | -              | -               | ⭐ 7    | 🟢 july           |
| 🔗 [jisho](https://github.com/eagleflo/jisho) ⭐ 18 \| 🐛 5 \| 🌐 Rust \| 📅 2026-04-02                                           | -              | -               | ⭐ 18   | 🟡 april          |
| 🔗 [kanalizer](https://github.com/voicevox/kanalizer) ⭐ 31 \| 🐛 15 \| 🌐 Rust \| 📅 2026-05-04                                  | -              | -               | ⭐ 31   | 🟡 may            |
| 🔗 [koharu](https://github.com/mayocream/koharu) ⭐ 5,330 \| 🐛 73 \| 🌐 Rust \| 📅 2026-08-20                                    | -              | -               | ⭐ 5.3k | 🟢 today          |
| 🔗 [yomine](https://github.com/mcgrizzz/yomine) ⭐ 60 \| 🐛 4 \| 🌐 Rust \| 📅 2026-08-19                                         | -              | -               | ⭐ 59   | 🟢 last friday    |
| 🔗 [matsuba](https://github.com/mrpicklepinosaur/matsuba) ⭐ 19 \| 🐛 24 \| 🌐 Rust \| 📅 2023-03-23                              | -              | -               | ⭐ 19   | 🔴 march 2023     |
| 🔗 [hujiang\_dictionary](https://github.com/asutorufa/hujiang_dictionary) ⭐ 72 \| 🐛 11 \| 🌐 Rust \| 📅 2026-08-11              | -              | -               | ⭐ 72   | 🟢 july           |
| 🔗 [mecab-dic-converter](https://github.com/tomokane/mecab-dic-converter) ⭐ 1 \| 🐛 2 \| 🌐 Rust \| 📅 2026-05-29                | -              | -               | ⭐ 1    | 🟡 may            |
| 🔗 [jp-deinflector](https://github.com/btrkeks/jp-deinflector) ⭐ 7 \| 🐛 2 \| 🌐 Rust \| 📅 2026-07-29                           | -              | -               | ⭐ 7    | 🟢 july           |

## JavaScript

### Morphology analysis

Japanese morphological analysis libraries for browser and Node.js

* [kuromoji.js](https://github.com/takuyaa/kuromoji.js) ⭐ 1,000 | 🐛 23 | 🌐 JavaScript | 📅 2023-11-12 - JavaScript implementation of Japanese morphological analyzer
* [rakutenma](https://github.com/rakuten-nlp/rakutenma) ⭐ 471 | 🐛 8 | 🌐 JavaScript | 📅 2019-02-02 -  Rakuten MA - morphological analyzer (word segmentor + PoS Tagger) for Chinese and Japanese written purely in JavaScript.
* [node-mecab-ya](https://github.com/golbin/node-mecab-ya) ⭐ 110 | 🐛 2 | 🌐 JavaScript | 📅 2022-10-20 - Yet another mecab wrapper for nodejs
* [node-mecab-async](https://github.com/hecomi/node-mecab-async) ⭐ 104 | 🐛 1 | 🌐 JavaScript | 📅 2023-07-24 - Asynchronous japanese morphological analyser using MeCab.
* [juman-bin](https://github.com/thammin/juman-bin) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2017-05-11 - a User-Extensible Morphological Analyzer for Japanese. 日本語形態素解析システム

| Name                                                                                                              | downloads/week | total downloads | stars | last commit      |
| ----------------------------------------------------------------------------------------------------------------- | -------------- | --------------- | ----- | ---------------- |
| 🔗 [kuromoji.js](https://github.com/takuyaa/kuromoji.js) ⭐ 1,000 \| 🐛 23 \| 🌐 JavaScript \| 📅 2023-11-12       | 📥 253k/week   | 📦 11M          | ⭐ 999 | 🔴 november 2018 |
| 🔗 [rakutenma](https://github.com/rakuten-nlp/rakutenma) ⭐ 471 \| 🐛 8 \| 🌐 JavaScript \| 📅 2019-02-02          | 📥 31/week     | 📦 1.1k         | ⭐ 471 | 🔴 january 2015  |
| 🔗 [node-mecab-ya](https://github.com/golbin/node-mecab-ya) ⭐ 110 \| 🐛 2 \| 🌐 JavaScript \| 📅 2022-10-20       | 📥 109/week    | 📦 7.7k         | ⭐ 110 | 🔴 june 2021     |
| 🔗 [juman-bin](https://github.com/thammin/juman-bin) ⭐ 3 \| 🐛 0 \| 🌐 JavaScript \| 📅 2017-05-11                | 📥 14/week     | 📦 467          | ⭐ 3   | 🔴 may 2017      |
| 🔗 [node-mecab-async](https://github.com/hecomi/node-mecab-async) ⭐ 104 \| 🐛 1 \| 🌐 JavaScript \| 📅 2023-07-24 | 📥 1.2k/week   | 📦 325k         | ⭐ 104 | 🔴 october 2017  |

### Converter

Libraries for converting Japanese scripts and readings

* [kuroshiro](https://github.com/hexenq/kuroshiro) ⭐ 987 | 🐛 49 | 🌐 JavaScript | 📅 2022-06-07 - Japanese language library for converting Japanese sentence to Hiragana, Katakana or Romaji with furigana and okurigana modes supported.
* [normalize-japanese-addresses](https://github.com/geolonia/normalize-japanese-addresses) ⭐ 959 | 🐛 34 | 🌐 TypeScript | 📅 2026-08-17 - オープンソースの住所正規化ライブラリ。
* [WanaKana](https://github.com/WaniKani/WanaKana) ⭐ 934 | 🐛 27 | 🌐 JavaScript | 📅 2026-06-29 - Javascript library for detecting and transliterating Hiragana <--> Katakana <--> Romaji
* [genshijin](https://github.com/interfacex-co-jp/genshijin) ⭐ 310 | 🐛 13 | 🌐 JavaScript | 📅 2026-08-15 - About
  genshijin 原始人 🗿| Claude Code / Codex等AIエージェント 向け超圧縮コミュニケーションスキル。caveman の日本語版をベースに、日本語特有の冗長表現に最適化。
* [japanese.js](https://github.com/hakatashi/japanese.js) ⭐ 167 | 🐛 21 | 🌐 JavaScript | 📅 2020-08-27 - Util collection for Japanese text processing. Hiraganize, Katakanize, and Romanize.
* [hepburn](https://github.com/lovell/hepburn) ⭐ 131 | 🐛 4 | 🌐 JavaScript | 📅 2026-07-21 - Node.js module for converting Japanese Hiragana and Katakana script to, and from, Romaji using Hepburn romanisation
* [jaconv](https://github.com/kazuhikoarase/jaconv) ⭐ 88 | 🐛 5 | 🌐 Java | 📅 2025-06-28 - 日本語文字変換ライブラリ (javascript)
* [japanese-addresses-v2](https://github.com/geolonia/japanese-addresses-v2) ⭐ 79 | 🐛 20 | 🌐 TypeScript | 📅 2026-08-20 - 全国の住所データAPI
* [kuroshiro-analyzer-kuromoji](https://github.com/hexenq/kuroshiro-analyzer-kuromoji) ⭐ 72 | 🐛 6 | 🌐 JavaScript | 📅 2022-02-20 - Kuromoji morphological analyzer for kuroshiro.
* [japanese-numerals-to-number](https://github.com/twada/japanese-numerals-to-number) ⭐ 59 | 🐛 1 | 🌐 JavaScript | 📅 2023-07-19 - Converts Japanese Numerals into number
* [jslingua](https://github.com/kariminf/jslingua) ⭐ 53 | 🐛 11 | 🌐 JavaScript | 📅 2023-10-19 - Javascript libraries to process text: Arabic, Japanese, etc.
* [node-romaji-name](https://github.com/jeresig/node-romaji-name) ⭐ 39 | 🐛 0 | 🌐 JavaScript | 📅 2023-12-27 - Normalize and fix common issues with Romaji-based Japanese names.
* [romaji-conv](https://github.com/koozaki/romaji-conv) ⭐ 25 | 🐛 7 | 🌐 JavaScript | 📅 2026-03-21 - Convert romaji into hiragana
* [kyujitai.js](https://github.com/hakatashi/kyujitai.js) ⭐ 23 | 🐛 0 | 🌐 JavaScript | 📅 2020-08-30 - Utility collections for making Japanese text old-fashioned
* [jptext-to-emoji](https://github.com/elzup/jptext-to-emoji) ⭐ 1 | 🐛 4 | 🌐 TypeScript | 📅 2026-06-11 - テキストの単語を絵文字に変換する

| Name                                                                                                                                         | downloads/week | total downloads | stars | last commit      |
| -------------------------------------------------------------------------------------------------------------------------------------------- | -------------- | --------------- | ----- | ---------------- |
| 🔗 [kuroshiro](https://github.com/hexenq/kuroshiro) ⭐ 987 \| 🐛 49 \| 🌐 JavaScript \| 📅 2022-06-07                                         | 📥 20k/week    | 📦 760k         | ⭐ 985 | 🔴 june 2021     |
| 🔗 [kuroshiro-analyzer-kuromoji](https://github.com/hexenq/kuroshiro-analyzer-kuromoji) ⭐ 72 \| 🐛 6 \| 🌐 JavaScript \| 📅 2022-02-20       | 📥 14k/week    | 📦 722k         | ⭐ 72  | 🔴 august 2018   |
| 🔗 [hepburn](https://github.com/lovell/hepburn) ⭐ 131 \| 🐛 4 \| 🌐 JavaScript \| 📅 2026-07-21                                              | 📥 79k/week    | 📦 6.3M         | ⭐ 131 | 🟢 july          |
| 🔗 [japanese-numerals-to-number](https://github.com/twada/japanese-numerals-to-number) ⭐ 59 \| 🐛 1 \| 🌐 JavaScript \| 📅 2023-07-19        | 📥 80k/week    | 📦 3M           | ⭐ 59  | 🔴 february 2023 |
| 🔗 [jslingua](https://github.com/kariminf/jslingua) ⭐ 53 \| 🐛 11 \| 🌐 JavaScript \| 📅 2023-10-19                                          | 📥 134/week    | 📦 10k          | ⭐ 53  | 🔴 october 2023  |
| 🔗 [WanaKana](https://github.com/WaniKani/WanaKana) ⭐ 934 \| 🐛 27 \| 🌐 JavaScript \| 📅 2026-06-29                                         | 📥 55k/week    | 📦 3.1M         | ⭐ 933 | 🟢 june          |
| 🔗 [node-romaji-name](https://github.com/jeresig/node-romaji-name) ⭐ 39 \| 🐛 0 \| 🌐 JavaScript \| 📅 2023-12-27                            | 📥 88/week     | 📦 20k          | ⭐ 39  | 🔴 december 2023 |
| 🔗 [kyujitai.js](https://github.com/hakatashi/kyujitai.js) ⭐ 23 \| 🐛 0 \| 🌐 JavaScript \| 📅 2020-08-30                                    | 📥 68/week     | 📦 2.3k         | ⭐ 23  | 🔴 august 2020   |
| 🔗 [normalize-japanese-addresses](https://github.com/geolonia/normalize-japanese-addresses) ⭐ 959 \| 🐛 34 \| 🌐 TypeScript \| 📅 2026-08-17 | -              | -               | ⭐ 959 | 🟢 august        |
| 🔗 [jaconv](https://github.com/kazuhikoarase/jaconv) ⭐ 88 \| 🐛 5 \| 🌐 Java \| 📅 2025-06-28                                                | -              | -               | ⭐ 88  | 🔴 june 2025     |
| 🔗 [romaji-conv](https://github.com/koozaki/romaji-conv) ⭐ 25 \| 🐛 7 \| 🌐 JavaScript \| 📅 2026-03-21                                      | -              | -               | ⭐ 25  | 🟡 february      |
| 🔗 [japanese-addresses-v2](https://github.com/geolonia/japanese-addresses-v2) ⭐ 79 \| 🐛 20 \| 🌐 TypeScript \| 📅 2026-08-20                | -              | -               | ⭐ 77  | 🟢 august        |
| 🔗 [jptext-to-emoji](https://github.com/elzup/jptext-to-emoji) ⭐ 1 \| 🐛 4 \| 🌐 TypeScript \| 📅 2026-06-11                                 | -              | -               | ⭐ 1   | 🟢 june          |
| 🔗 [japanese.js](https://github.com/hakatashi/japanese.js) ⭐ 167 \| 🐛 21 \| 🌐 JavaScript \| 📅 2020-08-27                                  | -              | -               | ⭐ 167 | 🔴 august 2020   |
| 🔗 [genshijin](https://github.com/interfacex-co-jp/genshijin) ⭐ 310 \| 🐛 13 \| 🌐 JavaScript \| 📅 2026-08-15                               | -              | -               | ⭐ 310 | 🟢 august        |

### Others

Other libraries for Japanese NLP in JavaScript

* [voicevox](https://github.com/VOICEVOX/voicevox) ⭐ 3,223 | 🐛 332 | 🌐 TypeScript | 📅 2026-08-09 - 無料で使える中品質なテキスト読み上げソフトウェア、VOICEVOXのエディター
* [yomichan](https://github.com/FooSoft/yomichan) ⚠️ Archived - Japanese pop-up dictionary extension for Chrome and Firefox.
* [japanese-analyzer](https://github.com/cokice/japanese-analyzer) ⭐ 787 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-02 - Japanese Sentence Analyzer (日本語文章解析器)
* [bangumi-data](https://github.com/bangumi-data/bangumi-data) ⭐ 635 | 🐛 6 | 🌐 JavaScript | 📅 2026-08-17 - Raw data for Japanese Anime
* [proofreading-tool](https://github.com/gecko655/proofreading-tool) ⚠️ Archived - GUIで動作する文書校正ツール GUI tool for textlinting.
* [japanese-toolkit](https://github.com/echamudi/japanese-toolkit) ⭐ 64 | 🐛 57 | 🌐 JavaScript | 📅 2023-03-05 - Monorepo for Kanji, Furigana, Japanese DB, and others
* [kanjigrid](https://github.com/minosvasilias/kanjigrid) ⭐ 45 | 🐛 0 | 🌐 JavaScript | 📅 2018-11-19 - A web-app displaying the 2200 kanji characters taught in James Heisig's "Remembering the Kanji", 6th edition.
* [hatsuon](https://github.com/DJTB/hatsuon) ⭐ 38 | 🐛 2 | 🌐 JavaScript | 📅 2023-03-07 - Japanese pitch accent utils
* [tweetMapping](https://github.com/wtnv-lab/tweetMapping) ⭐ 27 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-15 - 東日本大震災発生から24時間以内につぶやかれたジオタグ付きツイートのデジタルアーカイブです。
* [kamiya-codec](https://github.com/fasiha/kamiya-codec) ⭐ 26 | 🐛 7 | 🌐 JavaScript | 📅 2026-03-29 - Towards a Japanese verb conjugator and deconjugator based on Taeko Kamiya's *The Handbook of Japanese Verbs* and *The Handbook of Japanese Adjectives and Adverbs* opuses.
* [kana2ipa](https://github.com/amanoese/kana2ipa) ⭐ 19 | 🐛 12 | 🌐 JavaScript | 📅 2023-01-05 - 「ひらがな」または「カタカナ」を日本語で発音する際の音声記号(IPA)に変換するコマンド
* [analyze-desumasu-dearu](https://github.com/textlint-ja/analyze-desumasu-dearu) ⭐ 18 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-07 - 文の敬体(ですます調)、常体(である調)を解析するJavaScriptライブラリ
* [sudachi-synonyms-dictionary](https://github.com/azu/sudachi-synonyms-dictionary) ⭐ 15 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-26 - Sudachi's synonyms dictionary
* [sentiment\_ja\_js](https://github.com/otodn/sentiment_ja_js) ⭐ 10 | 🐛 0 | 🌐 JavaScript | 📅 2022-04-01 - Sentiment Analysis in Japanese. sentiment\_ja with JavaScript
* [mecab-ipadic-seed](https://github.com/takuyaa/mecab-ipadic-seed) ⭐ 8 | 🐛 0 | 🌐 JavaScript | 📅 2016-07-30 - mecab-ipadic seed dictionary reader
* [yama](https://github.com/sapjax/yama) ⭐ 7 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-11 - acquire Japanese vocabulary on any website
* [japanese-furigana-normalize](https://github.com/marvnc/japanese-furigana-normalize) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2024-07-07 - Normalize Japanese Furigana
* [tsukeru-furigana-converter](https://github.com/ln2058/tsukeru-furigana-converter) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-25 - Browser extension (Chrome/Edge/Firefox) that injects furigana into Japanese webpages on-demand; includes dictionary tooltips, JLPT filtering, and vocab/Anki export.
* [closewords](https://github.com/otoneko1102/closewords) ⭐ 5 | 🐛 6 | 🌐 TypeScript | 📅 2026-06-13 - 最も似た単語を単語群から検索する日本語(漢字含む)対応のライブラリ
* [qmd-ja](https://github.com/joycodetech/qmd-ja) ⭐ 3 | 🐛 10 | 🌐 TypeScript | 📅 2026-08-04 - Japanese-enhanced fork of qmd — Vaporetto WASM morphological tokenizer for accurate Japanese BM25 search
* [oskim](https://github.com/esrille/oskim) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2023-02-24 - Extend GNOME On-Screen Keyboard for Input Methods
* [pitch-accent](https://github.com/shirakaba/pitch-accent) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2023-09-07 - Predict pitch accent in Japanese
* [kaitai](https://github.com/compile10/kaitai) ⭐ 1 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-19 - An application for analyzing Japanese sentence structure using AI. This tool visualizes how words and phrases relate to each other, showing grammatical relationships with interactive diagrams.
* [shirabe-sdk](https://github.com/techwell-inc-jp/shirabe-sdk) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-17 - Official TypeScript SDK for the Shirabe Japan data APIs — ready-made Vercel AI SDK / LangChain tools for Japanese name splitting/reading, address normalization, corporate number lookup, and calendar (rokuyo). Zero runtime dependencies in the core.
* [pii-ja-ner-onnx-demo](https://github.com/shirokane-suri/pii-ja-ner-onnx-demo) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-21 - PII-JA NER Browser Demo
* [Japanese-Word-Of-The-Day](https://github.com/LuanRT/Japanese-Word-Of-The-Day) - Well, a different Japanese word everyday.

| Name                                                                                                                                  | downloads/week | total downloads | stars            | last commit       |
| ------------------------------------------------------------------------------------------------------------------------------------- | -------------- | --------------- | ---------------- | ----------------- |
| 🔗 [bangumi-data](https://github.com/bangumi-data/bangumi-data) ⭐ 635 \| 🐛 6 \| 🌐 JavaScript \| 📅 2026-08-17                       | 📥 1.6k/week   | 📦 62k          | ⭐ 635            | 🟢 last saturday  |
| 🔗 [yomichan](https://github.com/FooSoft/yomichan) ⚠️ Archived                                                                        | -              | -               | ⭐ 1.1k           | 🔴 february 2023  |
| 🔗 [proofreading-tool](https://github.com/gecko655/proofreading-tool) ⚠️ Archived                                                     | -              | -               | ⭐ 87             | 🟡 october 2025   |
| 🔗 [kanjigrid](https://github.com/minosvasilias/kanjigrid) ⭐ 45 \| 🐛 0 \| 🌐 JavaScript \| 📅 2018-11-19                             | -              | -               | ⭐ 45             | 🔴 november 2018  |
| 🔗 [japanese-toolkit](https://github.com/echamudi/japanese-toolkit) ⭐ 64 \| 🐛 57 \| 🌐 JavaScript \| 📅 2023-03-05                   | -              | -               | ⭐ 64             | 🔴 january 2023   |
| 🔗 [analyze-desumasu-dearu](https://github.com/textlint-ja/analyze-desumasu-dearu) ⭐ 18 \| 🐛 0 \| 🌐 TypeScript \| 📅 2026-04-07     | 📥 156k/week   | 📦 6.7M         | ⭐ 18             | 🟡 april          |
| 🔗 [hatsuon](https://github.com/DJTB/hatsuon) ⭐ 38 \| 🐛 2 \| 🌐 JavaScript \| 📅 2023-03-07                                          | 📥 30/week     | 📦 2.1k         | ⭐ 38             | 🔴 march 2022     |
| 🔗 [sentiment\_ja\_js](https://github.com/otodn/sentiment_ja_js) ⭐ 10 \| 🐛 0 \| 🌐 JavaScript \| 📅 2022-04-01                       | -              | -               | ⭐ 10             | 🔴 december 2021  |
| 🔗 [mecab-ipadic-seed](https://github.com/takuyaa/mecab-ipadic-seed) ⭐ 8 \| 🐛 0 \| 🌐 JavaScript \| 📅 2016-07-30                    | 📥 180/week    | 📦 8k           | ⭐ 8              | 🔴 july 2016      |
| 🔗 [Japanese-Word-Of-The-Day](https://github.com/LuanRT/Japanese-Word-Of-The-Day)                                                     | 📥 6/week      | 📦 303          | ⭐ repo not found | 🔴 repo not found |
| 🔗 [oskim](https://github.com/esrille/oskim) ⭐ 2 \| 🐛 0 \| 🌐 JavaScript \| 📅 2023-02-24                                            | -              | -               | ⭐ 2              | 🔴 february 2023  |
| 🔗 [tweetMapping](https://github.com/wtnv-lab/tweetMapping) ⭐ 27 \| 🐛 0 \| 🌐 JavaScript \| 📅 2026-06-15                            | -              | -               | ⭐ 27             | 🟡 march          |
| 🔗 [pitch-accent](https://github.com/shirakaba/pitch-accent) ⭐ 2 \| 🐛 0 \| 🌐 TypeScript \| 📅 2023-09-07                            | 📥 6/week      | 📦 172          | ⭐ 2              | 🔴 september 2023 |
| 🔗 [kana2ipa](https://github.com/amanoese/kana2ipa) ⭐ 19 \| 🐛 12 \| 🌐 JavaScript \| 📅 2023-01-05                                   | -              | -               | ⭐ 19             | 🔴 october 2020   |
| 🔗 [voicevox](https://github.com/VOICEVOX/voicevox) ⭐ 3,223 \| 🐛 332 \| 🌐 TypeScript \| 📅 2026-08-09                               | -              | -               | ⭐ 3.2k           | 🟢 august         |
| 🔗 [kamiya-codec](https://github.com/fasiha/kamiya-codec) ⭐ 26 \| 🐛 7 \| 🌐 JavaScript \| 📅 2026-03-29                              | -              | -               | ⭐ 26             | 🔴 may 2025       |
| 🔗 [closewords](https://github.com/otoneko1102/closewords) ⭐ 5 \| 🐛 6 \| 🌐 TypeScript \| 📅 2026-06-13                              | -              | -               | ⭐ 5              | 🟡 may            |
| 🔗 [japanese-analyzer](https://github.com/cokice/japanese-analyzer) ⭐ 787 \| 🐛 0 \| 🌐 TypeScript \| 📅 2026-08-02                   | -              | -               | ⭐ 786            | 🟢 august         |
| 🔗 [japanese-furigana-normalize](https://github.com/marvnc/japanese-furigana-normalize) ⭐ 6 \| 🐛 0 \| 🌐 TypeScript \| 📅 2024-07-07 | -              | -               | ⭐ 6              | 🔴 july 2024      |
| 🔗 [yama](https://github.com/sapjax/yama) ⭐ 7 \| 🐛 0 \| 🌐 TypeScript \| 📅 2026-02-11                                               | -              | -               | ⭐ 7              | 🟡 february       |
| 🔗 [kaitai](https://github.com/compile10/kaitai) ⭐ 1 \| 🐛 5 \| 🌐 TypeScript \| 📅 2026-08-19                                        | -              | -               | ⭐ 1              | 🟢 yesterday      |
| 🔗 [tsukeru-furigana-converter](https://github.com/ln2058/tsukeru-furigana-converter) ⭐ 6 \| 🐛 0 \| 🌐 JavaScript \| 📅 2026-05-25   | -              | -               | ⭐ 5              | 🟡 may            |
| 🔗 [sudachi-synonyms-dictionary](https://github.com/azu/sudachi-synonyms-dictionary) ⭐ 15 \| 🐛 0 \| 🌐 JavaScript \| 📅 2026-07-26   | -              | -               | ⭐ 15             | 🟢 july           |
| 🔗 [qmd-ja](https://github.com/joycodetech/qmd-ja) ⭐ 3 \| 🐛 10 \| 🌐 TypeScript \| 📅 2026-08-04                                     | -              | -               | ⭐ 3              | 🟢 june           |
| 🔗 [shirabe-sdk](https://github.com/techwell-inc-jp/shirabe-sdk) ⭐ 0 \| 🐛 0 \| 🌐 TypeScript \| 📅 2026-07-17                        | -              | -               | ⭐ 0              | 🟢 july           |
| 🔗 [pii-ja-ner-onnx-demo](https://github.com/shirokane-suri/pii-ja-ner-onnx-demo) ⭐ 0 \| 🐛 0 \| 🌐 TypeScript \| 📅 2026-07-21       | -              | -               | ⭐ 0              | 🟢 july           |

## Go

### Morphology analysis

Lightweight Japanese morphological analysis libraries in Go

* [kagome](https://github.com/ikawaha/kagome) ⭐ 979 | 🐛 0 | 🌐 Go | 📅 2026-07-30 - Self-contained Japanese Morphological Analyzer written in pure Go

| Name                                                                                   | downloads/week | total downloads | stars | last commit |
| -------------------------------------------------------------------------------------- | -------------- | --------------- | ----- | ----------- |
| 🔗 [kagome](https://github.com/ikawaha/kagome) ⭐ 979 \| 🐛 0 \| 🌐 Go \| 📅 2026-07-30 | -              | -               | ⭐ 977 | 🟢 july     |

### Others

Additional Go-based Japanese text processing libraries

* [ojichat](https://github.com/greymd/ojichat) ⭐ 1,274 | 🐛 3 | 🌐 Go | 📅 2024-10-14 - おじさんがLINEやメールで送ってきそうな文を生成する
* [ojosama](https://github.com/jiro4989/ojosama) ⭐ 388 | 🐛 13 | 🌐 Go | 📅 2026-08-19 - テキストを壱百満天原サロメお嬢様風の口調に変換します
* [yomichan-import](https://github.com/FooSoft/yomichan-import) ⚠️ Archived - External dictionary importer for Yomichan.
* [nihongo](https://github.com/gojp/nihongo) ⭐ 83 | 🐛 7 | 🌐 Go | 📅 2026-07-01 - Japanese Dictionary
* [imas-ime-dic](https://github.com/maruamyu/imas-ime-dic) ⭐ 32 | 🐛 2 | 🌐 Go | 📅 2026-01-01 - THE IDOLM\@STER words dictionary for Japanese IME (by imas-db.jp)
* [go-moji](https://github.com/ktnyt/go-moji) ⭐ 21 | 🐛 0 | 🌐 Go | 📅 2019-04-17 - A Go library for Zenkaku/Hankaku conversion
* [name](https://github.com/kuniwak/name) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2025-01-26 - Name Searcher in Japanese
* [go-kakasi](https://github.com/sarumaj/go-kakasi) ⭐ 6 | 🐛 2 | 🌐 Go | 📅 2026-08-11 - Kanji transliteration to hiragana/katakana/romaji, in Go
* [jp-pii-detector](https://github.com/baneido/jp-pii-detector) ⭐ 3 | 🐛 1 | 🌐 Go | 📅 2026-08-06 - 日本語個人情報検出器

| Name                                                                                                   | downloads/week | total downloads | stars  | last commit      |
| ------------------------------------------------------------------------------------------------------ | -------------- | --------------- | ------ | ---------------- |
| 🔗 [ojosama](https://github.com/jiro4989/ojosama) ⭐ 388 \| 🐛 13 \| 🌐 Go \| 📅 2026-08-19             | -              | -               | ⭐ 388  | 🟢 july          |
| 🔗 [nihongo](https://github.com/gojp/nihongo) ⭐ 83 \| 🐛 7 \| 🌐 Go \| 📅 2026-07-01                   | -              | -               | ⭐ 83   | 🟢 june          |
| 🔗 [yomichan-import](https://github.com/FooSoft/yomichan-import) ⚠️ Archived                           | -              | -               | ⭐ 88   | 🔴 february 2023 |
| 🔗 [imas-ime-dic](https://github.com/maruamyu/imas-ime-dic) ⭐ 32 \| 🐛 2 \| 🌐 Go \| 📅 2026-01-01     | -              | -               | ⭐ 32   | 🟡 january       |
| 🔗 [go-kakasi](https://github.com/sarumaj/go-kakasi) ⭐ 6 \| 🐛 2 \| 🌐 Go \| 📅 2026-08-11             | -              | -               | ⭐ 6    | 🟢 july          |
| 🔗 [go-moji](https://github.com/ktnyt/go-moji) ⭐ 21 \| 🐛 0 \| 🌐 Go \| 📅 2019-04-17                  | -              | -               | ⭐ 21   | 🔴 april 2019    |
| 🔗 [ojichat](https://github.com/greymd/ojichat) ⭐ 1,274 \| 🐛 3 \| 🌐 Go \| 📅 2024-10-14              | -              | -               | ⭐ 1.3k | 🔴 october 2024  |
| 🔗 [name](https://github.com/kuniwak/name) ⭐ 11 \| 🐛 0 \| 🌐 Go \| 📅 2025-01-26                      | -              | -               | ⭐ 11   | 🔴 january 2025  |
| 🔗 [jp-pii-detector](https://github.com/baneido/jp-pii-detector) ⭐ 3 \| 🐛 1 \| 🌐 Go \| 📅 2026-08-06 | -              | -               | ⭐ 3    | 🟢 august        |

## Java

### Morphology analysis

Japanese morphological analysis and dictionary management libraries

* [kuromoji](https://github.com/atilika/kuromoji) ⭐ 1,056 | 🐛 31 | 🌐 Java | 📅 2023-01-23 - Kuromoji is a self-contained and very easy to use Japanese morphological analyzer designed for search
* [Sudachi](https://github.com/WorksApplications/Sudachi) ⭐ 996 | 🐛 14 | 🌐 Java | 📅 2026-07-14 -　A Japanese Tokenizer for Business
* [SudachiDict](https://github.com/WorksApplications/SudachiDict) ⭐ 305 | 🐛 23 | 🌐 Python | 📅 2026-07-24 - A lexicon for Sudachi
* [meval](https://github.com/teru-oka-1933/meval) ⭐ 7 | 🐛 0 | 🌐 Java | 📅 2019-08-13 - 形態素解析器性能評価システム MevAL

| Name                                                                                                            | downloads/week | total downloads | stars  | last commit       |
| --------------------------------------------------------------------------------------------------------------- | -------------- | --------------- | ------ | ----------------- |
| 🔗 [kuromoji](https://github.com/atilika/kuromoji) ⭐ 1,056 \| 🐛 31 \| 🌐 Java \| 📅 2023-01-23                 | -              | -               | ⭐ 1.1k | 🔴 september 2019 |
| 🔗 [Sudachi](https://github.com/WorksApplications/Sudachi) ⭐ 996 \| 🐛 14 \| 🌐 Java \| 📅 2026-07-14           | -              | -               | ⭐ 995  | 🟢 july           |
| 🔗 [SudachiDict](https://github.com/WorksApplications/SudachiDict) ⭐ 305 \| 🐛 23 \| 🌐 Python \| 📅 2026-07-24 | -              | -               | ⭐ 305  | 🟢 july           |
| 🔗 [meval](https://github.com/teru-oka-1933/meval) ⭐ 7 \| 🐛 0 \| 🌐 Java \| 📅 2019-08-13                      | -              | -               | ⭐ 7    | 🔴 august 2019    |

### Others

Java libraries for Japanese NLP and OCR

* [elasticsearch-sudachi](https://github.com/worksapplications/elasticsearch-sudachi) ⭐ 220 | 🐛 14 | 🌐 Kotlin | 📅 2026-08-07 - The Japanese analysis plugin for elasticsearch
* [kanjitomo-ocr](https://github.com/sakarika/kanjitomo-ocr) ⭐ 204 | 🐛 4 | 🌐 Java | 📅 2021-05-03 - Java library for identifying Japanese characters from images
* [Kamite](https://github.com/fauu/Kamite) ⭐ 144 | 🐛 7 | 🌐 Java | 📅 2025-04-03 - A desktop language immersion companion for learners of Japanese
* [jakaroma](https://github.com/nicolas-raoul/jakaroma) ⭐ 70 | 🐛 10 | 🌐 Java | 📅 2025-06-02 - Java library and command-line tool to transliterate Japanese kanji to romaji (Latin alphabet)
* [kakasi-java](https://github.com/nicolas-raoul/kakasi-java) ⭐ 56 | 🐛 1 | 🌐 Java | 📅 2022-05-09 - Kanji transliteration to hiragana/katakana/romaji, in Java
* [react-native-japanese-tokenizer](https://github.com/craftzdog/react-native-japanese-tokenizer) ⭐ 40 | 🐛 0 | 🌐 Java | 📅 2023-06-19 - Async Japanese Tokenizer Native Plugin for React Native for iOS and Android
* [moji4j](https://github.com/andree-surya/moji4j) ⭐ 35 | 🐛 4 | 🌐 Java | 📅 2022-06-24 - A Java library to converts between Japanese Hiragana, Katakana, and Romaji scripts.
* [elasticsearch-analysis-japanese](https://github.com/suguru/elasticsearch-analysis-japanese) ⭐ 29 | 🐛 1 | 🌐 Java | 📅 2020-02-11 - Japanese analyzer uses kuromoji japanese tokenizer for ElasticSearch
* [neologdn-java](https://github.com/ikegami-yukino/neologdn-java) ⭐ 5 | 🐛 0 | 🌐 Java | 📅 2026-02-06 - Japanese text normalizer for mecab-neologd

| Name                                                                                                                                        | downloads/week | total downloads | stars | last commit   |
| ------------------------------------------------------------------------------------------------------------------------------------------- | -------------- | --------------- | ----- | ------------- |
| 🔗 [kanjitomo-ocr](https://github.com/sakarika/kanjitomo-ocr) ⭐ 204 \| 🐛 4 \| 🌐 Java \| 📅 2021-05-03                                     | -              | -               | ⭐ 204 | 🔴 may 2021   |
| 🔗 [jakaroma](https://github.com/nicolas-raoul/jakaroma) ⭐ 70 \| 🐛 10 \| 🌐 Java \| 📅 2025-06-02                                          | -              | -               | ⭐ 70  | 🔴 june 2025  |
| 🔗 [kakasi-java](https://github.com/nicolas-raoul/kakasi-java) ⭐ 56 \| 🐛 1 \| 🌐 Java \| 📅 2022-05-09                                     | -              | -               | ⭐ 56  | 🔴 april 2016 |
| 🔗 [Kamite](https://github.com/fauu/Kamite) ⭐ 144 \| 🐛 7 \| 🌐 Java \| 📅 2025-04-03                                                       | -              | -               | ⭐ 144 | 🔴 march 2025 |
| 🔗 [react-native-japanese-tokenizer](https://github.com/craftzdog/react-native-japanese-tokenizer) ⭐ 40 \| 🐛 0 \| 🌐 Java \| 📅 2023-06-19 | -              | -               | ⭐ 40  | 🔴 june 2023  |
| 🔗 [elasticsearch-analysis-japanese](https://github.com/suguru/elasticsearch-analysis-japanese) ⭐ 29 \| 🐛 1 \| 🌐 Java \| 📅 2020-02-11    | -              | -               | ⭐ 29  | 🔴 march 2012 |
| 🔗 [moji4j](https://github.com/andree-surya/moji4j) ⭐ 35 \| 🐛 4 \| 🌐 Java \| 📅 2022-06-24                                                | -              | -               | ⭐ 35  | 🔴 june 2022  |
| 🔗 [neologdn-java](https://github.com/ikegami-yukino/neologdn-java) ⭐ 5 \| 🐛 0 \| 🌐 Java \| 📅 2026-02-06                                 | -              | -               | ⭐ 5   | 🟡 february   |
| 🔗 [elasticsearch-sudachi](https://github.com/worksapplications/elasticsearch-sudachi) ⭐ 220 \| 🐛 14 \| 🌐 Kotlin \| 📅 2026-08-07         | -              | -               | ⭐ 220 | 🟢 june       |

## Pretrained model

### Word2Vec

Models that convert words into numeric vectors to capture semantic similarity

* [chiVe](https://github.com/WorksApplications/chiVe) ⭐ 178 | 🐛 0 | 🌐 Python | 📅 2024-03-01 - Japanese word embedding with Sudachi and NWJC
* [japanese-words-to-vectors](https://github.com/philipperemy/japanese-words-to-vectors) ⭐ 87 | 🐛 0 | 🌐 Python | 📅 2022-01-25 - Word2vec (word to vectors) approach for Japanese language using Gensim and Mecab.
* [embedrank](https://github.com/yagays/embedrank) ⭐ 48 | 🐛 1 | 🌐 Python | 📅 2019-03-19 - Python Implementation of EmbedRank
* [jawiki\_word\_vector\_updater](https://github.com/kamigaito/jawiki_word_vector_updater) ⭐ 11 | 🐛 0 | 🌐 Shell | 📅 2020-05-06 - 最新の日本語Wikipediaのダンプデータから，MeCabを用いてIPA辞書と最新のNeologd辞書の両方で形態素解析を実施し，その結果に基づいた word2vec，fastText，GloVeの単語分散表現を学習するためのスクリプト
* [dependency-based-japanese-word-embeddings](https://github.com/lapras-inc/dependency-based-japanese-word-embeddings) ⭐ 8 | 🐛 0 | 📅 2019-08-14 - This is a repository for the AI LAB article "係り受けに基づく日本語単語埋込 (Dependency-based Japanese Word Embeddings)" ( Article URL <https://ai-lab.lapras.com/nlp/japanese-word-embedding/>)
* [elmo-japanese](https://github.com/cl-tohoku/elmo-japanese) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2019-10-07 - elmo-japanese
* [aovec](https://github.com/eggplants/aovec) ⚠️ Archived - Easy aozorabunko Word2Vec Builder - 青空文庫全書籍のWord2Vecビルダー+構築済みモデル
* [jawikivec](https://github.com/wikiwikification/jawikivec) ⭐ 2 | 🐛 0 | 📅 2018-11-24 - Yet Another Japanese-Wikipedia Entity Vectors

| Name                                                                                                                                                 | downloads/week | total downloads | stars | last commit      |
| ---------------------------------------------------------------------------------------------------------------------------------------------------- | -------------- | --------------- | ----- | ---------------- |
| 🔗 [japanese-words-to-vectors](https://github.com/philipperemy/japanese-words-to-vectors) ⭐ 87 \| 🐛 0 \| 🌐 Python \| 📅 2022-01-25                 | -              | -               | ⭐ 87  | 🔴 august 2020   |
| 🔗 [chiVe](https://github.com/WorksApplications/chiVe) ⭐ 178 \| 🐛 0 \| 🌐 Python \| 📅 2024-03-01                                                   | -              | -               | ⭐ 178 | 🔴 march 2024    |
| 🔗 [elmo-japanese](https://github.com/cl-tohoku/elmo-japanese) ⭐ 4 \| 🐛 0 \| 🌐 Python \| 📅 2019-10-07                                             | -              | -               | ⭐ 4   | 🔴 october 2019  |
| 🔗 [embedrank](https://github.com/yagays/embedrank) ⭐ 48 \| 🐛 1 \| 🌐 Python \| 📅 2019-03-19                                                       | -              | -               | ⭐ 48  | 🔴 march 2019    |
| 🔗 [aovec](https://github.com/eggplants/aovec) ⚠️ Archived                                                                                           | 📥 196         | 📦 87k          | ⭐ 3   | 🔴 january 2023  |
| 🔗 [dependency-based-japanese-word-embeddings](https://github.com/lapras-inc/dependency-based-japanese-word-embeddings) ⭐ 8 \| 🐛 0 \| 📅 2019-08-14 | -              | -               | ⭐ 8   | 🔴 august 2019   |
| 🔗 [jawikivec](https://github.com/wikiwikification/jawikivec) ⭐ 2 \| 🐛 0 \| 📅 2018-11-24                                                           | -              | -               | ⭐ 2   | 🔴 november 2018 |
| 🔗 [jawiki\_word\_vector\_updater](https://github.com/kamigaito/jawiki_word_vector_updater) ⭐ 11 \| 🐛 0 \| 🌐 Shell \| 📅 2020-05-06                | -              | -               | ⭐ 11  | 🔴 may 2020      |

### Transformer based models

Models that use self-attention to understand context and perform advanced language tasks

* [luke](https://github.com/studio-ousia/luke) ⭐ 725 | 🐛 14 | 🌐 Jupyter Notebook | 📅 2023-11-19 - LUKE -- Language Understanding with Knowledge-based Embeddings
* [bert-japanese](https://github.com/cl-tohoku/bert-japanese) ⭐ 551 | 🐛 15 | 🌐 Python | 📅 2024-03-23 - BERT models for Japanese text.
* [bert-japanese](https://github.com/yoheikikuta/bert-japanese) ⭐ 497 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2021-02-15 - BERT with SentencePiece for Japanese text.
* [gpt2-japanese](https://github.com/tanreinama/gpt2-japanese) ⭐ 323 | 🐛 0 | 🌐 Python | 📅 2023-09-02 - Japanese GPT2 Generation Model
* [japanese-dialog-transformers](https://github.com/nttcslab/japanese-dialog-transformers) ⭐ 246 | 🐛 2 | 🌐 Python | 📅 2023-06-21 - Code for evaluating Japanese pretrained models provided by NTT Ltd.
* [DistilBERT-base-jp](https://github.com/BandaiNamcoResearchInc/DistilBERT-base-jp) ⭐ 161 | 🐛 1 | 📅 2020-10-19 - A Japanese DistilBERT pretrained model, which was trained on Wikipedia.
* [Japanese-Alpaca-LoRA](https://github.com/kunishou/Japanese-Alpaca-LoRA) ⭐ 141 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2023-04-02 - 日本語に翻訳したStanford Alpacaのデータセットを用いてLLaMAをファインチューニングし作成したLow-Rank AdapterのリンクとGenerateサンプルコード
* [GPTSAN](https://github.com/tanreinama/GPTSAN) ⭐ 119 | 🐛 2 | 🌐 Python | 📅 2023-09-13 - General-purpose Swich transformer based Japanese language mode
* [ja\_text\_bert](https://github.com/Kosuke-Szk/ja_text_bert) ⭐ 114 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2018-11-08 - 日本語WikipediaコーパスでBERTのPre-Trainedモデルを生成するためのリポジトリ
* [shiba](https://github.com/octanove/shiba) ⭐ 89 | 🐛 1 | 🌐 Python | 📅 2023-11-03 - Pytorch implementation and pre-trained Japanese model for CANINE, the efficient character-level transformer.
* [SudachiTra](https://github.com/WorksApplications/SudachiTra) ⭐ 81 | 🐛 9 | 🌐 Python | 📅 2023-12-15 - Japanese tokenizer for Transformers
* [Laboro-BERT-Japanese](https://github.com/laboroai/Laboro-BERT-Japanese) ⭐ 73 | 🐛 1 | 🌐 Python | 📅 2022-05-12 - Laboro BERT Japanese: Japanese BERT Pre-Trained With Web-Corpus
* [Dialog](https://github.com/reppy4620/Dialog) ⭐ 72 | 🐛 1 | 🌐 Python | 📅 2021-11-18 - A PyTorch Implementation of japanese chatbot using BERT and Transformer's decoder
* [japanese-llama-experiment](https://github.com/lighttransport/japanese-llama-experiment) ⭐ 54 | 🐛 9 | 🌐 C | 📅 2025-12-27 - Japanese LLaMa experiment
* [language-pretraining](https://github.com/retarfi/language-pretraining) ⭐ 50 | 🐛 1 | 🌐 Python | 📅 2023-07-02 - BERT and ELECTRA models of PyTorch implementations for Japanese text.
* [LINE-DistilBERT-Japanese](https://github.com/line/LINE-DistilBERT-Japanese) ⭐ 47 | 🐛 0 | 📅 2023-03-22 - DistilBERT model pre-trained on 131 GB of Japanese web text. The teacher model is BERT-base that built in-house at LINE.
* [easylightchatassistant](https://github.com/zuntan03/easylightchatassistant) ⭐ 45 | 🐛 5 | 🌐 Batchfile | 📅 2024-04-23 - EasyLightChatAssistant は軽量で検閲や規制のないローカル日本語モデルのLightChatAssistant を、KoboldCpp で簡単にお試しする環境です。
* [t5-japanese](https://github.com/megagonlabs/t5-japanese) ⭐ 40 | 🐛 1 | 🌐 Python | 📅 2021-09-07 - Codes to pre-train Japanese T5 models
* [bert-japanese-aozora](https://github.com/akirakubo/bert-japanese-aozora) ⭐ 40 | 🐛 0 | 📅 2020-08-08 - Japanese BERT trained on Aozora Bunko and Wikipedia, pre-tokenized by MeCab with UniDic & SudachiPy
* [pytorch\_bert\_japanese](https://github.com/yagays/pytorch_bert_japanese) ⭐ 35 | 🐛 3 | 🌐 Python | 📅 2020-08-20 - PytorchでBERTの日本語学習済みモデルを利用する
* [text2text-japanese](https://github.com/tanreinama/text2text-japanese) ⭐ 34 | 🐛 0 | 🌐 Python | 📅 2021-07-22 - gpt-2 based text2text conversion model
* [albert-japanese](https://github.com/alinear-corp/albert-japanese) ⭐ 33 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2021-10-28 - BERT with SentencePiece for Japanese text.
* [bert](https://github.com/informatix-inc/bert) ⭐ 28 | 🐛 1 | 🌐 Python | 📅 2022-04-05 - This repository provides snippets to use RoBERTa pre-trained on Japanese corpus. Our dataset consists of Japanese Wikipedia and web-scrolled articles, 25GB in total. The released model is built based on that from HuggingFace.
* [ILYS-aoba-chatbot](https://github.com/cl-tohoku/ILYS-aoba-chatbot) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2021-10-01 - ILYS-aoba-chatbot
* [RoBERTa-japanese](https://github.com/tanreinama/RoBERTa-japanese) ⭐ 23 | 🐛 1 | 🌐 Python | 📅 2021-11-13 - Japanese BERT Pretrained Model
* [aMLP-japanese](https://github.com/tanreinama/aMLP-japanese) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2022-05-10 - aMLP Transformer Model for Japanese
* [Laboro-DistilBERT-Japanese](https://github.com/laboroai/Laboro-DistilBERT-Japanese) ⭐ 16 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2020-12-17 - Laboro DistilBERT Japanese
* [medbertjp](https://github.com/ou-medinfo/medbertjp) ⭐ 13 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2020-11-21 - Trials of pre-trained BERT models for the medical domain in Japanese.
* [albert-japanese-tinysegmenter](https://github.com/nknytk/albert-japanese-tinysegmenter) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2023-09-26 - Pretrained models, codes and guidances to pretrain official ALBERT(<https://github.com/google-research/albert> ⚠️ Archived) on Japanese Wikipedia Resources
* [sbert-ja](https://github.com/colorfulscoop/sbert-ja) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2021-08-08 - Code to train Sentence BERT Japanese model for Hugging Face Model Hub
* [AcademicRoBERTa](https://github.com/EhimeNLP/AcademicRoBERTa) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2024-09-03 - We pretrained a RoBERTa-based Japanese masked language model on paper abstracts from the academic database CiNii Articles.
* [BERT-Japan-vaccination](https://github.com/PatrickJohnRamos/BERT-Japan-vaccination) ⭐ 7 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2022-05-22 - Official fine-tuning code for "Emotion Analysis of Japanese Tweets and Comparison to Vaccinations in Japan"
* [gpt-ja](https://github.com/colorfulscoop/gpt-ja) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2021-09-27 - GPT-2 Japanese model for HuggingFace's transformers
* [AcademicBART](https://github.com/EhimeNLP/AcademicBART) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2024-07-11 - We pretrained a BART-based Japanese masked language model on paper abstracts from the academic database CiNii Articles
* [friendly\_JA-Model](https://github.com/astremo/friendly_JA-Model) ⭐ 1 | 🐛 0 | 📅 2022-05-22 - MT model trained using the friendly\_JA Corpus attempting to make Japanese easier/more accessible to occidental people by using the Latin/English derived katakana lexicon instead of the standard Sino-Japanese lexicon
* [japanese-pretrained-models](https://github.com/rinnakk/japanese-pretrained-models) - Code for producing Japanese pretrained models provided by rinna Co., Ltd.
* [japanese-clip](https://github.com/rinnakk/japanese-clip) - Japanese CLIP by rinna Co., Ltd.

| Name                                                                                                                                         | downloads/week | total downloads | stars            | last commit       |
| -------------------------------------------------------------------------------------------------------------------------------------------- | -------------- | --------------- | ---------------- | ----------------- |
| 🔗 [bert-japanese](https://github.com/cl-tohoku/bert-japanese) ⭐ 551 \| 🐛 15 \| 🌐 Python \| 📅 2024-03-23                                  | -              | -               | ⭐ 551            | 🔴 march 2024     |
| 🔗 [japanese-pretrained-models](https://github.com/rinnakk/japanese-pretrained-models)                                                       | -              | -               | ⭐ repo not found | 🔴 repo not found |
| 🔗 [bert-japanese](https://github.com/yoheikikuta/bert-japanese) ⭐ 497 \| 🐛 1 \| 🌐 Jupyter Notebook \| 📅 2021-02-15                       | -              | -               | ⭐ 497            | 🔴 february 2021  |
| 🔗 [SudachiTra](https://github.com/WorksApplications/SudachiTra) ⭐ 81 \| 🐛 9 \| 🌐 Python \| 📅 2023-12-15                                  | 📥 218         | 📦 206k         | ⭐ 81             | 🔴 december 2023  |
| 🔗 [japanese-dialog-transformers](https://github.com/nttcslab/japanese-dialog-transformers) ⭐ 246 \| 🐛 2 \| 🌐 Python \| 📅 2023-06-21      | -              | -               | ⭐ 246            | 🔴 june 2023      |
| 🔗 [shiba](https://github.com/octanove/shiba) ⭐ 89 \| 🐛 1 \| 🌐 Python \| 📅 2023-11-03                                                     | 📥 6           | 📦 9k           | ⭐ 89             | 🔴 november 2023  |
| 🔗 [Dialog](https://github.com/reppy4620/Dialog) ⭐ 72 \| 🐛 1 \| 🌐 Python \| 📅 2021-11-18                                                  | -              | -               | ⭐ 72             | 🔴 october 2020   |
| 🔗 [language-pretraining](https://github.com/retarfi/language-pretraining) ⭐ 50 \| 🐛 1 \| 🌐 Python \| 📅 2023-07-02                        | -              | -               | ⭐ 50             | 🔴 may 2023       |
| 🔗 [medbertjp](https://github.com/ou-medinfo/medbertjp) ⭐ 13 \| 🐛 1 \| 🌐 Jupyter Notebook \| 📅 2020-11-21                                 | -              | -               | ⭐ 13             | 🔴 november 2020  |
| 🔗 [ILYS-aoba-chatbot](https://github.com/cl-tohoku/ILYS-aoba-chatbot) ⭐ 23 \| 🐛 0 \| 🌐 Python \| 📅 2021-10-01                            | -              | -               | ⭐ 23             | 🔴 october 2021   |
| 🔗 [t5-japanese](https://github.com/megagonlabs/t5-japanese) ⭐ 40 \| 🐛 1 \| 🌐 Python \| 📅 2021-09-07                                      | -              | -               | ⭐ 40             | 🔴 september 2021 |
| 🔗 [pytorch\_bert\_japanese](https://github.com/yagays/pytorch_bert_japanese) ⭐ 35 \| 🐛 3 \| 🌐 Python \| 📅 2020-08-20                     | -              | -               | ⭐ 35             | 🔴 june 2019      |
| 🔗 [Laboro-BERT-Japanese](https://github.com/laboroai/Laboro-BERT-Japanese) ⭐ 73 \| 🐛 1 \| 🌐 Python \| 📅 2022-05-12                       | -              | -               | ⭐ 73             | 🔴 may 2022       |
| 🔗 [RoBERTa-japanese](https://github.com/tanreinama/RoBERTa-japanese) ⭐ 23 \| 🐛 1 \| 🌐 Python \| 📅 2021-11-13                             | -              | -               | ⭐ 23             | 🔴 november 2021  |
| 🔗 [aMLP-japanese](https://github.com/tanreinama/aMLP-japanese) ⭐ 16 \| 🐛 0 \| 🌐 Python \| 📅 2022-05-10                                   | -              | -               | ⭐ 16             | 🔴 may 2022       |
| 🔗 [bert-japanese-aozora](https://github.com/akirakubo/bert-japanese-aozora) ⭐ 40 \| 🐛 0 \| 📅 2020-08-08                                   | -              | -               | ⭐ 40             | 🔴 august 2020    |
| 🔗 [sbert-ja](https://github.com/colorfulscoop/sbert-ja) ⭐ 11 \| 🐛 0 \| 🌐 Python \| 📅 2021-08-08                                          | -              | -               | ⭐ 11             | 🔴 august 2021    |
| 🔗 [BERT-Japan-vaccination](https://github.com/PatrickJohnRamos/BERT-Japan-vaccination) ⭐ 7 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2022-05-22  | -              | -               | ⭐ 7              | 🔴 may 2022       |
| 🔗 [gpt2-japanese](https://github.com/tanreinama/gpt2-japanese) ⭐ 323 \| 🐛 0 \| 🌐 Python \| 📅 2023-09-02                                  | -              | -               | ⭐ 323            | 🔴 september 2023 |
| 🔗 [text2text-japanese](https://github.com/tanreinama/text2text-japanese) ⭐ 34 \| 🐛 0 \| 🌐 Python \| 📅 2021-07-22                         | -              | -               | ⭐ 34             | 🔴 july 2021      |
| 🔗 [gpt-ja](https://github.com/colorfulscoop/gpt-ja) ⭐ 3 \| 🐛 0 \| 🌐 Python \| 📅 2021-09-27                                               | -              | -               | ⭐ 3              | 🔴 september 2021 |
| 🔗 [friendly\_JA-Model](https://github.com/astremo/friendly_JA-Model) ⭐ 1 \| 🐛 0 \| 📅 2022-05-22                                           | -              | -               | ⭐ 1              | 🔴 may 2022       |
| 🔗 [albert-japanese](https://github.com/alinear-corp/albert-japanese) ⭐ 33 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2021-10-28                   | -              | -               | ⭐ 33             | 🔴 october 2021   |
| 🔗 [ja\_text\_bert](https://github.com/Kosuke-Szk/ja_text_bert) ⭐ 114 \| 🐛 1 \| 🌐 Jupyter Notebook \| 📅 2018-11-08                        | -              | -               | ⭐ 114            | 🔴 november 2018  |
| 🔗 [DistilBERT-base-jp](https://github.com/BandaiNamcoResearchInc/DistilBERT-base-jp) ⭐ 161 \| 🐛 1 \| 📅 2020-10-19                         | -              | -               | ⭐ 161            | 🔴 april 2020     |
| 🔗 [bert](https://github.com/informatix-inc/bert) ⭐ 28 \| 🐛 1 \| 🌐 Python \| 📅 2022-04-05                                                 | -              | -               | ⭐ 28             | 🔴 april 2022     |
| 🔗 [Laboro-DistilBERT-Japanese](https://github.com/laboroai/Laboro-DistilBERT-Japanese) ⭐ 16 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2020-12-17 | -              | -               | ⭐ 16             | 🔴 december 2020  |
| 🔗 [luke](https://github.com/studio-ousia/luke) ⭐ 725 \| 🐛 14 \| 🌐 Jupyter Notebook \| 📅 2023-11-19                                       | -              | -               | ⭐ 725            | 🔴 june 2023      |
| 🔗 [GPTSAN](https://github.com/tanreinama/GPTSAN) ⭐ 119 \| 🐛 2 \| 🌐 Python \| 📅 2023-09-13                                                | -              | -               | ⭐ 119            | 🔴 september 2023 |
| 🔗 [japanese-clip](https://github.com/rinnakk/japanese-clip)                                                                                 | -              | -               | ⭐ repo not found | 🔴 repo not found |
| 🔗 [AcademicBART](https://github.com/EhimeNLP/AcademicBART) ⭐ 2 \| 🐛 0 \| 🌐 Python \| 📅 2024-07-11                                        | -              | -               | ⭐ 2              | 🔴 july 2024      |
| 🔗 [AcademicRoBERTa](https://github.com/EhimeNLP/AcademicRoBERTa) ⭐ 10 \| 🐛 0 \| 🌐 Python \| 📅 2024-09-03                                 | -              | -               | ⭐ 10             | 🔴 september 2024 |
| 🔗 [LINE-DistilBERT-Japanese](https://github.com/line/LINE-DistilBERT-Japanese) ⭐ 47 \| 🐛 0 \| 📅 2023-03-22                                | -              | -               | ⭐ 47             | 🔴 march 2023     |
| 🔗 [Japanese-Alpaca-LoRA](https://github.com/kunishou/Japanese-Alpaca-LoRA) ⭐ 141 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2023-04-02            | -              | -               | ⭐ 141            | 🔴 april 2023     |
| 🔗 [albert-japanese-tinysegmenter](https://github.com/nknytk/albert-japanese-tinysegmenter) ⭐ 13 \| 🐛 1 \| 🌐 Python \| 📅 2023-09-26       | -              | -               | ⭐ 13             | 🔴 september 2023 |
| 🔗 [japanese-llama-experiment](https://github.com/lighttransport/japanese-llama-experiment) ⭐ 54 \| 🐛 9 \| 🌐 C \| 📅 2025-12-27            | -              | -               | ⭐ 54             | 🟡 december 2025  |
| 🔗 [easylightchatassistant](https://github.com/zuntan03/easylightchatassistant) ⭐ 45 \| 🐛 5 \| 🌐 Batchfile \| 📅 2024-04-23                | -              | -               | ⭐ 45             | 🔴 april 2024     |

## ChatGPT

Resources for using ChatGPT and APIs for Japanese dialogue and text generation

* [ChatdollKit](https://github.com/uezo/ChatdollKit) ⭐ 1,212 | 🐛 32 | 🌐 C# | 📅 2026-03-11 - ChatdollKit enables you to make your 3D model into a chatbot
* [chatvrm](https://github.com/pixiv/chatvrm) ⚠️ Archived - ChatVRMはブラウザで簡単に3Dキャラクターと会話ができるデモアプリケーションです。
* [aiavatarkit](https://github.com/uezo/aiavatarkit) ⭐ 656 | 🐛 6 | 🌐 Python | 📅 2026-08-18 - Building AI-based conversational avatars lightning fast
* [chatgpt-prompt-sample-japanese](https://github.com/dahatake/chatgpt-prompt-sample-japanese) ⭐ 434 | 🐛 0 | 🌐 HTML | 📅 2026-08-16 - ChatGPT の Prompt のサンプルです。
* [generativeai-prompt-sample-japanese](https://github.com/dahatake/generativeai-prompt-sample-japanese) ⭐ 434 | 🐛 0 | 🌐 HTML | 📅 2026-08-16 - ChatGPTやCopilotなど各種生成AI用の「日本語]の Prompt のサンプル
* [jp-azureopenai-samples](https://github.com/azure-samples/jp-azureopenai-samples) ⚠️ Archived - Azure OpenAIを活用したアプリケーション実装のリファレンスを目的として、アプリのサンプル（リファレンスアーキテクチャ、サンプルコードとデプロイ手順）を無償提供しています。
* [summarize\_arxv](https://github.com/rkmt/summarize_arxv) ⭐ 173 | 🐛 1 | 🌐 Python | 📅 2023-05-22 - Summarize arXiv paper with figures
* [wanna](https://github.com/hirokidaichi/wanna) ⭐ 142 | 🐛 1 | 🌐 Python | 📅 2023-04-02 - Shell command launcher with natural language
* [chatgpt-slackbot](https://github.com/sifue/chatgpt-slackbot) ⭐ 64 | 🐛 0 | 🌐 Python | 📅 2024-07-22 - OpenAIのChatGPT APIをSlack上で利用するためのSlackbotスクリプト (日本語での利用が前提)
* [gptuber-by-langchain](https://github.com/karakuri-ai/gptuber-by-langchain) ⭐ 63 | 🐛 0 | 🌐 Python | 📅 2023-12-15 - GPTがYouTuberをやります
* [IgakuQA](https://github.com/jungokasai/IgakuQA) ⭐ 52 | 🐛 1 | 🌐 Python | 📅 2023-03-31 - Evaluating GPT-4 and ChatGPT on Japanese Medical Licensing Examinations
* [azure-search-openai-demo](https://github.com/nohanaga/azure-search-openai-demo) ⭐ 46 | 🐛 0 | 🌐 Python | 📅 2024-04-18 - このサンプルでは、Retrieval Augmented Generation パターンを使用して、独自のデータに対してChatGPT のような体験を作成するためのいくつかのアプローチを示しています。
* [vrchatbot](https://github.com/Geson-anko/vrchatbot) ⭐ 30 | 🐛 2 | 🌐 Python | 📅 2022-12-20 - VRChatにAI Botを作るためのリポジトリ
* [AISisterAIChan](https://github.com/manju-summoner/AISisterAIChan) ⭐ 27 | 🐛 0 | 🌐 C# | 📅 2023-05-18 - ChatGPT3.5を搭載した伺かゴースト「AI妹アイちゃん」です。利用には別途ChatGPTのAPIキーが必要です。
* [character\_chat](https://github.com/mutaguchi/character_chat) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2023-06-03 - OpenAIのAPIを利用して、設定したキャラクターと日本語で会話するチャットスクリプトです。
* [openai-chatfriend](https://github.com/supershaneski/openai-chatfriend) ⭐ 16 | 🐛 0 | 🌐 Vue | 📅 2023-04-03 - A chatbox application built using Nuxt 3 powered by Open AI Text completion endpoint. You can select different personality of your AI friend. The default will respond in Japanese. You can use this app to practice your Nihongo skills!
* [VRChatGPT](https://github.com/Yuchi-Games/VRChatGPT) ⚠️ Archived - ChatGPTを使ってVRChat上でお喋り出来るようにするプログラム。
* [AITuberDegikkoMirii](https://github.com/M-gen/AITuberDegikkoMirii) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2023-03-17 - AITuberの基礎となる部分を開発しています
* [kanji-flashcard-app-gpt4](https://github.com/adilmoujahid/kanji-flashcard-app-gpt4) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2023-10-17 - A Japanese Kanji Flashcard App built using Python and Langchain, enhanced with the intelligence of GPT-4.
* [sftly-replace](https://github.com/kmizu/sftly-replace) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2023-05-23 - A Chrome extention to replace the selected text softly
* [ChuanhuChatGPTJapanese](https://github.com/gyokuro33/ChuanhuChatGPTJapanese) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2023-03-07 - GUI for ChatGPT API For Japanese
* [chrome-ext-translate-to-hiragana-with-chatgpt](https://github.com/franzwong/chrome-ext-translate-to-hiragana-with-chatgpt) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2023-04-01 - This Chrome extension can translate selected Japanese text to Hiragana by using ChatGPT.
* [japagen](https://github.com/retrieva/japagen) ⭐ 1 | 🐛 0 | 📅 2024-10-31 - 日本語タスクにおけるLLMを用いた疑似学習データ生成の検討
* [pva-aoai-integration-solution](https://github.com/City-of-Kobe/pva-aoai-integration-solution) - このリポジトリは、神戸市役所でのChatGPTの試行利用に向けて作成したフロー等をソリューション化し公開するものです。

| Name                                                                                                                                                                         | downloads/week | total downloads | stars            | last commit       |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------- | --------------- | ---------------- | ----------------- |
| 🔗 [VRChatGPT](https://github.com/Yuchi-Games/VRChatGPT) ⚠️ Archived                                                                                                         | -              | -               | ⭐ 15             | 🔴 march 2023     |
| 🔗 [AITuberDegikkoMirii](https://github.com/M-gen/AITuberDegikkoMirii) ⭐ 5 \| 🐛 0 \| 🌐 C# \| 📅 2023-03-17                                                                 | -              | -               | ⭐ 5              | 🔴 march 2023     |
| 🔗 [wanna](https://github.com/hirokidaichi/wanna) ⭐ 142 \| 🐛 1 \| 🌐 Python \| 📅 2023-04-02                                                                                | 📥 70          | 📦 21k          | ⭐ 142            | 🔴 april 2023     |
| 🔗 [ChatdollKit](https://github.com/uezo/ChatdollKit) ⭐ 1,212 \| 🐛 32 \| 🌐 C# \| 📅 2026-03-11                                                                             | -              | -               | ⭐ 1.2k           | 🟡 march          |
| 🔗 [ChuanhuChatGPTJapanese](https://github.com/gyokuro33/ChuanhuChatGPTJapanese) ⭐ 1 \| 🐛 0 \| 🌐 Python \| 📅 2023-03-07                                                   | -              | -               | ⭐ 1              | 🔴 march 2023     |
| 🔗 [AISisterAIChan](https://github.com/manju-summoner/AISisterAIChan) ⭐ 27 \| 🐛 0 \| 🌐 C# \| 📅 2023-05-18                                                                 | -              | -               | ⭐ 27             | 🔴 may 2023       |
| 🔗 [vrchatbot](https://github.com/Geson-anko/vrchatbot) ⭐ 30 \| 🐛 2 \| 🌐 Python \| 📅 2022-12-20                                                                           | -              | -               | ⭐ 30             | 🔴 december 2022  |
| 🔗 [gptuber-by-langchain](https://github.com/karakuri-ai/gptuber-by-langchain) ⭐ 63 \| 🐛 0 \| 🌐 Python \| 📅 2023-12-15                                                    | -              | -               | ⭐ 63             | 🔴 january 2023   |
| 🔗 [openai-chatfriend](https://github.com/supershaneski/openai-chatfriend) ⭐ 16 \| 🐛 0 \| 🌐 Vue \| 📅 2023-04-03                                                           | -              | -               | ⭐ 16             | 🔴 april 2023     |
| 🔗 [chrome-ext-translate-to-hiragana-with-chatgpt](https://github.com/franzwong/chrome-ext-translate-to-hiragana-with-chatgpt) ⭐ 1 \| 🐛 0 \| 🌐 JavaScript \| 📅 2023-04-01 | -              | -               | ⭐ 1              | 🔴 april 2023     |
| 🔗 [azure-search-openai-demo](https://github.com/nohanaga/azure-search-openai-demo) ⭐ 46 \| 🐛 0 \| 🌐 Python \| 📅 2024-04-18                                               | -              | -               | ⭐ 46             | 🔴 december 2023  |
| 🔗 [chatvrm](https://github.com/pixiv/chatvrm) ⚠️ Archived                                                                                                                   | -              | -               | ⭐ 846            | 🔴 may 2025       |
| 🔗 [sftly-replace](https://github.com/kmizu/sftly-replace) ⭐ 4 \| 🐛 0 \| 🌐 JavaScript \| 📅 2023-05-23                                                                     | -              | -               | ⭐ 4              | 🔴 may 2023       |
| 🔗 [summarize\_arxv](https://github.com/rkmt/summarize_arxv) ⭐ 173 \| 🐛 1 \| 🌐 Python \| 📅 2023-05-22                                                                     | -              | -               | ⭐ 173            | 🔴 may 2023       |
| 🔗 [aiavatarkit](https://github.com/uezo/aiavatarkit) ⭐ 656 \| 🐛 6 \| 🌐 Python \| 📅 2026-08-18                                                                            | -              | -               | ⭐ 655            | 🟢 yesterday      |
| 🔗 [pva-aoai-integration-solution](https://github.com/City-of-Kobe/pva-aoai-integration-solution)                                                                            | -              | -               | ⭐ repo not found | 🔴 repo not found |
| 🔗 [jp-azureopenai-samples](https://github.com/azure-samples/jp-azureopenai-samples) ⚠️ Archived                                                                             | -              | -               | ⭐ 279            | 🟡 march          |
| 🔗 [character\_chat](https://github.com/mutaguchi/character_chat) ⭐ 17 \| 🐛 0 \| 🌐 Python \| 📅 2023-06-03                                                                 | -              | -               | ⭐ 17             | 🔴 june 2023      |
| 🔗 [chatgpt-slackbot](https://github.com/sifue/chatgpt-slackbot) ⭐ 64 \| 🐛 0 \| 🌐 Python \| 📅 2024-07-22                                                                  | -              | -               | ⭐ 64             | 🔴 july 2024      |
| 🔗 [chatgpt-prompt-sample-japanese](https://github.com/dahatake/chatgpt-prompt-sample-japanese) ⭐ 434 \| 🐛 0 \| 🌐 HTML \| 📅 2026-08-16                                    | -              | -               | ⭐ 434            | 🟢 yesterday      |
| 🔗 [kanji-flashcard-app-gpt4](https://github.com/adilmoujahid/kanji-flashcard-app-gpt4) ⭐ 5 \| 🐛 0 \| 🌐 JavaScript \| 📅 2023-10-17                                        | -              | -               | ⭐ 5              | 🔴 october 2023   |
| 🔗 [IgakuQA](https://github.com/jungokasai/IgakuQA) ⭐ 52 \| 🐛 1 \| 🌐 Python \| 📅 2023-03-31                                                                               | -              | -               | ⭐ 52             | 🔴 march 2023     |
| 🔗 [japagen](https://github.com/retrieva/japagen) ⭐ 1 \| 🐛 0 \| 📅 2024-10-31                                                                                               | -              | -               | ⭐ 1              | 🔴 october 2024   |
| 🔗 [generativeai-prompt-sample-japanese](https://github.com/dahatake/generativeai-prompt-sample-japanese) ⭐ 434 \| 🐛 0 \| 🌐 HTML \| 📅 2026-08-16                          | -              | -               | ⭐ 434            | 🟢 yesterday      |

## Dictionary and IME

Resources for Japanese dictionaries and input method editors (IME)

* [mecab-ipadic-neologd](https://github.com/neologd/mecab-ipadic-neologd) ⭐ 2,787 | 🐛 21 | 🌐 Shell | 📅 2023-12-27 - Neologism dictionary based on the language resources on the Web for mecab-ipadic
* [azooKey-Desktop](https://github.com/azooKey/azooKey-Desktop) ⭐ 988 | 🐛 31 | 🌐 Swift | 📅 2026-08-02 - azooKey-Desktop is an open-source Japanese input method for macOS, written in Swift and powered by the Zenzai neural kana-kanji converter. It provides live conversion, optional LLM-based “Magic Conversions”, and Tuner-backed personalization for a smooth, desktop typing experience.
* [yomitan-dictionaries](https://github.com/marvnc/yomitan-dictionaries) ⭐ 889 | 🐛 12 | 🌐 JavaScript | 📅 2026-03-18 - Japanese and Chinese dictionaries for Yomitan.
* [azooKey](https://github.com/azooKey/azooKey) ⭐ 754 | 🐛 26 | 🌐 Swift | 📅 2026-08-17 - azooKey is an open-source Japanese keyboard for iPhone and iPad, written in Swift and powered by its own kana-kanji conversion engine. It provides live conversion, flexible key layouts, and a clean SwiftUI interface for a smooth typing experience.
* [karukan](https://github.com/togatoga/karukan) ⭐ 706 | 🐛 28 | 🌐 Rust | 📅 2026-08-16 - Japanese Input Method System for Linux, Neural Kana-Kanji Conversion Engine + fcitx5 IME
* [Jitendex](https://github.com/stephenmk/Jitendex) ⭐ 521 | 🐛 25 | 🌐 C# | 📅 2026-08-05 - A free and openly licensed Japanese-to-English dictionary compatible with multiple dictionary clients
* [jitendex](https://github.com/jitendex/jitendex) ⭐ 521 | 🐛 25 | 🌐 C# | 📅 2026-08-05 - A free, offline, and openly licensed Japanese-to-English dictionary. Updates monthly!
* [ichiran](https://github.com/tshatrov/ichiran) ⭐ 405 | 🐛 13 | 🌐 Common Lisp | 📅 2026-07-04 - Linguistic tools for texts in Japanese language
* [jmdict-simplified](https://github.com/scriptin/jmdict-simplified) ⭐ 387 | 🐛 1 | 🌐 Kotlin | 📅 2026-08-17 - JMdict and JMnedict in JSON format
* [emoji-ime-dictionary](https://github.com/peaceiris/emoji-ime-dictionary) ⭐ 375 | 🐛 12 | 🌐 Python | 📅 2026-06-18 - 日本語で絵文字入力をするための IME 追加辞書 orange\_book Google 日本語入力などで日本語から絵文字への変換を可能にする IME 拡張辞書
* [japanesekeyboard](https://github.com/kazumaproject/japanesekeyboard) ⭐ 328 | 🐛 22 | 🌐 Kotlin | 📅 2026-08-19 - スミレ - 完全オフラインの日本語キーボードアプリ
* [jmdict-yomitan](https://github.com/themoeway/jmdict-yomitan) ⭐ 309 | 🐛 0 | 🌐 Shell | 📅 2026-08-20 - JMdict, JMnedict, KANJIDIC for Yomitan/Yomichan.
* [macskk](https://github.com/mtgto/macskk) ⭐ 307 | 🐛 15 | 🌐 Swift | 📅 2026-08-16 - Yet Another macOS SKK Input Method
* [EJDict](https://github.com/kujirahand/EJDict) ⭐ 268 | 🐛 7 | 🌐 Python | 📅 2026-06-22 - English-Japanese Dictionary data (Public Domain) EJDict-hand
* [fcitx5-hazkey](https://github.com/7ka-hiira/fcitx5-hazkey) ⭐ 229 | 🐛 17 | 🌐 Swift | 📅 2026-03-07 - Japanese input method for fcitx5, powered by azooKey engine
* [jamdict](https://github.com/neocl/jamdict) ⭐ 170 | 🐛 8 | 🌐 Python | 📅 2021-06-06 - Python 3 library for manipulating Jim Breen's JMdict, KanjiDic2, JMnedict and kanji-radical mappings
* [AzooKeyKanaKanjiConverter](https://github.com/azooKey/AzooKeyKanaKanjiConverter) ⭐ 155 | 🐛 10 | 🌐 Swift | 📅 2026-08-02 - Kana-Kanji Conversion Module written in Swift, supporting Neural Kana-Kanji Conversion and other cool features.
* [skk-emoji-jisyo](https://github.com/uasi/skk-emoji-jisyo) ⭐ 142 | 🐛 2 | 🌐 Ruby | 📅 2025-01-02 - SKK 絵文字辞書
* [yomichan-jlpt-vocab](https://github.com/stephenmk/yomichan-jlpt-vocab) ⭐ 141 | 🐛 0 | 📅 2025-08-26 - JLPT level tags for words in Yomichan
* [jiten](https://github.com/obfusk/jiten) ⭐ 132 | 🐛 54 | 🌐 Python | 📅 2024-08-31 - japanese android/cli/web dictionary based on jmdict/kanjidic — 日本語　辞典　和英辞典　漢英字典　和独辞典　和蘭辞典
* [genshin-dict](https://github.com/kotofurumiya/genshin-dict) ⭐ 130 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-07 - Windows/macOSで使える原神の単語辞書です
* [tdmelodic](https://github.com/PKSHATechnology-Research/tdmelodic) ⭐ 126 | 🐛 3 | 🌐 Python | 📅 2024-03-21 - A Japanese accent dictionary generator
* [libkkc](https://github.com/ueno/libkkc) ⭐ 115 | 🐛 17 | 🌐 Vala | 📅 2024-09-02 - Japanese Kana Kanji conversion input method library
* [unidic-py](https://github.com/polm/unidic-py) ⭐ 114 | 🐛 4 | 🌐 Python | 📅 2025-02-26 - Unidic packaged for installation via pip.
* [cjkvi-dict](https://github.com/cjkvi/cjkvi-dict) ⭐ 112 | 🐛 4 | 🌐 XSLT | 📅 2022-11-28 - 漢字データベースの辞書関連データ
* [google-ime-dictionary](https://github.com/peaceiris/google-ime-dictionary) ⭐ 107 | 🐛 7 | 🌐 Shell | 📅 2026-06-18 - 日英変換・英語略語展開のための IME 追加辞書 orange\_book 日本語から英語への和英変換や英語略語の展開を Google 日本語入力や ATOK などで可能にする IME 拡張辞書
* [libskk](https://github.com/ueno/libskk) ⭐ 101 | 🐛 9 | 🌐 Vala | 📅 2026-06-02 - Japanese SKK input method library
* [Japanese-Company-Lexicon](https://github.com/chakki-works/Japanese-Company-Lexicon) ⭐ 99 | 🐛 1 | 🌐 Python | 📅 2023-07-23 - Japanese Company Lexicon (JCLdic)
* [dic-nico-intersection-pixiv](https://github.com/ncaq/dic-nico-intersection-pixiv) ⭐ 99 | 🐛 2 | 🌐 Haskell | 📅 2024-09-03 - ニコニコ大百科とピクシブ百科事典の共通部分のIME辞書
* [mecab-unidic-neologd](https://github.com/neologd/mecab-unidic-neologd) ⭐ 88 | 🐛 4 | 🌐 Shell | 📅 2020-09-14 - Neologism dictionary based on the language resources on the Web for mecab-unidic
* [mozcdict-ext](https://github.com/reasonset/mozcdict-ext) ⭐ 73 | 🐛 0 | 🌐 Ruby | 📅 2026-05-09 - Convert external words into Mozc system dictionary
* [mouse\_over\_dictionary](https://github.com/kengo700/mouse_over_dictionary) ⭐ 72 | 🐛 9 | 🌐 C++ | 📅 2020-01-23 - マウスオーバーした単語を自動で読み取る汎用辞書ツール
* [pixiv-yomitan](https://github.com/MarvNC/pixiv-yomitan) ⭐ 68 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-20 - Pixiv Encyclopedia Dictionary for Yomitan
* [jisho-open](https://github.com/hlorenzi/jisho-open) ⭐ 67 | 🐛 4 | 🌐 TypeScript | 📅 2026-07-23 - Web frontend for the JMdict Japanese-English dictionary project, with study list support!
* [jawiki-kana-kanji-dict](https://github.com/tokuhirom/jawiki-kana-kanji-dict) ⭐ 65 | 🐛 2 | 🌐 Python | 📅 2026-08-14 - Generate SKK/MeCab dictionary from Wikipedia(Japanese edition)
* [google-ime-user-dictionary-ja-en](https://github.com/KEINOS/google-ime-user-dictionary-ja-en) ⭐ 62 | 🐛 0 | 📅 2018-12-22 - GoogleIME用カタカナ語辞書プロジェクトのアーカイブです。Project archive of Google IME user dictionary from Katakana word ( Japanese loanword ) to English.
* [sumibi](https://github.com/kiyoka/sumibi) ⭐ 62 | 🐛 4 | 🌐 Emacs Lisp | 📅 2026-08-16 - Japanese input method powered by ChatGPT API
* [Sumibi](https://github.com/kiyoka/Sumibi) ⭐ 62 | 🐛 4 | 🌐 Emacs Lisp | 📅 2026-08-16 - Japanese/Chinese input method powered by ChatGPT API
* [dvorakjp-roman-table](https://github.com/shinespark/dvorakjp-roman-table) ⭐ 58 | 🐛 1 | 🌐 Rust | 📅 2026-08-18 - azooKey, Google 日本語入力用 DvorakJP ローマ字テーブル / DvorakJP Roman Table for azooKey, Google Japanese Input
* [unidic-lite](https://github.com/polm/unidic-lite) ⭐ 52 | 🐛 0 | 🌐 Python | 📅 2020-09-01 - A small version of UniDic for easy pip installs.
* [emoticon](https://github.com/tiwanari/emoticon) ⭐ 46 | 🐛 2 | 🌐 Python | 📅 2020-05-07 - Google日本語入力の顔文字辞書∩(,,Ò‿Ó,,)∩
* [anthy-unicode](https://github.com/fujiwarat/anthy-unicode) ⭐ 46 | 🐛 5 | 🌐 Raku | 📅 2026-08-17 - Anthy Unicode - Another Anthy
* [nijisanji-ime-dic](https://github.com/Umichang/nijisanji-ime-dic) ⭐ 42 | 🐛 0 | 🌐 Makefile | 📅 2026-07-21 - Microsoft IMEなどで利用することを想定した「にじさんじ」関連用語の用語辞書です。
* [JIWC-Dictionary](https://github.com/sociocom/JIWC-Dictionary) ⭐ 40 | 🐛 0 | 📅 2021-01-27 - dictionary to find emotion related to text
* [anthywl](https://github.com/tadeokondrak/anthywl) ⭐ 34 | 🐛 5 | 🌐 C | 📅 2025-04-07 - Japanese input method for Sway using libanthy
* [cl-skkserv](https://github.com/tani/cl-skkserv) ⭐ 32 | 🐛 4 | 🌐 Common Lisp | 📅 2024-10-31 - Common LispによるSKK辞書サーバーとその拡張
* [skk-jisyo.emoji-ja](https://github.com/ymrl/skk-jisyo.emoji-ja) ⭐ 30 | 🐛 2 | 🌐 Ruby | 📅 2023-07-01 - 日本語の読みから Emoji に変換するための SKK 辞書 😂
* [rakukan](https://github.com/fukuyori/rakukan) ⭐ 29 | 🐛 0 | 🌐 Rust | 📅 2026-08-09 - ローカルLLMを利用した、Windows 向け日本語 IMEgit
* [jisyo](https://github.com/skk-dict/jisyo) ⭐ 28 | 🐛 0 | 🌐 TypeScript | 📅 2023-09-22 - かな漢字変換エンジン SKKのための新しい辞書形式
* [mozcdic-ut-personal-names](https://github.com/utuhiro78/mozcdic-ut-personal-names) ⭐ 27 | 🐛 0 | 📅 2026-08-09 - A personal name dictionary for Mozc.
* [nihongo](https://github.com/sph-mn/nihongo) ⭐ 26 | 🐛 0 | 🌐 HTML | 📅 2025-01-08 - japanese language data and dictionary
* [hololive-dictionary](https://github.com/heppokofrontend/hololive-dictionary) ⭐ 25 | 🐛 1 | 🌐 TypeScript | 📅 2024-12-04 - ホロライブ（ホロライブプロダクション）に関する辞書ファイルです。./dictionary フォルダ内のテキストファイルを使って、IMEに単語を追加できます。詳細はREADME.mdをご覧ください。
* [ipadic-py](https://github.com/polm/ipadic-py) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2021-10-31 - IPAdic packaged for easy use from Python.
* [Ayashiy-Nipongo-Dic](https://github.com/Rinrin0413/Ayashiy-Nipongo-Dic) ⭐ 24 | 🐛 0 | 📅 2024-05-05 - 贵樣ばこゐ辞畫を使て正レい日本语を使ラことが出來ゑ。
* [mozcdic-ut-place-names](https://github.com/utuhiro78/mozcdic-ut-place-names) ⭐ 24 | 🐛 0 | 📅 2026-08-09 - Mozc UT Place Name Dictionary is a dictionary converted from the Japan Post's ZIP code data for Mozc.
* [mikan](https://github.com/mojyack/mikan) ⭐ 24 | 🐛 0 | 🌐 C++ | 📅 2025-06-27 - A Japanese input method.
* [sekka](https://github.com/kiyoka/sekka) ⭐ 24 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-16 - Yet another Japanese Input Method inspired by SKK.
* [mozcdic-ut-sudachidict](https://github.com/utuhiro78/mozcdic-ut-sudachidict) ⭐ 23 | 🐛 0 | 📅 2026-07-24 - A dictionary converted from SudachiDict for Mozc.
* [japanesearabic](https://github.com/a-hamdi/japanesearabic) ⭐ 20 | 🐛 1 | 🌐 Python | 📅 2025-05-20 - JapaneseArabic Dictionary (日本語・アラビア語辞書) قاموس اللغة اليابانية والعربية (Yomitan)
* [mzimeja](https://github.com/katahiromz/mzimeja) ⭐ 19 | 🐛 2 | 🌐 C++ | 📅 2026-07-18 - MZ-IME Japanese Input for Windows
* [anthy](https://github.com/netsphere-labs/anthy) ⭐ 16 | 🐛 4 | 🌐 C | 📅 2023-02-25 - Anthy is a kana-kanji conversion engine for Japanese. It converts roma-ji to kana, and the kana text to a mixed kana and kanji.
* [kagome-dict](https://github.com/ikawaha/kagome-dict) ⭐ 15 | 🐛 1 | 🌐 Go | 📅 2026-08-17 - Dictionary Library for Kagome v2
* [canna](https://github.com/canna-input/canna) ⭐ 15 | 🐛 11 | 🌐 Perl | 📅 2026-08-15 - Canna Japanese input system
* [Kaomoji\_proj](https://github.com/mtripg6666tdr/Kaomoji_proj) ⭐ 11 | 🐛 1 | 📅 2025-10-21 - (๑ ᴖ ᴑ ᴖ ๑)みょんかおもじ（旧Kaomoji\_proj）はMicrosoft社の入力ソフト、Microsoft IME向けの顔文字の辞書を作成するプロジェクトです。
* [mecab-mozcdic](https://github.com/akirakubo/mecab-mozcdic) ⭐ 10 | 🐛 0 | 📅 2018-01-12 - open source mozc dictionaryをMeCab辞書のフォーマットに変換したものです。
* [colloquial-kansai-dictionary](https://github.com/sethclydesdale/colloquial-kansai-dictionary) ⭐ 9 | 🐛 0 | 🌐 HTML | 📅 2026-06-20 - A quick reference for the material taught in Colloquial Kansai Japanese.
* [jinmei-dict](https://github.com/s1r-j/jinmei-dict) ⭐ 9 | 🐛 0 | 🌐 HTML | 📅 2020-04-01 - 辞書データから人名だけを抜き出し、読み仮名（カタカナ）をキーとして、候補となる書き文字をリストで保持するようなJSON形式に整形しています。
* [manbyo-sudachi](https://github.com/yagays/manbyo-sudachi) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2021-04-06 - Sudachi向け万病辞書
* [aws\_dic\_for\_google\_ime](https://github.com/konyu/aws_dic_for_google_ime) ⭐ 7 | 🐛 3 | 🌐 CSS | 📅 2023-06-10 - AWSサービス名のGoogle日本語入力向けの辞書
* [alfred-japanese-dictionary](https://github.com/chrisgrieser/alfred-japanese-dictionary) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-03 - Japanese-English Dictionary using jisho.org with audio, csv export of entries, and preview of dictionary sites.
* [mh-dict-jp](https://github.com/utubo/mh-dict-jp) ⭐ 6 | 🐛 8 | 🌐 JavaScript | 📅 2025-04-04 - MonsterHunterのユーザー辞書を作りたい…
* [kanji-dict](https://github.com/marmooo/kanji-dict) ⭐ 6 | 🐛 0 | 🌐 HTML | 📅 2026-05-03 - 漢字の書き順(筆順)・読み方・画数・部首・用例・成り立ちを調べるための漢字辞書です。Unicode 15.1 のすべての漢字 98,682字を収録しています。
* [kotlin-kana-kanji-converter](https://github.com/KazumaProject/kotlin-kana-kanji-converter) ⭐ 6 | 🐛 1 | 🌐 Kotlin | 📅 2026-08-19 - Kotlin かな漢字変換プログラム
* [o-dic](https://github.com/makotoga/o-dic) ⭐ 6 | 🐛 1 | 🌐 Perl | 📅 2026-02-24 - 沖縄辞書
* [jmdict-fst](https://github.com/theGlenn/jmdict-fst) ⭐ 6 | 🐛 3 | 🌐 Rust | 📅 2026-05-25 - Fast JMdict lookup engine with FST-based exact/prefix/fuzzy/gloss search, deinflection, Rust core, and Swift/Kotlin/Flutter bindings.
* [anthy](https://github.com/xorgy/anthy) ⭐ 5 | 🐛 0 | 🌐 C | 📅 2022-04-27 - Anthy maintenance
* [JMdictSQLite](https://github.com/seanmcbroom/JMdictSQLite) ⭐ 5 | 🐛 9 | 🌐 TypeScript | 📅 2026-08-11 - SQLite database for JMdict and Kanjidic, a Japanese-English dictionary. Automatic daily updates.
* [JumanDIC](https://github.com/ku-nlp/JumanDIC) ⭐ 4 | 🐛 2 | 🌐 Perl | 📅 2026-04-21 - This repository contains source dictionary files to build dictionaries for JUMAN and Juman++.
* [uchinaaguchi\_dict](https://github.com/nanjakkun/uchinaaguchi_dict) ⭐ 4 | 🐛 26 | 🌐 Ruby | 📅 2026-08-11 - うちなーぐち辞典（沖縄語辞典）
* [denonbu-ime-dic](https://github.com/albno273/denonbu-ime-dic) ⭐ 2 | 🐛 0 | 🌐 Makefile | 📅 2022-11-13 - 電音IME: Microsoft IMEなどで利用することを想定した「電音部」関連用語の辞書
* [wlsp-classical](https://github.com/yocjyet/wlsp-classical) ⭐ 2 | 🐛 0 | 📅 2025-11-20 - 古典日本語の分類語彙表データ
* [japanese\_android\_ime](https://github.com/nelsonapenn/japanese_android_ime) ⚠️ Archived - A FOSS Japanese IME for Android
* [kansai-accent-dictionary](https://github.com/nullponull/kansai-accent-dictionary) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-06-10 - 京阪式アクセント（関西弁）辞書 - 4,615語を収録した日本語方言アクセント辞書
* [pokemon-ime-dic](https://github.com/Umichang/pokemon-ime-dic) ⭐ 1 | 🐛 0 | 🌐 Makefile | 📅 2020-01-10 - Microsoft IMEなどで利用することを想定した、現状判明している全てのポケモンの名前を網羅した用語辞書です。
* [nandoku](https://github.com/marmooo/nandoku) ⭐ 1 | 🐛 0 | 🌐 HTML | 📅 2026-05-06 - 難読漢字を学年別にまとめた辞書です。
* [shitto-mania-dic](https://github.com/junikematsu/shitto-mania-dic) ⭐ 0 | 🐛 0 | 📅 2026-03-17 - 嫉妬辞書（Shitto-Mania / Jealousy Dictionary）
* [jitenbot](https://github.com/stephenmk/jitenbot) - Convert data from Japanese dictionary websites and applications into portable file formats
* [kanayomi-dict](https://github.com/warihima/kanayomi-dict) - openjtalk形式のユーザー辞書

| Name                                                                                                                                      | downloads/week | total downloads | stars            | last commit       |
| ----------------------------------------------------------------------------------------------------------------------------------------- | -------------- | --------------- | ---------------- | ----------------- |
| 🔗 [mecab-ipadic-neologd](https://github.com/neologd/mecab-ipadic-neologd) ⭐ 2,787 \| 🐛 21 \| 🌐 Shell \| 📅 2023-12-27                  | -              | -               | ⭐ 2.8k           | 🔴 september 2020 |
| 🔗 [tdmelodic](https://github.com/PKSHATechnology-Research/tdmelodic) ⭐ 126 \| 🐛 3 \| 🌐 Python \| 📅 2024-03-21                         | -              | -               | ⭐ 126            | 🔴 march 2024     |
| 🔗 [jamdict](https://github.com/neocl/jamdict) ⭐ 170 \| 🐛 8 \| 🌐 Python \| 📅 2021-06-06                                                | 📥 2k          | 📦 76k          | ⭐ 169            | 🔴 june 2021      |
| 🔗 [unidic-py](https://github.com/polm/unidic-py) ⭐ 114 \| 🐛 4 \| 🌐 Python \| 📅 2025-02-26                                             | 📥 84k         | 📦 12M          | ⭐ 113            | 🔴 february 2025  |
| 🔗 [Japanese-Company-Lexicon](https://github.com/chakki-works/Japanese-Company-Lexicon) ⭐ 99 \| 🐛 1 \| 🌐 Python \| 📅 2023-07-23        | -              | -               | ⭐ 99             | 🔴 january 2023   |
| 🔗 [manbyo-sudachi](https://github.com/yagays/manbyo-sudachi) ⭐ 7 \| 🐛 0 \| 🌐 Python \| 📅 2021-04-06                                   | -              | -               | ⭐ 7              | 🔴 april 2021     |
| 🔗 [jawiki-kana-kanji-dict](https://github.com/tokuhirom/jawiki-kana-kanji-dict) ⭐ 65 \| 🐛 2 \| 🌐 Python \| 📅 2026-08-14               | -              | -               | ⭐ 65             | 🟢 last friday    |
| 🔗 [JIWC-Dictionary](https://github.com/sociocom/JIWC-Dictionary) ⭐ 40 \| 🐛 0 \| 📅 2021-01-27                                           | -              | -               | ⭐ 40             | 🔴 january 2021   |
| 🔗 [JumanDIC](https://github.com/ku-nlp/JumanDIC) ⭐ 4 \| 🐛 2 \| 🌐 Perl \| 📅 2026-04-21                                                 | -              | -               | ⭐ 4              | 🔴 august 2022    |
| 🔗 [ipadic-py](https://github.com/polm/ipadic-py) ⭐ 24 \| 🐛 0 \| 🌐 Python \| 📅 2021-10-31                                              | 📥 47k         | 📦 7M           | ⭐ 24             | 🔴 october 2021   |
| 🔗 [unidic-lite](https://github.com/polm/unidic-lite) ⭐ 52 \| 🐛 0 \| 🌐 Python \| 📅 2020-09-01                                          | 📥 105k        | 📦 12M          | ⭐ 52             | 🔴 september 2020 |
| 🔗 [emoji-ime-dictionary](https://github.com/peaceiris/emoji-ime-dictionary) ⭐ 375 \| 🐛 12 \| 🌐 Python \| 📅 2026-06-18                 | -              | -               | ⭐ 375            | 🟡 may            |
| 🔗 [google-ime-dictionary](https://github.com/peaceiris/google-ime-dictionary) ⭐ 107 \| 🐛 7 \| 🌐 Shell \| 📅 2026-06-18                 | -              | -               | ⭐ 107            | 🟡 may            |
| 🔗 [dic-nico-intersection-pixiv](https://github.com/ncaq/dic-nico-intersection-pixiv) ⭐ 99 \| 🐛 2 \| 🌐 Haskell \| 📅 2024-09-03         | -              | -               | ⭐ 98             | 🔴 september 2024 |
| 🔗 [google-ime-user-dictionary-ja-en](https://github.com/KEINOS/google-ime-user-dictionary-ja-en) ⭐ 62 \| 🐛 0 \| 📅 2018-12-22           | -              | -               | ⭐ 62             | 🔴 december 2016  |
| 🔗 [emoticon](https://github.com/tiwanari/emoticon) ⭐ 46 \| 🐛 2 \| 🌐 Python \| 📅 2020-05-07                                            | -              | -               | ⭐ 46             | 🔴 may 2020       |
| 🔗 [mecab-mozcdic](https://github.com/akirakubo/mecab-mozcdic) ⭐ 10 \| 🐛 0 \| 📅 2018-01-12                                              | -              | -               | ⭐ 10             | 🔴 january 2018   |
| 🔗 [denonbu-ime-dic](https://github.com/albno273/denonbu-ime-dic) ⭐ 2 \| 🐛 0 \| 🌐 Makefile \| 📅 2022-11-13                             | -              | -               | ⭐ 2              | 🔴 november 2022  |
| 🔗 [nijisanji-ime-dic](https://github.com/Umichang/nijisanji-ime-dic) ⭐ 42 \| 🐛 0 \| 🌐 Makefile \| 📅 2026-07-21                        | -              | -               | ⭐ 42             | 🟢 july           |
| 🔗 [pokemon-ime-dic](https://github.com/Umichang/pokemon-ime-dic) ⭐ 1 \| 🐛 0 \| 🌐 Makefile \| 📅 2020-01-10                             | -              | -               | ⭐ 1              | 🔴 january 2020   |
| 🔗 [EJDict](https://github.com/kujirahand/EJDict) ⭐ 268 \| 🐛 7 \| 🌐 Python \| 📅 2026-06-22                                             | -              | -               | ⭐ 268            | 🟢 june           |
| 🔗 [Ayashiy-Nipongo-Dic](https://github.com/Rinrin0413/Ayashiy-Nipongo-Dic) ⭐ 24 \| 🐛 0 \| 📅 2024-05-05                                 | -              | -               | ⭐ 24             | 🔴 may 2024       |
| 🔗 [genshin-dict](https://github.com/kotofurumiya/genshin-dict) ⭐ 130 \| 🐛 3 \| 🌐 TypeScript \| 📅 2026-08-07                           | -              | -               | ⭐ 130            | 🟢 august         |
| 🔗 [jmdict-simplified](https://github.com/scriptin/jmdict-simplified) ⭐ 387 \| 🐛 1 \| 🌐 Kotlin \| 📅 2026-08-17                         | -              | -               | ⭐ 385            | 🟢 august         |
| 🔗 [mozcdict-ext](https://github.com/reasonset/mozcdict-ext) ⭐ 73 \| 🐛 0 \| 🌐 Ruby \| 📅 2026-05-09                                     | -              | -               | ⭐ 73             | 🟡 may            |
| 🔗 [mh-dict-jp](https://github.com/utubo/mh-dict-jp) ⭐ 6 \| 🐛 8 \| 🌐 JavaScript \| 📅 2025-04-04                                        | -              | -               | ⭐ 5              | 🔴 april 2025     |
| 🔗 [jitenbot](https://github.com/stephenmk/jitenbot)                                                                                      | -              | -               | ⭐ repo not found | 🔴 repo not found |
| 🔗 [mecab-unidic-neologd](https://github.com/neologd/mecab-unidic-neologd) ⭐ 88 \| 🐛 4 \| 🌐 Shell \| 📅 2020-09-14                      | -              | -               | ⭐ 88             | 🔴 september 2020 |
| 🔗 [hololive-dictionary](https://github.com/heppokofrontend/hololive-dictionary) ⭐ 25 \| 🐛 1 \| 🌐 TypeScript \| 📅 2024-12-04           | -              | -               | ⭐ 25             | 🔴 december 2024  |
| 🔗 [jmdict-yomitan](https://github.com/themoeway/jmdict-yomitan) ⭐ 309 \| 🐛 0 \| 🌐 Shell \| 📅 2026-08-20                               | -              | -               | ⭐ 309            | 🟡 may            |
| 🔗 [yomichan-jlpt-vocab](https://github.com/stephenmk/yomichan-jlpt-vocab) ⭐ 141 \| 🐛 0 \| 📅 2025-08-26                                 | -              | -               | ⭐ 141            | 🔴 august 2025    |
| 🔗 [Jitendex](https://github.com/stephenmk/Jitendex) ⭐ 521 \| 🐛 25 \| 🌐 C# \| 📅 2026-08-05                                             | -              | -               | ⭐ 521            | 🟢 august         |
| 🔗 [jiten](https://github.com/obfusk/jiten) ⭐ 132 \| 🐛 54 \| 🌐 Python \| 📅 2024-08-31                                                  | -              | -               | ⭐ 132            | 🔴 december 2023  |
| 🔗 [pixiv-yomitan](https://github.com/MarvNC/pixiv-yomitan) ⭐ 68 \| 🐛 2 \| 🌐 TypeScript \| 📅 2026-08-20                                | -              | -               | ⭐ 68             | 🟡 march          |
| 🔗 [uchinaaguchi\_dict](https://github.com/nanjakkun/uchinaaguchi_dict) ⭐ 4 \| 🐛 26 \| 🌐 Ruby \| 📅 2026-08-11                          | -              | -               | ⭐ 4              | 🟢 july           |
| 🔗 [yomitan-dictionaries](https://github.com/marvnc/yomitan-dictionaries) ⭐ 889 \| 🐛 12 \| 🌐 JavaScript \| 📅 2026-03-18                | -              | -               | ⭐ 887            | 🟡 march          |
| 🔗 [mouse\_over\_dictionary](https://github.com/kengo700/mouse_over_dictionary) ⭐ 72 \| 🐛 9 \| 🌐 C++ \| 📅 2020-01-23                   | -              | -               | ⭐ 72             | 🔴 january 2020   |
| 🔗 [jisyo](https://github.com/skk-dict/jisyo) ⭐ 28 \| 🐛 0 \| 🌐 TypeScript \| 📅 2023-09-22                                              | -              | -               | ⭐ 28             | 🔴 september 2023 |
| 🔗 [skk-jisyo.emoji-ja](https://github.com/ymrl/skk-jisyo.emoji-ja) ⭐ 30 \| 🐛 2 \| 🌐 Ruby \| 📅 2023-07-01                              | -              | -               | ⭐ 30             | 🔴 march 2018     |
| 🔗 [aws\_dic\_for\_google\_ime](https://github.com/konyu/aws_dic_for_google_ime) ⭐ 7 \| 🐛 3 \| 🌐 CSS \| 📅 2023-06-10                   | -              | -               | ⭐ 7              | 🔴 november 2019  |
| 🔗 [cl-skkserv](https://github.com/tani/cl-skkserv) ⭐ 32 \| 🐛 4 \| 🌐 Common Lisp \| 📅 2024-10-31                                       | -              | -               | ⭐ 32             | 🔴 october 2024   |
| 🔗 [anthy](https://github.com/xorgy/anthy) ⭐ 5 \| 🐛 0 \| 🌐 C \| 📅 2022-04-27                                                           | -              | -               | ⭐ 5              | 🔴 july 2013      |
| 🔗 [anthy-unicode](https://github.com/fujiwarat/anthy-unicode) ⭐ 46 \| 🐛 5 \| 🌐 Raku \| 📅 2026-08-17                                   | -              | -               | ⭐ 46             | 🟢 today          |
| 🔗 [azooKey](https://github.com/azooKey/azooKey) ⭐ 754 \| 🐛 26 \| 🌐 Swift \| 📅 2026-08-17                                              | -              | -               | ⭐ 753            | 🟢 august         |
| 🔗 [azooKey-Desktop](https://github.com/azooKey/azooKey-Desktop) ⭐ 988 \| 🐛 31 \| 🌐 Swift \| 📅 2026-08-02                              | -              | -               | ⭐ 985            | 🟢 august         |
| 🔗 [fcitx5-hazkey](https://github.com/7ka-hiira/fcitx5-hazkey) ⭐ 229 \| 🐛 17 \| 🌐 Swift \| 📅 2026-03-07                                | -              | -               | ⭐ 228            | 🟡 february       |
| 🔗 [mozcdic-ut-place-names](https://github.com/utuhiro78/mozcdic-ut-place-names) ⭐ 24 \| 🐛 0 \| 📅 2026-08-09                            | -              | -               | ⭐ 24             | 🟢 august         |
| 🔗 [AzooKeyKanaKanjiConverter](https://github.com/azooKey/AzooKeyKanaKanjiConverter) ⭐ 155 \| 🐛 10 \| 🌐 Swift \| 📅 2026-08-02          | -              | -               | ⭐ 154            | 🟢 august         |
| 🔗 [libkkc](https://github.com/ueno/libkkc) ⭐ 115 \| 🐛 17 \| 🌐 Vala \| 📅 2024-09-02                                                    | -              | -               | ⭐ 115            | 🔴 august 2024    |
| 🔗 [libskk](https://github.com/ueno/libskk) ⭐ 101 \| 🐛 9 \| 🌐 Vala \| 📅 2026-06-02                                                     | -              | -               | ⭐ 101            | 🟢 june           |
| 🔗 [kanayomi-dict](https://github.com/warihima/kanayomi-dict)                                                                             | -              | -               | ⭐ repo not found | 🔴 repo not found |
| 🔗 [cjkvi-dict](https://github.com/cjkvi/cjkvi-dict) ⭐ 112 \| 🐛 4 \| 🌐 XSLT \| 📅 2022-11-28                                            | -              | -               | ⭐ 112            | 🔴 september 2017 |
| 🔗 [wlsp-classical](https://github.com/yocjyet/wlsp-classical) ⭐ 2 \| 🐛 0 \| 📅 2025-11-20                                               | -              | -               | ⭐ 2              | 🟡 november 2025  |
| 🔗 [kanji-dict](https://github.com/marmooo/kanji-dict) ⭐ 6 \| 🐛 0 \| 🌐 HTML \| 📅 2026-05-03                                            | -              | -               | ⭐ 6              | 🟡 may            |
| 🔗 [Kaomoji\_proj](https://github.com/mtripg6666tdr/Kaomoji_proj) ⭐ 11 \| 🐛 1 \| 📅 2025-10-21                                           | -              | -               | ⭐ 11             | 🟡 october 2025   |
| 🔗 [kotlin-kana-kanji-converter](https://github.com/KazumaProject/kotlin-kana-kanji-converter) ⭐ 6 \| 🐛 1 \| 🌐 Kotlin \| 📅 2026-08-19  | -              | -               | ⭐ 6              | 🟢 yesterday      |
| 🔗 [alfred-japanese-dictionary](https://github.com/chrisgrieser/alfred-japanese-dictionary) ⭐ 7 \| 🐛 0 \| 🌐 JavaScript \| 📅 2026-08-03 | -              | -               | ⭐ 7              | 🟢 august         |
| 🔗 [ichiran](https://github.com/tshatrov/ichiran) ⭐ 405 \| 🐛 13 \| 🌐 Common Lisp \| 📅 2026-07-04                                       | -              | -               | ⭐ 404            | 🟢 july           |
| 🔗 [mikan](https://github.com/mojyack/mikan) ⭐ 24 \| 🐛 0 \| 🌐 C++ \| 📅 2025-06-27                                                      | -              | -               | ⭐ 24             | 🔴 june 2025      |
| 🔗 [colloquial-kansai-dictionary](https://github.com/sethclydesdale/colloquial-kansai-dictionary) ⭐ 9 \| 🐛 0 \| 🌐 HTML \| 📅 2026-06-20 | -              | -               | ⭐ 9              | 🟢 june           |
| 🔗 [jisho-open](https://github.com/hlorenzi/jisho-open) ⭐ 67 \| 🐛 4 \| 🌐 TypeScript \| 📅 2026-07-23                                    | -              | -               | ⭐ 67             | 🟢 july           |
| 🔗 [macskk](https://github.com/mtgto/macskk) ⭐ 307 \| 🐛 15 \| 🌐 Swift \| 📅 2026-08-16                                                  | -              | -               | ⭐ 304            | 🟢 yesterday      |
| 🔗 [nandoku](https://github.com/marmooo/nandoku) ⭐ 1 \| 🐛 0 \| 🌐 HTML \| 📅 2026-05-06                                                  | -              | -               | ⭐ 1              | 🟡 may            |
| 🔗 [japanese\_android\_ime](https://github.com/nelsonapenn/japanese_android_ime) ⚠️ Archived                                              | -              | -               | ⭐ 2              | 🟡 september 2025 |
| 🔗 [anthywl](https://github.com/tadeokondrak/anthywl) ⭐ 34 \| 🐛 5 \| 🌐 C \| 📅 2025-04-07                                               | -              | -               | ⭐ 34             | 🔴 april 2025     |
| 🔗 [sekka](https://github.com/kiyoka/sekka) ⭐ 24 \| 🐛 0 \| 🌐 JavaScript \| 📅 2026-05-16                                                | -              | -               | ⭐ 24             | 🟡 may            |
| 🔗 [sumibi](https://github.com/kiyoka/sumibi) ⭐ 62 \| 🐛 4 \| 🌐 Emacs Lisp \| 📅 2026-08-16                                              | -              | -               | ⭐ 62             | 🟢 yesterday      |
| 🔗 [jinmei-dict](https://github.com/s1r-j/jinmei-dict) ⭐ 9 \| 🐛 0 \| 🌐 HTML \| 📅 2020-04-01                                            | -              | -               | ⭐ 9              | 🔴 april 2020     |
| 🔗 [japanesearabic](https://github.com/a-hamdi/japanesearabic) ⭐ 20 \| 🐛 1 \| 🌐 Python \| 📅 2025-05-20                                 | -              | -               | ⭐ 20             | 🔴 may 2025       |
| 🔗 [o-dic](https://github.com/makotoga/o-dic) ⭐ 6 \| 🐛 1 \| 🌐 Perl \| 📅 2026-02-24                                                     | -              | -               | ⭐ 6              | 🟡 february       |
| 🔗 [skk-emoji-jisyo](https://github.com/uasi/skk-emoji-jisyo) ⭐ 142 \| 🐛 2 \| 🌐 Ruby \| 📅 2025-01-02                                   | -              | -               | ⭐ 142            | 🔴 january 2025   |
| 🔗 [mozcdic-ut-personal-names](https://github.com/utuhiro78/mozcdic-ut-personal-names) ⭐ 27 \| 🐛 0 \| 📅 2026-08-09                      | -              | -               | ⭐ 27             | 🟢 august         |
| 🔗 [mozcdic-ut-sudachidict](https://github.com/utuhiro78/mozcdic-ut-sudachidict) ⭐ 23 \| 🐛 0 \| 📅 2026-07-24                            | -              | -               | ⭐ 23             | 🟢 july           |
| 🔗 [nihongo](https://github.com/sph-mn/nihongo) ⭐ 26 \| 🐛 0 \| 🌐 HTML \| 📅 2025-01-08                                                  | -              | -               | ⭐ 25             | 🔴 january 2025   |
| 🔗 [kagome-dict](https://github.com/ikawaha/kagome-dict) ⭐ 15 \| 🐛 1 \| 🌐 Go \| 📅 2026-08-17                                           | -              | -               | ⭐ 15             | 🟢 july           |
| 🔗 [canna](https://github.com/canna-input/canna) ⭐ 15 \| 🐛 11 \| 🌐 Perl \| 📅 2026-08-15                                                | -              | -               | ⭐ 15             | 🟢 last saturday  |
| 🔗 [kansai-accent-dictionary](https://github.com/nullponull/kansai-accent-dictionary) ⭐ 2 \| 🐛 0 \| 🌐 Python \| 📅 2026-06-10           | -              | -               | ⭐ 2              | 🟢 june           |
| 🔗 [jitendex](https://github.com/jitendex/jitendex) ⭐ 521 \| 🐛 25 \| 🌐 C# \| 📅 2026-08-05                                              | -              | -               | ⭐ 521            | 🟢 august         |
| 🔗 [karukan](https://github.com/togatoga/karukan) ⭐ 706 \| 🐛 28 \| 🌐 Rust \| 📅 2026-08-16                                              | -              | -               | ⭐ 703            | 🟢 yesterday      |
| 🔗 [shitto-mania-dic](https://github.com/junikematsu/shitto-mania-dic) ⭐ 0 \| 🐛 0 \| 📅 2026-03-17                                       | -              | -               | ⭐ 0              | 🟡 march          |
| 🔗 [dvorakjp-roman-table](https://github.com/shinespark/dvorakjp-roman-table) ⭐ 58 \| 🐛 1 \| 🌐 Rust \| 📅 2026-08-18                    | -              | -               | ⭐ 58             | 🟢 last tuesday   |
| 🔗 [jmdict-fst](https://github.com/theGlenn/jmdict-fst) ⭐ 6 \| 🐛 3 \| 🌐 Rust \| 📅 2026-05-25                                           | -              | -               | ⭐ 6              | 🟡 may            |
| 🔗 [mzimeja](https://github.com/katahiromz/mzimeja) ⭐ 19 \| 🐛 2 \| 🌐 C++ \| 📅 2026-07-18                                               | -              | -               | ⭐ 19             | 🟢 july           |
| 🔗 [japanesekeyboard](https://github.com/kazumaproject/japanesekeyboard) ⭐ 328 \| 🐛 22 \| 🌐 Kotlin \| 📅 2026-08-19                     | -              | -               | ⭐ 325            | 🟢 yesterday      |
| 🔗 [Sumibi](https://github.com/kiyoka/Sumibi) ⭐ 62 \| 🐛 4 \| 🌐 Emacs Lisp \| 📅 2026-08-16                                              | -              | -               | ⭐ 62             | 🟢 yesterday      |
| 🔗 [rakukan](https://github.com/fukuyori/rakukan) ⭐ 29 \| 🐛 0 \| 🌐 Rust \| 📅 2026-08-09                                                | -              | -               | ⭐ 29             | 🟢 august         |
| 🔗 [JMdictSQLite](https://github.com/seanmcbroom/JMdictSQLite) ⭐ 5 \| 🐛 9 \| 🌐 TypeScript \| 📅 2026-08-11                              | -              | -               | ⭐ 5              | 🟢 august         |

## Corpus

### Part-of-speech tagging / Named entity recognition

Corpora annotated with part-of-speech tags and named entities

* [ner-wikipedia-dataset](https://github.com/stockmarkteam/ner-wikipedia-dataset) ⭐ 143 | 🐛 0 | 📅 2023-09-02 - Wikipediaを用いた日本語の固有表現抽出データセット
* [KWDLC](https://github.com/ku-nlp/KWDLC) ⭐ 84 | 🐛 12 | 🌐 Python | 📅 2023-12-18 - Kyoto University Web Document Leads Corpus
* [IOB2Corpus](https://github.com/Hironsan/IOB2Corpus) ⭐ 61 | 🐛 1 | 📅 2020-02-25 - Japanese IOB2 tagged corpus for Named Entity Recognition.
* [UD\_Japanese-GSD](https://github.com/megagonlabs/UD_Japanese-GSD) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2023-03-24 - Japanese data from the Google UDT 2.0.
* [ud\_japanese-bccwj](https://github.com/universaldependencies/ud_japanese-bccwj) ⭐ 27 | 🐛 0 | 🌐 Python | 📅 2026-05-06 - This Universal Dependencies (UD) Japanese treebank is based on the definition of UD Japanese convention described in the UD documentation.
* [TwitterCorpus](https://github.com/tmu-nlp/TwitterCorpus) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2016-03-14 - 首都大日本語 Twitter コーパス
* [AnnotatedFKCCorpus](https://github.com/ku-nlp/AnnotatedFKCCorpus) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2023-12-18 - Annotated Fuman Kaitori Center Corpus
* [UD\_Japanese-GSDLUW](https://github.com/UniversalDependencies/UD_Japanese-GSDLUW) ⭐ 3 | 🐛 0 | 📅 2026-05-06 - Long-unit-word version of UD\_Japanese-GSD
* [UD\_Japanese-PUD](https://github.com/megagonlabs/UD_Japanese-PUD) ⭐ 0 | 🐛 0 | 📅 2020-05-18 - Parallel Universal Dependencies.

| Name                                                                                                                           | downloads/week | total downloads | stars | last commit       |
| ------------------------------------------------------------------------------------------------------------------------------ | -------------- | --------------- | ----- | ----------------- |
| 🔗 [ner-wikipedia-dataset](https://github.com/stockmarkteam/ner-wikipedia-dataset) ⭐ 143 \| 🐛 0 \| 📅 2023-09-02              | -              | -               | ⭐ 143 | 🔴 september 2023 |
| 🔗 [IOB2Corpus](https://github.com/Hironsan/IOB2Corpus) ⭐ 61 \| 🐛 1 \| 📅 2020-02-25                                          | -              | -               | ⭐ 61  | 🔴 february 2020  |
| 🔗 [TwitterCorpus](https://github.com/tmu-nlp/TwitterCorpus) ⭐ 21 \| 🐛 0 \| 🌐 Python \| 📅 2016-03-14                        | -              | -               | ⭐ 21  | 🔴 march 2016     |
| 🔗 [UD\_Japanese-PUD](https://github.com/megagonlabs/UD_Japanese-PUD) ⭐ 0 \| 🐛 0 \| 📅 2020-05-18                             | -              | -               | ⭐ 0   | 🔴 may 2020       |
| 🔗 [UD\_Japanese-GSD](https://github.com/megagonlabs/UD_Japanese-GSD) ⭐ 28 \| 🐛 0 \| 🌐 Python \| 📅 2023-03-24               | -              | -               | ⭐ 28  | 🔴 may 2022       |
| 🔗 [KWDLC](https://github.com/ku-nlp/KWDLC) ⭐ 84 \| 🐛 12 \| 🌐 Python \| 📅 2023-12-18                                        | -              | -               | ⭐ 84  | 🔴 december 2023  |
| 🔗 [AnnotatedFKCCorpus](https://github.com/ku-nlp/AnnotatedFKCCorpus) ⭐ 18 \| 🐛 0 \| 🌐 Python \| 📅 2023-12-18               | -              | -               | ⭐ 18  | 🔴 december 2023  |
| 🔗 [anthy](https://github.com/netsphere-labs/anthy) ⭐ 16 \| 🐛 4 \| 🌐 C \| 📅 2023-02-25                                      | -              | -               | ⭐ 16  | 🔴 february 2023  |
| 🔗 [UD\_Japanese-GSDLUW](https://github.com/UniversalDependencies/UD_Japanese-GSDLUW) ⭐ 3 \| 🐛 0 \| 📅 2026-05-06             | -              | -               | ⭐ 3   | 🟡 may            |
| 🔗 [ud\_japanese-bccwj](https://github.com/universaldependencies/ud_japanese-bccwj) ⭐ 27 \| 🐛 0 \| 🌐 Python \| 📅 2026-05-06 | -              | -               | ⭐ 27  | 🟡 may            |

### Parallel corpus

Bilingual corpora containing aligned sentences for translation tasks

* [cjk-compsci-terms](https://github.com/dahlia/cjk-compsci-terms) ⭐ 155 | 🐛 3 | 🌐 TypeScript | 📅 2026-02-20 - CJK computer science terms comparison / 中日韓電腦科學術語對照 / 日中韓のコンピュータ科学の用語対照 / 한·중·일 전산학 용어 대조
* [small\_parallel\_enja](https://github.com/odashi/small_parallel_enja) ⭐ 97 | 🐛 0 | 🌐 Roff | 📅 2019-09-11 - 50k English-Japanese Parallel Corpus for Machine Translation Benchmark.
* [JESC](https://github.com/rpryzant/JESC) ⭐ 91 | 🐛 0 | 🌐 Python | 📅 2017-11-01 - A large parallel corpus of English and Japanese
* [Laboro-ParaCorpus](https://github.com/laboroai/Laboro-ParaCorpus) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2021-11-09 - Scripts for creating a Japanese-English parallel corpus and training NMT models
* [Web-Crawled-Corpus-for-Japanese-Chinese-NMT](https://github.com/zhang-jinyi/Web-Crawled-Corpus-for-Japanese-Chinese-NMT) ⭐ 16 | 🐛 0 | 📅 2023-09-30 - A Web Crawled Corpus for Japanese-Chinese NMT
* [CourseraParallelCorpusMining](https://github.com/shyyhs/CourseraParallelCorpusMining) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2024-08-27 - Coursera Corpus Mining and Multistage Fine-Tuning for Improving Lectures Translation
* [AMI-Meeting-Parallel-Corpus](https://github.com/tsuruoka-lab/AMI-Meeting-Parallel-Corpus) ⭐ 13 | 🐛 0 | 📅 2020-12-11 - AMI Meeting Parallel Corpus
* [matcha](https://github.com/ehimenlp/matcha) ⭐ 7 | 🐛 0 | 📅 2026-05-30 - 訪日観光客向けメディアMATCHAの記事から、日本語のテキスト平易化のためのデータセットを構築しました。
* [graded-enja-corpus](https://github.com/marmooo/graded-enja-corpus) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2025-08-25 - 禁止用語や単語レベルを考慮した日英対訳コーパスです。
* [giant\_ja-en\_parallel\_corpus](https://github.com/DayuanJiang/giant_ja-en_parallel_corpus) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2019-08-04 - This directory includes a giant Japanese-English subtitle corpus. The raw data comes from the Stanford’s JESC project.
* [google-vs-deepl-je](https://github.com/Tzawa/google-vs-deepl-je) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2020-03-22 - google-vs-deepl-je
* [jesc\_small](https://github.com/yusugomori/jesc_small) ⭐ 3 | 🐛 1 | 📅 2019-07-06 - Small Japanese-English Subtitle Corpus
* [en-ja-el](https://github.com/shigashiyama/en-ja-el) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-01-29 - EnJaEL: En-Ja Parallel Entity Linking Dataset (Version 1.0)

| Name                                                                                                                                                       | downloads/week | total downloads | stars | last commit       |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------- | --------------- | ----- | ----------------- |
| 🔗 [small\_parallel\_enja](https://github.com/odashi/small_parallel_enja) ⭐ 97 \| 🐛 0 \| 🌐 Roff \| 📅 2019-09-11                                         | -              | -               | ⭐ 97  | 🔴 september 2019 |
| 🔗 [Web-Crawled-Corpus-for-Japanese-Chinese-NMT](https://github.com/zhang-jinyi/Web-Crawled-Corpus-for-Japanese-Chinese-NMT) ⭐ 16 \| 🐛 0 \| 📅 2023-09-30 | -              | -               | ⭐ 16  | 🔴 september 2023 |
| 🔗 [CourseraParallelCorpusMining](https://github.com/shyyhs/CourseraParallelCorpusMining) ⭐ 15 \| 🐛 0 \| 🌐 Python \| 📅 2024-08-27                       | -              | -               | ⭐ 15  | 🔴 august 2024    |
| 🔗 [JESC](https://github.com/rpryzant/JESC) ⭐ 91 \| 🐛 0 \| 🌐 Python \| 📅 2017-11-01                                                                     | -              | -               | ⭐ 90  | 🔴 november 2017  |
| 🔗 [AMI-Meeting-Parallel-Corpus](https://github.com/tsuruoka-lab/AMI-Meeting-Parallel-Corpus) ⭐ 13 \| 🐛 0 \| 📅 2020-12-11                                | -              | -               | ⭐ 13  | 🔴 december 2020  |
| 🔗 [giant\_ja-en\_parallel\_corpus](https://github.com/DayuanJiang/giant_ja-en_parallel_corpus) ⭐ 5 \| 🐛 0 \| 🌐 Python \| 📅 2019-08-04                  | -              | -               | ⭐ 5   | 🔴 august 2019    |
| 🔗 [jesc\_small](https://github.com/yusugomori/jesc_small) ⭐ 3 \| 🐛 1 \| 📅 2019-07-06                                                                    | -              | -               | ⭐ 3   | 🔴 july 2019      |
| 🔗 [graded-enja-corpus](https://github.com/marmooo/graded-enja-corpus) ⭐ 6 \| 🐛 0 \| 🌐 JavaScript \| 📅 2025-08-25                                       | -              | -               | ⭐ 6   | 🔴 august 2025    |
| 🔗 [cjk-compsci-terms](https://github.com/dahlia/cjk-compsci-terms) ⭐ 155 \| 🐛 3 \| 🌐 TypeScript \| 📅 2026-02-20                                        | -              | -               | ⭐ 154 | 🟡 february       |
| 🔗 [Laboro-ParaCorpus](https://github.com/laboroai/Laboro-ParaCorpus) ⭐ 19 \| 🐛 0 \| 🌐 Python \| 📅 2021-11-09                                           | -              | -               | ⭐ 19  | 🔴 november 2021  |
| 🔗 [google-vs-deepl-je](https://github.com/Tzawa/google-vs-deepl-je) ⭐ 4 \| 🐛 0 \| 🌐 Python \| 📅 2020-03-22                                             | -              | -               | ⭐ 4   | 🔴 march 2020     |
| 🔗 [matcha](https://github.com/ehimenlp/matcha) ⭐ 7 \| 🐛 0 \| 📅 2026-05-30                                                                               | -              | -               | ⭐ 7   | 🟡 may            |
| 🔗 [en-ja-el](https://github.com/shigashiyama/en-ja-el) ⭐ 2 \| 🐛 0 \| 🌐 Python \| 📅 2025-01-29                                                          | -              | -               | ⭐ 2   | 🔴 january 2025   |

### Dialog corpus

Collections of conversation data for training dialogue systems

* [open2ch-dialogue-corpus](https://github.com/1never/open2ch-dialogue-corpus) ⭐ 102 | 🐛 0 | 🌐 Python | 📅 2021-06-06 - おーぷん2ちゃんねるをクロールして作成した対話コーパス
* [llm-japanese-dataset](https://github.com/masanorihirano/llm-japanese-dataset) ⭐ 88 | 🐛 6 | 🌐 Python | 📅 2024-01-23 - LLM構築用の日本語チャットデータセット
* [BSD](https://github.com/tsuruoka-lab/BSD) ⭐ 75 | 🐛 0 | 📅 2021-11-10 - The Business Scene Dialogue corpus
* [japanese-daily-dialogue](https://github.com/jqk09a/japanese-daily-dialogue) ⭐ 60 | 🐛 1 | 📅 2023-03-17 - Japanese Daily Dialogue, or 日本語日常対話コーパス in Japanese, is a high-quality multi-turn dialogue dataset containing daily conversations on five topics: dailylife, school, travel, health, and entertainment.
* [JMRD](https://github.com/ku-nlp/JMRD) ⭐ 30 | 🐛 0 | 📅 2022-07-19 - Japanese Movie Recommendation Dialogue dataset
* [asdc](https://github.com/megagonlabs/asdc) ⭐ 25 | 🐛 12 | 🌐 Python | 📅 2024-01-19 - Accommodation Search Dialog Corpus (宿泊施設探索対話コーパス)
* [kokorochat](https://github.com/uec-inabalab/kokorochat) ⭐ 23 | 🐛 1 | 📅 2026-05-03 - ロールプレイで収集した日本語のカウンセリング対話データセット
* [ETCDataset](https://github.com/UEC-InabaLab/ETCDataset) ⭐ 13 | 🐛 1 | 📅 2026-05-26 - Emotion Transcription in Conversation Dataset は，対話中の各発話に対して話者自身が記述した心情文を含む，約1,000 件の対話からなる日本語対話データセットです．
* [BPersona-chat](https://github.com/cl-tohoku/BPersona-chat) ⭐ 6 | 🐛 0 | 📅 2023-01-12 - This repository contains the Japanese–English bilingual chat corpus BPersona-chat published in the paper Chat Translation Error Detection for Assisting Cross-lingual Communications at AACL-IJCNLP 2022's Workshop Eval4NLP 2022.
* [japanese-corpus](https://github.com/MokkeMeguru/japanese-corpus) ⭐ 4 | 🐛 0 | 📅 2018-10-09 - 日本語の対話データ for seq2seq etc
* [JMultiWOZ-TC](https://github.com/llm-jp/JMultiWOZ-TC) ⭐ 4 | 🐛 2 | 🌐 Python | 📅 2026-08-17 - マルチターン対話でのエージェントのfunction calling評価
* [HOTATE](https://github.com/EhimeNLP/HOTATE) ⭐ 1 | 🐛 0 | 📅 2026-06-17 - 本音・建前付き日本語対話データセット

| Name                                                                                                                         | downloads/week | total downloads | stars | last commit      |
| ---------------------------------------------------------------------------------------------------------------------------- | -------------- | --------------- | ----- | ---------------- |
| 🔗 [JMRD](https://github.com/ku-nlp/JMRD) ⭐ 30 \| 🐛 0 \| 📅 2022-07-19                                                      | -              | -               | ⭐ 29  | 🔴 july 2022     |
| 🔗 [open2ch-dialogue-corpus](https://github.com/1never/open2ch-dialogue-corpus) ⭐ 102 \| 🐛 0 \| 🌐 Python \| 📅 2021-06-06  | -              | -               | ⭐ 102 | 🔴 june 2021     |
| 🔗 [BSD](https://github.com/tsuruoka-lab/BSD) ⭐ 75 \| 🐛 0 \| 📅 2021-11-10                                                  | -              | -               | ⭐ 75  | 🔴 november 2021 |
| 🔗 [asdc](https://github.com/megagonlabs/asdc) ⭐ 25 \| 🐛 12 \| 🌐 Python \| 📅 2024-01-19                                   | -              | -               | ⭐ 25  | 🔴 august 2023   |
| 🔗 [japanese-corpus](https://github.com/MokkeMeguru/japanese-corpus) ⭐ 4 \| 🐛 0 \| 📅 2018-10-09                            | -              | -               | ⭐ 4   | 🔴 october 2018  |
| 🔗 [BPersona-chat](https://github.com/cl-tohoku/BPersona-chat) ⭐ 6 \| 🐛 0 \| 📅 2023-01-12                                  | -              | -               | ⭐ 6   | 🔴 january 2023  |
| 🔗 [japanese-daily-dialogue](https://github.com/jqk09a/japanese-daily-dialogue) ⭐ 60 \| 🐛 1 \| 📅 2023-03-17                | -              | -               | ⭐ 60  | 🔴 march 2023    |
| 🔗 [llm-japanese-dataset](https://github.com/masanorihirano/llm-japanese-dataset) ⭐ 88 \| 🐛 6 \| 🌐 Python \| 📅 2024-01-23 | -              | -               | ⭐ 88  | 🔴 january 2024  |
| 🔗 [kokorochat](https://github.com/uec-inabalab/kokorochat) ⭐ 23 \| 🐛 1 \| 📅 2026-05-03                                    | -              | -               | ⭐ 23  | 🟡 may           |
| 🔗 [JMultiWOZ-TC](https://github.com/llm-jp/JMultiWOZ-TC) ⭐ 4 \| 🐛 2 \| 🌐 Python \| 📅 2026-08-17                          | -              | -               | ⭐ 4   | 🟢 july          |
| 🔗 [HOTATE](https://github.com/EhimeNLP/HOTATE) ⭐ 1 \| 🐛 0 \| 📅 2026-06-17                                                 | -              | -               | ⭐ 1   | 🟢 june          |
| 🔗 [ETCDataset](https://github.com/UEC-InabaLab/ETCDataset) ⭐ 13 \| 🐛 1 \| 📅 2026-05-26                                    | -              | -               | ⭐ 13  | 🟡 may           |

### Others

Corpora for tasks such as question answering or entailment recognition

* [engineer-vocabulary-list](https://github.com/mercari/engineer-vocabulary-list) ⭐ 1,973 | 🐛 1 | 📅 2022-12-03 - Engineer Vocabulary List in Japanese/English
* [japanese-addresses](https://github.com/geolonia/japanese-addresses) ⭐ 770 | 🐛 26 | 🌐 JavaScript | 📅 2026-08-05 - 全国の町丁目レベル（277,191件）の住所データのオープンデータ
* [kanji-data-media](https://github.com/kanjialive/kanji-data-media) ⭐ 426 | 🐛 4 | 📅 2026-07-29 - Japanese language data on kanji, radicals, media files, fonts and related resources from Kanji alive
* [gimei](https://github.com/willnet/gimei) ⭐ 426 | 🐛 9 | 🌐 Ruby | 📅 2026-08-17 - random Japanese name and address generator
* [reazonspeech](https://github.com/reazon-research/reazonspeech) ⭐ 396 | 🐛 13 | 🌐 Python | 📅 2026-06-10 - Construct large-scale Japanese audio corpus at home
* [animedb](https://github.com/anilogia/animedb) ⭐ 332 | 🐛 9 | 🌐 Python | 📅 2023-10-26 - 約100年に渡るアニメ作品リストデータベース
* [lawqa\_jp](https://github.com/digital-go-jp/lawqa_jp) ⭐ 276 | 🐛 0 | 📅 2026-02-13 - 日本の法令に関する多肢選択式QAデータセット
* [ita-corpus](https://github.com/mmorise/ita-corpus) ⭐ 241 | 🐛 1 | 📅 2026-07-03 - ITAコーパスの文章リスト
* [jtubespeech](https://github.com/sarulab-speech/jtubespeech) ⭐ 233 | 🐛 8 | 🌐 Python | 📅 2023-11-13 - JTubeSpeech: Corpus of Japanese speech collected from YouTube
* [kanji-data](https://github.com/davidluzgouveia/kanji-data) ⭐ 231 | 🐛 3 | 🌐 Python | 📅 2026-02-27 - A JSON kanji dataset with updated JLPT levels and WaniKani information
* [phishurl-list](https://github.com/JPCERTCC/phishurl-list) ⭐ 210 | 🐛 0 | 🌐 HTML | 📅 2026-06-29 - Phishing URL dataset from JPCERT/CC
* [inappropriate-words-ja](https://github.com/MosasoM/inappropriate-words-ja) ⭐ 208 | 🐛 0 | 🌐 Python | 📅 2021-12-01 - 日本語における不適切表現を収集します。自然言語処理の時のデータクリーニング用等に使えると思います。
* [topokanji](https://github.com/scriptin/topokanji) ⭐ 206 | 🐛 1 | 🌐 JavaScript | 📅 2023-03-24 - Topologically ordered lists of kanji for effective learning
* [open-mantra-dataset](https://github.com/mantra-inc/open-mantra-dataset) ⭐ 203 | 🐛 0 | 📅 2023-03-18 - Dataset introduced in the paper "Towards Fully Automated Manga Translation" presented in AAAI21
* [PAX\_SAPIENTICA](https://github.com/AsPJT/PAX_SAPIENTICA) ⭐ 189 | 🐛 1 | 🌐 C++ | 📅 2026-01-31 - GIS & Archaeological Simulator. 2023 in development.
* [house-of-representatives](https://github.com/smartnews-smri/house-of-representatives) ⭐ 181 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-20 - 国会議案データベース：衆議院
* [wrime](https://github.com/ids-cv/wrime) ⭐ 178 | 🐛 3 | 📅 2025-09-11 - WRIME: 主観と客観の感情分析データセット
* [awesome-japan-opendata](https://github.com/japan-opendata/awesome-japan-opendata) ⭐ 167 | 🐛 1 | 📅 2026-08-13 - Awesome Japan Open Data - 日本のオープンデータ情報一覧・まとめ
* [kanji-frequency](https://github.com/scriptin/kanji-frequency) ⭐ 165 | 🐛 10 | 🌐 Astro | 📅 2026-06-20 - Kanji usage frequency data collected from various sources
* [lawhub](https://github.com/lwhb/lawhub) ⭐ 153 | 🐛 76 | 📅 2020-11-17 - Repository to track Japanese Law in text format
* [chABSA-dataset](https://github.com/chakki-works/chABSA-dataset) ⭐ 143 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2022-02-25 - chakki's Aspect-Based Sentiment Analysis dataset
* [ja.text8](https://github.com/Hironsan/ja.text8) ⭐ 112 | 🐛 0 | 🌐 Python | 📅 2017-10-04 - Japanese text8 corpus for word embedding.
* [JaQuAD](https://github.com/SkelterLabsInc/JaQuAD) ⭐ 111 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2022-03-02 - JaQuAD: Japanese Question Answering Dataset for Machine Reading Comprehension (2022, Skelter Labs)
* [house-of-councillors](https://github.com/smartnews-smri/house-of-councillors) ⭐ 109 | 🐛 1 | 🌐 Python | 📅 2026-08-20 - 参議院の公式ウェブサイトから会派、議員、議案、質問主意書のデータを整理しました。
* [pfgen-bench](https://github.com/pfnet-research/pfgen-bench) ⭐ 107 | 🐛 1 | 🌐 Python | 📅 2026-08-07 - Preferred Generation Benchmark
* [JapaneseWordSimilarityDataset](https://github.com/tmu-nlp/JapaneseWordSimilarityDataset) ⭐ 103 | 🐛 0 | 🌐 Python | 📅 2021-12-07 - Japanese Word Similarity Dataset
* [NMeCab](https://github.com/komutan/NMeCab) ⭐ 103 | 🐛 9 | 🌐 C# | 📅 2024-03-30 - NMeCab: About Japanese morphological analyzer on .NET
* [lawtext](https://github.com/yamachig/lawtext) ⭐ 100 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-19 - Plain text format for Japanese law
* [aozorabunko\_text](https://github.com/aozorahack/aozorabunko_text) ⭐ 95 | 🐛 0 | 🌐 Ruby | 📅 2023-03-22 - text-only archives of [www.aozora.gr.jp](http://www.aozora.gr.jp)
* [CoARiJ](https://github.com/chakki-works/CoARiJ) ⭐ 94 | 🐛 4 | 🌐 Python | 📅 2020-12-19 - Corpus of Annual Reports in Japan
* [japanese](https://github.com/hingston/japanese) ⭐ 91 | 🐛 0 | 📅 2026-07-27 - This repo contains a list of the 44,998 most common Japanese words in order of frequency, as determined by the University of Leeds Corpus.
* [jlpt-word-list](https://github.com/elzup/jlpt-word-list) ⭐ 91 | 🐛 0 | 🌐 JavaScript | 📅 2023-04-04 - Japanese word list from JLPT vocabulary
* [STAIR-captions](https://github.com/STAIR-Lab-CIT/STAIR-captions) ⭐ 90 | 🐛 1 | 📅 2018-07-04 - STAIR captions: large-scale Japanese image caption dataset
* [databricks-dolly-15k-ja](https://github.com/kunishou/databricks-dolly-15k-ja) ⭐ 89 | 🐛 4 | 📅 2023-07-25 - databricks/dolly-v2-12b の学習データに使用されたdatabricks-dolly-15k.jsonl を日本語に翻訳したデータセットになります。
* [alpaca\_ja](https://github.com/shi3z/alpaca_ja) ⭐ 86 | 🐛 3 | 📅 2023-06-03 - alpacaデータセットを日本語化したものです
* [emoji-ja](https://github.com/yagays/emoji-ja) ⭐ 83 | 🐛 0 | 🌐 Python | 📅 2025-03-19 - UNICODE絵文字の日本語読み/キーワード/分類辞書
* [pdmocrdataset-part1](https://github.com/ndl-lab/pdmocrdataset-part1) ⭐ 81 | 🐛 0 | 📅 2024-06-26 - デジタル化資料OCRテキスト化事業において作成されたOCR学習用データセット
* [wikipedia-utils](https://github.com/singletongue/wikipedia-utils) ⭐ 78 | 🐛 1 | 🌐 Python | 📅 2024-04-09 - Utility scripts for preprocessing Wikipedia texts for NLP
* [jrte-corpus](https://github.com/megagonlabs/jrte-corpus) ⭐ 77 | 🐛 0 | 🌐 Python | 📅 2023-06-23 - Japanese Realistic Textual Entailment Corpus (NLP 2020, LREC 2020)
* [rohan4600](https://github.com/mmorise/rohan4600) ⭐ 73 | 🐛 1 | 🌐 HTML | 📅 2026-03-13 - モーラバランス型日本語コーパス
* [Kokoro-Speech-Dataset](https://github.com/kaiidams/Kokoro-Speech-Dataset) ⭐ 69 | 🐛 1 | 🌐 Python | 📅 2026-04-14 - A public domain single speaker Japanese speech dataset
* [koniwa](https://github.com/koniwa/koniwa) ⚠️ Archived - An open collection of annotated voices in Japanese language
* [yjcaptions](https://github.com/yahoojapan/yjcaptions) ⭐ 60 | 🐛 0 | 📅 2016-11-29 - YJ Captions 26k Dataset
* [jmed-llm](https://github.com/sociocom/jmed-llm) ⭐ 59 | 🐛 0 | 🌐 Python | 📅 2024-09-22 - JMED-LLM: Japanese Medical Evaluation Dataset for Large Language Models
* [data\_set](https://github.com/japanese-law-analysis/data_set) ⭐ 53 | 🐛 0 | 📅 2025-01-08 - 法律・判例関係のデータセット
* [hurigana-speech-corpus-aozora](https://github.com/ndl-lab/hurigana-speech-corpus-aozora) ⭐ 50 | 🐛 1 | 📅 2025-03-07 - 青空文庫振り仮名注釈付き音声コーパスのデータセット
* [japanese-llm-benchmark](https://github.com/shi3z/japanese-llm-benchmark) ⭐ 49 | 🐛 0 | 🌐 Python | 📅 2026-07-25 - A benchmark tool for evaluating Japanese language capabilities of various LLMs.
* [llm-jp-corpus](https://github.com/llm-jp/llm-jp-corpus) ⭐ 48 | 🐛 4 | 🌐 Python | 📅 2024-02-02 - This repository contains scripts to reproduce the LLM-jp corpus.
* [JSICK](https://github.com/verypluming/JSICK) ⭐ 46 | 🐛 0 | 📅 2023-05-31 - Japanese Sentences Involving Compositional Knowledge (JSICK) Dataset/JSICK-stress Test Set
* [jqara](https://github.com/hotchpotch/jqara) ⭐ 45 | 🐛 0 | 🌐 Python | 📅 2025-09-09 - JQaRA: Japanese Question Answering with Retrieval Augmentation - 検索拡張(RAG)評価のための日本語Q\&Aデータセット
* [hdic](https://github.com/shikeda/hdic) ⭐ 44 | 🐛 3 | 📅 2026-08-19 - HDIC : Integrated Database of Hanzi Dictionaries in Early Japan
* [JMMLU](https://github.com/nlp-waseda/JMMLU) ⭐ 41 | 🐛 0 | 📅 2025-10-07 - 日本語マルチタスク言語理解ベンチマーク Japanese Massive Multitask Language Understanding Benchmark
* [EDINET-Bench](https://github.com/SakanaAI/EDINET-Bench) ⭐ 36 | 🐛 1 | 🌐 Python | 📅 2026-03-06 - ICLR 2026 Evaluating the performance of LLMs on Japanese challenging financial tasks.
* [nayose-wikipedia-ja](https://github.com/yagays/nayose-wikipedia-ja) ⭐ 35 | 🐛 0 | 🌐 Python | 📅 2020-03-10 - Wikipediaから作成した日本語名寄せデータセット
* [wikihow\_japanese](https://github.com/Katsumata420/wikihow_japanese) ⭐ 35 | 🐛 0 | 🌐 HTML | 📅 2020-12-17 - wikiHow dataset (Japanese version)
* [jconj](https://github.com/yamagoya/jconj) ⭐ 35 | 🐛 1 | 🌐 Python | 📅 2020-05-26 - A table-based Japanese word conjugator
* [jlpt-kanji-dictionary](https://github.com/AnchorI/jlpt-kanji-dictionary) ⭐ 34 | 🐛 0 | 📅 2025-05-02 - Structured Japanese Kanji and Vocabulary JSON datasets organized by JLPT level with English and Russian translations — ready for use in language learning apps, NLP, and kanji study tools.
* [simple-jppdb](https://github.com/tmu-nlp/simple-jppdb) ⭐ 32 | 🐛 0 | 🌐 Python | 📅 2017-03-12 - A paraphrase database for Japanese text simplification
* [huriganacorpus-ndlbib](https://github.com/ndl-lab/huriganacorpus-ndlbib) ⭐ 32 | 🐛 0 | 📅 2021-09-21 - 全国書誌データから作成した振り仮名のデータセット
* [ThreeLineSummaryDataset](https://github.com/KodairaTomonori/ThreeLineSummaryDataset) ⭐ 31 | 🐛 1 | 📅 2018-04-04 - 3行要約データセット
* [jvs\_hiho](https://github.com/Hiroshiba/jvs_hiho) ⭐ 31 | 🐛 0 | 🌐 Shell | 📅 2021-04-11 - JVS (Japanese versatile speech) コーパスの自作のラベル
* [comet-atomic-ja](https://github.com/nlp-waseda/comet-atomic-ja) ⭐ 31 | 🐛 0 | 🌐 Python | 📅 2024-03-08 - COMET-ATOMIC ja
* [jemhopqa](https://github.com/aiishii/jemhopqa) ⭐ 30 | 🐛 0 | 🌐 Python | 📅 2025-04-10 - JEMHopQA (Japanese Explainable Multi-hop Question Answering) is a Japanese multi-hop QA dataset that can evaluate internal reasoning.
* [WikipediaAnnotatedCorpus](https://github.com/ku-nlp/WikipediaAnnotatedCorpus) ⭐ 30 | 🐛 0 | 🌐 Python | 📅 2026-08-01 - This is a Japanese text corpus that consists of Wikipedia articles with various linguistic annotations.
* [kanji](https://github.com/sylhare/kanji) ⭐ 30 | 🐛 9 | 🌐 Python | 📅 2026-08-08 - List of japanese kanji radicals to learn
* [ja-vg-vqa](https://github.com/yahoojapan/ja-vg-vqa) ⭐ 30 | 🐛 1 | 📅 2018-11-15 - Japanese Visual Genome VQA dataset
* [kanji-data](https://github.com/mimneko/kanji-data) ⭐ 28 | 🐛 1 | 📅 2026-06-26 - 常用漢字表他、漢字に関するデータ
* [TEDxJP-10K](https://github.com/laboroai/TEDxJP-10K) ⭐ 27 | 🐛 1 | 🌐 Python | 📅 2021-01-14 - TEDxJP-10K ASR Evaluation Dataset
* [security\_words](https://github.com/SaitoLab/security_words) ⭐ 27 | 🐛 0 | 📅 2023-08-18 - サイバーセキュリティに関連する公的な組織の日英対応
* [technological-book-corpus-ja](https://github.com/textlint-ja/technological-book-corpus-ja) ⭐ 26 | 🐛 1 | 🌐 JavaScript | 📅 2026-04-08 - 日本語で書かれた技術書を収集した生コーパス/ツール
* [camera](https://github.com/CyberAgentAILab/camera) ⚠️ Archived - CAMERA (CyberAgent Multimodal Evaluation for Ad Text GeneRAtion) is the Japanese ad text generation dataset.
* [instruction\_ja](https://github.com/megagonlabs/instruction_ja) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2023-07-13 - Japanese instruction data (日本語指示データ)
* [do-not-answer-ja](https://github.com/kunishou/do-not-answer-ja) ⭐ 24 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2023-12-15 - 2023年8月にメルボルン大学から公開された安全性評価データセット『Do-Not-Answer』を日本語LLMの評価においても使用できるように日本語に自動翻訳し、さらに日本文化も考慮して修正したデータセット。
* [huriganacorpus-aozora](https://github.com/ndl-lab/huriganacorpus-aozora) ⭐ 23 | 🐛 0 | 📅 2024-01-17 - 青空文庫及びサピエの点字データから作成した振り仮名のデータセット
* [ajimee-bench](https://github.com/azookey/ajimee-bench) ⭐ 23 | 🐛 2 | 🌐 Python | 📅 2025-01-13 - AJIMEE-Bench (Advanced Japanese IME Evaluation Benchmark)
* [honkoku-data](https://github.com/yuta1984/honkoku-data) ⭐ 22 | 🐛 1 | 📅 2026-08-16 - 歴史資料の市民参加型翻刻プラットフォーム「みんなで翻刻」のテキストデータ置き場です。 / Transcription texts created on Minna de Honkoku (<https://honkoku.org>), a crowdsourced transcription platform for historical Japanese documents.
* [ndl-minhon-ocrdataset](https://github.com/ndl-lab/ndl-minhon-ocrdataset) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2026-03-13 - NDL古典籍OCR学習用データセット（みんなで翻刻加工データ）
* [japanese-toxic-dataset](https://github.com/inspection-ai/japanese-toxic-dataset) ⭐ 22 | 🐛 2 | 📅 2023-01-11 - "Proposal and Evaluation of Japanese Toxicity Schema" provides a schema and dataset for toxicity in the Japanese language.
* [Japanese-RP-Bench](https://github.com/Aratako/Japanese-RP-Bench) ⭐ 22 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-09-29 - Japanese-RP-BenchはLLMの日本語ロールプレイ能力を測定するためのベンチマークです。
* [keigo\_transfer\_task](https://github.com/cl-tohoku/keigo_transfer_task) ⭐ 21 | 🐛 0 | 📅 2022-11-24 - 敬語変換タスクにおける評価用データセット
* [Japanese-Fakenews-Dataset](https://github.com/tanreinama/Japanese-Fakenews-Dataset) ⭐ 21 | 🐛 0 | 📅 2021-05-02 - 日本語フェイクニュースデータセット
* [aozorasearch](https://github.com/myokoym/aozorasearch) ⭐ 21 | 🐛 9 | 🌐 Ruby | 📅 2026-06-09 - The full-text search system for Aozora Bunko by Groonga. 青空文庫全文検索ライブラリ兼Webアプリ。
* [extract\_jawp\_names](https://github.com/hiroshi-manabe/extract_jawp_names) ⭐ 21 | 🐛 0 | 🌐 Perl | 📅 2022-12-06 - Extracts personal names in Wikipedia Japanese.
* [loanwords\_gairaigo](https://github.com/jamesohortle/loanwords_gairaigo) ⭐ 19 | 🐛 3 | 🌐 Python | 📅 2024-10-24 - English loanwords in Japanese
* [ebe-dataset](https://github.com/megagonlabs/ebe-dataset) ⭐ 18 | 🐛 0 | 🌐 PLSQL | 📅 2020-12-17 - Evidence-based Explanation Dataset (AACL-IJCNLP 2020)
* [japanese-family-names](https://github.com/siikamiika/japanese-family-names) ⭐ 18 | 🐛 1 | 🌐 Python | 📅 2017-09-27 - Top 5000 Japanese family names, with readings, ordered by frequency.
* [niilc-qa](https://github.com/mynlp/niilc-qa) ⭐ 18 | 🐛 0 | 📅 2015-11-20 - NIILC QA data
* [hiragana\_mojigazo](https://github.com/ndl-lab/hiragana_mojigazo) ⭐ 18 | 🐛 0 | 📅 2020-04-06 - 文字画像データセット(平仮名73文字版)
* [JaNLI](https://github.com/verypluming/JaNLI) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2023-05-31 - Japanese Adversarial Natural Language Inference Dataset
* [ndlngramdata](https://github.com/ndl-lab/ndlngramdata) ⭐ 17 | 🐛 0 | 📅 2023-01-10 - デジタル化資料から作成したOCRテキストデータのngram頻度統計情報のデータセット
* [oasst1-89k-ja](https://github.com/kunishou/oasst1-89k-ja) ⭐ 16 | 🐛 2 | 🌐 Python | 📅 2023-11-19 - OpenAssistant のオープンソースデータ OASST1 を日本語に翻訳したデータセットになります。
* [commonsense-moral-ja](https://github.com/Language-Media-Lab/commonsense-moral-ja) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2025-11-20 - JCommonsenseMorality is a dataset created through crowdsourcing that reflects the commonsense morality of Japanese annotators.
* [pdmocrdataset-part2](https://github.com/ndl-lab/pdmocrdataset-part2) ⭐ 15 | 🐛 0 | 📅 2024-06-26 - OCR処理プログラム研究開発事業において作成されたOCR学習用データセット
* [jfbench](https://github.com/pfnet-research/jfbench) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2026-08-06 - JFBench: Japanese instruction Following Benchmark
* [huggingface-datasets\_JGLUE](https://github.com/shunk031/huggingface-datasets_JGLUE) ⭐ 14 | 🐛 8 | 🌐 Python | 📅 2025-03-31 - JGLUE: Japanese General Language Understanding Evaluation for huggingface datasets
* [japanese-address-testdata](https://github.com/t-sagara/japanese-address-testdata) ⭐ 14 | 🐛 0 | 📅 2023-09-25 - 解析が難しい日本の住所のテストデータセット
* [cejc\_yomichan\_freq\_dict](https://github.com/forsakeninfinity/cejc_yomichan_freq_dict) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2023-06-23 - Frequency dictionary for yomichan based on the Corpus of Everyday Japanese Conversation dataset
* [j-liwc2015](https://github.com/tasukuigarashi/j-liwc2015) ⭐ 13 | 🐛 0 | 📅 2024-11-06 - Japanese version of LIWC2015
* [WLSP-familiarity](https://github.com/masayu-a/WLSP-familiarity) ⭐ 13 | 🐛 1 | 📅 2025-01-02 - Word Familiarity Rate for 'Word List by Semantic Principles (WLSP)'
* [JSeM](https://github.com/DaisukeBekki/JSeM) ⭐ 13 | 🐛 4 | 🌐 HTML | 📅 2026-04-21 - Japanese semantic test suite (FraCaS counterpart and extensions)
* [public-annotations](https://github.com/manga109/public-annotations) ⭐ 13 | 🐛 0 | 📅 2025-04-23 - Various annotations of Manga109 dataset
* [J-CRe3](https://github.com/riken-grp/J-CRe3) ⭐ 11 | 🐛 0 | 📅 2025-01-04 - Code for J-CRe3 experiments (Ueda et al., LREC-COLING, 2024)
* [j-ono-data](https://github.com/ObakeConstructs/j-ono-data) ⭐ 11 | 🐛 5 | 📅 2026-07-31 - A simple, open-source collection of Japanese onomatopoeic and mimetic sound words in JSON format. With manga samples.
* [jmle2026-bench](https://github.com/naoto-iwase/jmle2026-bench) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2026-06-10 - LLM benchmark on the 120th Japanese Medical Licensing Examination (Feb 7-8, 2026)
* [j-tau-bench](https://github.com/sbintuitions/j-tau-bench) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2026-08-13 - J-tau: A Japanese tau-bench for Benchmarking Tool-Agent-User Interaction in Real-World Domains
* [meconaudio](https://github.com/elith-co-jp/meconaudio) ⭐ 10 | 🐛 0 | 📅 2023-10-25 - Mecon Audio(Medical Conference Audio)は厚生労働省主催の先進医療会議の議事録の読み上げデータセットです。
* [nwjc](https://github.com/masayu-a/nwjc) ⭐ 10 | 🐛 0 | 📅 2026-05-13 - NINJAL Web Japanese Corpus
* [jcms](https://github.com/shigashiyama/jcms) ⭐ 9 | 🐛 0 | 🌐 Mask | 📅 2026-04-03 - A Japanese Corpus of Many Specialized Domains (JCMS)
* [jacwir](https://github.com/hotchpotch/jacwir) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2025-09-09 - JaCWIR: Japanese Casual Web IR - 日本語情報検索評価のための小規模でカジュアルなWebタイトルと概要のデータセット
* [j-unimorph](https://github.com/cl-tohoku/j-unimorph) ⭐ 9 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-22 - Dataset of UniMorph in Japanese
* [safety-boundary-test](https://github.com/sbintuitions/safety-boundary-test) ⭐ 9 | 🐛 0 | 🌐 Jinja | 📅 2026-04-14 - 日本語言語モデルの安全性の振る舞いを評価するテストセット
* [ramendb](https://github.com/nuko-yokohama/ramendb) ⭐ 8 | 🐛 2 | 🌐 Python | 📅 2026-04-25 - なんとかデータベース( <https://supleks.jp/> )からのスクレイピングツールと収集データ
* [jacred](https://github.com/youmima/jacred) ⭐ 8 | 🐛 2 | 📅 2024-03-08 - Repository for Japanese Document-level Relation Extraction Dataset (plan to be released in March).
* [elaws-history](https://github.com/kissge/elaws-history) ⭐ 8 | 🐛 0 | 📅 2026-08-20 - e-Gov 法令検索で配布されている「全ての法令データ」を定期的にダウンロードし、アーカイブしています
* [LookVQA](https://github.com/riken-grp/LookVQA) ⭐ 8 | 🐛 0 | 📅 2024-08-30 - A Gaze-grounded Visual Question Answering Dataset for Clarifying Ambiguous Japanese Questions (LREC-COLING 2024)
* [hirakanadic](https://github.com/po3rin/hirakanadic) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2023-07-08 - Allows Sudachi to normalize from hiragana to katakana from any compound word list
* [swallow-corpus](https://github.com/swallow-llm/swallow-corpus) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2024-11-23 - This repository provides Python implementation for building Swallow Corpus Version 1, a large Japanese web corpus (Okazaki et al., 2024), from Common Crawl archives.
* [waon](https://github.com/llm-jp/waon) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2025-11-02 - WAON: Large-Scale and High-Quality Japanese Image-Text Dataset for Vision-Language Models
* [jvs\_nonpara\_kana](https://github.com/CyberAgentAILab/jvs_nonpara_kana) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-06-17 - Katakana annotation of JVS nonpara corpus for G2P evaluation
* [Winograd-Schema-Challenge-Ja](https://github.com/ku-nlp/Winograd-Schema-Challenge-Ja) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2019-01-25 - Japanese Translation of Winograd Schema Challenge
* [GeneralPolicySpeechOfPrimeMinisterOfJapan](https://github.com/yuukimiyo/GeneralPolicySpeechOfPrimeMinisterOfJapan) ⭐ 6 | 🐛 0 | 📅 2020-01-14 - This is the corpus of Japanese Text that general policy speech of prime minister of Japan
* [dcsg-ja](https://github.com/nlp-waseda/dcsg-ja) ⭐ 6 | 🐛 0 | 📅 2023-03-10 - Dialogue Commonsense Graph in Japanese
* [jalecon](https://github.com/naist-nlp/jalecon) ⭐ 6 | 🐛 0 | 📅 2023-07-04 - A Dataset of Japanese Lexical Complexity for Non-Native Readers
* [wikidict-ja](https://github.com/open-dict-data/wikidict-ja) ⭐ 6 | 🐛 0 | 📅 2016-06-17 - Wikipedia Bilingual Reference Data (Japanese)
* [j-spaw](https://github.com/takamichi-lab/j-spaw) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2025-08-26 - J-SpAW: Japanese speech corpus for speaker verification and anti-spoofing
* [JTruthfulQA](https://github.com/nlp-waseda/JTruthfulQA) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2025-02-06 - JTruthfulQA is a Japanese version of TruthfulQA (Lin+, 2022). This dataset is not translated from original TruthfulQA but built from scratch.
* [medLLM\_QA\_benchmark](https://github.com/aistairc/medLLM_QA_benchmark) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2025-01-22 - Trilingual (English, Japanese, Chinese) QA benchmark for medical LLM
* [ita-corpus-chuwa](https://github.com/shirayu/ita-corpus-chuwa) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2021-08-25 - Chunked word annotation for ITA corpus
* [huggingface-datasets\_wrime](https://github.com/shunk031/huggingface-datasets_wrime) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2023-01-15 - WRIME for huggingface datasets
* [ProSub](https://github.com/matbahasa/ProSub) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2025-04-03 - A cross-linguistic study of pronoun substitutes and address terms
* [chain-of-thought-ja-dataset](https://github.com/nlp-waseda/chain-of-thought-ja-dataset) ⭐ 5 | 🐛 0 | 📅 2023-09-14 - Dataset of paper "Verification of Chain-of-Thought Prompting in Japanese"
* [kuci](https://github.com/ku-nlp/kuci) ⭐ 5 | 🐛 0 | 📅 2024-02-16 - Kyoto University Commonsense Inference dataset (KUCI)
* [LCTG-Bench](https://github.com/CyberAgentAILab/LCTG-Bench) ⚠️ Archived - LCTG Bench: LLM Controlled Text Generation Benchmark
* [bbh-ja](https://github.com/pfnet-research/bbh-ja) ⭐ 5 | 🐛 0 | 📅 2025-07-08 - Japanese Translation of BIG-Bench-Hard (<https://github.com/suzgunmirac/BIG-Bench-Hard/> ⭐ 569 | 🐛 11 | 📅 2024-06-25)
* [jawikicorpus](https://github.com/wikiwikification/jawikicorpus) ⭐ 4 | 🐛 0 | 📅 2018-11-24 - Japanese-Wikipedia Wikification Corpus
* [camera3](https://github.com/cyberagentailab/camera3) ⚠️ Archived - CAMERA3: An Evaluation Dataset for Controllable Ad Text Generation in Japanese
* [JMedWiC](https://github.com/EhimeNLP/JMedWiC) ⭐ 4 | 🐛 0 | 📅 2026-05-07 - マスク言語モデルを用いて擬似的な同義・非同義ペアを自動抽出し，人手による同義性アノテーションを通じてラベルを決定することで，日本語の医療分野における語義同一性判定データセットを構築しました．
* [speechBSD](https://github.com/ku-nlp/speechBSD) ⭐ 3 | 🐛 0 | 📅 2024-02-07 - An extension of the BSD corpus with audio and speaker attribute information
* [anlp-jp-history](https://github.com/whym/anlp-jp-history) ⭐ 3 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2024-04-05 - 言語処理学会年次大会講演の全リスト・機械可読版など
* [Data-on-Japanese-Diet-Members](https://github.com/sugi2000/Data-on-Japanese-Diet-Members) ⭐ 3 | 🐛 0 | 📅 2022-09-29 - 日本の国会議員のデータ
* [ndlngramviewer\_v2](https://github.com/ndl-lab/ndlngramviewer_v2) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2026-05-01 - 2023年1月にリニューアルしたNDL Ngram Viewerのソースコード等一式
* [huggingface-datasets\_livedoor-news-corpus](https://github.com/shunk031/huggingface-datasets_livedoor-news-corpus) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2023-10-28 - Japanese Livedoor news corpus for huggingface datasets
* [huggingface-datasets\_CAMERA](https://github.com/shunk031/huggingface-datasets_CAMERA) ⚠️ Archived - CAMERA (CyberAgent Multimodal Evaluation for Ad Text GeneRAtion) for huggingface datasets
* [japanese-technical-dict](https://github.com/laoshubaby/japanese-technical-dict) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2024-11-21 - 日本語学習者のための科学技術業界でよく使われる片仮名と元の単語対照表
* [japanesetopicwsd](https://github.com/nut-jnlp/japanesetopicwsd) ⭐ 3 | 🐛 0 | 📅 2018-09-27 - 話題に基づく語義曖昧性解消評価セット
* [tanaka-corpus-plus](https://github.com/marmooo/tanaka-corpus-plus) ⭐ 3 | 🐛 0 | 📅 2021-06-05 - Tanaka Corpus のノイズを除去しています。
* [kotowaza](https://github.com/septn/kotowaza) ⭐ 3 | 🐛 1 | 🌐 JavaScript | 📅 2026-02-15 - Structured JSON dataset of Japanese proverbs (kotowaza) with meanings in Indonesian & English, examples, JLPT levels, and tags.
* [jhpt](https://github.com/nict-astrec-att/jhpt) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-03-07 - 歴史的日本語資料の原文テキストと，現代語訳（参照訳）テキストをセグメント単位で対応付けた対訳データセットです．詳細は論文を参照ください．
* [WikipediaWordFrequencyList](https://github.com/maeda6uiui-backup/WikipediaWordFrequencyList) ⚠️ Archived - 日本語Wikipediaで使用される頻出単語のリスト
* [openchj-genji](https://github.com/togiso/openchj-genji) ⭐ 2 | 🐛 0 | 📅 2025-03-07 - 「源氏物語」形態論情報データ
* [jethics](https://github.com/language-media-lab/jethics) ⭐ 2 | 🐛 0 | 📅 2025-06-23 - 日本語道徳理解度評価用データセットJETHICSの概説ページ (to be update)
* [jgpqa](https://github.com/llm-jp/jgpqa) ⭐ 2 | 🐛 0 | 📅 2025-09-01 - Japanese translation of the GPQA dataset
* [emotioncorpusjapanesetokushimaa2lab](https://github.com/kmatsu-tokudai/emotioncorpusjapanesetokushimaa2lab) ⭐ 2 | 🐛 0 | 📅 2024-09-02 - Japanese emotion corpus Tokushima Univ. A-2 Lab.
* [osworld-jp](https://github.com/karakuri-ai/osworld-jp) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-05-14 - 言語を考慮した評価のための、日本語版コンピュータユースベンチマーク
* [JSTS-Neg](https://github.com/reiko-y/JSTS-Neg) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-05-21 - 否定理解能力を評価するための日本語意味的類似度計算データセット JSTS-Neg の公開用リポジトリです。 JSTS-Neg は、JGLUE に含まれる言語推論データセット JSTS を拡張して作成しました。
* [business-slide-questions](https://github.com/stockmarkteam/business-slide-questions) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-05-23 - このリポジトリでは、ビジネス資料（スライド）を対象とした Visual Question Answering (VQA) ベンチマーク「BusinessSlideVQA」を提供しています。
* [WLSP-antonym](https://github.com/masayu-a/WLSP-antonym) ⭐ 2 | 🐛 0 | 📅 2021-03-18 - Antonym relations for 'Word List by Semantic Principles (WLSP)'
* [Doppelganger-JC](https://github.com/0017-alt/Doppelganger-JC) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-01-20 - This is a dataset benchmarking the misuse of cross-lingual homographs between Chinese and Japanese in LLMs.
* [modelvista-3lang](https://github.com/kuramitsulab/modelvista-3lang) ⭐ 2 | 🐛 1 | 📅 2026-03-16 - ソフトウェア図理解のためのVLM評価ベンチマーク（日本語・英語・韓国語対応）
* [nijl-manyoshutei](https://github.com/kokubunken/nijl-manyoshutei) ⭐ 2 | 🐛 0 | 📅 2026-03-27 - 本リポジトリでは、関西大学所蔵廣瀬本万葉集のTEI/XMLデータ等をCC-BYライセンスのもとで公開しています。
* [kamuskita](https://github.com/matbahasa/kamuskita) ⭐ 2 | 🐛 0 | 🌐 HTML | 📅 2026-07-14 - マレー語勉強会で作っているオープンなマレー語・日本語辞典『みんなのマレー語辞典』
* [japanese-dataset-for-automated-fact-checking](https://github.com/FujitsuResearch/japanese-dataset-for-automated-fact-checking) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-06-08 - Japanese Dataset for Automated Fact-Checking: JAD-AFC
* [llm-jp-longbench](https://github.com/llm-jp/llm-jp-longbench) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2026-03-04 - 日本語版longbench作成のため、jemhopデータセットを活用。
* [doctrine-corpus](https://github.com/shimo4228/doctrine-corpus) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-08-19 - Bilingual (Japanese + English) judgment-eliciting Q\&A corpus (851 examples) encoding documented research-program decisions, with per-example metadata (CC0, Hugging Face mirror available)
* [kokkosho\_data](https://github.com/rindybell/kokkosho_data) ⭐ 1 | 🐛 0 | 📅 2019-07-09 - 車両不具合情報に関するデータセット
* [isbn4groups](https://github.com/uribo/isbn4groups) ⭐ 1 | 🐛 0 | 🌐 R | 📅 2024-06-25 - ISBN-13における日本語での出版物 (978-4-XXXXXXXXX) に関するデータ等
* [copa-japanese](https://github.com/nlp-titech/copa-japanese) ⭐ 1 | 🐛 0 | 📅 2023-02-24 - COPA Dataset in Japanese
* [EaST-MELD](https://github.com/ku-nlp/EaST-MELD) ⭐ 1 | 🐛 0 | 📅 2023-06-23 - EaST-MELD is an English-Japanese dataset for emotion-aware speech translation based on MELD.
* [temporalNLI\_dataset](https://github.com/tomo-vv/temporalNLI_dataset) ⭐ 1 | 🐛 0 | 📅 2023-07-22 - Jamp: Controlled Japanese Temporal Inference Dataset for Evaluating Generalization Capacity of Language Models
* [AdParaphrase](https://github.com/CyberAgentAILab/AdParaphrase) ⭐ 1 | 🐛 0 | 📅 2025-05-28 - This repository contains data for our paper "AdParaphrase: Paraphrase Dataset for Analyzing Linguistic Features toward Generating Attractive Ad Texts".
* [quasi\_japanese\_reviews](https://github.com/megagonlabs/quasi_japanese_reviews) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2023-07-21 - Quasi Japanese Reviews (擬似レビューデータ)
* [psychiatry-clinical-notes](https://github.com/sociocom/psychiatry-clinical-notes) ⭐ 1 | 🐛 0 | 📅 2025-10-08 - 精神科初診カルテ作成アンケート データセット
* [merged-town-names](https://github.com/yuukitoriyama/merged-town-names) ⭐ 1 | 🐛 2 | 🌐 TypeScript | 📅 2022-05-05 - 市町村合併などにより消滅した旧地名と新地名の対応表
* [japanesetextemoticondata](https://github.com/kuroshiba-ginji/japanesetextemoticondata) ⭐ 1 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2021-03-06 - Japanese text-emoticon data.
* [mishearing-corpus](https://github.com/kishiyamat/mishearing-corpus) ⭐ 1 | 🐛 10 | 🌐 HTML | 📅 2026-04-12 - 聞き間違えコーパス︱CSV＋Table Schema で約 1 万件を管理し、VS Code＋pre-commit＋Frictionless＋GitHub Actions で自動検証を行う日本語データセット
* [selective-rag-kasensabo](https://github.com/tk-yasuno/selective-rag-kasensabo) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-11-11 - 建設の技術基準に関する質問の専門性粒度（細かい/粗い）を96%正確に自動判定し、最適なRAGシステム（ColBERT/Naive）を選択する実用的なAgentic RAGシステムのMVPです。2025年11月に公開された河川砂防ダムの技術基準を対象に４つのRAGシステムを構築し、専門性の粒度が異なる200問の質問に対して、精度と速度を比較した。
* [japanese-hr-niah](https://github.com/kufu/japanese-hr-niah) ⭐ 1 | 🐛 0 | 📅 2026-01-06 - 日本語人事労務ドメインにおけるロングコンテキストLLMの性能評価ベンチマーク
* [FactCheckSentenceNLI-FCSNLI-](https://github.com/nlp-waseda/FactCheckSentenceNLI-FCSNLI-) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2021-03-03 - FactCheckSentenceNLIデータセット
* [jades](https://github.com/naist-nlp/jades) ⭐ 0 | 🐛 0 | 📅 2022-12-13 - JADES is a dataset for text simplification in Japanese, described in "JADES: New Text Simplification Dataset in Japanese Targeted at Non-Native Speakers" (the paper will be available soon).
* [GazeVQA](https://github.com/riken-grp/GazeVQA) ⭐ 0 | 🐛 0 | 📅 2024-09-20 - Dataset for the LREC-COLING 2024 paper "A Gaze-grounded Visual Question Answering Dataset for Clarifying Ambiguous Japanese Questions"
* [Jamp\_sp](https://github.com/ynklab/Jamp_sp) ⭐ 0 | 🐛 0 | 📅 2024-06-15 - アスペクトを考慮した日本語時間推論データセットの構築（Jamp\_sp: Controlled Japanese Temporal Inference Dataset Considering Aspect）
* [jnli-neg](https://github.com/asahi-y/jnli-neg) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-12-21 - 否定理解能力を評価するための日本語言語推論データセット JNLI-Neg の公開用リポジトリです。
* [multils-japanese](https://github.com/naist-nlp/multils-japanese) ⭐ 0 | 🐛 0 | 📅 2026-08-19 - MultiLS-Japanese Lexical Complexity Prediction and Lexical Simplification Dataset for Japanese: annotator profiles, unaggregated annotation, and annotatation guidelines.
* [YouCook2-JP](https://github.com/nlab-mpg/YouCook2-JP) ⭐ 0 | 🐛 0 | 📅 2025-08-27 - Japanese translation of the YouCook2 dataset.
* [E2U](https://github.com/sociocom/E2U) ⭐ 0 | 🐛 0 | 📅 2026-03-04 - つたわる化に関するデータ
* [annotation-2025](https://github.com/Tiny-Colony/annotation-2025) ⭐ 0 | 🐛 0 | 📅 2026-01-23 - このリポジトリは，テキストの「解釈」を人手とLLM出力で比較できるデータを公開するためのものです．
* [JBE-QA](https://github.com/hancules/JBE-QA) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-11-26 - Japanese Bar Exam QA
* [kaomoji-data](https://github.com/kaomojikan/kaomoji-data) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-08 - 約1,700種類の日本語顔文字を全件、かな読み（擬態語・キーワード）・タグ・カテゴリでアノテーションした構造化JSONデータセット。多カテゴリ対応・カテゴリ別ファイル分割、MITライセンス。
* [friendly\_JA-Corpus](https://github.com/astremo/friendly_JA-Corpus) - friendly\_JA is a parallel Japanese-to-Japanese corpus aimed at making Japanese easier by using the Latin/English derived katakana lexicon instead of the standard Sino-Japanese lexicon
* [jpn\_explainable\_qa\_dataset](https://github.com/aiishii/jpn_explainable_qa_dataset) - jpn\_explainable\_qa\_dataset
* [japanese-subtitles-word-kanji-frequency-lists](https://github.com/chriskempson/japanese-subtitles-word-kanji-frequency-lists) - A word frequency list derived from subtitles from Japanese drama, anime and films.

| Name                                                                                                                                                                         | downloads/week | total downloads | stars            | last commit       |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------- | --------------- | ---------------- | ----------------- |
| 🔗 [jrte-corpus](https://github.com/megagonlabs/jrte-corpus) ⭐ 77 \| 🐛 0 \| 🌐 Python \| 📅 2023-06-23                                                                      | -              | -               | ⭐ 77             | 🔴 june 2023      |
| 🔗 [kanji-data](https://github.com/davidluzgouveia/kanji-data) ⭐ 231 \| 🐛 3 \| 🌐 Python \| 📅 2026-02-27                                                                   | -              | -               | ⭐ 231            | 🟡 february       |
| 🔗 [JapaneseWordSimilarityDataset](https://github.com/tmu-nlp/JapaneseWordSimilarityDataset) ⭐ 103 \| 🐛 0 \| 🌐 Python \| 📅 2021-12-07                                     | -              | -               | ⭐ 103            | 🔴 december 2021  |
| 🔗 [simple-jppdb](https://github.com/tmu-nlp/simple-jppdb) ⭐ 32 \| 🐛 0 \| 🌐 Python \| 📅 2017-03-12                                                                        | -              | -               | ⭐ 32             | 🔴 march 2017     |
| 🔗 [chABSA-dataset](https://github.com/chakki-works/chABSA-dataset) ⭐ 143 \| 🐛 2 \| 🌐 Jupyter Notebook \| 📅 2022-02-25                                                    | -              | -               | ⭐ 142            | 🔴 september 2018 |
| 🔗 [JaQuAD](https://github.com/SkelterLabsInc/JaQuAD) ⭐ 111 \| 🐛 3 \| 🌐 Jupyter Notebook \| 📅 2022-03-02                                                                  | -              | -               | ⭐ 111            | 🔴 january 2022   |
| 🔗 [JaNLI](https://github.com/verypluming/JaNLI) ⭐ 17 \| 🐛 0 \| 🌐 Python \| 📅 2023-05-31                                                                                  | -              | -               | ⭐ 17             | 🔴 may 2023       |
| 🔗 [ebe-dataset](https://github.com/megagonlabs/ebe-dataset) ⭐ 18 \| 🐛 0 \| 🌐 PLSQL \| 📅 2020-12-17                                                                       | -              | -               | ⭐ 18             | 🔴 december 2020  |
| 🔗 [emoji-ja](https://github.com/yagays/emoji-ja) ⭐ 83 \| 🐛 0 \| 🌐 Python \| 📅 2025-03-19                                                                                 | -              | -               | ⭐ 83             | 🔴 march 2025     |
| 🔗 [nayose-wikipedia-ja](https://github.com/yagays/nayose-wikipedia-ja) ⭐ 35 \| 🐛 0 \| 🌐 Python \| 📅 2020-03-10                                                           | -              | -               | ⭐ 35             | 🔴 march 2020     |
| 🔗 [ja.text8](https://github.com/Hironsan/ja.text8) ⭐ 112 \| 🐛 0 \| 🌐 Python \| 📅 2017-10-04                                                                              | -              | -               | ⭐ 112            | 🔴 october 2017   |
| 🔗 [ThreeLineSummaryDataset](https://github.com/KodairaTomonori/ThreeLineSummaryDataset) ⭐ 31 \| 🐛 1 \| 📅 2018-04-04                                                       | -              | -               | ⭐ 31             | 🔴 april 2018     |
| 🔗 [japanese](https://github.com/hingston/japanese) ⭐ 91 \| 🐛 0 \| 📅 2026-07-27                                                                                            | -              | -               | ⭐ 91             | 🔴 september 2018 |
| 🔗 [kanji-frequency](https://github.com/scriptin/kanji-frequency) ⭐ 165 \| 🐛 10 \| 🌐 Astro \| 📅 2026-06-20                                                                | -              | -               | ⭐ 165            | 🟡 march          |
| 🔗 [TEDxJP-10K](https://github.com/laboroai/TEDxJP-10K) ⭐ 27 \| 🐛 1 \| 🌐 Python \| 📅 2021-01-14                                                                           | -              | -               | ⭐ 26             | 🔴 january 2021   |
| 🔗 [CoARiJ](https://github.com/chakki-works/CoARiJ) ⭐ 94 \| 🐛 4 \| 🌐 Python \| 📅 2020-12-19                                                                               | -              | -               | ⭐ 94             | 🔴 december 2020  |
| 🔗 [technological-book-corpus-ja](https://github.com/textlint-ja/technological-book-corpus-ja) ⭐ 26 \| 🐛 1 \| 🌐 JavaScript \| 📅 2026-04-08                                | -              | -               | ⭐ 26             | 🟡 april          |
| 🔗 [ita-corpus-chuwa](https://github.com/shirayu/ita-corpus-chuwa) ⭐ 5 \| 🐛 0 \| 🌐 Python \| 📅 2021-08-25                                                                 | -              | -               | ⭐ 5              | 🔴 august 2021    |
| 🔗 [wikipedia-utils](https://github.com/singletongue/wikipedia-utils) ⭐ 78 \| 🐛 1 \| 🌐 Python \| 📅 2024-04-09                                                             | -              | -               | ⭐ 78             | 🔴 april 2024     |
| 🔗 [inappropriate-words-ja](https://github.com/MosasoM/inappropriate-words-ja) ⭐ 208 \| 🐛 0 \| 🌐 Python \| 📅 2021-12-01                                                   | -              | -               | ⭐ 208            | 🔴 december 2021  |
| 🔗 [house-of-councillors](https://github.com/smartnews-smri/house-of-councillors) ⭐ 109 \| 🐛 1 \| 🌐 Python \| 📅 2026-08-20                                                | -              | -               | ⭐ 109            | 🟢 yesterday      |
| 🔗 [house-of-representatives](https://github.com/smartnews-smri/house-of-representatives) ⭐ 181 \| 🐛 0 \| 🌐 JavaScript \| 📅 2026-08-20                                    | -              | -               | ⭐ 181            | 🟢 yesterday      |
| 🔗 [STAIR-captions](https://github.com/STAIR-Lab-CIT/STAIR-captions) ⭐ 90 \| 🐛 1 \| 📅 2018-07-04                                                                           | -              | -               | ⭐ 90             | 🔴 july 2018      |
| 🔗 [Winograd-Schema-Challenge-Ja](https://github.com/ku-nlp/Winograd-Schema-Challenge-Ja) ⭐ 6 \| 🐛 1 \| 🌐 Python \| 📅 2019-01-25                                          | -              | -               | ⭐ 6              | 🔴 january 2019   |
| 🔗 [speechBSD](https://github.com/ku-nlp/speechBSD) ⭐ 3 \| 🐛 0 \| 📅 2024-02-07                                                                                             | -              | -               | ⭐ 3              | 🔴 february 2024  |
| 🔗 [ita-corpus](https://github.com/mmorise/ita-corpus) ⭐ 241 \| 🐛 1 \| 📅 2026-07-03                                                                                        | -              | -               | ⭐ 241            | 🟢 july           |
| 🔗 [rohan4600](https://github.com/mmorise/rohan4600) ⭐ 73 \| 🐛 1 \| 🌐 HTML \| 📅 2026-03-13                                                                                | -              | -               | ⭐ 73             | 🟡 march          |
| 🔗 [anlp-jp-history](https://github.com/whym/anlp-jp-history) ⭐ 3 \| 🐛 2 \| 🌐 Jupyter Notebook \| 📅 2024-04-05                                                            | -              | -               | ⭐ 3              | 🔴 april 2024     |
| 🔗 [keigo\_transfer\_task](https://github.com/cl-tohoku/keigo_transfer_task) ⭐ 21 \| 🐛 0 \| 📅 2022-11-24                                                                   | -              | -               | ⭐ 21             | 🔴 november 2022  |
| 🔗 [loanwords\_gairaigo](https://github.com/jamesohortle/loanwords_gairaigo) ⭐ 19 \| 🐛 3 \| 🌐 Python \| 📅 2024-10-24                                                      | -              | -               | ⭐ 19             | 🔴 january 2021   |
| 🔗 [jawikicorpus](https://github.com/wikiwikification/jawikicorpus) ⭐ 4 \| 🐛 0 \| 📅 2018-11-24                                                                             | -              | -               | ⭐ 4              | 🔴 november 2018  |
| 🔗 [GeneralPolicySpeechOfPrimeMinisterOfJapan](https://github.com/yuukimiyo/GeneralPolicySpeechOfPrimeMinisterOfJapan) ⭐ 6 \| 🐛 0 \| 📅 2020-01-14                          | -              | -               | ⭐ 6              | 🔴 january 2020   |
| 🔗 [wrime](https://github.com/ids-cv/wrime) ⭐ 178 \| 🐛 3 \| 📅 2025-09-11                                                                                                   | -              | -               | ⭐ 178            | 🟡 september 2025 |
| 🔗 [jtubespeech](https://github.com/sarulab-speech/jtubespeech) ⭐ 233 \| 🐛 8 \| 🌐 Python \| 📅 2023-11-13                                                                  | -              | -               | ⭐ 233            | 🔴 march 2023     |
| 🔗 [WikipediaWordFrequencyList](https://github.com/maeda6uiui-backup/WikipediaWordFrequencyList) ⚠️ Archived                                                                 | -              | -               | ⭐ 2              | 🔴 april 2022     |
| 🔗 [kokkosho\_data](https://github.com/rindybell/kokkosho_data) ⭐ 1 \| 🐛 0 \| 📅 2019-07-09                                                                                 | -              | -               | ⭐ 1              | 🔴 july 2019      |
| 🔗 [pdmocrdataset-part1](https://github.com/ndl-lab/pdmocrdataset-part1) ⭐ 81 \| 🐛 0 \| 📅 2024-06-26                                                                       | -              | -               | ⭐ 81             | 🔴 june 2024      |
| 🔗 [huriganacorpus-ndlbib](https://github.com/ndl-lab/huriganacorpus-ndlbib) ⭐ 32 \| 🐛 0 \| 📅 2021-09-21                                                                   | -              | -               | ⭐ 32             | 🔴 september 2021 |
| 🔗 [jvs\_hiho](https://github.com/Hiroshiba/jvs_hiho) ⭐ 31 \| 🐛 0 \| 🌐 Shell \| 📅 2021-04-11                                                                              | -              | -               | ⭐ 31             | 🔴 february 2021  |
| 🔗 [hirakanadic](https://github.com/po3rin/hirakanadic) ⭐ 7 \| 🐛 0 \| 🌐 Python \| 📅 2023-07-08                                                                            | 📥 8           | 📦 15k          | ⭐ 7              | 🔴 july 2023      |
| 🔗 [animedb](https://github.com/anilogia/animedb) ⭐ 332 \| 🐛 9 \| 🌐 Python \| 📅 2023-10-26                                                                                | -              | -               | ⭐ 332            | 🔴 january 2023   |
| 🔗 [security\_words](https://github.com/SaitoLab/security_words) ⭐ 27 \| 🐛 0 \| 📅 2023-08-18                                                                               | -              | -               | ⭐ 27             | 🔴 august 2023    |
| 🔗 [Data-on-Japanese-Diet-Members](https://github.com/sugi2000/Data-on-Japanese-Diet-Members) ⭐ 3 \| 🐛 0 \| 📅 2022-09-29                                                   | -              | -               | ⭐ 3              | 🔴 september 2022 |
| 🔗 [honkoku-data](https://github.com/yuta1984/honkoku-data) ⭐ 22 \| 🐛 1 \| 📅 2026-08-16                                                                                    | -              | -               | ⭐ 21             | 🟢 yesterday      |
| 🔗 [wikihow\_japanese](https://github.com/Katsumata420/wikihow_japanese) ⭐ 35 \| 🐛 0 \| 🌐 HTML \| 📅 2020-12-17                                                            | -              | -               | ⭐ 35             | 🔴 december 2020  |
| 🔗 [engineer-vocabulary-list](https://github.com/mercari/engineer-vocabulary-list) ⭐ 1,973 \| 🐛 1 \| 📅 2022-12-03                                                          | -              | -               | ⭐ 2k             | 🔴 november 2020  |
| 🔗 [JSICK](https://github.com/verypluming/JSICK) ⭐ 46 \| 🐛 0 \| 📅 2023-05-31                                                                                               | -              | -               | ⭐ 46             | 🔴 may 2023       |
| 🔗 [phishurl-list](https://github.com/JPCERTCC/phishurl-list) ⭐ 210 \| 🐛 0 \| 🌐 HTML \| 📅 2026-06-29                                                                      | -              | -               | ⭐ 210            | 🟢 june           |
| 🔗 [jcms](https://github.com/shigashiyama/jcms) ⭐ 9 \| 🐛 0 \| 🌐 Mask \| 📅 2026-04-03                                                                                      | -              | -               | ⭐ 9              | 🟡 april          |
| 🔗 [aozorabunko\_text](https://github.com/aozorahack/aozorabunko_text) ⭐ 95 \| 🐛 0 \| 🌐 Ruby \| 📅 2023-03-22                                                              | -              | -               | ⭐ 95             | 🔴 march 2023     |
| 🔗 [friendly\_JA-Corpus](https://github.com/astremo/friendly_JA-Corpus)                                                                                                      | -              | -               | ⭐ repo not found | 🔴 repo not found |
| 🔗 [topokanji](https://github.com/scriptin/topokanji) ⭐ 206 \| 🐛 1 \| 🌐 JavaScript \| 📅 2023-03-24                                                                        | -              | -               | ⭐ 206            | 🔴 january 2016   |
| 🔗 [isbn4groups](https://github.com/uribo/isbn4groups) ⭐ 1 \| 🐛 0 \| 🌐 R \| 📅 2024-06-25                                                                                  | -              | -               | ⭐ 1              | 🔴 june 2024      |
| 🔗 [NMeCab](https://github.com/komutan/NMeCab) ⭐ 103 \| 🐛 9 \| 🌐 C# \| 📅 2024-03-30                                                                                       | -              | -               | ⭐ 103            | 🔴 march 2024     |
| 🔗 [ndlngramdata](https://github.com/ndl-lab/ndlngramdata) ⭐ 17 \| 🐛 0 \| 📅 2023-01-10                                                                                     | -              | -               | ⭐ 17             | 🔴 january 2023   |
| 🔗 [ndlngramviewer\_v2](https://github.com/ndl-lab/ndlngramviewer_v2) ⭐ 3 \| 🐛 0 \| 🌐 Java \| 📅 2026-05-01                                                                | -              | -               | ⭐ 3              | 🟡 april          |
| 🔗 [data\_set](https://github.com/japanese-law-analysis/data_set) ⭐ 53 \| 🐛 0 \| 📅 2025-01-08                                                                              | -              | -               | ⭐ 53             | 🔴 january 2025   |
| 🔗 [huggingface-datasets\_wrime](https://github.com/shunk031/huggingface-datasets_wrime) ⭐ 5 \| 🐛 0 \| 🌐 Python \| 📅 2023-01-15                                           | -              | -               | ⭐ 5              | 🔴 january 2023   |
| 🔗 [ndl-minhon-ocrdataset](https://github.com/ndl-lab/ndl-minhon-ocrdataset) ⭐ 22 \| 🐛 0 \| 🌐 Python \| 📅 2026-03-13                                                      | -              | -               | ⭐ 22             | 🟡 march          |
| 🔗 [PAX\_SAPIENTICA](https://github.com/AsPJT/PAX_SAPIENTICA) ⭐ 189 \| 🐛 1 \| 🌐 C++ \| 📅 2026-01-31                                                                       | -              | -               | ⭐ 189            | 🟡 december 2025  |
| 🔗 [j-liwc2015](https://github.com/tasukuigarashi/j-liwc2015) ⭐ 13 \| 🐛 0 \| 📅 2024-11-06                                                                                  | -              | -               | ⭐ 13             | 🔴 november 2024  |
| 🔗 [huggingface-datasets\_livedoor-news-corpus](https://github.com/shunk031/huggingface-datasets_livedoor-news-corpus) ⭐ 3 \| 🐛 1 \| 🌐 Python \| 📅 2023-10-28             | -              | -               | ⭐ 3              | 🔴 october 2023   |
| 🔗 [huggingface-datasets\_JGLUE](https://github.com/shunk031/huggingface-datasets_JGLUE) ⭐ 14 \| 🐛 8 \| 🌐 Python \| 📅 2025-03-31                                          | -              | -               | ⭐ 14             | 🔴 march 2025     |
| 🔗 [commonsense-moral-ja](https://github.com/Language-Media-Lab/commonsense-moral-ja) ⭐ 15 \| 🐛 0 \| 🌐 Python \| 📅 2025-11-20                                             | -              | -               | ⭐ 15             | 🟡 november 2025  |
| 🔗 [comet-atomic-ja](https://github.com/nlp-waseda/comet-atomic-ja) ⭐ 31 \| 🐛 0 \| 🌐 Python \| 📅 2024-03-08                                                               | -              | -               | ⭐ 31             | 🔴 march 2024     |
| 🔗 [dcsg-ja](https://github.com/nlp-waseda/dcsg-ja) ⭐ 6 \| 🐛 0 \| 📅 2023-03-10                                                                                             | -              | -               | ⭐ 6              | 🔴 march 2023     |
| 🔗 [japanese-toxic-dataset](https://github.com/inspection-ai/japanese-toxic-dataset) ⭐ 22 \| 🐛 2 \| 📅 2023-01-11                                                           | -              | -               | ⭐ 22             | 🔴 january 2023   |
| 🔗 [camera](https://github.com/CyberAgentAILab/camera) ⚠️ Archived                                                                                                           | -              | -               | ⭐ 26             | 🔴 august 2024    |
| 🔗 [Japanese-Fakenews-Dataset](https://github.com/tanreinama/Japanese-Fakenews-Dataset) ⭐ 21 \| 🐛 0 \| 📅 2021-05-02                                                        | -              | -               | ⭐ 21             | 🔴 may 2021       |
| 🔗 [jpn\_explainable\_qa\_dataset](https://github.com/aiishii/jpn_explainable_qa_dataset)                                                                                    | -              | -               | ⭐ repo not found | 🔴 repo not found |
| 🔗 [copa-japanese](https://github.com/nlp-titech/copa-japanese) ⭐ 1 \| 🐛 0 \| 📅 2023-02-24                                                                                 | -              | -               | ⭐ 1              | 🔴 february 2023  |
| 🔗 [WLSP-familiarity](https://github.com/masayu-a/WLSP-familiarity) ⭐ 13 \| 🐛 1 \| 📅 2025-01-02                                                                            | -              | -               | ⭐ 13             | 🔴 january 2025   |
| 🔗 [ProSub](https://github.com/matbahasa/ProSub) ⭐ 5 \| 🐛 0 \| 🌐 Python \| 📅 2025-04-03                                                                                   | -              | -               | ⭐ 5              | 🔴 april 2025     |
| 🔗 [ramendb](https://github.com/nuko-yokohama/ramendb) ⭐ 8 \| 🐛 2 \| 🌐 Python \| 📅 2026-04-25                                                                             | -              | -               | ⭐ 8              | 🟡 april          |
| 🔗 [huggingface-datasets\_CAMERA](https://github.com/shunk031/huggingface-datasets_CAMERA) ⚠️ Archived                                                                       | -              | -               | ⭐ 3              | 🔴 march 2023     |
| 🔗 [FactCheckSentenceNLI-FCSNLI-](https://github.com/nlp-waseda/FactCheckSentenceNLI-FCSNLI-) ⭐ 0 \| 🐛 0 \| 🌐 Python \| 📅 2021-03-03                                      | -              | -               | ⭐ 0              | 🔴 march 2021     |
| 🔗 [databricks-dolly-15k-ja](https://github.com/kunishou/databricks-dolly-15k-ja) ⭐ 89 \| 🐛 4 \| 📅 2023-07-25                                                              | -              | -               | ⭐ 89             | 🔴 july 2023      |
| 🔗 [EaST-MELD](https://github.com/ku-nlp/EaST-MELD) ⭐ 1 \| 🐛 0 \| 📅 2023-06-23                                                                                             | -              | -               | ⭐ 1              | 🔴 june 2023      |
| 🔗 [meconaudio](https://github.com/elith-co-jp/meconaudio) ⭐ 10 \| 🐛 0 \| 📅 2023-10-25                                                                                     | -              | -               | ⭐ 10             | 🔴 october 2023   |
| 🔗 [japanese-addresses](https://github.com/geolonia/japanese-addresses) ⭐ 770 \| 🐛 26 \| 🌐 JavaScript \| 📅 2026-08-05                                                     | -              | -               | ⭐ 769            | 🟢 august         |
| 🔗 [aozorasearch](https://github.com/myokoym/aozorasearch) ⭐ 21 \| 🐛 9 \| 🌐 Ruby \| 📅 2026-06-09                                                                          | -              | -               | ⭐ 21             | 🟡 march          |
| 🔗 [llm-jp-corpus](https://github.com/llm-jp/llm-jp-corpus) ⭐ 48 \| 🐛 4 \| 🌐 Python \| 📅 2024-02-02                                                                       | -              | -               | ⭐ 48             | 🔴 october 2023   |
| 🔗 [alpaca\_ja](https://github.com/shi3z/alpaca_ja) ⭐ 86 \| 🐛 3 \| 📅 2023-06-03                                                                                            | -              | -               | ⭐ 86             | 🔴 may 2023       |
| 🔗 [instruction\_ja](https://github.com/megagonlabs/instruction_ja) ⭐ 24 \| 🐛 0 \| 🌐 Python \| 📅 2023-07-13                                                               | -              | -               | ⭐ 24             | 🔴 july 2023      |
| 🔗 [japanese-family-names](https://github.com/siikamiika/japanese-family-names) ⭐ 18 \| 🐛 1 \| 🌐 Python \| 📅 2017-09-27                                                   | -              | -               | ⭐ 18             | 🔴 june 2017      |
| 🔗 [kanji-data-media](https://github.com/kanjialive/kanji-data-media) ⭐ 426 \| 🐛 4 \| 📅 2026-07-29                                                                         | -              | -               | ⭐ 424            | 🟢 july           |
| 🔗 [reazonspeech](https://github.com/reazon-research/reazonspeech) ⭐ 396 \| 🐛 13 \| 🌐 Python \| 📅 2026-06-10                                                              | -              | -               | ⭐ 397            | 🟢 june           |
| 🔗 [huriganacorpus-aozora](https://github.com/ndl-lab/huriganacorpus-aozora) ⭐ 23 \| 🐛 0 \| 📅 2024-01-17                                                                   | -              | -               | ⭐ 23             | 🔴 january 2024   |
| 🔗 [koniwa](https://github.com/koniwa/koniwa) ⚠️ Archived                                                                                                                    | -              | -               | ⭐ 62             | 🔴 april 2025     |
| 🔗 [JMMLU](https://github.com/nlp-waseda/JMMLU) ⭐ 41 \| 🐛 0 \| 📅 2025-10-07                                                                                                | -              | -               | ⭐ 41             | 🟡 october 2025   |
| 🔗 [hurigana-speech-corpus-aozora](https://github.com/ndl-lab/hurigana-speech-corpus-aozora) ⭐ 50 \| 🐛 1 \| 📅 2025-03-07                                                   | -              | -               | ⭐ 50             | 🔴 march 2025     |
| 🔗 [jqara](https://github.com/hotchpotch/jqara) ⭐ 45 \| 🐛 0 \| 🌐 Python \| 📅 2025-09-09                                                                                   | -              | -               | ⭐ 45             | 🟡 september 2025 |
| 🔗 [jemhopqa](https://github.com/aiishii/jemhopqa) ⭐ 30 \| 🐛 0 \| 🌐 Python \| 📅 2025-04-10                                                                                | -              | -               | ⭐ 30             | 🔴 april 2025     |
| 🔗 [jacred](https://github.com/youmima/jacred) ⭐ 8 \| 🐛 2 \| 📅 2024-03-08                                                                                                  | -              | -               | ⭐ 8              | 🔴 march 2024     |
| 🔗 [jades](https://github.com/naist-nlp/jades) ⭐ 0 \| 🐛 0 \| 📅 2022-12-13                                                                                                  | -              | -               | ⭐ 0              | 🔴 december 2022  |
| 🔗 [do-not-answer-ja](https://github.com/kunishou/do-not-answer-ja) ⭐ 24 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2023-12-15                                                     | -              | -               | ⭐ 24             | 🔴 december 2023  |
| 🔗 [oasst1-89k-ja](https://github.com/kunishou/oasst1-89k-ja) ⭐ 16 \| 🐛 2 \| 🌐 Python \| 📅 2023-11-19                                                                     | -              | -               | ⭐ 16             | 🔴 november 2023  |
| 🔗 [jacwir](https://github.com/hotchpotch/jacwir) ⭐ 9 \| 🐛 0 \| 🌐 Python \| 📅 2025-09-09                                                                                  | -              | -               | ⭐ 9              | 🟡 september 2025 |
| 🔗 [japanese-technical-dict](https://github.com/laoshubaby/japanese-technical-dict) ⭐ 3 \| 🐛 0 \| 🌐 Python \| 📅 2024-11-21                                                | -              | -               | ⭐ 3              | 🔴 november 2024  |
| 🔗 [j-unimorph](https://github.com/cl-tohoku/j-unimorph) ⭐ 9 \| 🐛 0 \| 🌐 JavaScript \| 📅 2026-05-22                                                                       | -              | -               | ⭐ 9              | 🟡 may            |
| 🔗 [GazeVQA](https://github.com/riken-grp/GazeVQA) ⭐ 0 \| 🐛 0 \| 📅 2024-09-20                                                                                              | -              | -               | ⭐ 0              | 🔴 september 2024 |
| 🔗 [J-CRe3](https://github.com/riken-grp/J-CRe3) ⭐ 11 \| 🐛 0 \| 📅 2025-01-04                                                                                               | -              | -               | ⭐ 11             | 🔴 january 2025   |
| 🔗 [jmed-llm](https://github.com/sociocom/jmed-llm) ⭐ 59 \| 🐛 0 \| 🌐 Python \| 📅 2024-09-22                                                                               | -              | -               | ⭐ 59             | 🔴 september 2024 |
| 🔗 [lawtext](https://github.com/yamachig/lawtext) ⭐ 100 \| 🐛 0 \| 🌐 TypeScript \| 📅 2026-08-19                                                                            | -              | -               | ⭐ 100            | 🟢 july           |
| 🔗 [pdmocrdataset-part2](https://github.com/ndl-lab/pdmocrdataset-part2) ⭐ 15 \| 🐛 0 \| 📅 2024-06-26                                                                       | -              | -               | ⭐ 15             | 🔴 june 2024      |
| 🔗 [japanesetopicwsd](https://github.com/nut-jnlp/japanesetopicwsd) ⭐ 3 \| 🐛 0 \| 📅 2018-09-27                                                                             | -              | -               | ⭐ 3              | 🔴 september 2018 |
| 🔗 [temporalNLI\_dataset](https://github.com/tomo-vv/temporalNLI_dataset) ⭐ 1 \| 🐛 0 \| 📅 2023-07-22                                                                       | -              | -               | ⭐ 1              | 🔴 july 2023      |
| 🔗 [JSeM](https://github.com/DaisukeBekki/JSeM) ⭐ 13 \| 🐛 4 \| 🌐 HTML \| 📅 2026-04-21                                                                                     | -              | -               | ⭐ 13             | 🔴 november 2024  |
| 🔗 [niilc-qa](https://github.com/mynlp/niilc-qa) ⭐ 18 \| 🐛 0 \| 📅 2015-11-20                                                                                               | -              | -               | ⭐ 18             | 🔴 november 2015  |
| 🔗 [chain-of-thought-ja-dataset](https://github.com/nlp-waseda/chain-of-thought-ja-dataset) ⭐ 5 \| 🐛 0 \| 📅 2023-09-14                                                     | -              | -               | ⭐ 5              | 🔴 september 2023 |
| 🔗 [WikipediaAnnotatedCorpus](https://github.com/ku-nlp/WikipediaAnnotatedCorpus) ⭐ 30 \| 🐛 0 \| 🌐 Python \| 📅 2026-08-01                                                 | -              | -               | ⭐ 30             | 🟢 august         |
| 🔗 [elaws-history](https://github.com/kissge/elaws-history) ⭐ 8 \| 🐛 0 \| 📅 2026-08-20                                                                                     | -              | -               | ⭐ 8              | 🟢 yesterday      |
| 🔗 [Japanese-RP-Bench](https://github.com/Aratako/Japanese-RP-Bench) ⭐ 22 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2024-09-29                                                    | -              | -               | ⭐ 22             | 🔴 september 2024 |
| 🔗 [hdic](https://github.com/shikeda/hdic) ⭐ 44 \| 🐛 3 \| 📅 2026-08-19                                                                                                     | -              | -               | ⭐ 44             | 🟢 august         |
| 🔗 [awesome-japan-opendata](https://github.com/japan-opendata/awesome-japan-opendata) ⭐ 167 \| 🐛 1 \| 📅 2026-08-13                                                         | -              | -               | ⭐ 167            | 🟢 last thursday  |
| 🔗 [kanji-data](https://github.com/mimneko/kanji-data) ⭐ 28 \| 🐛 1 \| 📅 2026-06-26                                                                                         | -              | -               | ⭐ 27             | 🟢 june           |
| 🔗 [openchj-genji](https://github.com/togiso/openchj-genji) ⭐ 2 \| 🐛 0 \| 📅 2025-03-07                                                                                     | -              | -               | ⭐ 2              | 🔴 march 2025     |
| 🔗 [AdParaphrase](https://github.com/CyberAgentAILab/AdParaphrase) ⭐ 1 \| 🐛 0 \| 📅 2025-05-28                                                                              | -              | -               | ⭐ 1              | 🔴 may 2025       |
| 🔗 [Jamp\_sp](https://github.com/ynklab/Jamp_sp) ⭐ 0 \| 🐛 0 \| 📅 2024-06-15                                                                                                | -              | -               | ⭐ 0              | 🔴 june 2024      |
| 🔗 [jnli-neg](https://github.com/asahi-y/jnli-neg) ⭐ 0 \| 🐛 0 \| 🌐 Python \| 📅 2025-12-21                                                                                 | -              | -               | ⭐ 0              | 🟡 december 2025  |
| 🔗 [swallow-corpus](https://github.com/swallow-llm/swallow-corpus) ⭐ 7 \| 🐛 0 \| 🌐 Python \| 📅 2024-11-23                                                                 | -              | -               | ⭐ 7              | 🔴 november 2024  |
| 🔗 [jalecon](https://github.com/naist-nlp/jalecon) ⭐ 6 \| 🐛 0 \| 📅 2023-07-04                                                                                              | -              | -               | ⭐ 6              | 🔴 july 2023      |
| 🔗 [multils-japanese](https://github.com/naist-nlp/multils-japanese) ⭐ 0 \| 🐛 0 \| 📅 2026-08-19                                                                            | -              | -               | ⭐ 0              | 🟡 january        |
| 🔗 [nwjc](https://github.com/masayu-a/nwjc) ⭐ 10 \| 🐛 0 \| 📅 2026-05-13                                                                                                    | -              | -               | ⭐ 10             | 🔴 april 2022     |
| 🔗 [open-mantra-dataset](https://github.com/mantra-inc/open-mantra-dataset) ⭐ 203 \| 🐛 0 \| 📅 2023-03-18                                                                   | -              | -               | ⭐ 203            | 🔴 march 2023     |
| 🔗 [gimei](https://github.com/willnet/gimei) ⭐ 426 \| 🐛 9 \| 🌐 Ruby \| 📅 2026-08-17                                                                                       | -              | -               | ⭐ 426            | 🟢 july           |
| 🔗 [safety-boundary-test](https://github.com/sbintuitions/safety-boundary-test) ⭐ 9 \| 🐛 0 \| 🌐 Jinja \| 📅 2026-04-14                                                     | -              | -               | ⭐ 9              | 🟡 april          |
| 🔗 [j-ono-data](https://github.com/ObakeConstructs/j-ono-data) ⭐ 11 \| 🐛 5 \| 📅 2026-07-31                                                                                 | -              | -               | ⭐ 11             | 🟢 july           |
| 🔗 [kanji](https://github.com/sylhare/kanji) ⭐ 30 \| 🐛 9 \| 🌐 Python \| 📅 2026-08-08                                                                                      | -              | -               | ⭐ 30             | 🟢 august         |
| 🔗 [jethics](https://github.com/language-media-lab/jethics) ⭐ 2 \| 🐛 0 \| 📅 2025-06-23                                                                                     | -              | -               | ⭐ 2              | 🔴 june 2025      |
| 🔗 [waon](https://github.com/llm-jp/waon) ⭐ 7 \| 🐛 0 \| 🌐 Python \| 📅 2025-11-02                                                                                          | -              | -               | ⭐ 7              | 🟡 november 2025  |
| 🔗 [kuci](https://github.com/ku-nlp/kuci) ⭐ 5 \| 🐛 0 \| 📅 2024-02-16                                                                                                       | -              | -               | ⭐ 5              | 🔴 february 2024  |
| 🔗 [japanese-address-testdata](https://github.com/t-sagara/japanese-address-testdata) ⭐ 14 \| 🐛 0 \| 📅 2023-09-25                                                          | -              | -               | ⭐ 14             | 🔴 september 2023 |
| 🔗 [jlpt-word-list](https://github.com/elzup/jlpt-word-list) ⭐ 91 \| 🐛 0 \| 🌐 JavaScript \| 📅 2023-04-04                                                                  | -              | -               | ⭐ 91             | 🔴 february 2022  |
| 🔗 [hiragana\_mojigazo](https://github.com/ndl-lab/hiragana_mojigazo) ⭐ 18 \| 🐛 0 \| 📅 2020-04-06                                                                          | -              | -               | ⭐ 18             | 🔴 april 2020     |
| 🔗 [lawqa\_jp](https://github.com/digital-go-jp/lawqa_jp) ⭐ 276 \| 🐛 0 \| 📅 2026-02-13                                                                                     | -              | -               | ⭐ 276            | 🟡 february       |
| 🔗 [yjcaptions](https://github.com/yahoojapan/yjcaptions) ⭐ 60 \| 🐛 0 \| 📅 2016-11-29                                                                                      | -              | -               | ⭐ 60             | 🔴 november 2016  |
| 🔗 [ja-vg-vqa](https://github.com/yahoojapan/ja-vg-vqa) ⭐ 30 \| 🐛 1 \| 📅 2018-11-15                                                                                        | -              | -               | ⭐ 30             | 🔴 november 2018  |
| 🔗 [lawhub](https://github.com/lwhb/lawhub) ⭐ 153 \| 🐛 76 \| 📅 2020-11-17                                                                                                  | -              | -               | ⭐ 153            | 🔴 november 2020  |
| 🔗 [japanese-subtitles-word-kanji-frequency-lists](https://github.com/chriskempson/japanese-subtitles-word-kanji-frequency-lists)                                            | -              | -               | ⭐ repo not found | 🔴 repo not found |
| 🔗 [jconj](https://github.com/yamagoya/jconj) ⭐ 35 \| 🐛 1 \| 🌐 Python \| 📅 2020-05-26                                                                                     | -              | -               | ⭐ 35             | 🔴 may 2020       |
| 🔗 [extract\_jawp\_names](https://github.com/hiroshi-manabe/extract_jawp_names) ⭐ 21 \| 🐛 0 \| 🌐 Perl \| 📅 2022-12-06                                                     | -              | -               | ⭐ 21             | 🔴 december 2022  |
| 🔗 [cejc\_yomichan\_freq\_dict](https://github.com/forsakeninfinity/cejc_yomichan_freq_dict) ⭐ 14 \| 🐛 0 \| 🌐 Python \| 📅 2023-06-23                                      | -              | -               | ⭐ 14             | 🔴 june 2023      |
| 🔗 [wikidict-ja](https://github.com/open-dict-data/wikidict-ja) ⭐ 6 \| 🐛 0 \| 📅 2016-06-17                                                                                 | -              | -               | ⭐ 6              | 🔴 june 2016      |
| 🔗 [ajimee-bench](https://github.com/azookey/ajimee-bench) ⭐ 23 \| 🐛 2 \| 🌐 Python \| 📅 2025-01-13                                                                        | -              | -               | ⭐ 23             | 🔴 january 2025   |
| 🔗 [j-spaw](https://github.com/takamichi-lab/j-spaw) ⭐ 6 \| 🐛 0 \| 🌐 Python \| 📅 2025-08-26                                                                               | -              | -               | ⭐ 6              | 🔴 august 2025    |
| 🔗 [camera3](https://github.com/cyberagentailab/camera3) ⚠️ Archived                                                                                                         | -              | -               | ⭐ 4              | 🔴 may 2024       |
| 🔗 [jgpqa](https://github.com/llm-jp/jgpqa) ⭐ 2 \| 🐛 0 \| 📅 2025-09-01                                                                                                     | -              | -               | ⭐ 2              | 🟡 september 2025 |
| 🔗 [tanaka-corpus-plus](https://github.com/marmooo/tanaka-corpus-plus) ⭐ 3 \| 🐛 0 \| 📅 2021-06-05                                                                          | -              | -               | ⭐ 3              | 🔴 june 2021      |
| 🔗 [emotioncorpusjapanesetokushimaa2lab](https://github.com/kmatsu-tokudai/emotioncorpusjapanesetokushimaa2lab) ⭐ 2 \| 🐛 0 \| 📅 2024-09-02                                 | -              | -               | ⭐ 2              | 🔴 september 2024 |
| 🔗 [osworld-jp](https://github.com/karakuri-ai/osworld-jp) ⭐ 2 \| 🐛 0 \| 🌐 Python \| 📅 2026-05-14                                                                         | -              | -               | ⭐ 2              | 🟡 may            |
| 🔗 [quasi\_japanese\_reviews](https://github.com/megagonlabs/quasi_japanese_reviews) ⭐ 1 \| 🐛 0 \| 🌐 Python \| 📅 2023-07-21                                               | -              | -               | ⭐ 1              | 🔴 july 2023      |
| 🔗 [psychiatry-clinical-notes](https://github.com/sociocom/psychiatry-clinical-notes) ⭐ 1 \| 🐛 0 \| 📅 2025-10-08                                                           | -              | -               | ⭐ 1              | 🟡 october 2025   |
| 🔗 [merged-town-names](https://github.com/yuukitoriyama/merged-town-names) ⭐ 1 \| 🐛 2 \| 🌐 TypeScript \| 📅 2022-05-05                                                     | -              | -               | ⭐ 1              | 🔴 may 2022       |
| 🔗 [japanesetextemoticondata](https://github.com/kuroshiba-ginji/japanesetextemoticondata) ⭐ 1 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2021-03-06                               | -              | -               | ⭐ 1              | 🔴 march 2021     |
| 🔗 [mishearing-corpus](https://github.com/kishiyamat/mishearing-corpus) ⭐ 1 \| 🐛 10 \| 🌐 HTML \| 📅 2026-04-12                                                             | -              | -               | ⭐ 1              | 🟡 january        |
| 🔗 [kotowaza](https://github.com/septn/kotowaza) ⭐ 3 \| 🐛 1 \| 🌐 JavaScript \| 📅 2026-02-15                                                                               | -              | -               | ⭐ 3              | 🟡 february       |
| 🔗 [selective-rag-kasensabo](https://github.com/tk-yasuno/selective-rag-kasensabo) ⭐ 1 \| 🐛 0 \| 🌐 Python \| 📅 2025-11-11                                                 | -              | -               | ⭐ 1              | 🟡 november 2025  |
| 🔗 [jmle2026-bench](https://github.com/naoto-iwase/jmle2026-bench) ⭐ 11 \| 🐛 0 \| 🌐 Python \| 📅 2026-06-10                                                                | -              | -               | ⭐ 11             | 🟡 march          |
| 🔗 [JSTS-Neg](https://github.com/reiko-y/JSTS-Neg) ⭐ 2 \| 🐛 0 \| 🌐 Python \| 📅 2026-05-21                                                                                 | -              | -               | ⭐ 2              | 🟡 may            |
| 🔗 [business-slide-questions](https://github.com/stockmarkteam/business-slide-questions) ⭐ 2 \| 🐛 0 \| 🌐 Python \| 📅 2025-05-23                                           | -              | -               | ⭐ 2              | 🔴 may 2025       |
| 🔗 [WLSP-antonym](https://github.com/masayu-a/WLSP-antonym) ⭐ 2 \| 🐛 0 \| 📅 2021-03-18                                                                                     | -              | -               | ⭐ 2              | 🔴 march 2021     |
| 🔗 [YouCook2-JP](https://github.com/nlab-mpg/YouCook2-JP) ⭐ 0 \| 🐛 0 \| 📅 2025-08-27                                                                                       | -              | -               | ⭐ 0              | 🔴 august 2025    |
| 🔗 [E2U](https://github.com/sociocom/E2U) ⭐ 0 \| 🐛 0 \| 📅 2026-03-04                                                                                                       | -              | -               | ⭐ 0              | 🟡 march          |
| 🔗 [annotation-2025](https://github.com/Tiny-Colony/annotation-2025) ⭐ 0 \| 🐛 0 \| 📅 2026-01-23                                                                            | -              | -               | ⭐ 0              | 🟡 january        |
| 🔗 [jhpt](https://github.com/nict-astrec-att/jhpt) ⭐ 3 \| 🐛 0 \| 🌐 Python \| 📅 2026-03-07                                                                                 | -              | -               | ⭐ 3              | 🟡 march          |
| 🔗 [JBE-QA](https://github.com/hancules/JBE-QA) ⭐ 0 \| 🐛 0 \| 🌐 Python \| 📅 2025-11-26                                                                                    | -              | -               | ⭐ 0              | 🟡 november 2025  |
| 🔗 [JMedWiC](https://github.com/EhimeNLP/JMedWiC) ⭐ 4 \| 🐛 0 \| 📅 2026-05-07                                                                                               | -              | -               | ⭐ 4              | 🟡 may            |
| 🔗 [Doppelganger-JC](https://github.com/0017-alt/Doppelganger-JC) ⭐ 2 \| 🐛 0 \| 🌐 Python \| 📅 2026-01-20                                                                  | -              | -               | ⭐ 2              | 🟡 january        |
| 🔗 [modelvista-3lang](https://github.com/kuramitsulab/modelvista-3lang) ⭐ 2 \| 🐛 1 \| 📅 2026-03-16                                                                         | -              | -               | ⭐ 2              | 🟡 march          |
| 🔗 [japanese-hr-niah](https://github.com/kufu/japanese-hr-niah) ⭐ 1 \| 🐛 0 \| 📅 2026-01-06                                                                                 | -              | -               | ⭐ 1              | 🟡 january        |
| 🔗 [nijl-manyoshutei](https://github.com/kokubunken/nijl-manyoshutei) ⭐ 2 \| 🐛 0 \| 📅 2026-03-27                                                                           | -              | -               | ⭐ 2              | 🟡 march          |
| 🔗 [kamuskita](https://github.com/matbahasa/kamuskita) ⭐ 2 \| 🐛 0 \| 🌐 HTML \| 📅 2026-07-14                                                                               | -              | -               | ⭐ 2              | 🟢 july           |
| 🔗 [japanese-llm-benchmark](https://github.com/shi3z/japanese-llm-benchmark) ⭐ 49 \| 🐛 0 \| 🌐 Python \| 📅 2026-07-25                                                      | -              | -               | ⭐ 50             | 🟢 july           |
| 🔗 [EDINET-Bench](https://github.com/SakanaAI/EDINET-Bench) ⭐ 36 \| 🐛 1 \| 🌐 Python \| 📅 2026-03-06                                                                       | -              | -               | ⭐ 36             | 🟡 march          |
| 🔗 [LCTG-Bench](https://github.com/CyberAgentAILab/LCTG-Bench) ⚠️ Archived                                                                                                   | -              | -               | ⭐ 5              | 🔴 july 2024      |
| 🔗 [Kokoro-Speech-Dataset](https://github.com/kaiidams/Kokoro-Speech-Dataset) ⭐ 69 \| 🐛 1 \| 🌐 Python \| 📅 2026-04-14                                                     | -              | -               | ⭐ 69             | 🟡 april          |
| 🔗 [LookVQA](https://github.com/riken-grp/LookVQA) ⭐ 8 \| 🐛 0 \| 📅 2024-08-30                                                                                              | -              | -               | ⭐ 8              | 🔴 august 2024    |
| 🔗 [JTruthfulQA](https://github.com/nlp-waseda/JTruthfulQA) ⭐ 6 \| 🐛 0 \| 🌐 Python \| 📅 2025-02-06                                                                        | -              | -               | ⭐ 6              | 🔴 february 2025  |
| 🔗 [japanese-dataset-for-automated-fact-checking](https://github.com/FujitsuResearch/japanese-dataset-for-automated-fact-checking) ⭐ 2 \| 🐛 0 \| 🌐 Python \| 📅 2026-06-08 | -              | -               | ⭐ 2              | 🟢 june           |
| 🔗 [llm-jp-longbench](https://github.com/llm-jp/llm-jp-longbench) ⭐ 2 \| 🐛 1 \| 🌐 Python \| 📅 2026-03-04                                                                  | -              | -               | ⭐ 2              | 🟡 march          |
| 🔗 [doctrine-corpus](https://github.com/shimo4228/doctrine-corpus) ⭐ 2 \| 🐛 0 \| 🌐 Python \| 📅 2026-08-19                                                                 | -              | -               | ⭐ 2              | 🟢 july           |
| 🔗 [medLLM\_QA\_benchmark](https://github.com/aistairc/medLLM_QA_benchmark) ⭐ 6 \| 🐛 0 \| 🌐 Python \| 📅 2025-01-22                                                        | -              | -               | ⭐ 6              | 🔴 january 2025   |
| 🔗 [kaomoji-data](https://github.com/kaomojikan/kaomoji-data) ⭐ 0 \| 🐛 0 \| 🌐 JavaScript \| 📅 2026-06-08                                                                  | -              | -               | ⭐ 0              | 🟢 june           |
| 🔗 [jvs\_nonpara\_kana](https://github.com/CyberAgentAILab/jvs_nonpara_kana) ⭐ 7 \| 🐛 0 \| 🌐 Python \| 📅 2026-06-17                                                       | -              | -               | ⭐ 7              | 🟢 june           |
| 🔗 [jlpt-kanji-dictionary](https://github.com/AnchorI/jlpt-kanji-dictionary) ⭐ 34 \| 🐛 0 \| 📅 2025-05-02                                                                   | -              | -               | ⭐ 34             | 🔴 may 2025       |
| 🔗 [pfgen-bench](https://github.com/pfnet-research/pfgen-bench) ⭐ 107 \| 🐛 1 \| 🌐 Python \| 📅 2026-08-07                                                                  | -              | -               | ⭐ 107            | 🟢 august         |
| 🔗 [j-tau-bench](https://github.com/sbintuitions/j-tau-bench) ⭐ 11 \| 🐛 0 \| 🌐 Python \| 📅 2026-08-13                                                                     | -              | -               | ⭐ 9              | 🟢 last thursday  |
| 🔗 [bbh-ja](https://github.com/pfnet-research/bbh-ja) ⭐ 5 \| 🐛 0 \| 📅 2025-07-08                                                                                           | -              | -               | ⭐ 5              | 🔴 july 2025      |
| 🔗 [jfbench](https://github.com/pfnet-research/jfbench) ⭐ 15 \| 🐛 0 \| 🌐 Python \| 📅 2026-08-06                                                                           | -              | -               | ⭐ 15             | 🟢 august         |

## Tutorial

Guides and tutorials for learning Japanese NLP tools and techniques

* [llm-book](https://github.com/ghmagazine/llm-book) ⭐ 474 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2025-12-31 - 「大規模言語モデル入門」（技術評論社, 2023）のGitHubリポジトリ
* [ttslearn](https://github.com/r9y9/ttslearn) ⭐ 269 | 🐛 7 | 🌐 Jupyter Notebook | 📅 2023-03-07 - ttslearn: Library for Pythonで学ぶ音声合成 (Text-to-speech with Python)
* [bert-book](https://github.com/stockmarkteam/bert-book) ⭐ 265 | 🐛 8 | 🌐 Jupyter Notebook | 📅 2024-02-13 - 「BERTによる自然言語処理入門: Transformersを使った実践プログラミング」サポートページ
* [bert-classification-tutorial](https://github.com/hppRC/bert-classification-tutorial) ⭐ 232 | 🐛 0 | 🌐 Python | 📅 2024-05-28 -【2023年版】BERTによるテキスト分類
* [fastTextJapaneseTutorial](https://github.com/icoxfog417/fastTextJapaneseTutorial) ⭐ 205 | 🐛 0 | 🌐 Python | 📅 2016-09-29 - Tutorial to train fastText with Japanese corpus
* [genai-agent-advanced-book](https://github.com/masamasa59/genai-agent-advanced-book) ⭐ 203 | 🐛 15 | 🌐 Python | 📅 2025-09-09 - 書籍「現場で活用するための生成AIエージェント実践入門」（講談社サイエンティフィック社）で利用されるソースコード
* [deep-learning-with-pytorch-ja](https://github.com/Gin5050/deep-learning-with-pytorch-ja) ⭐ 145 | 🐛 22 | 🌐 Jupyter Notebook | 📅 2023-08-22 - deep-learning-with-pytorchの日本語版repositoryです。
* [nlp2024-tutorial-3](https://github.com/hiroshi-matsuda-rit/nlp2024-tutorial-3) ⭐ 113 | 🐛 0 | 📅 2024-04-02 - NLP2024 チュートリアル３ 作って学ぶ日本語大規模言語モデル - 環境構築手順とソースコード
* [support-genai-book](https://github.com/yoheikikuta/support-genai-book) ⭐ 102 | 🐛 0 | 📅 2026-08-16 - 原論文から解き明かす生成AI（技術評論社）のサポートページです
* [ir100](https://github.com/ir100/ir100) ⭐ 93 | 🐛 3 | 📅 2025-12-03 - 情報検索100本ノック
* [nlp100v2020](https://github.com/upura/nlp100v2020) ⭐ 90 | 🐛 0 | 🌐 Python | 📅 2025-04-21 - 「言語処理100本ノック 2020」をPythonで解く
* [nlp100v2025](https://github.com/upura/nlp100v2025) ⭐ 90 | 🐛 0 | 🌐 Python | 📅 2025-04-21 - 「言語処理100本ノック 2025」をPythonで解く
* [spacy\_tutorial](https://github.com/yuibi/spacy_tutorial) ⭐ 65 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2020-01-25 - spaCy tutorial in English and Japanese. spacy-transformers, BERT, GiNZA.
* [slp2025](https://github.com/ryota-komatsu/slp2025) ⭐ 65 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-04-18 -音学シンポジウム2025チュートリアル「マルチモーダル大規模言語モデル入門」資料
* [kaggle\_llm\_book](https://github.com/sinchir0/kaggle_llm_book) ⭐ 39 | 🐛 0 | 📅 2026-07-05 - 『Kaggle ではじめる大規模言語モデル入門　～自然言語処理〈実践〉プログラミング～』のサポートサイト
* [llm-jp-4-cookbook](https://github.com/llm-jp/llm-jp-4-cookbook) ⭐ 32 | 🐛 3 | 🌐 Python | 📅 2026-06-23 - Example scripts for LLM-jp-4 models
* [janome-tutorial](https://github.com/mocobeta/janome-tutorial) ⚠️ Archived - Janome を使ったテキストマイニング入門チュートリアルです。
* [bert-classification-tutorial-2024](https://github.com/hpprc/bert-classification-tutorial-2024) ⭐ 30 | 🐛 0 | 🌐 Python | 📅 2024-07-08 - 【2024年版】BERTによるテキスト分類
* [BERT\_Japanese\_Google\_Colaboratory](https://github.com/YutaroOgawa/BERT_Japanese_Google_Colaboratory) ⭐ 29 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2022-01-25 - Google Colaboratoryで日本語のBERTを動かす方法です。
* [kantan-regex-book](https://github.com/makenowjust/kantan-regex-book) ⭐ 21 | 🐛 1 | 🌐 Ruby | 📅 2024-03-23 - 作って学ぶ正規表現エンジン
* [nlp-lecture-keio](https://github.com/takamichi-lab/nlp-lecture-keio) ⭐ 19 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-07-15 - 慶応義塾大学 理工学部 情報工学科 講義「自然言語処理」
* [nlp2025-tutorial-2](https://github.com/yuiseki/nlp2025-tutorial-2) ⭐ 17 | 🐛 48 | 🌐 Jupyter Notebook | 📅 2026-08-20 - NLP2025 のチュートリアル「地理情報と言語処理 実践入門」の資料とソースコード
* [ginza-examples](https://github.com/poyo46/ginza-examples) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2021-01-28 - 日本語NLPライブラリGiNZAのすゝめ
* [nlpbook](https://github.com/mamorlis/nlpbook) ⭐ 14 | 🐛 0 | 📅 2025-04-01 - 「自然言語処理の教科書」サポートサイト
* [Gemma2\_2b\_Japanese\_finetuning\_colab.ipynb](https://github.com/qianniu95/gemma2_2b_finetune_jp_tutorial/blob/main/Gemma2_2b_Japanese_finetuning_colab.ipynb) ⭐ 12 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-08-11 - Fine-Tuning Google Gemma for Japanese Instructions
* [python-nlp-book](https://github.com/python-nlp-book/python-nlp-book) ⭐ 10 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2023-05-07 - ディープラーニングによる自然言語処理（共立出版）のサポートページです
* [JapaneseNLI](https://github.com/verypluming/JapaneseNLI) ⭐ 6 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2021-06-08 - Google Colabで日本語テキスト推論を試す
* [allennlp-NER-ja](https://github.com/shunk031/allennlp-NER-ja) ⚠️ Archived - AllenNLP-NER-ja: AllenNLP による日本語を対象とした固有表現抽出
* [chariot-PyTorch-Japanese-text-classification](https://github.com/ymym3412/chariot-PyTorch-Japanese-text-classification) ⭐ 5 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2019-03-18 - Experiment for Japanese Text classification using chariot and PyTorch
* [topic-models-ao](https://github.com/anemptyarchive/topic-models-ao) ⭐ 4 | 🐛 0 | 🌐 R | 📅 2025-05-26 - 『トピックモデル』(機械学習プロフェッショナルシリーズ)のノート
* [book\_impress\_it-basic-education-ai](https://github.com/liber-craft-co-ltd/book_impress_it-basic-education-ai) ⭐ 4 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-06-18 - インプレス出版「IT基礎教養 自然言語処理＆画像解析」
* [handson-language-models](https://github.com/hnishi/handson-language-models) ⚠️ Archived - 日本語の言語モデルのハンズオン資料です
* [japanese-ir-tutorial](https://github.com/mpkato/japanese-ir-tutorial) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2026-06-11 - 日本語情報検索チュートリアル
* [textmining-ja](https://github.com/paithiov909/textmining-ja) ⭐ 3 | 🐛 2 | 🌐 Dockerfile | 📅 2026-03-24 - Rによる自然言語処理・テキスト分析の練習
* [DocumentClassificationUsingBERT-Japanese](https://github.com/nekoumei/DocumentClassificationUsingBERT-Japanese) ⭐ 0 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-08-27 - DocumentClassificationUsingBERT-Japanese
* [course2024-nlp](https://github.com/tomonari-masada/course2024-nlp) - 2024年度 立教大学大学院 人工知能科学研究科 自然言語処理特論

| Name                                                                                                                                                                                                                     | downloads/week | total downloads | stars            | last commit       |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------- | --------------- | ---------------- | ----------------- |
| 🔗 [spacy\_tutorial](https://github.com/yuibi/spacy_tutorial) ⭐ 65 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2020-01-25                                                                                                       | -              | -               | ⭐ 65             | 🔴 january 2020   |
| 🔗 [fastTextJapaneseTutorial](https://github.com/icoxfog417/fastTextJapaneseTutorial) ⭐ 205 \| 🐛 0 \| 🌐 Python \| 📅 2016-09-29                                                                                        | -              | -               | ⭐ 205            | 🔴 september 2016 |
| 🔗 [allennlp-NER-ja](https://github.com/shunk031/allennlp-NER-ja) ⚠️ Archived                                                                                                                                            | -              | -               | ⭐ 5              | 🔴 may 2022       |
| 🔗 [chariot-PyTorch-Japanese-text-classification](https://github.com/ymym3412/chariot-PyTorch-Japanese-text-classification) ⭐ 5 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2019-03-18                                          | -              | -               | ⭐ 5              | 🔴 march 2019     |
| 🔗 [ginza-examples](https://github.com/poyo46/ginza-examples) ⭐ 15 \| 🐛 0 \| 🌐 Python \| 📅 2021-01-28                                                                                                                 | -              | -               | ⭐ 15             | 🔴 january 2021   |
| 🔗 [DocumentClassificationUsingBERT-Japanese](https://github.com/nekoumei/DocumentClassificationUsingBERT-Japanese) ⭐ 0 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2025-08-27                                                  | -              | -               | ⭐ 0              | 🔴 august 2025    |
| 🔗 [BERT\_Japanese\_Google\_Colaboratory](https://github.com/YutaroOgawa/BERT_Japanese_Google_Colaboratory) ⭐ 29 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2022-01-25                                                         | -              | -               | ⭐ 29             | 🔴 january 2022   |
| 🔗 [bert-book](https://github.com/stockmarkteam/bert-book) ⭐ 265 \| 🐛 8 \| 🌐 Jupyter Notebook \| 📅 2024-02-13                                                                                                         | -              | -               | ⭐ 265            | 🔴 february 2024  |
| 🔗 [janome-tutorial](https://github.com/mocobeta/janome-tutorial) ⚠️ Archived                                                                                                                                            | -              | -               | ⭐ 31             | 🔴 march 2019     |
| 🔗 [handson-language-models](https://github.com/hnishi/handson-language-models) ⚠️ Archived                                                                                                                              | -              | -               | ⭐ 3              | 🔴 march 2021     |
| 🔗 [JapaneseNLI](https://github.com/verypluming/JapaneseNLI) ⭐ 6 \| 🐛 1 \| 🌐 Jupyter Notebook \| 📅 2021-06-08                                                                                                         | -              | -               | ⭐ 6              | 🔴 june 2021      |
| 🔗 [deep-learning-with-pytorch-ja](https://github.com/Gin5050/deep-learning-with-pytorch-ja) ⭐ 145 \| 🐛 22 \| 🌐 Jupyter Notebook \| 📅 2023-08-22                                                                      | -              | -               | ⭐ 144            | 🔴 may 2021       |
| 🔗 [bert-classification-tutorial](https://github.com/hppRC/bert-classification-tutorial) ⭐ 232 \| 🐛 0 \| 🌐 Python \| 📅 2024-05-28                                                                                     | -              | -               | ⭐ 232            | 🔴 may 2024       |
| 🔗 [python-nlp-book](https://github.com/python-nlp-book/python-nlp-book) ⭐ 10 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2023-05-07                                                                                            | -              | -               | ⭐ 10             | 🔴 may 2023       |
| 🔗 [llm-book](https://github.com/ghmagazine/llm-book) ⭐ 474 \| 🐛 5 \| 🌐 Jupyter Notebook \| 📅 2025-12-31                                                                                                              | -              | -               | ⭐ 474            | 🟡 december 2025  |
| 🔗 [nlp2024-tutorial-3](https://github.com/hiroshi-matsuda-rit/nlp2024-tutorial-3) ⭐ 113 \| 🐛 0 \| 📅 2024-04-02                                                                                                        | -              | -               | ⭐ 113            | 🔴 april 2024     |
| 🔗 [japanese-ir-tutorial](https://github.com/mpkato/japanese-ir-tutorial) ⭐ 3 \| 🐛 1 \| 🌐 Python \| 📅 2026-06-11                                                                                                      | -              | -               | ⭐ 3              | 🔴 june 2024      |
| 🔗 [nlpbook](https://github.com/mamorlis/nlpbook) ⭐ 14 \| 🐛 0 \| 📅 2025-04-01                                                                                                                                          | -              | -               | ⭐ 14             | 🔴 april 2025     |
| 🔗 [kantan-regex-book](https://github.com/makenowjust/kantan-regex-book) ⭐ 21 \| 🐛 1 \| 🌐 Ruby \| 📅 2024-03-23                                                                                                        | -              | -               | ⭐ 21             | 🔴 march 2024     |
| 🔗 [bert-classification-tutorial-2024](https://github.com/hpprc/bert-classification-tutorial-2024) ⭐ 30 \| 🐛 0 \| 🌐 Python \| 📅 2024-07-08                                                                            | -              | -               | ⭐ 30             | 🔴 july 2024      |
| 🔗 [Gemma2\_2b\_Japanese\_finetuning\_colab.ipynb](https://github.com/qianniu95/gemma2_2b_finetune_jp_tutorial/blob/main/Gemma2_2b_Japanese_finetuning_colab.ipynb) ⭐ 12 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2024-08-11 | -              | -               | ⭐ repo not found | 🔴 august 2024    |
| 🔗 [nlp100v2020](https://github.com/upura/nlp100v2020) ⭐ 90 \| 🐛 0 \| 🌐 Python \| 📅 2025-04-21                                                                                                                        | -              | -               | ⭐ 89             | 🔴 april 2025     |
| 🔗 [textmining-ja](https://github.com/paithiov909/textmining-ja) ⭐ 3 \| 🐛 2 \| 🌐 Dockerfile \| 📅 2026-03-24                                                                                                           | -              | -               | ⭐ 3              | 🟡 march          |
| 🔗 [nlp2025-tutorial-2](https://github.com/yuiseki/nlp2025-tutorial-2) ⭐ 17 \| 🐛 48 \| 🌐 Jupyter Notebook \| 📅 2026-08-20                                                                                             | -              | -               | ⭐ 17             | 🟡 february       |
| 🔗 [nlp100v2025](https://github.com/upura/nlp100v2025) ⭐ 90 \| 🐛 0 \| 🌐 Python \| 📅 2025-04-21                                                                                                                        | -              | -               | ⭐ 89             | 🔴 april 2025     |
| 🔗 [public-annotations](https://github.com/manga109/public-annotations) ⭐ 13 \| 🐛 0 \| 📅 2025-04-23                                                                                                                    | -              | -               | ⭐ 13             | 🔴 april 2025     |
| 🔗 [topic-models-ao](https://github.com/anemptyarchive/topic-models-ao) ⭐ 4 \| 🐛 0 \| 🌐 R \| 📅 2025-05-26                                                                                                             | -              | -               | ⭐ 4              | 🔴 may 2025       |
| 🔗 [slp2025](https://github.com/ryota-komatsu/slp2025) ⭐ 65 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2026-04-18                                                                                                              | -              | -               | ⭐ 65             | 🟡 april          |
| 🔗 [book\_impress\_it-basic-education-ai](https://github.com/liber-craft-co-ltd/book_impress_it-basic-education-ai) ⭐ 4 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2025-06-18                                                  | -              | -               | ⭐ 4              | 🔴 june 2025      |
| 🔗 [genai-agent-advanced-book](https://github.com/masamasa59/genai-agent-advanced-book) ⭐ 203 \| 🐛 15 \| 🌐 Python \| 📅 2025-09-09                                                                                     | -              | -               | ⭐ 203            | 🟡 september 2025 |
| 🔗 [course2024-nlp](https://github.com/tomonari-masada/course2024-nlp)                                                                                                                                                   | -              | -               | ⭐ repo not found | 🔴 repo not found |
| 🔗 [support-genai-book](https://github.com/yoheikikuta/support-genai-book) ⭐ 102 \| 🐛 0 \| 📅 2026-08-16                                                                                                                | -              | -               | ⭐ 102            | 🟢 yesterday      |
| 🔗 [ir100](https://github.com/ir100/ir100) ⭐ 93 \| 🐛 3 \| 📅 2025-12-03                                                                                                                                                 | -              | -               | ⭐ 93             | 🟡 december 2025  |
| 🔗 [kaggle\_llm\_book](https://github.com/sinchir0/kaggle_llm_book) ⭐ 39 \| 🐛 0 \| 📅 2026-07-05                                                                                                                        | -              | -               | ⭐ 38             | 🟢 july           |
| 🔗 [nlp-lecture-keio](https://github.com/takamichi-lab/nlp-lecture-keio) ⭐ 19 \| 🐛 0 \| 🌐 Jupyter Notebook \| 📅 2026-07-15                                                                                            | -              | -               | ⭐ 19             | 🟢 july           |
| 🔗 [llm-jp-4-cookbook](https://github.com/llm-jp/llm-jp-4-cookbook) ⭐ 32 \| 🐛 3 \| 🌐 Python \| 📅 2026-06-23                                                                                                           | -              | -               | ⭐ 32             | 🟢 june           |
| 🔗 [ttslearn](https://github.com/r9y9/ttslearn) ⭐ 269 \| 🐛 7 \| 🌐 Jupyter Notebook \| 📅 2023-03-07                                                                                                                    | -              | -               | ⭐ 269            | 🔴 march 2023     |

## Research summary

Summaries of studies and papers in Japanese NLP research

* [awesome-japanese-llm](https://github.com/llm-jp/awesome-japanese-llm) ⭐ 1,426 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-19 - オープンソースの日本語LLMまとめ
* [tuning\_playbook\_ja](https://github.com/Valkyrja3607/tuning_playbook_ja) ⭐ 190 | 🐛 0 | 📅 2023-01-22 - ディープラーニングモデルの性能を体系的に最大化するためのプレイブック
* [awesome-bert-japanese](https://github.com/himkt/awesome-bert-japanese) ⭐ 132 | 🐛 7 | 📅 2023-03-15 - A list of pre-trained BERT models for Japanese with word/subword tokenization + vocabulary construction algorithm information
* [japanese-pitch-accent-resources](https://github.com/olety/japanese-pitch-accent-resources) ⭐ 127 | 🐛 1 | 📅 2024-02-10 - Trying to consolidate japanese phonetic, and in particular pitch accent resources into one list
* [dataset-list](https://github.com/ikegami-yukino/dataset-list) ⭐ 120 | 🐛 0 | 📅 2024-07-25 - lists of text corpus and more (mainly Japanese)
* [GEC-Info-ja](https://github.com/gotutiyan/GEC-Info-ja) ⭐ 14 | 🐛 0 | 📅 2025-04-17 - 文法誤り訂正に関する日本語文献を収集・分類するためのリポジトリ

| Name                                                                                                                          | downloads/week | total downloads | stars  | last commit      |
| ----------------------------------------------------------------------------------------------------------------------------- | -------------- | --------------- | ------ | ---------------- |
| 🔗 [awesome-bert-japanese](https://github.com/himkt/awesome-bert-japanese) ⭐ 132 \| 🐛 7 \| 📅 2023-03-15                     | -              | -               | ⭐ 132  | 🔴 march 2023    |
| 🔗 [GEC-Info-ja](https://github.com/gotutiyan/GEC-Info-ja) ⭐ 14 \| 🐛 0 \| 📅 2025-04-17                                      | -              | -               | ⭐ 14   | 🔴 april 2025    |
| 🔗 [dataset-list](https://github.com/ikegami-yukino/dataset-list) ⭐ 120 \| 🐛 0 \| 📅 2024-07-25                              | -              | -               | ⭐ 120  | 🔴 july 2024     |
| 🔗 [tuning\_playbook\_ja](https://github.com/Valkyrja3607/tuning_playbook_ja) ⭐ 190 \| 🐛 0 \| 📅 2023-01-22                  | -              | -               | ⭐ 190  | 🔴 january 2023  |
| 🔗 [japanese-pitch-accent-resources](https://github.com/olety/japanese-pitch-accent-resources) ⭐ 127 \| 🐛 1 \| 📅 2024-02-10 | -              | -               | ⭐ 127  | 🔴 february 2024 |
| 🔗 [awesome-japanese-llm](https://github.com/llm-jp/awesome-japanese-llm) ⭐ 1,426 \| 🐛 1 \| 🌐 TypeScript \| 📅 2026-08-19   | -              | -               | ⭐ 1.4k | 🟢 august        |

## Reference

* [Awesome-Rust-MachineLearning-日本語向けのrustクレートや記事等をまとめたもの](https://github.com/vaaaaanquish/Awesome-Rust-MachineLearning/blob/main/README.ja.md) ⭐ 2,264 | 🐛 12 | 🌐 JavaScript | 📅 2023-09-25
* <https://github.com/himkt/awesome-bert-japanese> ⭐ 132 | 🐛 7 | 📅 2023-03-15
* [自然言語処理の餅屋](https://www.jnlp.org/nlp/top)
* [yasuokaの日記： 日本語係り受け解析器「2020年の総ざらえ」](https://srad.jp/~yasuoka/journal/643631/)
* [yasuokaの日記： 日本語係り受け解析器「2021年の総ざらえ」](https://srad.jp/~yasuoka/journal/651542/)
* <https://github.com/topics/japanese?l=python>
* <https://github.com/topics/japanese-language?l=python>
* <https://github.com/search?o=desc&q=corpus+japanese&s=&type=Repositories>
* <https://paperswithcode.com/datasets?lang=japanese>
* [大規模言語モデル入門Ⅱ 〜生成型LLMの実装と評価](https://gihyo.jp/book/2024/978-4-297-14393-0)

## Contributors

* [kaisugi](https://github.com/kaisugi) - [website](https://kaisugi.me)
* [bomin0624](https://github.com/bomin0624) - [twitter](https://twitter.com/bomin0624_c)
* [passaglia](https://github.com/passaglia) - [twitter](https://twitter.com/SamPassaglia)
* [sarumaj](https://github.com/sarumaj) - [github](https://github.com/sarumaj)
* [ln2058](https://github.com/ln2058) - [github](https://github.com/ln2058)
* [ajtgjmdjp](https://github.com/ajtgjmdjp) - [github](https://github.com/ajtgjmdjp)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-20._
