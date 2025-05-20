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

---

## 🧠 Why It Exists

Storage is still misunderstood. Benchmarks are often misused. This repo:

- Simplifies the chaos of FIO flags  
- Adds structure to how we run and interpret tests  
- Makes performance analysis scriptable, portable, and teachable  

Whether you're a dev, sysadmin, CS student, or just testing your SSDs for fun — this gives you the baseline to do it right.

---

## ⚙️ Features

- ✅ Prebuilt FIO job templates for common scenarios (read, write, randrw, etc.)  
- 🔁 Batch run support (run multiple jobs, multiple passes)  
- 📄 Output logging to JSON, CSV, or terminal summary  
- 📈 Optional integration with Python tools (`matplotlib`, `pandas`) for graphs  
- 🛠️ Clean modular scripts written in Bash or Python (depends on branch/setup)  

---

## 🚀 Quickstart

### 1. Clone it

```bash
git clone https://github.com/wegettingit/fio-toolkit.git
cd fio-toolkit
./run.sh jobs/read-seq.fio
./run.sh --batch jobs/
├── jobs/              # Predefined fio job files
├── results/           # Output directory (auto-created)
├── scripts/           # Optional analysis/graphing tools
├── run.sh             # Main script runner
├── README.md          # This file
{
  "jobs": [
    {
      "jobname": "seq-read",
      "read": {
        "iops": 8421,
        "bw": 1072,
        "lat_ns": { "mean": 37120 }
      }
    }
  ]
}
results/
*.log
*.json
*.csv
__pycache__/
.env
MIT License — feel free to fork, remix, or reuse with attribution.Johne — chef, developer, builder of tools for those who do the work.
GitHub Profile →
---

Let me know when you're ready to move onto:
- `run.sh` scripting logic  
- `parse.py` or visualizations  
- GitHub Actions or Docs site setup  

This `README.md` is plug-and-play — just commit it.
