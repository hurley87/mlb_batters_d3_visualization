# MLB Data Visualization
Are left handed hitters better then right handed hitters?

## Summary 
*In no more than 4 sentences, briefly introduce your data visualization and add any context that can help readers understand it.*

I used the MLB data to vizualize 1,157 MLB baseball players and their batting average, homerun count, and whether they were right handed, left handed or hit both ways. After doing some research I discovered an article that suggested left handed hitter were typically better then right handed hitters so I wantd to see if that was true or not. 


##Design 
*Explain any design choices you made including changes to the visualization after collecting feedback.*

index_first.html: My goal here was to show that left handed batters are better hitters then right handed batters. I decided to use a scatter plot with homeruns on the y-axis and their batting average on the x-axis. To keep things simple I excluded players who hit both ways and used color to differentiate right handed hitters(green) and left handed hitters(blue). That information would be available in a legend. My thinking here was that one color would appear more prodominent, have higher x and y values, and I could say one type of hitter had a higher average and more homeruns. This wasn't the case as the graph ended up being just a bunch of dots with no clear advantage to either type of hitter. 

index_second.html: Based on feedback I wanted to take the first visualization and show the overall homerun and batting average for each type of hitter. I found the homerun and batting average of each and creating a cooresponding line on the graph. It would be clear then that the type of hitter with a line further right down the x-axis would have a higher average and the higher horizontal line would indicate a higher homerun average. To see these results a user could simply hover over the line. This made the visual more informative but it also created a mess as there as now too much information is one spot. I tried to clean it up by animating between each type of hitter but that only seemed to create more chaos but to the astute observer, is was clear that the left handed hitters performed better. 

index_final.html: In this iteration I decided to go with a different kind of graph. While it's neat seeing a scatter plot of over 1000 basbell players it's ultimately not that helpful when trying to figure out which type of hitter was better in aggregate. I decided to stick to overall statistics and show a box plot. Instead of trying to compare homeruns and batting average at the same time I added a switch button that would alternate between the two. This simplified the entire visual and made it easier to consume and compare the information around each metric. It was clear from the feedback that this graph showed that left handed hitters were better overall then right handed hitters. This was encouraged because it was the same conclusion that I had researched earlier. 



##Feedback
*Include all feedback you received from others on your visualization from the first sketch to the final visualization*
#### Girlfriend
The numbers on the bottom axis don't make sense, I'm not really sure what average is?  I like the colors blue and green. I'm not really sure who's better(left handed or right handed hitters). 


The second graph looks like kind of a mess. The the animation is cool, how do you do that? 


I'm not sure what's going on in the third graph but it looks like the left handed batters are better. I'm not sure by how much. 

#### Cousin
First graph: can't tell which type of hitter is better. Do you know the overall homerun and batting average of each type? What make's a better hitter, one with more homeruns or one with a better average? The first graph doesn't tell me much. 


I thought the animation on the secnod graph was cool until I tried to hover over the lines for more information. It was hard to explore the data but it was easy to see that left handed hitters had a slight advantage to right handed hitters. I could learn more from the second graph but it was way too confusing.


The third graph is clean and it's clear left handed hitters had better results for homeruns and batting average. 

#### Friend
Graphs 1 is interesting but I'm not sure which type hitter is better. It was cool taking a look at indiviual stats of the hitters who did really well in the first graph. 


Graph 2 is kinda crazy. I think it's telling me left handed hitters are better but it's hard to be sure. 


Graph 3 is nice, I've seen similar graphs used in the past. It's clear left handed hitters had better results but it would have been cool to see an animation from batting average to homeruns. 


##Resources
*List any sources you consulted to create your visualization:*

[http://www.hardballtimes.com/the-advantage-of-batting-left-handed](http://www.hardballtimes.com/the-advantage-of-batting-left-handed)

[http://stackoverflow.com/questions/10247209/d3-click-coordinates-are-relative-to-page-not-svg-how-to-translate-them-chrom](http://stackoverflow.com/questions/10247209/d3-click-coordinates-are-relative-to-page-not-svg-how-to-translate-them-chrom)

[http://bl.ocks.org/weiglemc/6185069](http://bl.ocks.org/weiglemc/6185069)

[http://bl.ocks.org/pbogden/7487564](http://bl.ocks.org/pbogden/7487564)
