# AI Pipeline

> A modular pipeline for extracting structured company information from unstructured documents using Large Language Models (LLMs).

---

## Overview

AI Pipeline is a Python application designed to automate the extraction of structured business information from multiple document sources.

The project emphasizes:

- Clean Architecture
- SOLID principles
- Modular design
- Testability
- Technology independence

Rather than coupling business logic to a specific LLM provider, the system is designed around abstractions that allow different implementations to be used with minimal changes.

---

## Goals

- Extract structured information from company documents.
- Support multiple document formats.
- Produce consistent datasets for downstream analysis.
- Remain independent of any specific LLM provider.
- Be easy to extend and maintain.

---

## Planned Features

- Document ingestion
- LLM-based information extraction
- Data validation
- Structured dataset generation
- Configurable storage backends
- CLI interface

---

## Project Structure

```text
src/
    ai_pipeline/
        application/
        cli/
        config/
        core/
        domain/
        infrastructure/

docs/
tests/
```

---

## Technology Stack

- Python 3.12
- uv
- Ruff
- Pytest
- Git
- GitHub

Additional technologies will be introduced as the project evolves.

---

## Status

🚧 Early development