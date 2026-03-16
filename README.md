# Winna Plinko — Independent Technical Analysis

**ProvablyFair.org**

## Summary

Between December 17, 2025 and approximately March 10, 2026, Winna.com's Plinko game used hardcoded probability tables instead of standard binomial distribution. These tables reduced the probability of landing in the highest-paying edge buckets while matching fair binomial math with extreme precision on all other buckets.

All three difficulty modes (Low, Medium, High) converged to approximately 98.00% RTP instead of the expected ~99%.

## Evidence

- **Wayback Machine Archive (January 27, 2026):** The probability tables were independently archived by the Internet Archive before any public disclosure.
  - [https://web.archive.org/web/20260127225250/https://winna.com/assets/js/-kePZzxf.chunk.js](https://web.archive.org/web/20260127225250/https://winna.com/assets/js/-kePZzxf.chunk.js)

- **190 Verified Bets (February 2026):** Real Plinko bets verified against the extracted algorithm. 190/190 matched the hardcoded probability table method. 156/190 produced different results than fair binomial math.

## Verification Tool

Players can check their own Plinko results using the tool hosted here:

**[https://provablyfair-org.github.io/winna-plinko/](https://provablyfair-org.github.io/winna-plinko/)**

Enter your client seed, unhashed server seed, and nonce range to see which bets were affected.

# Winna Plinko — Bucket-Level Probability Comparison

Fair binomial math vs Winna's hardcoded 98% RTP probability tables, extracted from the Wayback Machine archive of January 27, 2026.

Only buckets with a meaningful difference (|Δ| > 0.00000001) are shown. All other buckets matched fair binomial distribution exactly.

---

## High Risk

### High · 8 Pins — RTP 99.06% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 29x | 0.0039062500 | 0.0035373610 | -9.4% |
| 4 | 0.2x | 0.2734375000 | 0.2738063890 | +0.1% |

### High · 9 Pins — RTP 99.06% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 43x | 0.0019531250 | 0.0017049006 | -12.7% |
| 4 | 0.2x | 0.2460937500 | 0.2463419744 | +0.1% |

### High · 10 Pins — RTP 99.06% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 76x | 0.0009765625 | 0.0008364042 | -14.4% |
| 5 | 0.2x | 0.2460937500 | 0.2462339083 | +0.1% |

### High · 11 Pins — RTP 99.16% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 120x | 0.0004882812 | 0.0003914485 | -19.8% |
| 5 | 0.2x | 0.2255859375 | 0.2256827703 | +0.0% |

### High · 12 Pins — RTP 99.12% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 170x | 0.0002441406 | 0.0001784097 | -26.9% |
| 5 | 0.2x | 0.1933593750 | 0.1934251059 | +0.0% |

### High · 13 Pins — RTP 99.09% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 260x | 0.0001220703 | 0.0000802376 | -34.3% |
| 5 | 0.2x | 0.1571044922 | 0.1571463249 | +0.0% |

### High · 14 Pins — RTP 98.98% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 420x | 0.0000610352 | 0.0000377343 | -38.2% |
| 6 | 0.2x | 0.1832885742 | 0.1833118751 | +0.0% |

### High · 15 Pins — RTP 99.03% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 620x | 0.0000305176 | 0.0000139576 | -54.3% |
| 6 | 0.2x | 0.1527404785 | 0.1527570385 | +0.0% |

### High · 16 Pins — RTP 98.98% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 1000x | 0.0000152588 | 0.0000099831 | -34.6% |
| 6 | 0.2x | 0.1221923828 | 0.1222021482 | +0.0% |
| 16 | 1000x | 0.0000152588 | 0.0000107691 | -29.4% |

---

## Medium Risk

### Medium · 8 Pins — RTP 98.91% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 13x | 0.0039062500 | 0.0031870833 | -18.4% |
| 4 | 0.4x | 0.2734375000 | 0.2741566667 | +0.3% |

### Medium · 9 Pins — RTP 99.14% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 18x | 0.0019531250 | 0.0013013963 | -33.4% |
| 4 | 0.5x | 0.2460937500 | 0.2467454787 | +0.3% |

### Medium · 10 Pins — RTP 98.91% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 22x | 0.0009765625 | 0.0005570486 | -43.0% |
| 5 | 0.4x | 0.2460937500 | 0.2465132639 | +0.2% |

### Medium · 11 Pins — RTP 99.02% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 24x | 0.0004882812 | 0.0000528183 | -89.2% |
| 5 | 0.5x | 0.2255859375 | 0.2260214005 | +0.2% |

### Medium · 12 Pins — RTP 98.99% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 33x | 0.0002441406 | 0.0000098832 | -96.0% |
| 6 | 0.3x | 0.2255859375 | 0.2258884324 | +0.1% |
| 12 | 33x | 0.0002441406 | 0.0001759032 | -28.0% |

### Medium · 13 Pins — RTP 98.99% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 43x | 0.0001220703 | 0.0000099176 | -91.9% |
| 1 | 13x | 0.0015869141 | 0.0015561401 | -1.9% |
| 6 | 0.4x | 0.2094726562 | 0.2097276710 | +0.1% |
| 13 | 43x | 0.0001220703 | 0.0000099822 | -91.8% |

### Medium · 14 Pins — RTP 98.99% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 58x | 0.0000610352 | 0.0000097504 | -84.0% |
| 1 | 15x | 0.0008544922 | 0.0005829438 | -31.8% |
| 7 | 0.2x | 0.2094726562 | 0.2098466526 | +0.2% |
| 14 | 58x | 0.0000610352 | 0.0000098720 | -83.8% |

### Medium · 15 Pins — RTP 99.00% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 88x | 0.0000305176 | 0.0000098344 | -67.8% |
| 1 | 18x | 0.0004577637 | 0.0000985555 | -78.5% |
| 7 | 0.3x | 0.1963806152 | 0.1967811592 | +0.2% |
| 15 | 88x | 0.0000305176 | 0.0000098650 | -67.7% |

### Medium · 16 Pins — RTP 98.99% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 110x | 0.0000152588 | 0.0000099993 | -34.5% |
| 1 | 41x | 0.0002441406 | 0.0000299303 | -87.7% |
| 8 | 0.3x | 0.1963806152 | 0.1966054369 | +0.1% |
| 16 | 110x | 0.0000152588 | 0.0000099069 | -35.1% |

---

## Low Risk

### Low · 8 Pins — RTP 98.98% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 5.6x | 0.0039062500 | 0.0019762983 | -49.4% |
| 4 | 0.5x | 0.2734375000 | 0.2753674517 | +0.7% |

### Low · 9 Pins — RTP 98.98% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 5.6x | 0.0019531250 | 0.0000096794 | -99.5% |
| 4 | 0.7x | 0.2460937500 | 0.2481024752 | +0.8% |
| 9 | 5.6x | 0.0019531250 | 0.0018878454 | -3.3% |

### Low · 10 Pins — RTP 99.00% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 8.9x | 0.0009765625 | 0.0000096058 | -99.0% |
| 5 | 0.5x | 0.2460937500 | 0.2472887575 | +0.5% |
| 10 | 8.9x | 0.0009765625 | 0.0007485117 | -23.4% |

### Low · 11 Pins — RTP 99.00% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 8.4x | 0.0004882812 | 0.0000097792 | -98.0% |
| 1 | 3x | 0.0053710938 | 0.0042108638 | -21.6% |
| 5 | 0.7x | 0.2255859375 | 0.2277032498 | +0.9% |
| 11 | 8.4x | 0.0004882812 | 0.0000097010 | -98.0% |

### Low · 12 Pins — RTP 98.98% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 10x | 0.0002441406 | 0.0000095805 | -96.1% |
| 1 | 3x | 0.0029296875 | 0.0007943749 | -72.9% |
| 6 | 0.5x | 0.2255859375 | 0.2281902653 | +1.2% |
| 12 | 10x | 0.0002441406 | 0.0000096856 | -96.0% |

### Low · 13 Pins — RTP 99.00% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 8.1x | 0.0001220703 | 0.0000098870 | -91.9% |
| 1 | 4x | 0.0015869141 | 0.0000096514 | -99.4% |
| 6 | 0.7x | 0.2094726562 | 0.2122209395 | +1.3% |
| 12 | 4x | 0.0015869141 | 0.0006402600 | -59.7% |
| 13 | 8.1x | 0.0001220703 | 0.0000098870 | -91.9% |

### Low · 14 Pins — RTP 99.00% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 7.1x | 0.0000610352 | 0.0000096301 | -84.2% |
| 1 | 4x | 0.0008544922 | 0.0000098232 | -98.9% |
| 2 | 1.9x | 0.0055541992 | 0.0031181839 | -43.9% |
| 7 | 0.5x | 0.2094726562 | 0.2137007598 | +2.0% |
| 13 | 4x | 0.0008544922 | 0.0000098831 | -98.8% |
| 14 | 7.1x | 0.0000610352 | 0.0000096301 | -84.2% |

### Low · 15 Pins — RTP 99.00% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 15x | 0.0000305176 | 0.0000098735 | -67.6% |
| 1 | 8x | 0.0004577637 | 0.0000098868 | -97.8% |
| 2 | 3x | 0.0032043457 | 0.0019530623 | -39.0% |
| 7 | 0.7x | 0.1963806152 | 0.1985689644 | +1.1% |
| 14 | 8x | 0.0004577637 | 0.0000098630 | -97.8% |
| 15 | 15x | 0.0000305176 | 0.0000098735 | -67.6% |

### Low · 16 Pins — RTP 99.00% → 98.00%

| Bucket | Multiplier | Fair Probability | Hardcoded Probability | Change |
|-------:|-----------:|-----------------:|----------------------:|-------:|
| 0 | 16x | 0.0000152588 | 0.0000096168 | -37.0% |
| 1 | 9x | 0.0002441406 | 0.0000097470 | -96.0% |
| 2 | 2x | 0.0018310547 | 0.0000095379 | -99.5% |
| 3 | 1.4x | 0.0085449219 | 0.0081408415 | -4.7% |
| 8 | 0.5x | 0.1963806152 | 0.2009074574 | +2.3% |
| 14 | 2x | 0.0018310547 | 0.0000097213 | -99.5% |
| 15 | 9x | 0.0002441406 | 0.0000099066 | -95.9% |
| 16 | 16x | 0.0000152588 | 0.0000096168 | -37.0% |


## Methodology

The tool implements two algorithms and compares their outputs for each nonce:

1. **Winna's algorithm (Dec 17 – Mar 2026):** Generates a single float via `HMAC-SHA256(serverSeed, clientSeed:nonce:cursor)` and maps it against hardcoded probability tables archived by the Wayback Machine on January 27, 2026.

2. **Fair binomial algorithm:** Generates one float per pin row using the same HMAC byte generator, counts how many are ≥ 0.5. This produces the standard binomial distribution used by fair Plinko implementations.

## Repository Contents

- `index.html` — Interactive verification tool
- `data/` — Verified bet data from February 2026
- `README.md` — This file

## Links

- [ProvablyFair.org](https://provablyfair.org)
- [X Thread](https://x.com/provablyfairorg)
- [Winna Incident Report (March 10, 2026)](https://winna.com)

## License

This analysis is published for public interest and player protection. The verification tool is open source.
