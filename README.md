# 🔧 FIO Toolkit by Johne

A modular, scriptable, and human-readable benchmarking suite built around [FIO](https://github.com/axboe/fio), designed for real-world testing, automation, and education.

> “Measure like a scientist. Optimize like a chef.”

---

## 📌 What This Repo Is

This is more than just a wrapper around `fio`. It’s a growing toolkit for:

- 🔁 Automating repeatable I/O tests across environments
- 🧪 Teaching others how to understand disk behavior through real results
- 📊 Parsing and visualizing FIO JSON output
- 🧰 Crafting your own FIO job files with smart defaults
- 🔬 Auditing disk performance over time

## 🧠 Why It Exists

Storage is still misunderstood. Benchmarks are often misused. This repo:
- Simplifies the chaos of FIO flags
- Adds structure to how we run and interpret tests
- Makes performance analysis scriptable, portable, and teachable

Whether you're a dev, sysadmin, CS student, or just testing your SSDs for fun — this gives you the baseline to do it right.

---

## ⚙️ Features

- ✅ Prebuilt FIO job templates for common scenarios (read, write, randrw, etc.)
- 🌀 Batch run support (run multiple jobs, multiple passes)
- 📄 Output logging to JSON, CSV, or terminal summary
- 📈 Optional integration with Python tools (`matplotlib`, `pandas`) for graphs
- 🛠️ Clean modular scripts written in Bash or Python (depends on branch/setup)

---

## 🚀 Quickstart

### 1. Clone it

```bash
git clone https://github.com/wegettingit/fio-toolkit.git
cd fio-toolkit
