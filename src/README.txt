====HOW TO CRAW DATA FROM THE WEB=====

*Install Python, Jupyter NoteBook and Scrapy:
1. Install Anaconda: https://docs.anaconda.com/anaconda/install/windows/
2. Install Scrapy: https://docs.scrapy.org/en/latest/intro/install.html

*How to use Scrapy after installed:
1. Open your terminal, type "cd src/crawler".
2. Type "scrapy crawl full2ImdbCrawler -o data.csv".
3. After finishing crawling data, continue to type "scrapy crawl full2MpaaCrawler -o data_mpaa.csv".
4. Open the folder named crawler, we will see two new files being created: "data.csv" & "data_mpaa.csv". Move those files to "dataset" folder.
5. Open new terminal and type "cd src" then type "python join_data.py". We will get a new file named "data_joined.csv". Move that file to "dataset folder.
