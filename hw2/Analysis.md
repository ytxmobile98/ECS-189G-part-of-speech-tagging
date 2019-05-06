# ECS 189G Part of speech tagging

## Task 1

In this task, the file I used to train ([ptb.22.txt](./ptb.22.txt)) contains 1700 lines. Hence I chose breakpoints to be 50, 100, 200, 500, 1000, 1500, 1700. I stored the results in [task1-results.txt](./task1-results.txt). The plot of errors vs. training size is seen as follows:

![](./task1.svg)

The results are not very surprising. The assumption is that the larger the corpus is used for training, the less percent error will be occuring; it is verified by the plot.

Moreover, for percent error by words (the blue line), as the data set gets bigger, the errors decline more and more slowly, so this means that at certain size of training corpus, the benefits of trying larger training sizes would be negligible. But for percent error by sentences (the orange line), the rate of decrease is much slower than that by words.
