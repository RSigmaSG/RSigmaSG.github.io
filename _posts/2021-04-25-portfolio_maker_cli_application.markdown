---
layout: post
title:      "Portfolio Maker CLI application"
date:       2021-04-26 02:25:19 +0000
permalink:  portfolio_maker_cli_application
---


For my final project of Module 6, object-oriented-ruby of my learn curriculum, I decided to do a simulation of a stock portfolio.  The reason I went with this has been my recent interest in following the stock market and wanting to dip my hands into fintech in the future. 

I started off by trying to find sites to scrape, went through several sites and decided on Yahoo whose individual stock pages seemed one of the best to work with. Others had tables and such which I was not used to scraping data from yet. Yahoo's trending stocks were a little hard to scrap[e so I decided to go to investing.com to get a table of trending stocks and then scrape individual pages of these stocks to display their data.

After finishing and testing the scrapper, I started working on the CLI to just display stock info and data that the scrapper creates. I then added my stock object to encapsulate scrapped data into an object followed by a portfolio for the user to track their investment into these stocks. After integrating these objects into my CLI, my projects were essentially done. I wanted to try making a gem for this but I kept getting errors. I spent quite a few days on this but unable to figure it out, I decided to submit this as a git repo and figure out the gem part later on my own time. 
