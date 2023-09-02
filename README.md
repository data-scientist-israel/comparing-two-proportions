TWO PROPORTION TEST
Israel Valencia-Esquivel, 
https://github.com/data-scientist-israel , 
https://www.fiverr.com/israel_analyst_?public_mode=true

Hello, I am presenting the document where you will find the z-test to calculate the difference between two proportions. The proportion in this case is that the nominator is the number of units sold of variant A and the denominator is the number of impressions of variant A, that is, the number of units sold over the number of impressions.

First you will find the "Data" table where you have to modify the data of the number of impressions, amount of sales and unit price, the rest of the parameters are calculated by itself. Please try to make the "products" column have integer numbers, the algorithm can work with decimal numbers too, but it is not correct with this test.

The second section "Results" gives you the value of "Pooled sample proportion" used to calculate the z-statistic of the test, in addition, the formula to calculate it is noted. Later there is the z-statistic that you must report, in addition, the formula to calculate it is noted. Next, there are the p-values that indicate the probability of rejecting the null hypothesis being true, that is, the probability of committing a type I error. The first p-value indicates whether both proportions are different, a two-tailed p-value. The second p-value indicates whether one proportion is significantly higher than the other, a one-tailed p-value. The test is significant if the p-value is less than 0.05, if it is, the cell will be filled green, otherwise it will be blank. 
The third section "Results Notes" indicates the meaning of the letters in the formulas in the Results section. It also indicates the difference between the two p-values.

The fourth section "How to report the results?" indicates how to use the z-value and p-value to report (i) the significant difference between the proportions of both variants, (ii) when the proportion of variant A is greater than that of variant B, and (iii) when there is no significant difference between the proportions of both variants.
The fifth section is the figure of the proportions of both variants.

The second tab of the document contains the R script to calculate the difference between two proportions using the z-test. I indicate the way to calculate the test to know the difference between proportions, two-tailed, or to know if the first variant has a greater proportion than the second, one-tailed. I also write what each line of the results that could come out means.

