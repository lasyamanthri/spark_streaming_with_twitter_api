# spark_streaming_with_twitter_api
Getting live data from Twitter API and conducting analysis on the same.
## Step 1
1. Create virtual box by downloading it from  - https://www.virtualbox.org/
2. Download the Ubuntu image - http://old-releases.ubuntu.com/releases/16.04.2/ (I used 16.04, you can use the latest one)
3. Start the virtual box - choose Ubuntu 64 bit and upload the image from step2.

### It requires minimum 8.6 gb memory to allocated, and in most cases - go with the default value, shouldn't be problem.

## Step 2

Get your twitter credentials from - https://developer.twitter.com/en (get the free version and start an app, and then the credentials)

## Step 3 

1. Run the Streaming.py to start the socket - it gets the data from twitter API
2. Run the SparkStreaming.ipynb to start the spark session and perform some analysis.


### Credits 
1. https://towardsdatascience.com/hands-on-big-data-streaming-apache-spark-at-scale-fd89c15fa6b0
2. https://www.udemy.com/course/spark-and-python-for-big-data-with-pyspark/
