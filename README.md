Nectar Profile Challenge
========================

You have 2 data sets - one data set is collected from the a bottle profiler (`profile.csv`) and another one is collected from the testing machine (`raw.csv`).

We need to compute the accuracy of the raw values coming from the hardware in testing compared to the profile data. We consider measurements as one of three categories: `Acceptable`, `Low Confidence`, `Unacceptable`.

- `Acceptable`: < Actual measurement +/- variance mean
- `Low Confidence`: > Actual measurement +/- variance mean
- `Unacceptable`: > Actual measurement +/- (variance mean + variance standard deviation)

![Screenshot](/screenshots/sample_1.png?raw=true "Sample Graph Screenshot")

## Exercise
In order to verify the accuracy of the raw measurements compute the following:

- the variance values from a raw measurement compared to profile value
- the mean of all variances
- the standard deviation of all variances
- the total number of missed measurements
- the number of measurements that are `Acceptable`, `Low Confidence`, `Unacceptable`

Once you have computed all the values, output the results to a file. For bonus points you can generate the graph from your results. Feel free to write scripts in language of your choice to compute the numbers. Include instructions with your solution on how to run and setup the script.

Good Luck!
Don't hesitate to contact us if you have any questions.
