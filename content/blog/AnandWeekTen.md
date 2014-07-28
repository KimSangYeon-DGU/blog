Title: Improvement of Automatic Benchmarking System : Week-10 Highlights
Date: 2014-07-28 12:25:00
Tags: gsoc
Author: Anand Soni

Tenth week! Yes, this week was more work and more fun.  

I did Bootstrapping framework last week and this week we decided to work on some of the new methods that have been added to mlpack during this year's GSoC.

So, I started working on integrating the metrics with two new methods : Perceptron and Decsion Stump. Then I also added metrics to three other libraries which already had an implementation of Perceptron :

  * Scikit
  * Shogun
  * Matlab

The integration is complete now. Then we also had some egregious errors in the implementation of metrics definitions. It turned out that I had missed some of the crucial limiting cases there! I have got them right and working now! 

For the next week, I am planning to start working on the representation of the results. I had a plan to use d3 for this. Mostly I will stick to that! 

Thank you for visiting and feel free to catch me on IRC regarding any queries about the project or even for a quick chat!
