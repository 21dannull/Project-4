# Project-4
Analysis of subreddit hyperlink data https://snap.stanford.edu/data/soc-RedditHyperlinks.html  
Each node is a subreddit and each edge is a hyperlink from one subreddit to another. Instead of having parallel edges, I just used the amount of edges as the weight. Edges also include a sentiment label, 1 for positive or neutral, and -1 for negative.  
citation:
@inproceedings{kumar2018community,
  title={Community interaction and conflict on the web},
  author={Kumar, Srijan and Hamilton, William L and Leskovec, Jure and Jurafsky, Dan},
  booktitle={Proceedings of the 2018 World Wide Web Conference on World Wide Web},
  pages={933--943},
  year={2018},
  organization={International World Wide Web Conferences Steering Committee}
}
