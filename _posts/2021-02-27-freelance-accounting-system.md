---
title: Accounting System for Freelance v0.1
layout: post-projects
tags: [projects]
excerpt: A simple project for freelance accounting system
---

In the past, I have made accounting system for few companies that is created using spreadsheet as its core. Most of thems are customized according to what the company and its management team want to see in term of their financial perfomance. As I work with more companies, I improve the system bit by bit and recently as I go in depth with coding I am looking for a way to an accounting system that I have made in the past with my new interest in coding. 

Hence, I do this project out of my curiosity. I try to create accounting system on the web app for a freelancer. The web app is created using Google App Script, a derivative of JavaScript in my opinion. The database is stored on Google Sheet files and consisted of two layers of Google Sheet. After user click the submit button, the data will be store in database file and immediately will be sent to reporting file for it to be processed into various accounting report. Kindly take note whatever you see in this post is the dummy version. If you are interested to know more about the working version, feel free to email me.

#### The main interface of the web app 
As this is just for fun project, I just created this simple interface to test the data input. Once again this is a dummy web app, and whatever is inputted here will not appear on the databases that I will show later. 

<iframe
  src="https://script.google.com/macros/s/AKfycbw5360oLtGcRK7wA5YBRY8lhSYJP2ztjgBT2EztgOHHAMkgoajSCR-Nh_rl2AUx2Pep/exec"
  style="width:100%; height:380px;"
></iframe>

#### First layer : database file
After a user has inputted the data on the web app, the data will be sent to this file first. This is also where the data can be altered if there is mistakes during the data input on the web app. And since this is built on the Google Sheet, access can be restricted either by specific row, column, cells, or even by users. 

<iframe 
    src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSsepZ_lzw_IJTFC7jm9M6zTtO5Ez160_XqBMdEDsavgcw5_u8SDaMaIb19PnLa9dVTjPM2cKS2kjjW/pubhtml?widget=true&amp;headers=false"
    style="width:100%; height:280px;"
></iframe>

**Client** and **Vendor** is quite self-explanatory. The **Document Log** is used to collect all invoices and bills information while **CashFlow Log** is used to collect all cash related transaction like getting new asset, making payment, etc. 

#### Second layer : reporting file
After the data is received at database file, the data is simultaneoulsy is also sent to reporting file where it will be processed in to various accounting reports. 

<iframe 
    src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS19tBK0QkKC4vuU0N1CgEwPYwfjqzZnij9L7R1hRvut7iyF-JkkEGTbqoZW8s-r9LIWR6nRV9vXYjf/pubhtml?widget=true&amp;headers=false"
    style="width:100%; height:280px;"
></iframe>

Most of the tabs are self-explanatory, the **double entry** tab is mainly used for vlookup purpose to allocate each transaction to their respective accounts on each tabs. Most of the calculations in this file is done automatically, for instance the depreciation on **fixed assets** will be calculated automatically before it is sent to balance sheet and profit/loss statement. 

#### Conclusion
Of course this is just a simple system and it can be extended further like adding multiple bank accounts, multiple currencies, various depreciation and amortization rules or expanding the projects further for calculating stocks, calculating cost of productions etc. 

This system is quite low-cost especially if you just started your business in comparison with subscription based accounting system. I have seen that the possibility to use this as a support system on medium enterprise with other systems that the companies are using. The main drawback is due to it is built on spreadsheet, as the data grow over the year, the file can be heavy on the system especially for low-spec system. 

For any questions on this project you can contact me at **edward@costhin.com** and please mention the project name. Thank you for reading. 