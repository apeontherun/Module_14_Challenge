# Module_14_Challenge - Evaluation Report
Module 14 Challenge for RICE FinTech Assignment

## Conclusion

![Challenge_14_Strategy_Returns](https://github.com/apeontherun/Module_14_Challenge/assets/28538519/6e230ae5-edae-4ad6-8910-564e81104129)





## Tuning the Baseline Trading Algorithm

### What impact from increase or decreasing the training window?

As the training windows were increased it seem to have a better result where the strategic returns and actual returns where almost identical.

![Challenge_14_Strategy_Returns v Actual Returns 6mths](https://github.com/apeontherun/Module_14_Challenge/assets/28538519/1ffeb07c-2672-4bcf-97a9-92368b5691aa)

![Challenge_14_Strategy_Returns v Actual Returns 12mths](https://github.com/apeontherun/Module_14_Challenge/assets/28538519/8dc81a7e-6ffd-4a14-b96c-59d1c6e43295)


### What impact from increasing or decreasing both of the SMA windows?

As SMA windows were increased it seemed to have a better results where the strategic returns and actual returns where almost identical.

![Challenge_14_Strategy_Returns v Actual Returns SlowSMA200](https://github.com/apeontherun/Module_14_Challenge/assets/28538519/589ceee3-2e24-4bcc-83dc-e9f582438217)

![Challenge_14_Strategy_Returns v Actual Returns FastSMA50 SlowSMA800](https://github.com/apeontherun/Module_14_Challenge/assets/28538519/b1d91721-5c52-4b82-8c46-dcf5e35e73ec)

## Summary Evaluation

Overall the models proved to have desired results, where the new model had major drop at the end the selected period.  But through adjustments of the SMA and trading window could improve the overal performance.

### Did the new model perform better or worse than the provided baseline model?

Based on the results the new logisticregression model performed in a similar massion when the came to precision test. However, the recall test was better for -1.0 and worse for 1.0.  The overall the strategic returns performed initial than the baseline model until the end of selected timeframe, then the strategic returns dropped significantly. Models seemed to have similar outcomes with baseline having a period of time where the actual returns and strategic returns where very similar.  

### Did this new model perform better or worse than the your tuned trading algorithm?

The new model performed worse than teh tuned trading algorithm.  The best tuned trading algorithm the actual and strategic returns where identical.  

### SVM Model
![Challenge_14_Strategy_Returns v Actual Returns 1](https://github.com/apeontherun/Module_14_Challenge/assets/28538519/f7d5bdaa-84b1-4fd0-a68a-b91991cabbb9)

### LogisticRegression Model
![Challenge_14_Strategy_Returns v Actual Returns 2](https://github.com/apeontherun/Module_14_Challenge/assets/28538519/ce72405f-8e09-4d9b-be14-2d68a76a587e)
