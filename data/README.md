The datasets were generated from R as follows:

```r
install.packages(c("readr", "CDM"))
library(CDM)
Q <- data.fraction1$q.matrix
y <- data.fraction1$data
readr::write_csv(as.data.frame(Q), "item_skill_Q.csv")
readr::write_csv(y, "responses.csv")
```

and edited with the following Shell commands:

```sh
sed -i 's/T/I/g' responses.csv
```
