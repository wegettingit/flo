# 🧪 FIO Toolkit by Johne

A modular, scriptable, and human-readable benchmarking suite built around [FIO](https://fio.readthedocs.io/en/latest/).  
Designed for real-world testing, automation, and education in environments where precision matters.

> _“Measure like a scientist. Optimize like a chef.”_

---

## 📦 What This Repo Is

This is more than just a wrapper around `fio`. It's a growing toolkit for:

- 🔁 Automating repeatable I/O tests across environments  
- 📚 Teaching others how to understand disk behavior through real results  
- 📊 Producing readable `.csv` and `.json` reports from raw benchmarking  
- 🍳 Helping chefs, coders, and creators understand how the tools beneath them perform  

---

## 🚀 Quick Start

```bash
git clone https://github.com/wegettingit/fio-toolkit.git
cd fio-toolkit
./run.sh jobs/read-seq.fio
./run.sh --batch jobs/
