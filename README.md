# linksF1nd3r
![screen_1](http://i.imgur.com/2L7bFzQ.png)

Status: **Development**
## About LinksF1nder
Extracts links from an HTML page and display them with friendly way ,this tool could be used for web information gathering ,to get more details about the web application.

## Features

* Extract all the links not only the a href="#" tags
* Identifying the extention of the linked file
* Generate report
* Count the links based on the extension

## Usage

~~~
$ python linksF1nd3r.py URL

~~~

Example:
* Testing on the local host
~~~
python linksF1nd3r.py http://127.0.0.1/links.php
~~~
![screen_2](http://i.imgur.com/ifYafoX.png)

* Testing on real website [stackoverflow.com]
~~~
python linksF1nd3r.py https://stackoverflow.com/questions/11487049/python-list-of-lists
~~~
![screen_3](http://i.imgur.com/DdeK4bF.png)




## How to install
##### Clone
 - Clone the repository with:
```sh
$ git clone https://github.com/ihebski/LinksF1nd3r.git
$ cd LinksF1nd3r
$ python linksF1nd3r.py
```
##### Dependencies
* Install the required dependencies with:
```bash
$ sudo pip install -r requirements.txt
```
## License
The MIT License (MIT)