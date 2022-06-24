# Broken web links Checker and Analyzer
Python file for checking for broken links and analyzing links status on a single webpage   
or all webpages of a website   
   
it also has the support of using XML sitemap of a website to check for the broken links and analyze links in all webpages of the website   
   
## Dependencies   
`requests` and `BeautifulSoup4`   

### How to install `requests`   
```cmd
pip install requests
```   
   
### How to install `BeautifulSoup4`   
```cmd
pip install beautifulsoup4
```    
   
## How to run   
it works through the command line and you pass data to it through the python sys module using `sys.argv` then pass the data from `sys.argv` to the `main()` function as parameter   
   
## Command format   
-- Single webpage   
`the-python-file-name full-url`   
   
-- With sitemap for a full website scan   
`the-python-file-name --with-sitemap full/url/to/the/sitemap.xml`   
the `--with-sitemap` flag doesn't have to come before the url, it can also come after it   
   
you can also call the python file with a custom name like npm, git, composer and so on, you can watch my yt video on how to do it, link below   
[How to run python file with custom name like names like npm on Windows and Linux](https://youtu.be/3VOtRaopsIQ)
   
## Contribution   
Fork the repo and create a pull request with the description of the changes you made
