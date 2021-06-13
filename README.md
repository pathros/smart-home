# Smart Home

Final project for the [Building AI][1] course.


## Summary

Deploy a domotics system to automatically and/or remotely control water supply, windows opening and closing, turning on/off the lights, garden watering, and more.


The scope comprises development and deployment on a VPS server.


## Background



Home maintenance is hard and expensive, not only in terms of money, but in time.


A domotics system with the use of AI techniques can help both in maintenance and resources efficiency optimization. 


Suppose we have a quite big house with a garden, a dog, garage, some trees. 


The problems to take into account to optimize the home maintenance are:

* Weather conditions
* Defined raining season
* Garbage collection
* Water supply
* Sporadic electricity cut off
* Dog feeding
* Gas cut off
* Windows opening and closing
* Floor cleaning


### Personal motivation

It's very expensive for me to spend lots of time in home maintenance. Finding the right person to do this daily home maintenance job has been almost an impossible task.



### Weather conditions

Weather conditions usually consist of strong winds.


### Defined raining season


### Garbage collection


### Water supply


### Sporadic electricity cut off

No break batteries only last about three hours. If the cut off has already taken at least 20 minutes, the system should send a report with all the required details to the Electricity Company.


As for maintenance, with the use of 
in optimizing water and electricity use.




This is how you make a list, if you need one:
* problem 1
* problem 2
* etc.


## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration
* References
  * [What is domotics?](http://www.easydom.com/en/discover/what-is-domotics)
  * [Dillinger: online markdown](https://dillinger.io/)
  * [Source forge markdown syntax](https://sourceforge.net/nf/markdown_syntax)
  * [Markdown create links with target blank](https://stackoverflow.com/a/43710183/1883256)
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc



[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [1]: https://buildingai.elementsofai.com/?target=_blank "Building AI course by the Helsingin Yliopisto & Reaktor"
