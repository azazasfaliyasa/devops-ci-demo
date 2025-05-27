# DevOps CI Demo

Proyek ini adalah simulasi sederhana untuk memahami alur kerja Continuous Integration (CI) menggunakan GitHub Actions dengan Python.

## 🚀 Fitur

- Unit testing otomatis menggunakan `pytest`
- Coverage laporan dengan `pytest-cov`
- Linting kode dengan `flake8`
- GitHub Actions workflow yang berjalan otomatis saat push atau pull request

## 🧪 Struktur Workflow

File workflow berada di: `.github/workflows/python-ci.yml`

### Langkah CI:
1. Checkout kode dari repository
2. Setup Python 3.10 di runner
3. Install dependencies dari `requirements.txt`
4. Jalankan `pytest` dan tampilkan coverage
5. Jalankan linting dengan `flake8`

### Event Trigger:
- `push` ke branch apa pun
- `pull_request` ke branch utama

## 📊 Coverage dan Linting

Pastikan semua file Python:
- Memiliki coverage test minimal 80%
- Lolos pengecekan PEP8 dengan `flake8`

## ✅ Status CI

![CI](https://github.com/azazasfaliyasa/devops-ci-demo/actions/workflows/python-ci.yml/badge.svg)

> Ganti `USERNAME` dengan username GitHub kamu.

## 📂 Struktur Folder

```
.
├── hello.py
├── test_hello.py
├── requirements.txt
├── .gitignore
├── .flake8
├── README.md
└── .github/
    └── workflows/
        └── python-ci.yml
```

## 🧰 Tools

- Python 3.10+
- pytest
- pytest-cov
- flake8
- GitHub Actions

---

Happy DevOps-ing! 🚀