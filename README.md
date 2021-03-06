# Detailed Time Series Analysis Using Python (SARIMAX Model)

There is a thing known as **Laplace’s demon**. It is a notion of determinism that postulates that if someone (the demon) knows the precise location and momentum of every atom in the universe, their past and future values for any given time are entailed; they can be calculated from the laws of classical mechanics.
Indeed the future can be elusive, and we now know more than Laplace that there is a thing, an angel perhaps, called quantum mechanics that strongly opposes strong determinism. Mathematicians and physicists however have their techniques to approximate the future—aka forecast it. One very powerful tool for doing this is known as time series modeling. It has found applications from weather forecast to yield projection, stock market and budgetary analysis. 
In this script, we explore this technique and how to implement the model using python. 

### What is time series modeling?

First, Wikipedia defines time series as a sequence taken at successive equally spaced points in time—a series of data points indexed (or listed or graphed) in time order. Thus it is a sequence of discrete-time data. Examples of time series are heights of ocean tides, counts of sunspots, and the daily closing value of the Dow Jones Industrial Average. Time series modeling involves the extrapolation of future events from current and past ones, by leveraging the tracked record of a variable over equally spaced time periods.

In this script we have used FRED’s unemployment dataset for our analysis. The unemployment pattern is also predicted at the end.

![alt text](https://github.com/ACMoriarty/Detailed-Time-Series-Model-Using-Python-SARIMAX-/blob/master/unRate_chart.PNG)

***So what direction do you infer unemployment numbers would take in the U.S in the coming year? Did you notice the spike in 2020 and why?***
