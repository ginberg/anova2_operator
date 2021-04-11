# ANOVA 2-way operator

##### Description

The `anova2` operator performs a 2-way analysis of variance of the data.

##### Usage

Input projection|.
---|---
`color` | represents the groups to compare
`y-axis`| measurement value

Output relations|.
---|---
`pr`| numeric, p-value calculated per cell

##### Details

`anova2` operator performs an analysis of variance of the data. The operator is based on the [anova R function](https://www.rdocumentation.org/packages/stats/versions/3.6.2/topics/anova).

##### References

See [Analysis of variance on Wikipedia](https://en.wikipedia.org/wiki/Analysis_of_variance).
See [Two way anova in R](http://www.sthda.com/english/wiki/two-way-anova-test-in-r)

##### See Also

[ttest](https://github.com/tercen/ttest_operator), [rfImp](https://github.com/tercen/rfImp_operator)