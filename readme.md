# Conclusions

## Baseline performance

The performace of the Baseline algorhythm is that it is slightly higher than the actual returns over time.

### Baseline returns

![Baseline returns](https://github.com/blackrainz/simpletrade/blob/main/Resources/returnsBase.png "Baseline returns")

## 7 Month training dataset performance

The performance of the 7 month training dataset gave better results than the base dataset.

### 7 Month training dataset returns

![7 Month training dataset returns](https://github.com/blackrainz/simpletrade/blob/main/Resources/returns7mo.png "7 Month training dataset returns")

## Adjusted SMA performance

With a short SMA window of 5 and long window of 86 the results were better than actual returns but not as good as the baseline strategy.

### Adjusted SMA returns

![Adjusted SMA short 5 long 86 returns](https://github.com/blackrainz/simpletrade/blob/main/Resources/returnss5l86.png "SMA adjusted 5 short and 86 long returns")

## Adjusted timeframe and SMA performance

Adjusting the timeframe to a window of 5 short and 137 long, the results were significantly better than the baseline.

### Adjusted timeframe and SMA returns

![Adjusted SMA and timeframe returns](https://github.com/blackrainz/simpletrade/blob/main/Resources/returns7mons5l137.png "Adjusted SMA and timeframe returns")

## Logistics regression performance

Using the classifier LogisticsRegression, I found that the results were slightly unreliable at times with the baseline and it would require quite a bit of changing numbers to be effective.

### Logistic regression returns

![Logistics regression returns](https://github.com/blackrainz/simpletrade/blob/main/Resources/LogisticsRegression.png "Logistics regression returns")


# Summary

My overall conclusion is that adjusting the SMA long and short windows along with the timeframe are necessary to find a more effective machine learning bot. I found that changing the SMA windows by just a day or two can significantly change the results of the data, which when using live data seems like it could be extremely risky.
