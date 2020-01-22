# Period-Dissolution-Index
Solution for time periods and intevals in ordered domain indexing that enables logarithmic point-lookup search effieciency.

Periods/intevals are dissloved into binomial breakdown parts; these are used for standard B+ tree index.

In this version, domain values are supposed to be converted into numbers, which are further converted into binary code. Instead, conversion into binary preserving domain order can be applied.

All snippets of binary in between start and end point minimal in length are associated with the period/interval.These serve for the period/interval index.

Point-lookup query algorithm of logarithmic efficiency is proposed.
