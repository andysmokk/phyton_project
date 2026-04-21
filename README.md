# A|B test analysis for statistical significance of key metrics

Calculation of statistical significance for A|B test results across four key metrics, segmented by device, channel, and overall.

1. ```add_payment_info / session```
2. ```add_shipping_info / session```
3. ```begin_checkout / session```
4. ```new_accounts / session```

To analyze statistical significance, a proportions ```z-test``` is used, which calculates the ```p-value``` and ```z-statistic```, enabling validation or rejection of the statistical significance of the results.

The analysis includes [Tableau visualizations](https://public.tableau.com/app/profile/andrii.konovalov/viz/ABTest_17763507741560/Significance), significance calculations, and data files.
