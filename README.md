# PDPU-Mess Menu Scraping
[![followers](https://img.shields.io/github/followers/memr5?label=Follow&style=social )](https://github.com/memr5/PDPU-Mess-Menu-Scraper/blob/master/README.md) [![GitHub repo size](https://img.shields.io/github/languages/top/memr5/PDPU-Mess-Menu-Scraper)](https://github.com/memr5/PDPU-Mess-Menu-Scraper/blob/master/README.md) 
[![last-commit](https://img.shields.io/github/last-commit/memr5/PDPU-Mess-Menu-Scraper?style=plastic)](https://github.com/memr5/PDPU-Mess-Menu-Scraper/blob/master/README.md)
[![repo-size](https://img.shields.io/github/repo-size/memr5/PDPU-Mess-Menu-Scraper?style=plastic)](https://github.com/memr5/PDPU-Mess-Menu-Scraper/blob/master/README.md)

This python program scraps daily menu of mess in PDPU & send the menu as Whatsapp message.  

## Code

* Sometimes the menu is not updated on the website, so we don't want that menu to be fetched.  
The below-given function do this task, it checks whether the today's date matches with the date of the menu on the website.

![dateCheck](https://github.com/memr5/PDPU-Mess-Menu-Scraper/blob/master/Code%20snippets/dateCheck.png)

---

* After conforming that the menu is upddated on the website this fetchMenu function fetches the menu meal wise and stores every item into a dictionary.

![fetchMenu](https://github.com/memr5/PDPU-Mess-Menu-Scraper/blob/master/Code%20snippets/fetchMenu.png)

---

* sendMenu function will send the menu to a specified user or a group in Whatsapp for that the user is required to scan the QR-code of Whatsapp-web.

![sendMenu](https://github.com/memr5/PDPU-Mess-Menu-Scraper/blob/master/Code%20snippets/sendMenu.png)

---

## New features to be included

* A feature to store favourite food-items
* Reminder in Google-Calender if a user's favourite food is on the menu
* ~~Whatsapp message~~ => Text message
* Meal wise text messages

---
*[Suggestions are welcome](https://github.com/memr5/PDPU-Mess-Menu-Scraper/issues)*
 
