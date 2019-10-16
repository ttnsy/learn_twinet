1. If we want to visualize how twitter users communicate with each other by looking at who (`screen_name`) tags who (`mention_screen_name`), the edges of our graph structure will be:
    - [ ] `screen_name`
    - [ ] `mention_screen_name`
    - [ ] links between `screen_name` and `mention_screen_name`
2. Chaining `gt_edges()` and `gt_nodes()` to our dataframe will return an object with unfamiliar class, graphTweets. To extract a graphTweets object to a list, which of the function is appropriate?
    - [ ] `sg_nodes()` and `sg_edges()`
    - [ ] `nodes2sg()` and `edges2sg()`
    - [ ] `gt_collect()`
3. If we want to create a dynamic graph with time factor where the edges appear at different time steps, which variable from tweets data is appropriate to add:
    - [ ] `location`
    - [ ] `created_at`
4. If we want to analyze how information spreads throughout Twitter, which graph do you think more suitable?
    - [ ] A graph where each node is users which are linked together when one has @tagged another in a tweet.
    - [ ] A graph where each node is a user who is connected to other users who they retweeted.
    - [ ] A graph where each node is users which are linked when they are mentioned together in the same tweet.