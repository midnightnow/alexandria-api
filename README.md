# ⚡ Alexandria FastAPI Validation Service

**Lightweight DOI validation API for research papers**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.11](https://img.shields.io/badge/python-3.11-blue.svg)](https://www.python.org/downloads/)

A minimal, fast API for research paper validation data. Returns validation scores, peer review counts, citation metrics, and dispute flags for any DOI.

## 🚀 Live Demo

- **Base URL:** [https://alexandria.hardcard.org](https://alexandria.hardcard.org)
- **Health Check:** [https://alexandria.hardcard.org/health](https://alexandria.hardcard.org/health)
- **Sample DOI:** [https://alexandria.hardcard.org/api/v1/validations/10.1038/s41586-024-07123](https://alexandria.hardcard.org/api/v1/validations/10.1038/s41586-024-07123)

## ✨ Features

- ✅ **FastAPI** - Modern, async Python framework
- ✅ **Rate Limiting** - 1000 requests/hour per IP
- ✅ **Security Headers** - HSTS, CSP, XSS protection
- ✅ **Batch Validation** - Check up to 50 DOIs at once
- ✅ **Seed Data** - 20 example papers included
- ✅ **Auto Docs** - Swagger UI at `/docs`

## 🚀 Quick Start

### Local Development
```bash
# Clone and install
git clone https://github.com/midnightnow/alexandria-api
cd alexandria-api
pip install -r requirements.txt

# Run server
python main.py

# View at http://localhost:8083
# API docs at http://localhost:8083/docs