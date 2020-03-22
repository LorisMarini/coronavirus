## What
1. Data from Italy and Australia and visualise positive cases of COVID19 over time.
2. Fit a sigmoid model to the cumulative positive count
3. The effect of new data on the model predictions
4. The growth rate of the virus
5. A plot to identify the inflection point (growth rate=1)

## Datasets
- [Protezione Civile](https://github.com/pcm-dpc/COVID-19)
- [WHO](https://github.com/CSSEGISandData/COVID-19)

## Results
Restrictions came in place on January 15th an had a positive impact on the growth rate.

![Growth rate - Italy](./covid19-italy-growth-rate.png)

Time series model based on a "S" curve:
![Sigmod model - Italy ](./covid19-italy-positives-forecast.png)

There are not enough ICU units, and testing has gradually been restricted to patients with more severe symptoms.
![Sigmod model - Italy ](./covid19-italy-rates.png)