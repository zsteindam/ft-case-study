# ft-case-study
Repository for Fintech Case Study Homework 1


Robinhood


Introduction

The company I chose for my Fintech case study is Robinhood Markets, Inc. or more commonly known as just Robinhood. The company was incorporated on April 18th, 2013 by former Stanford roommates Vladimir Tenev and Baiju Bhatt. The company has grown so quickly that in July they announced a $323M Series E financing that values the company at $7.6B. Investors include DST Global, Ribbit Capital, NEA, Sequoia, and Thrive Capital. 
 It’s clear the founders purposely chose the name Robinhood when deciding what to name their company. With the financial crisis and its effects on the general public clearly on their mind, the two financial software professionals aimed to take on Wall Street while helping Main Street gain easy access to the US financial systems. The founders have spoken at length about their goal to “Democratize access the American financial system” and how they were inspired by the “Occupy Wall Street” movement.  

A Race to The Bottom

The term “a race to the bottom” traditionally has a negative connotation. Traditionally this phrase is used when companies look to undercut each other in price at the expense of quality and standards, ethics, and even regulation. In today’s world, we have flipped this connotation on its head. Instead of making sacrifices to be able to offer a less expensive product, we can use technology to be smarter, faster, and more efficient. Offering the end customer a better experience all while offering them a better price. 

In the case of retail equity brokerage, we have reached “the bottom”. Robinhood, a US financial services firm based in Menlo Park, CA has brought us there. Offering commission free stock and option trades to its customers, Robinhood has effectively ended this “race”. It even offers commission free cryptocurrency trading in some states. They also offer commission free equity option trading. Robinhood is fully licensed and registered with the Securities and Exchange Commission (SEC) and the Financial Industry Regulatory Authority (FINRA). It is also a member of the Securities Investors Protection Commission (SIPC). Regulation is obviously a big part of this industry and Robinhood is regulated just like all the big banks and big brokerage houses. They compete directly with the all the other traditional retail brokerages, Fidelity, Charles Schwab, Edward Jones, Merrill Lynch, etc. Also of course they compete with the online brokers such as E-Trade, TD Ameritrade, TradeStation, etc. 

E-Trade currently chares $6.95 in commission per trade and Charles Schwab charges $4.95. Robinhood charges $0.00 per trade, ZERO. There are no hidden fees or hidden costs that pop up later. It really is free stock trading. Now you may be asking yourself, “How can Robinhood offer this if the larger more established firms cannot?”. Essentially Robinhood’s competitive advantage is its size and technology.

Robinhood has 740 employees on LinkedIn over two office locations, Menlo Park, CA and Lake Mary, FL. E-Trade has over 4,000 employees with 30 “brick and mortar” branch locations and seven corporate locations. Charles Schwab has over 19,500 employees with 345 branch locations as well as multiple corporate locations. It is obvious that a company like Robinhood can use its smaller size to operate at thinner margins. Operating solely online with zero branch locations allows it keep overhead costs to a minimum. Lower headcount also plays right into this advantage. 

A very good example of how Robinhood has leveraged modern technology to offer their customers a better, more efficient and less expensive experience is one of their latest projects. At the onset Robinhood was using a company called Apex as their clearing firm. Apex was the firm that essentially organized, settled and acted as custodian for all of Robinhood’s customer’s trades and accounts. When you bought or sold a stock on Robinhood essentially Apex was the one who actually processed that transaction. Recently Robinhood built their own clearing firm, from scratch. The last brokerage house to build their own clearing firm from the ground up was Vanguard, in 2008. This makes “Clearing by Robinhood” the only clearing firm built on modern technology. Self-clearing allows Robinhood to eliminate or reduce many fees that typically were passed along to the customer. Additionally, Robinhood is able to take more accountability and have more visibility over accounts and settlements, which provides customers better support. One specific example is how the company now deals with accounts that are holding stocks that are going through a corporate action (stock splits, mergers, spin/split -offs, etc.). Typically clearing firms employ hundreds of people to help process these non-standard transactions that could have very unique details. Robinhood claims they had two engineers build an entire system to allow for this type of processing for their millions of customers with only two brokers. According to the company website this “Clearing by Robinhood” project leverages systems such as Python 3, Django/DRF, React JS, Kafka, Airflow, and more to achieve their goals. Specifically, they reference how Python and Django allow them to “model complex financial objects and quickly stand up API servers”. 

Robinhood generates revenues a couple ways that do no include per trade or per share commissions. First off, they keep the interest generated from the cash held in customer accounts. Secondly, they generate revenues off what it in the industry is called “payment for order flow”. This is a standard practice among retail brokers and almost of them use some form of this revenue stream. “Payment for order flow” is a totally legal and 100% disclosed process under SEC Rule 606. According to Robinhood’s website they send their order flow to high frequency trading firms such as Citadel, Two Sigma, Wolverine and Virtu. A Wall Street Journal article from November 2018, citing SEC filings, claims that Robinhood receives up to $5.20 for a 100 share order of Apple stock, where as Charles Schwab would be paid around $0.09 for the same order, and TD Ameritrade around $0.16. The article claims this difference affects their execution quality. The market makers deliver worse “price improvement” in exchange for the larger rebates. Robinhood’s website rebukes these claims saying “our execution quality and speed matches or beats what’s found at other major brokerages.” The Wall Street Journal article comes to a conclusion deciding Robinhood is best for small investors and smaller trades, where the “price improvement” may be less important than the commission free trades. To quote the article directly - “ “For small trades, the benefits of saving money on commissions outweigh any gains from price improvement”, said Chris Nagy, managing principal of KOR Group, a firm that studies quality of trade executions. ”. Other ways Robinhood generates revenues is from offering premium account types. They offer “Instant” and “Gold” status that come with a monthly subscription fee. Also, they offer margin trading, essentially loans to allow customer to make trades larger than the cash in their accounts, where they charge interest. Also a standard practice among brokerage firms.

Currently Robinhood has about six million accounts, compared to E-Trade’s seven million accounts, and Charles Schwab’s over eleven million accounts. Robinhood targets millennials and their platform is available on iOS and Android mobile apps. Their company mission is to allow easy and fair access to the markets for the new generation. In just 6 and a half short years the company has grown from an idea into over six million accounts. Additionally, the company has stated plans to go public in the near future. As Robinhood is a private company, we don’t have figures on their revenues and profits that we can compare to their competitors, but hopefully we will soon. 

If I were to advise the company, I would recommend they offer something similar to a robo-advisor service. Currently Robinhood allows for customers to pick their own stocks and ETFs, but what it doesn’t offer is a systematic diversified investing tool. It would be easy to nail down some portfolio theory and some trading algorithms and offer a tool that would start with the customer filling out some investment goals and risk tolerance questions and would wind up with offering investment suggestions. While many millennials like the ability to pick their own stock companies such as Wealthfront and Betterment have found success offering customers a full pre-organized portfolio including large cap, small cap, international and domestic equities as well as fixed income ETFs. Additionally, the company could offer an equity screening tool. Bringing real time data to the customers that they could easily sort and filter, helping them make their own smarter investment decisions. Providing customers with the data base to come to their own investment conclusions could be achieved using Python or SQL. These systems will allow for the database of company information to be recalled and queries to be as complex as the customer requests and maintained at efficient speeds. 

In conclusion, Robinhood does exactly what its name implies, “steals from the rich and gives to the poor”. It is stealing customers from the established brokers and banks and driving competition. It is taking commission dollars from the bigger brokers and returning it to the retails customers. It is forcing commissions down across the industry and even JP Morgan Chase has launched a product where it is offering up to 100 free trades a year to its customers, called “You Invest”. I don’t think we will see retail brokers offering rebates for trades, so zero commission is rock bottom. Robinhood has ended the race to the bottom. 













Sources:
https://www.forbes.com/companies/robinhood/?list=fintech/#4a4625556076
https://www.forbes.com/sites/jeffkauflin/2019/02/04/the-10-biggest-fintech-companies-in-america-2019/#5e6c8d4032b9
https://www.wsj.com/articles/why-free-trading-on-robinhood-isnt-really-free-1541772001
https://blog.robinhood.com/news/2019/7/21/robinhood-raises-323m-to-democratize-finance-for-all
https://blog.robinhood.com/news/2018/10/9/introducing-clearing-by-robinhood
https://www.bloomberg.com/news/features/2018-10-02/charles-schwab-on-his-3-6-trillion-edge-on-the-fintechs
https://robinhood.engineering/under-the-hood-of-clearing-by-robinhood-3ed7ab09d60


Link to slideshow

https://drive.google.com/open?id=1fH66719wDhcXoXselUJgdd2XxnryZYTm

