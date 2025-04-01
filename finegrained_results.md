For each candidate-LLM, we show the fine-grained per-question-type results of running our preambles attack and the best-performing baselines. Each attack is run five times and the results are averaged.

*Command R7B*

| | Refinement | Universal | Preambles |
|-----------|-----------|-----------|-----------|
| Writing | 8.45 ± 0.04 | 8.71 ± 0.01 | 8.61 ± 0.07 |
| Roleplay | 8.60 ± 0.05 | 8.65 ± 0.03 | 8.69 ± 0.06 |
| Reasoning | 5.63 ± 0.09 | 4.90 ± 0.06 | 5.89 ± 0.11 |
| Math | 4.47 ± 0.10 | 3.60 ± 0.07 | 6.51 ± 0.12 |
| Coding | 8.08 ± 0.09 | 7.15 ± 0.09 | 7.49 ± 0.09 |
| Extraction | 8.01 ± 0.08 | 8.41 ± 0.03 | 8.41 ± 0.05 |
| STEM | 8.93 ± 0.02 | 8.96 ± 0.01 | 9.00 ± 0.00 | 
| Humanities | 8.71 ± 0.01 | 8.92 ± 0.01 | 8.88 ± 0.02 |


*Command R*

| | Refinement | Universal | Preambles |
|-----------|-----------|-----------|-----------|
| Writing | 8.45 ± 0.04 | 8.76 ± 0.02 | 8.67 ± 0.01 |
| Roleplay | 8.64 ± 0.02 | 8.65 ± 0.02 | 8.65 ± 0.02 |
| Reasoning | 6.03 ± 0.05 | 5.98 ± 0.11 | 6.85 ± 0.07 |
| Math | 6.46 ± 0.15 | 6.29 ± 0.13 | 7.11 ± 0.10 |
| Coding | 7.99 ± 0.08 | 7.04 ± 0.05 | 7.47 ± 0.09 |
| Extraction | 8.29 ± 0.05 | 8.69 ± 0.03 | 8.80 ± 0.02 |
| STEM | 8.87 ± 0.01 | 9.00 ± 0.00 | 8.96 ± 0.02 | 
| Humanities | 8.89 ± 0.03 | 8.96 ± 0.01 | 8.90 ± 0.02 |


*Llama 3.1 70B Instruct*

| | Refinement | Universal | Preambles |
|-----------|-----------|-----------|-----------|
| Writing | 8.56 ± 0.03 | 8.64 ± 0.01 | 8.68 ± 0.05 |
| Roleplay | 8.71 ± 0.04 | 8.90 ± 0.02 | 8.82 ± 0.06 |
| Reasoning | 6.49 ± 0.13 | 5.74 ± 0.14 | 6.64 ± 0.13 |
| Math | 6.72 ± 0.13 | 7.68 ± 0.09 | 7.23 ± 0.12 |
| Coding | 8.48 ± 0.05 | 7.83 ± 0.09 | 7.73 ± 0.08 |
| Extraction | 8.47 ± 0.06 | 8.88 ± 0.03 | 8.79 ± 0.04 |
| STEM | 8.90 ± 0.03 | 8.69 ± 0.01 | 8.95 ± 0.03 | 
| Humanities | 8.69 ± 0.06 | 9.00 ± 0.00 | 8.92 ± 0.01 |



