---
title: "Getting started with Data Science"
layout: post
date: 2016-07-10 10:10
tag:
- data-science
- getting started
- python
blog: true
star: true
---

## Choosing Python for Data Science and Machine Learning

Well there are several languages and frameworks for Data Science and Machine Learning which sometimes makes choices difficult for us. The matter of fact is sometimes we need to make switch to other frameworks too for some particular job, reason might be for improved efficiency of the language or some special feature which will enable us to get our job done with ease.

Some popular languages/frameworks competing with **Python** are, **R**, **Matlab/Octave**, **Julia**, **Mathematica/Sage**

Instead of all this, we must have a primary language which we are comfortable and accustomed with, so why not Python? Python is versatile and easy to implement. The community of Python is huge and booming every second. The popularity of it results in a high development rate and quick addition of new feature and improvements. The number of Data Analytics packages we get in Python is massive. Generally for day to day task we would never have to write any package ourselves. But if we do come in a situation to write one, we can do it with ease in Python. It gives us such a level of flexibility. Python is one of the most well documented language present and the community has always been overwhelming. When we get stuck, we are very much likely to get help from the detailed documentations or community. The handling of data and it's manipulation is very easy in Python, though it needs major improvements in handling large data sets. Don't get de-motivated by it, as when I am referring to large, it really means very large, such datasets are not likely to be encountered in day to day life.

So till now, you must have got a fair idea that I have chosen Python as my primary language for Data Science and Machine Learning. Why wouldn't I? **Python is awesome!**. From my personal experience till now, it is surely one of the top choices in Programming Languages one have for the purpose, may it be a beginner or a professional. 

On this note I would also like to share my personal experience. If we give more importance to the programming language we love in comparison to the task we need to perform, we are most likely to decrease our efficiency. It happens on times when there is a more efficient way of performing the task using some other language but we tend to take the hard way and try to implement it with the language of our choice. I am not saying that it is a bad thing. It surely does increase the depth of our knowledge, but it is of no help in doing the job in hand, which is surely more important. It doesn't mean that we should not implement stuffs using language of our choice. If we don't, it will cease development. It's not that confusing what it sounds like. We just need to understand the priority. When there is a job in hand we need to perform, we should take the most efficient way. But when we are not under such constraints, we try to implement the task using the language of our choice and try to make it more efficient, which will lead to development of the language. By this procedure only new packages and modules come up. 

---

## Let's get started with setting up our environment

Now we would require Python to start with and the data analytics and machine learning packages along with it. Now there are three ways of getting that. Before we look into the ways, We should decide which version of Python we need to choose. There are majorly two versions **Python2.x** and **Python3.x**. To tell the truth there is an unending debate in the community. I am not getting into it at all, if you like you can read about it and decide yourself. My personal preference is **Python3.x** because its the future.

> If we try to hold on to the legacy long enough, we cease to make progress. Change is the ultimate truth, we need to accept it and evolve.

Python is pre-installed in the latest Linux/Unix based distribution. If it is not we need to get it. For Windows OS we need to install it. Simply go to the [official website](https://www.python.org) and get the latest Python. 

Coming to the procedures, there are three :

* Download the source from the official website of each packages and build it. (Trust me, being a Data Analyst, it should be our last resort)

* Now comes a bit more simpler way, using the python-pip package manager and installing each package by doing

	{% highlight bash %}
	$ pip install <package_name>
	{% endhighlight %}


* Now comes the most convenient way of doing it. Using the [Anaconda Distribution](https://www.continuum.io/downloads) from Continuum Analytics. Installation is just a cakewalk and best thing being it's not environment dependent, we can use Linux Based system or MacOS and even Windows, it takes care of it all. It also comes up with Python in it. Using it we would be able to set our own Python ecosystem. It comes with more than 300 popular python packages for Data Analysis and Machine Learning ready to be used. We need not have to worry about finding the packages and installing it manually. It comes with its own package manager and dependency resolver. We can install a new package and it would take care of all its dependency. We can also update all the packages in our system at once by a single command. Its really easy to use and more importantly it takes off the burden of setting up the environment and managing it, so that we could focus on our real deal, i.e. Data Analysis and Machine Learning implementations.

---

Please feel free to differ, suggest modifications or argue on the post. I will be more than happy to do that.

Share if you found the post useful.

Until next time. Keep Learning and Sharing.