# IMDBscraper

## Install

This project requires **Python 2.7** and the following Python libraries installed:

- [requests](http://docs.python-requests.org/en/master/)
- [bs4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [selenium](http://selenium-python.readthedocs.io/)
- [time](https://docs.python.org/2/library/time.html)
- [timeit](https://docs.python.org/2/library/timeit.html)
- [numpy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org/pandas-docs/stable/)
- [json](https://docs.python.org/2/library/json.html)
- [csv](https://docs.python.org/2/library/csv.html)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. Make sure that you select the Python 2.7 installer and not the Python 3.x installer.

## Code

Template code is provided in the `IMDB.ipynb` notebook file. 

The template code uses [The Hunger Games (2012)](http://www.imdb.com/title/tt1392170/reviews?start=0) as an example. To try another movie, you need to replace the current movie id (tt1392170) with the id of the movie you want to try.

Additionally, you need to download a [selenium webdriver](http://www.seleniumhq.org/projects/webdriver/).

## Run

In a terminal or command window, navigate to the top-level project directory `IMDBscraper/` (that contains this README), and run one of the following commands:

```bash
ipython notebook IMDB.ipynb
```  
or
```bash
jupyter notebook IMDB.ipynb
```
