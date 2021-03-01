#  Indoor Positioning Through Constraint Optimization

Fingerprinting is a well know method for improving indoor positioning. This method, however, requires a data collection process that includes physical measurement to determine ‘true’ locations. Taking physical measurements apriori is costly, time consuming, and in some cases, impossible. The intention of this project was to use a novel approach to determine highly accurate 'true' locations without physical measurement. This was done by adding a distance constraint to multiple tags which were moving simultaneously through the space. Using this known distance constraint, the aim was to test to what degree true position information could be determined even in the absence of physical measurements. 

The contributions of this study included:
-	Construction of a platform to test UWB technology
-	Collection, visualization, and analysis of data

The hypothesis was that additional ground-truth information about the inter-tag distance, along with the simultaneous collection of three tags would improve accuracy. There were two benchmarks to compare the results against: 
- The three independent vendor provided X,Y readings from each tag
- The average over 30 seconds from the combined information of all three tags
  
While this proposal was superior to the first benchmark, it was not better than the second. This could be because:
- There are data points where a tag has better accuracy in one dimension but worse in the other
- Reducing the data to eliminate noise was too simple given the two-dimensional nature of the data

The results provided important insight to the direction of research in this area. 
