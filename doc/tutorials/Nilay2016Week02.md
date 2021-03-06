@brief We need to go deeper, Googlenet - Week 2
@author Nilay Jain
@page Nilay2016WeekTwo We need to go deeper, Googlenet - Week 2
@date 2016-06-06 8:00:00

@section Nilay2016WeekTwo We need to go deeper, Googlenet - Week 2

This week was more about applying the things I learnt in the first week. It was also a week where I spent most hours debugging. I have completed the code on feature extraction and opened a pull request. Hopefully not a lot of edits will be required as I spent time on using effective ways. I also manually tested the code to some extent to try to ensure that it is correct. Because the number of features is large, I had to think a lot on how to avoid complex reshape operations on the regular and self similarity features. I think these issues can still be reviewed and will surely come up when pull request is evaluated.

After all the work done in the first 2 weeks, I can say confidently that I know now why we're doing what we're doing for the feature extraction part. This process started out as me being slightly confused as to what exactly needs to be done. It became all clear function by function. I have also started up reading on decision stumps as we will reuse these in training the random forest, which is my next assignment. The task for this week, includes reading up on decision stump and hoeffedding trees and train a structured random forest to detect edges in the image. This will be the cornerstone for the edge boxes algorithm.