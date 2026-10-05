## The missing number is **51**

**How to spot it:** The grid should contain every integer from 1 to 100. Scanning row by row, everything runs in perfect order until the 6th row, which reads:

> 46, 47, 48, 49, 50, **52**, 53, 54, 55

The sequence jumps from 50 straight to 52 — skipping **51**.

<details>
<summary>Verification details</summary>

| Check | Result |
|---|---|
| Numbers written in the image | 99 (should be 100) |
| Missing value | $\{51\}$ |
| Sum check | $\sum_{n=1}^{100} n = 5050$, but the written numbers sum to $4999$, and $5050 - 4999 = 51$ |

Row-by-row transcription:

```text
 1  2  3  4  5  6  7  8  9
10 11 12 13 14 15 16 17 18
19 20 21 22 23 24 25 26 27
28 29 30 31 32 33 34 35 36
37 38 39 40 41 42 43 44 45
46 47 48 49 50 [52] 53 54 55   ← 51 skipped
56 57 58 59 60 61 62 63 64
65 66 67 68 69 70 71 72 73
74 75 76 77 78 79 80 81 82
83 84 85 86 87 88 89 90 91
92 93 94 95 96 97 98 99 100
```

</details>