# Period-Dissolution-Index
Time periods or intevals in ordered domain index that enables logarithmic point-lookup search effieciency.

Periods/intevals of ordered domain are disslovel into binomial breakdown parts. These are used for standard B+ tree index.

In this version, domain values are supposed to be converted into numbers, which will be further converted into binary code. Instead, conversion into binary preserving domain order can be used.

All snippets of binary in between start and end point minimal in length are associated with the perod/interval.These serve for the period/interval indexing.

Point-lookup query algorithm is proposed of logarithmis efficiency.
