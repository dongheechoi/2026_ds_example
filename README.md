# 부산대 데이터과학입문 — 강의 코드 예제 (2026-1)

[부산대학교 정보컴퓨터공학부 · 데이터과학입문](https://pusan.ac.kr/) · 최동희 (`dchoi@pusan.ac.kr`)

강의 슬라이드의 모든 코드 예제를 **Google Colab에서 바로 실행**할 수 있도록 정리한 저장소.
데이터셋은 본 repo의 `data/` 폴더에서 raw URL로 직접 읽어오므로 **별도 파일 업로드 불필요**.

---

## Notebooks

| Lecture | Topic | Open in Colab |
|---------|-------|---------------|
| 10 | Functions, Tables, and Sampling | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dongheechoi/2026_ds_example/blob/main/notebooks/10_functions_tables_sampling.ipynb) |

---

## Datasets (`data/`)

| File | Source | Used in |
|------|--------|---------|
| `top_movies_2017.csv` | Berkeley Data 8 textbook | Lecture 10 (recap, sampling) |
| `galton.csv` | Galton family height data (Berkeley Data 8) | Lecture 10 (`apply()` prediction) |
| `united_summer2015.csv` | United Airlines summer 2015 flight delays (Berkeley Data 8) | Lecture 10 (sampling, statistic) |

원 데이터 출처: [data-8/textbook](https://github.com/data-8/textbook/tree/main/assets/data)

---

## 사용법

### Google Colab (권장)
위 표의 "Open in Colab" 배지 클릭 → 그대로 실행.

### 로컬 실행
```bash
git clone https://github.com/dongheechoi/2026_ds_example.git
cd 2026_ds_example
jupyter lab notebooks/
```
필요 패키지: `numpy pandas matplotlib seaborn`

---

## License
강의 자료 부분: CC BY 4.0  ·  데이터: 원본 출처 라이선스를 따름 (Berkeley Data 8 데이터는 공개)
