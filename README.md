# Benchmark Datasets for LLM Evaluation

This repository contains three datasets designed for evaluating and benchmarking large language models (LLMs) on legal question answering (QA) and related tasks.

## 📁 Datasets

### 1. Legal QA from Public Court Sources
A synthetic QA dataset created from real legal documents. Each question and answer is synthesized based on publicly available legal texts.

- **QA Pairs**: Each example includes a question, an answer, and a link to the source document.
- **Source Documents**: PDF files from:
  - [U.S. Department of Justice – Large Cases](https://www.justice.gov/information-victims-large-cases)
  - [U.S. Supreme Court – Slip Opinions](https://www.supremecourt.gov/opinions/slipopinion/24)
  - [U.S. Supreme Court – Orders](https://www.supremecourt.gov/opinions/relatingtoorders/24)
  - [U.S. Court of Appeals – First Circuit](https://www.ca1.uscourts.gov/opnrss)

### 2. LegalBench Subset for LLM Benchmarking
A smaller version of the [LegalBench](https://github.com/HazyResearch/legalbench) dataset, reformatted for easier benchmarking.

- **Tasks**: 129 legal reasoning tasks
- **Examples**: 10 examples per task
- **Format**: Reformatted for benchmark compatibility
- **License**: Includes only tasks with reuse-friendly licenses

### 3. LegalBench-RAG QA Samples
A subset of the [LegalBench-RAG](https://www.dropbox.com/scl/fo/r7xfa5i3hdsbxex1w6amw/AID389Olvtm-ZLTKAPrw6k4?rlkey=5n8zrbk4c08lbit3iiexofmwg&e=1&st=0hu354cq&dl=0) dataset, focused on retrieval-augmented QA tasks.

- **QA Pairs**: 200 examples
- **Domains**: ContractNLI, CUAD, MAUD, PrivacyQA
- **Format**: CSV files with prompt, expected answer, and reference context
- **Use Case**: Useful for testing legal document QA with retrieval-based context

---

These datasets are designed for legal QA, model training, and benchmarking tasks. Please refer to each dataset’s source license for usage terms.

