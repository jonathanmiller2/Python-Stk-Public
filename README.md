# Python-Stk-Public
A collection of models to do quantitative analysis on the stock market. The main model featured in this package is an ensemble composed of a DNN and a Random Forest. I found that the combination of these two models was enough to extract all meaningful statistical trends in stock prices. Any additional models have far too little added returns to justify the computational cost. 

The main technical analysis model of this package requires further testing using software like Zipline by Quantopian (a package with an issues I'm still waiting on). However, to my untrained eye it seems that any model that operates simply on stock price histories will only result in mediocre Sharpe ratios. Theoretically, you could put infinite effort into developing models that mine this data, and you would come out with an extremely valuable model with a mind-blowing Sharpe ratio. However, this is what quantitative traders do all day, and anyone reading this would be hard pressed to outrun hundreds of Statistics Ph.D's staring at the same problem as their day job. Therefore, I choose to believe that when it comes to technical analysis of simply stock price, the efficient-market hypothesis rings true, and all possible alpha is being mined the microsecond it appears. However, that doesn't make this model useless. Sharpe's ratio is extremely helpful when it comes to maximizing gains of a strategy while accounting for risk, but that doesn't mean we HAVE to optimize a Sharpe ratio. Data scientists can optimize whatever they like! This is exactly why I didn't trash this model as soon as I decided to move on to fundamental analysis. It's my theory that a vast majority of the ML algo traders out there are optimizing according to the metrics and analyses put out by hedge fund managers and wall street billionaires. Those metrics are extremely useful on the professional level, but the trade patterns of an everyday trader require a strategy to be optimized to a much different set of criteria. For example, say I need to optimize my positions around the fact that I need $1,500 for next month's bills. Sharpe's ratio isn't going to help me optimize this situation. This is where simple machine learning algorithms like the one above become useful. In the future, I'll be using this model to optimize positions around my personal constraints, taking in considerations from the outputs of my other models. Eventually, I'd like to have a big web of machine learning models, taking in data from hundreds of sources, doing a custom analysis on each source, and providing the result to be processed in a glorius, massive ensemble. That's going to take some doing though.

This project uses Keras as an interface for Tensorflow-GPU. The models are trained and tested on my PC's GPU.
All packages are installed using Anaconda and the Conda package manager.

Currently I'm working on another ensemble for options analysis, as well as a transformer to do sentiment analysis on company descriptions.

---

### **To potential employers:**
This project is one of my most cutting-edge projects, and I believe it demonstrates how up-to-date I am in computer science circles. Everything you see here is state-of-the-art.

Additionally, if you're looking for basic python skills, these are the skills you will find here:
1. Data retrieval/handling
2. Data structures (Numpy/Pandas)
3. Modular programming
4. Scalable applications
5. Code structuring
6. List comprehensions
7. Data visualization
