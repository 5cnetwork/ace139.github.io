---
title: "Installation guide for PyCharm in Linux"
layout: post
date: 2016-10-15 10:10
tag:
- pycharm
- installation
- python
- ide
blog: true
---

# Installing JetBrains PyCharm IDE in Linux

**PyCharm** has been controversially the best IDE available for Python and it's frameworks. It's competitor **Microsoft Visual Studio** is also very good but it comes with a whole lot of features irrelevant to Python and hence resource hungry. PyCharm is on the hand comparatively less resource hungry and Python oriented. PyCharm also allows to acquire [free license](https://www.jetbrains.com/student/) for Students.

### Download

Now, for downloading the software please visit this [Download Link](https://www.jetbrains.com/pycharm/download/#section=linux)


**System requirements**:

    * 512 MB RAM minimum, 1 GB RAM recommended

    * 1024x768 minimum screen resolution

    * Python 2.4 or higher, Jython, PyPy or IronPython

### Instructions

After downloading, you will be getting a **.tar.gz** file. Extract it. Then follow the instructions below in the bash shell/ terminal.

{% highlight bash %}
$ mv path/to/extracted_folder /opt/pycharm
$ bash /opt/pycharm/bin/pycharm.sh
{% endhighlight %}

**Note: You may need to be root for executing the comands above, depending on your privileges.**

Keep Coding, Godspeed!