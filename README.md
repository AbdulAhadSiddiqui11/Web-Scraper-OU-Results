# Osmania University Results WebScraper

This web scraper will fetch the results of students between the given roll numbers. A csv file with scores of each student and a bar graph will be created for visualization. This scraper will work on any result page uploaded on Osmania University's official site. - "https://www.osmania.ac.in"
The web-scraper can quickly be modified to a specific use case, for example detailed analysis of a set of students for a particular subject.

## Getting Started

Clone the repository to your local machine  
Extract all the files into a directory  
Run the  	**resultsscraper.py**  
You can otherwise run the notebook **ResultsScraper.ipynb** 

### Prerequisites

Dependencies:
1. BeautifulSoup
2. pandas
3. matplotlib
4. progressbar
```
from bs4 import BeautifulSoup
import pandas as pd
import requests
from matplotlib import pyplot as plt
from progressbar import ProgressBar
```

### Installing

Installing our dependencies :

BeautifulSoup

```
$ apt-get install python-bs4 (for Python 2)
$ apt-get install python3-bs4 (for Python 3)
$ easy_install beautifulsoup4
$ pip install beautifulsoup4
(these may be named pip3 and easy_install3 respectively if you’re using Python 3)

If you don’t have easy_install or pip installed, you can download the Beautiful Soup 4 source tarball and install it with setup.py.
$ python setup.py install
```

Pandas

```
$ pip install pandas
$ pip3 install pandas (For python3, use pip for windows here as well)
```

Matplotlib

```
$ pip install matplotlib

If you are on Linux, you might prefer to use your package manager. Matplotlib is packaged for almost every major Linux distribution.

    Debian / Ubuntu: sudo apt-get install python3-matplotlib
    Fedora: sudo dnf install python3-matplotlib
    Red Hat: sudo yum install python3-matplotlib
    Arch: sudo pacman -S python-matplotlib

```
Example Graph Created : 
![alt text](https://github.com/AbdulAhadSiddiqui11/Web-Scraper-OU-Results/blob/master/graph.png "Bar Graph Created")

## Deployment

Run the  	**resultsscraper.py**
Use can otherwise run the notebook **ResultsScraper.ipynb** 

## Built With

* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) - Used for pulling data from HTML page
* [Pandas](https://pandas.pydata.org/pandas-docs/stable/) - Dataframe used to organize the data
* [Matplotlib](https://matplotlib.org/) - Used for data visualization

## Contributing

Please read [CODE_OF_CONDUCT.md](https://github.com/AbdulAhadSiddiqui11/Web-Scraper-OU-Results/blob/master/CODE_OF_CONDUCT.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **Abdul Ahad Siddiqui** - *Idea and implementation* - [Abdul Ahad Siddiqui](https://github.com/AbdulAhadSiddiqui11)

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/AbdulAhadSiddiqui11/Web-Scraper-OU-Results/blob/master/LICENSE) file for details

## Acknowledgments

* StackOverflow
* **Inspiration** : It was cumbersome for me to analyze the results for all my classmates so I dicided to automate this process.

