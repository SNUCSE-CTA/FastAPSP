#FastAPSP

This source code is an implementation of \[1\], a new algorithm for APSP matching.

The source code is implemented based on SOF \[2\]. (SOF is available at http://confluence.qu.edu.qa/download/attachments/9240580/Prefix.tgz)



#make:

```sh
make
```

#run:

To run a test with datasets/all_ests.plain, output type output=2, the number of threads p=1, and overlap minimum om=15 and to write the results to output_all_ests.

```sh
./FastAPSP datasets/all_ests.plain -output 2 -p 1 -om 15 > output_all_ests
```

#references:
[1] Jihyuk Lim and Kunsoo Park, Algorithm Engineering for All-Pairs Suffix-Prefix Matching, SEA 2017.

[2] M.H. Rachid and Q. Malluhi, A Practical and Scalable Tool to Find Overlaps betweeen Sequences, BioMed Res. Int. 2015, 1-12, 2015
[3] Jihyuk Lim and Kunsoo Park, A Fast Algorithm for the All-Pairs Suffix-Prefix Problem, Theoretical Computer Science, "https://doi.org/10.1016/j.tcs.2017.07.013"

