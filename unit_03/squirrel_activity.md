# Squirrels? 

Nick and I couldn't find any data about the fat, friendly, happy squirrels that roam around the Berkeley campus. (What are these tame beasts doing now that there aren't visiting families and tourists to feed them?) 

But we found a pretty solid runner-up data set that combines things that we all share in common, with things that some of us are seeing right now -- Cal squirrels, the Census (where do we all count for this, by the way? Your representation matters **a great deal**) and New York City. In the following dataset, which we came across through [tidy_tuesday](https://github.com/rfordatascience/tidytuesday) is drawn from the NYC Squirrel Census. Yes, this is a thing.  And, yes, they provide their data. 

# Data and Data Dictionary 

The data dictionary is available at [this page](https://github.com/rfordatascience/tidytuesday/tree/master/data/2019/2019-10-29). The meta-meta data -- you've been at Berkeley long enough that you can handle this -- is that this is a count-in-place census of the squirrels that are present in a NYC geom on a single day, at a single point in time. 

There are several data features that are described in this data. Cruise over to the link, and check it out. 

Several meta-points to make: 

- Notice the file naming structure
- Notice the variable naming structure 
- Follow these patterns, please. 

## Ideas for Investigation

Cruise over to a notebook, load the data from [this URL ]("https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2019/2019-10-29/nyc_squirrels.csv"), and using only your undertanding of how the world works, your curiosity, and the `.value_counts ()` that are present in the variables write out 10 specific questions that you could ask (and hopefully answer) using this data. 

# Investigate! 

- Produce a single plot that draws a single point for each observation on the `x=latitude`, `y=longitude` coordinate axis. Does it feel like this plot *clearly* communicates the underlying information that is in the data? 
- Is there a grouping feature that you can pull that you can use to summarize this data up a level (hint: yes, there is). Using `groupby()`, and summary mappings: map this data up a level, and then replot where you represent the prevalance within this grouping using point size to communicate how many squirrels were present in that area. (hint 2, if you have imported `matplotlib pyplot` as `plt`, then you can set the point size as `plt(x=x,y=y,s=s)` where `s` is informative of the size of the point that you would like to draw. 
- There is a breakpoint in the park -- the Jacqueline Kennedy Onassis Reservoir -- does it seem like squirrels that are spotted north of the reservoir are more wild than the squirrels that are spotted south of the reservoir? 
  - How many squirrels are sited north and how many are sited south of the reservoir? Is this breakdown surprising or not based on how much area and people reside on the two poles of the park? 
   - Is there a variable that seems to capture "wildness" of the squirrel? If you were designing the data capture system, and you could take any action, at any cost, what would you measure to generate an understanding of how "wild" or "tame" are the squirrels. Are there variables in the data that seem to capture parts of this? What have you given up from your _ideal_ measurement vis-a-vis this _feasible_ measurement? Does the actual measurement that you have do a good job, or a bad job of capturing wildness? 
   
# Investigate! 

- Answer one of the questions that you wrote down. In doing so, tell us why this is interesting to you, and what is your answer to the question. 
  




