# STEP 1

Benchmark instances for the job-shop scheduling problem (minimizing makespan).

## Meta-data

The file `instances.json` has meta-data of each instance as follows.

```
{
  "name" : "instance", // the name of the instance [required]
  "jobs" : n,          // the number of jobs [required]
  "machines" : m,      // the number of machines [required]
  "optimum" : c,       // the optimum makespan or null [required]
  "bounds" : {         // required when the optimum is null
    "upper" : ub,      // the upper-bounds of makespan
    "lower" : lb,      // the lower-bounds of makespan
  },
  "path" : "*****"     // the file path to the instance [required]
}
```

## Includes

- Five instances donated as ABZ5-9 due to Adams et al. [1].
- Three instances donated as FT06, FT10 and FT20 due to Fisher and Thompson [2].
- Forty instances donated as LA01-40 due to Lawrence [3].
- Ten instances donated as ORB01-10 due to Applegate and Cook [4].
- Twenty instances donated as SWV01-20 due to Storer et al. [5].
- Four instances donated as yn1-4 due to Yamada and Nakano [6].
- Eighty instances donated as ta01-80 due to Taillard [7].

## References

1. https://github.com/tamy0612/JSPLIB.

# STEP 2

This part includes Genetic Algorithm approach towards solving jobshop problem.
They are found in the Step 3 folder. Instances can be found here : https://github.com/tamy0612/JSPLIB/tree/
