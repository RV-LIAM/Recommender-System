# Movie Recommnder System
In the whole world, these days all live a large part of their lives digitally on mobiles and laptops. This behaviour has enabled many new types of businesses and business processes to emerge from it. E-commerce systems, music/movie streaming services, news providers are such examples. If for a moment we think the available items in an E-commerce website to buy from, we could get overwhelmed very quickly just from the magnitude of items available. Similarly, if a user would like to find a movie from a catalogue of thousands of movies, it would almost be impossible for each user to browse through the options available. These kinds of problems have incentivised research in Recommender Systems. The research is in the direction of making RS making more efficient, scalable, and better for human interaction.

Mainly there are two types of Recommender System - Content Based (CB) and Collaboration Filtering Based (CF). Both the systems have been thoroughly researched and pros and cons of both systems have been documented well. This study is focussed on researching a hybrid method to include the goodness of both CB and CF systems for a movie recommendation system. This study aims to focus on few areas of research i.e. design a hybrid system to add CB and CF techniques; use a proxy/shadow rating for a new movie; design an algorithm to add serendipitous movie items This study used a public contributed dataset 'The Movies Dataset' with movie meta-data to conduct experiments.

The python notebook contains experiments in the below order:

a. Content Based Recommender System - using movie metadata cosine similarity

b. Collaboration Filtering Recommender System - using user movie ratings SVD Matrix Factorization

c. Hybrid Recommender System - using both a and b in order of first a then b to filter movies

d. Hybrid Recommender System from point c, added with a novel way to solve cold movie start problem (basically how to handle a new movie without any user ratings yet)

