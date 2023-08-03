# Broken web links Checker and Analyzer
Python script for checking for broken links and analyzing links status on a single webpage   
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

### in the python file   
```py
import sys
# ...
main(sys.argv)
```

### as an import into another python module
```py
from broken_links_checker import main as links_checker_main # or any other name
import sys
# ...
links_checker_main(sys.argv)
```
   
## Command format   
-- Single webpage   
### On Windows
```cmd
broken_links_checker https://full-url or http://full-url
```
### On Unix system
```cmd
python3 broken_links_checker https://full-url or http://full-url
```
   
-- With sitemap for a full website scan   
### On Windows
```cmd
broken_links_checker --with-sitemap C:/full/path/to/the/sitemap.xml
```
### On Unix system
```cmd
python3 broken_links_checker --with-sitemap /full/path/to/the/sitemap.xml
```
the `--with-sitemap` flag doesn't have to come before the url, it can also come after it   
   
you can also call the python file with a custom name like names like npm, git, composer and so on, you can watch my yt video on how to do it, link below   
[How to run python file with custom name like npm on Windows and Linux](https://youtu.be/3VOtRaopsIQ)
   
## Contribution   
Fork the repo and create a pull request with the description of the changes you made
