# Explain:
So, we have to predict the DissolvedOxygen. To do so, we have to take 2 day slots and predict the goal for next 6 hours. we have 2 sites (A and B) and each site has number of devices (site A: device1 and device2, site B: device 3, device 4, device 5)

Each device has its own correlation pattern with DissolvedOxygen. So, we can devide the data to different devices and foreach decive compute the goal.

Also, we observed that there are missing data (sometimes NAN value and sometimes missing hourly data for some devices). We saw that days 23 and 24 have complete data for each devices and we can use these two days.

We will use Several models to predict the goal. The RMSE score is then demonstrated to evalute each model.
