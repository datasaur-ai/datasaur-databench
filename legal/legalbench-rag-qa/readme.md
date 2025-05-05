# 📚 LegalBench-RAG QA Samples

This repository contains a curated and modified subset of the [LegalBench-RAG](https://www.dropbox.com/scl/fo/r7xfa5i3hdsbxex1w6amw/AID389Olvtm-ZLTKAPrw6k4?rlkey=5n8zrbk4c08lbit3iiexofmwg&e=1&st=0hu354cq&dl=0) dataset, designed to evaluate large language models (LLMs) for legal document understanding and question answering (QA) tasks.


## 🧾 Overview

LegalBench-RAG was originally developed to benchmark the retrieval capabilities of RAG systems in the legal domain. In this project, we adapt and restructure a sample of that dataset to support **QA tasks**, where answers are generated from reference contexts.

## 📊 Dataset Summary

- **Total QA Pairs:** 200
- **Source Domains:** ContractNLI, CUAD, MAUD, PrivacyQA
- **Format:** CSV files with `prompt`, `expected completion`, and `source_file` columns

## 🔍 Use Cases

- **Document QA Tasks:** Validate LLM performance on legal document comprehension when the relevant context is specified.
- **QA Data for Fine-tuning or Prompting:** Train or prompt models using structured legal QA examples.

## 🧪 How to Use

1. Load a sample CSV from any dataset (e.g., `contractnli.csv`).
2. Use the `prompt` as the input query.
3. Use the content from `source_file` as the reference context (or simulate retrieval).
4. Compare the model's output to the `expected completion`.

## 📜 License

This dataset is derived from the original LegalBench-RAG dataset. Please refer to the original project's [license](https://github.com/zeroentropy-ai/legalbenchrag?tab=MIT-1-ov-file) for more information.