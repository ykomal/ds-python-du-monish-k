
# Part 1.1: Explore New Feeds

- [ ]  **1.1.1 Identify your RSS news feed**

In short RSS feed is an XML feed where it contains the metadata about a particular webpage or website, like posts posted on different timeline, author of that post, etc. With these data available in RSS feed, it's smart to make use of that as your Datasource. In this step, you are expected to explore a good dataset (a RSS news feed) all by yourself, preferably in any topic from [analyticsvidhya.com](https://analyticsvidhya.com).

- [ ]  **1.1.2 Finalize the RSS news feed link that you want to run analytics on**

Well, not all websites give you readable RSS feeds, even most of the websites don't use RSS feeds. Look for a website that provides a standard format RSS feed. One tip would be, rather than searching in google for ‘websites that have RSS feeds’, it would be better to find the website you want to use and search for its RSS feed. Example: AnalyticalVidya, TowardsDataScience etc.

As a part of the bug listed in the ```issues``` tab with the same title add a comment which website would you be choosing, and why have you chosen the same.

# Part 1.2: Choose Your Data Attributes

- [ ]  **1.2.1 Understand Data Attribute from RSS XML**

In general, RSS feeds will have so many attributes and have a close look at each of the attributes required for the analysis.

For example, RSS feeds have many attributes like Datetime stamp, where few will be in IST and few will be in GST, likewise few websites offer hyperlinks to video/audio used in the webpage, which clearly is not much useful to run analytics. So lets better understand the feed and its attributes to avoid rework in the later point in time.

- [ ]  **1.2.2 Note down the data attributes needed for analysis**

RSS feeds come with a lot of metadata, you can use all of them to find insights, but some of the attributes may not provide much value to the analysis. For example, the name of the author does not have a big correlation with sentiment analysis. So before building your model, finalize which parameters you want to use for building your model.

As a part of the bug listed in the ```issues``` tab with the same title add a comment explaining in brief the parameters you have chosen to build your model. Also add a brief explanation about the model you are trying to build.

# Part 1.3: (Optional) Additional Learning

- [ ]  **1.3.1 Learning Links for Matplotlib**
- [Freecodecamp](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=video&cd=&cad=rja&uact=8&ved=2ahUKEwj57bT_5N_zAhVGPHAKHaSYALAQtwJ6BAgHEAM&url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3D3Xc3CA655Y4&usg=AOvVaw2BhsDxUYQN6A1rVHkSSCse) for basic video tutorial
- [Kaggle](https://www.kaggle.com/learn/data-visualization) Hands-on tutorial (It works with seaborn)
- [Matplotlib](https://matplotlib.org/stable/tutorials/index.html) Documentation

- [ ]  **1.3.2 Learning Links for NLTK**
- [Edureka](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=video&cd=&cad=rja&uact=8&ved=2ahUKEwja_qry5d_zAhUGBd4KHYs4DvsQtwJ6BAgFEAM&url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DU8m5ug9Q54M&usg=AOvVaw2jjaZOtaNbjt5Q09geS6tx) video tutorial
- [Kaggle](https://www.kaggle.com/learn/natural-language-processing) Hands-on tutorial for basic NPL
- [NLTK](https://www.nltk.org/api/nltk.html) Documentation
