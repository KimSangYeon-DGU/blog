@brief Improvement of Automatic Benchmarking System - Week 11
@author Anand Soni
@page Anand2016Week11 Improvement of Automatic Benchmarking System - Week 11
@date 2014-08-03 21:55:00

@section Anand2016Week11 Improvement of Automatic Benchmarking System - Week 11

Eleventh week! More coding, more debugging, more fun!

This week I had to work on the representation of results using d3. But before starting with that, I had to finish up some pending things. What I did first was add the Simple Mean Squared Error metric to the metric definitions. The MSE originally implemented requires some probabilities and all the methods do not offer such probabilities directly! So, we needed this simple predictions based definition.

To create the representations, we decided to first store the metrics in the database. I came up with the table structure and with Marcus' help added the required functions for table creation and insertions. The next thing I did was adding the Javascript and HTML code for the generation of a grouped bar chart which can show the metric values as bars for each library in a single plot! Extremely useful!

I need to add some more visualizations now. I am still working on that part. I am tinkering over the kind of plots to draw. As always, we also had some silly errors to fix.

For the next week, as I said, more plots and visualizations!

Thank you for visiting and feel free to catch me on IRC regarding any queries about the project or even for a quick chat!