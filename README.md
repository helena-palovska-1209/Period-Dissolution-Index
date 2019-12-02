# Period-Dissolution-Index
Solution for time periods and intevals in ordered domain indexing that enables logarithmic point-lookup search effieciency.

Periods/intevals are dissloved into binomial breakdown parts. These are used for standard B+ tree index.

In this version, domain values are supposed to be converted into numbers, which will be further converted into binary code. Instead, conversion into binary preserving domain order can be used.

All snippets of binary in between start and end point minimal in length are associated with the perod/interval.These serve for the period/interval indexing.

Point-lookup query algorithm is proposed of logarithmic efficiency.
