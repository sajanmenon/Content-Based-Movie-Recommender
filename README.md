# Content-Based-Movie-Recommender
Building a content based movie recommender system with natural language processing.The function will take movie name as input and show  top 3 recommended movies.(Using Netflix dataset) 



This type of filter does not involve other users if not ourselves. Based on what we like, the algorithm will simply pick items with similar content to recommend us.
In this case there will be less diversity in the recommendations, but this will work either the user rates things or not. If we compare this to the example above, maybe user B potentially likes dark comedy but he/she will never know, unless he/she decides to give it a try autonomously, because this filter will only keep recommending dystopian movies or similar. Of course there are many categories we can calculate the similarity on: in the case of movies we can decide to build our own recommender system based on genre only, or maybe we want to include director, main actors and so on.
These are not the only two types of existing filters, of course. There are also cluster or behavioral based for example, just to mention a couple more.
So far I have mentioned many times the word similarity, but what is it, exactly? It doesn’t really seem something we can quantify, but surprisingly it can be measured! Before jumping into a practical example of how to build a content-based system, let’s briefly review the concept of cosine similarity. This is one of the metric that we can use when calculating similarity, between users or contents.
