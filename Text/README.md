## Train Dataset
| Class  | Safe | Unsafe      | Total |
|-------|-----|----------|-----------|
| Safe | 4377 | 0 | 4377 |
| Adult | 0 | 1434 | 1434 |
| Harmful | 0 | 1100 | 1100 |
| Suicidal | 0 | 849 | 849 |
| Total | 4377 | 3383 | 7760 |

## Test Dataset
| Class  | Safe | Unsafe      | Total |
|-------|-----|----------|-----------|
| Safe | 285 | 0 | 285 |
| Adult | 0 | 93 | 93 |
| Harmful | 0 | 72 | 72 |
| Suicidal | 0 | 55 | 55 |
| Total | 285 | 220 | 505 |

## Result
db09c08b76c3a229711c587bff83682e1f1991eb

| Model | H1 (Safe/Unsafe) |   |   | H2 (Adult/Harmful/Suicidal) |   |   |  
|-------|----|---|---|----|---|---|  
|       | P | R | F1 | P | R | F1 |  
| BanglaBERT | 0.8147 | 0.8179 | 0.8158 | 0.8027 | 0.8019 | 0.8005 |
| mBERT | 0.8025  |  0.8047  |  0.8034 | 0.7939  |  0.7984 |   0.7942 |
| XLM-R | 0.8145 | 0.8163 | 0.8153 | 0.7776 | 0.7763 | 0.7707 |
