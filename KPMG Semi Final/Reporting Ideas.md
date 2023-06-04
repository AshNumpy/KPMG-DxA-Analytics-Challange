### About Performed Things
I'll examined the datasets and visualized the time series. Also I've saved the images on `./Images/..` directory.
Also I've examined the correlation between the variables and I've saved that image on the same directory.

I saw the datas seems like have seasonal time series data but first I'd try to do regression analysis. As you know there are many hypothesis that we have to test it before the regression.

I tested to normality hypothesis:

$H_0:$ There is no difference between datasets distribution and normal distribution.

Result of the hypothesis is $H_0$ rejected. Thats why I couldn't try the regression analysis. Because normality hypothesis is one of the suppositions of the regression. 

After that, I tried ARIMA models. I knew ARIMA models not good at long-term time series but I just tried it. And I got really terrible feedbacks. 
Also I tried oto-ARIMA models but results were same.

### Personal Ideas
If I had long time I would like to try ``fbprophet``. Because I tried ``fbprophet`` in my past and I'd got really good success rates.

Also I was thinking to try Vanilla and Stacked LSTM deep neural networks, but I'couldn't do it. 