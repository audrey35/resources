# Python

## Python Tutorials
- [Python Programming](https://testautomationu.applitools.com/python-tutorial/)
- [Python Tutorials (read)](https://careerkarma.com/blog/python-tutorials/)
  - top notch blog posts with snippets of code on different topics in Python

# Python Flask Resources
- [Extensive list of tutorials on building full-stack Flask apps](https://www.fullstackpython.com/flask.html)
- [Short and sweet tutorial to build a bookmarking app and wiki](http://charlesleifer.com/blog/dont-sweat-small-stuff-use-flask-blueprints/)

How can I structure a Flask application?
- [Structuring a large Flask application](https://www.digitalocean.com/community/tutorials/how-to-structure-large-flask-applications)

# Web Scraping using Python
What module do I use to scrape the web?
- [Choosing the Right Tool](https://www.pluralsight.com/guides/advanced-web-scraping-tactics-python-playbook)

How can I crawl the web without using the Terminal (with Scrapy)?
- [Scrapy API](https://docs.scrapy.org/en/latest/topics/api.html#topics-api)
- [Run Scrapy from a Script](https://docs.scrapy.org/en/latest/topics/practices.html)

How can I use Scrapy more effectively? Advice from experts that I never knew I needed?
- [Best Practices and Workarounds](https://www.codementor.io/blog/python-web-scraping-63l2v9sf2q)

How should I structure my spider (Scrapy)?
- [Organize your callbacks](http://www.thecodeknight.com/post_categories/search/posts/scrapy_python)
- [Utilize items and pipelines](https://blog.datahut.co/tutorial-how-to-scrape-amazon-data-using-python-scrapy/)

How do I edit a scrapy Request object to pass a dictionary to the parse function?
- First, I checked what functionality the Request object has by looking at the docs for Scrapy and thought `cb_kwargs` looked promising.
  - [cb_kwargs](https://docs.scrapy.org/en/latest/topics/request-response.html)
- Then I searched examples of how `cb_kwargs` are used and from that came to the conclusion this is what I needed.
  - [example use of cb_kwargs](https://stackoverflow.com/a/61794444)
  - [another example of cb_kwargs use](https://stackoverflow.com/a/58468587)