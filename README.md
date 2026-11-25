# Factor Graph Project

## Giới thiệu / Introduction

Dự án nghiên cứu và triển khai Factor Graph cho bài toán suy luận xác suất.

---

## Cấu trúc thư mục / Project Structure

```
Factor-Graph/
├── GROUP_INFO.md          # Team and topic information
├── AI_USAGE.md            # AI usage declaration
├── README.md
├── configs/               # Run configuration and interface version
├── docs/                  # Model, interface, and usage documentation
├── src/
│   ├── data_generator/    # Baseline and advanced data generators
│   ├── algorithm/         # Baseline and advanced algorithms
│   └── evaluator/         # Metrics, evaluator, and validator
├── data/
│   ├── baseline/          # Public baseline data
│   ├── advanced/          # Team-generated advanced data
│   └── tests/             # Test data and test cases
├── reports/               # Technical report and appendices
├── slides/                # Presentation slides
├── logs/
│   ├── meetings/          # Meeting minutes
│   └── work/              # Work logs
└── artifacts/             # Run results, plots, demos, and evidence
```

---

## Hướng dẫn cài đặt / Setup Instructions

```bash
# Clone repository
git clone <repo-url>
cd Factor-Graph

# Cài đặt dependencies
pip install -r configs/requirements.txt
```

---

## Hướng dẫn chạy / How to Run

```bash
# Chạy baseline
python src/algorithm/baseline.py --config configs/baseline.yaml

# Chạy advanced
python src/algorithm/advanced.py --config configs/advanced.yaml
```
