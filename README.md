This is an attempt to program in the tools for Pattern Discovery.

There are two major parts in this .Rmd file. The first one generates a small (80 transactions) database	from a restricted list of possible items. Then it mines for associations.

The second part is an attempt to implement the Pattern Fusion algorithm for finding a colossal frequent pattern in a dataset. First it generates two colossal patterns, then it makes them frequent in a database. All other transactions are random (and therefore probably not frequent). Apriori is used to find frequent two and three itemsets. A random subset of them are examined for possibly combining in the next step. 

The second part is not finished. There are still issues with combining two and three itemsets without resulting in NAs. The loops can be optimized for clarity as well as speed.  
