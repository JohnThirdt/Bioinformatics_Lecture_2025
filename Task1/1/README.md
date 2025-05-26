# Task 1.2

PubMed allows to save only first 10,000 results. To solve these problem, I divided results from 15 Dec to 20 Dec
into 4 intervals (to get less than 10,000 in any interval: 15-15, 16-18, 19-19, 20-20).

- Made requests in PubMed, reference request: ```("2022/12/DAY_START"[Date - Publication] : "2022/12/DAY_END"[Date - Publication])```

- Used button ```Save``` $\rightarrow$ ```All Results + Summary(Text)``` $\rightarrow$```Create File```

- Used command line to concatenate  all files in one named Results 

	```ivan@ivan-laptop:~/Bio_Inf/Lecture$ cat pub* >> results.txt```
