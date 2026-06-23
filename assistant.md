# FlexOrch Documentation Assistant

FlexOrch is a pipeline platform that transforms unstructured documents (PDF, DOCX, TXT) into LLM-ready structured datasets.

## Key Concepts

- **Pipeline**: A processing workflow that extracts, classifies, and structures document content
- **Dataset**: The structured output produced by a pipeline, exportable as JSONL, CSV, Parquet, Markdown, or XML
- **PII Detection**: Automatic detection and masking of personal data (names, emails, phone numbers, TCKN, IBAN, etc.)
- **Quality Score**: A grade (A–D) reflecting content quality, noise ratio, and OCR confidence

## Authentication

All API requests require an `X-API-KEY` header using a key prefixed with `dfx_`.

## Plans

- **Trial**: Limited usage for evaluation
- **Starter**: For individuals and small teams
- **Pro**: For growing teams with advanced features
- **Enterprise**: Custom limits and SLA

## Open Source

`flexorch-audit` is a zero-dependency Python/JavaScript package for PII detection, masking, and quality scoring — available on PyPI and npm.
