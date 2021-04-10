# Web scraping Warframe weapons from fandom.com Warframe wiki

Web scraping the warframe.fandom.com website to create a dataset of all the weapons in Warframe.

## Warframe
<a href='https://www.warframe.com/landing'>Warframe</a> is my favorite game. I wanted to make a dataset about it's weapons since it has so many nowadays.

### Warframe wiki

<a href='https://warframe.fandom.com/'>warframe.wiki</a> is a website that features the entire weapon roster of Warframe.<br>
For each weapon this website features some data about different aspects and attributes such as damage, fire rate, magazine size and others.<br>

### Tools

To extract the data I used the Python programming language as well as some of its modules.
* For requests I used the <a href='https://requests.readthedocs.io/en/master/'>Requests</a> module.
* For the web scraping I used the <a href='https://www.crummy.com/software/BeautifulSoup/bs4/doc/'>Beautiful Soup</a> module
* To save the data I used a json file.

### Data
All weapons share some basic attributes while other attributes are unique to the weapon type.<br>
Aside from that, Warframe has several weapons with special attacks that are unique to that weapon. Consequently, a csv format is not best suited for this kind of data.<br>
However, the weapons' attributes are grouped up in different sections of the info card on the website. This gave me the idea to organize the data in a json format.<br>
Each weapon's name is the key and the value is made up of the weapon's attributes, json formated by the section they belong to.<br>
![alt text](https://github.com/VictorMegir/Web-scraping-Warframe-weapons/blob/main/prt.png?raw=true)

The dataset can also be found here: 
