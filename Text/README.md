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
<table>
    <tr>
        <th>Model</th>
        <th colspan="3">H1 (Safe/Unsafe)</th>
        <th colspan="3">H2 (Adult/Harmful/Suicidal)</th>
    </tr>
    <tr>
        <th></th>
        <th>P</th>
        <th>R</th>
        <th>F1</th>
        <th>P</th>
        <th>R</th>
        <th>F1</th>
    </tr>
    <tr>
        <td>BanglaBERT</td>
        <td>0.8147</td>
        <td>0.8179</td>
        <td>0.8158</td>
        <td>0.8027</td>
        <td>0.8019</td>
        <td>0.8005</td>
    </tr>
    <tr>
        <td>mBERT</td>
        <td>0.8025</td>
        <td>0.8047</td>
        <td>0.8034</td>
        <td>0.7939</td>
        <td>0.7984</td>
        <td>0.7942</td>
    </tr>
    <tr>
        <td>XLM-R</td>
        <td>0.8145</td>
        <td>0.8163</td>
        <td>0.8153</td>
        <td>0.7776</td>
        <td>0.7763</td>
        <td>0.7707</td>
    </tr>
</table>

