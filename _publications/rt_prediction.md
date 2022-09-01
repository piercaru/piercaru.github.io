---
title: "Early prediction of SARS-CoV-2 reproductive number from environmental, atmospheric and mobility data: A supervised machine learning approach"
collection: publications
permalink: /publication/rt_prediction
excerpt: 'Introduction: SARS-CoV-2 was declared a pandemic by the WHO on March 11th, 2020. Public protective measures were enforced in every country to limit the diffusion of SARS-CoV-2. Its transmission, mainly by droplets, has been measured by the effective reproduction number (Rt) that counts the number of secondary cases caused in a population by an average infectious individual at time t. Current strategies to calculate Rt reflect the number of secondary cases after several days, due to a delay from symptoms onset to reporting. We propose a complementary Rt estimation using supervised machine learning techniques to predict short term variations with more timely results.

Material and methods: Our primary goal was to predict Rt of the current day in the twelve provinces of Lombardy with the highest possible accuracy, and with no influence of the local testing strategies. We gathered data about mobility, weather, and pollution from different public sources as a proxy of human behavior and public health measures. We built four supervised machine learning algorithms with different strategies: the outcome variable was the daily median Rt values per province obtained from officially adopted algorithms.

Results: Data from 243 days for every province were presented to our four models (from February 15th, 2020, to October 14th, 2020). Two models using differential calculation of Rt instead of the raw values showed the highest mean coefficient of determination (0.93 for both) and residuals reported the lowest mean error (-0.03 and 0.01) and standard deviation (0.13 for both) as well. The one with access to the value of Rt of the day before heavily relied on that feature for prediction, while the other one had more distributed weights.

Discussion: The model that had not access to the Rt value of the previous day and used Rt differential value as outcome (FDRt) was considered the most robust according to the metrics. Its forecasts were able to predict the trend that Rt values would have developed over different weeks, but it was not particularly accurate in predicting the precise value of Rt. A correlation among mobility, atmospheric, features, pollution and Rt values is plausible, but further testing should be performed.

[Please find the paper here](https://doi.org/10.1016/j.ijmedinf.2022.104755)'
date: 2022-04-01
venue: 'Int J Med Inform'
paperurl: 'https://doi.org/10.1016/j.ijmedinf.2022.104755'
citation: 'Caruso PF, Angelotti G, Greco M, et al. Early prediction of SARS-CoV-2 reproductive number from environmental, atmospheric and mobility data: A supervised machine learning approach [published online ahead of print, 2022 Apr 1].<i> Int J Med Inform. </i> 2022;162:104755. doi:10.1016/j.ijmedinf.2022.104755'
---


Recommended citation: Caruso PF, Angelotti G, Greco M, et al. Early prediction of SARS-CoV-2 reproductive number from environmental, atmospheric and mobility data: A supervised machine learning approach [published online ahead of print, 2022 Apr 1].<i> Int J Med Inform. </i> 2022;162:104755. doi:10.1016/j.ijmedinf.2022.104755