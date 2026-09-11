
# Robbery Crime Analysis (2016–2021)

## Summary

From the local crime data (71 records across 2014–2021), there were **6 robbery records** total out of 11 crime types. Of these, **5 robbery records occur between 2016 and 2021**.

| Date Reported | Location | Suspect Age |
|---|---|---|
| 2016-11-09 | Bank | 35 |
| 2017-12-15 | Convenience Store | 25 |
| 2019-05-14 | Bank | 37 |
| 2020-06-14 | Convenience Store | 27 |
| 2021-02-14 | Bank | 39 |

**Average age of robbery suspects (2016–2021): 32.6 years**

**Most frequent location:** **Bank** (3 times), followed by Convenience Store (2 times).

---

### Methodology

- Filtered by `Crime_Type == 'Robbery'` and `Date_Reported` between 2016 and 2021 inclusive.
- Computed average age as the arithmetic mean of suspect ages.
- Determined the most frequent location using simple frequency counting.
