
# 🧾 Legal QA Dataset from Public Court Sources

This folder contains a dataset we created for legal question answering (QA) tasks. The data includes both questions and answers, along with the source legal documents they refer to.

## 📂 What's Inside

- **QA pairs**: Each example includes a question, an answer, and a reference to the source document.
- **Source files**: Legal documents in PDF format, used to create and support the QA pairs.

## 🌐 Sources

We collected legal documents from publicly available websites, including:

- [U.S. Department of Justice - Large Cases](https://www.justice.gov/information-victims-large-cases)
- [U.S. Supreme Court - Slip Opinions](https://www.supremecourt.gov/opinions/slipopinion/24)
- [U.S. Supreme Court - Orders](https://www.supremecourt.gov/opinions/relatingtoorders/24)
- [U.S. Court of Appeals for the First Circuit](https://www.ca1.uscourts.gov/opnrss)

## 🧠 Purpose

This dataset is designed to:
- Support legal document understanding tasks
- Benchmark LLM (large language model) performance on real legal documents
- Enable QA systems to answer questions grounded in official court materials

## ✍️ QA Generation

The questions and answers in this dataset are synthesized based on real legal documents. We carefully created the QA pairs by selecting key information from the legal texts and framing relevant questions. This ensures that the dataset remains grounded in real legal content while facilitating effective legal document understanding and QA tasks.

## 📎 Notes

- All source documents are publicly available.
- Each QA example is linked to a specific legal document from one of the sources above.
