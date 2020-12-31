# nodeScraper
## Module 1:This is a scraper for  readability adaptation for my favorite sites, and articles. After adaptation new version of readable articles should be viewed on electron based reading app for better reading experiences.

## based on node.js, Cheerio and express.js. And if there are right readability node.js library available try first.
- https://github.com/luin/readability this looks great
  This works fine for xueqiu, but not for SA.Checking works or not on wechat articles
- https://github.com/bndr/node-read might worth a try
  This also works fine with XQ and similar result to WC, but also not work to SA
- https://github.com/mozilla/readability
- Maybe try myself for some specific website only.

For authentication requested site, like SA, AR3000 etc,try:
Reference discussion: https://stackoverflow.com/questions/8726079/how-can-i-scrape-sites-that-require-authentication-using-node-js
  How can I scrape sites that require authentication using node.js?
 Option 1: Use Mikeal's Request library, you need to enable cookies support
 Option 2:Using Puppeteer
 Option 3 Using NightmareJs
 Option 4: Using SuperAgent for agent is then a persistent browser, which will handle getting and setting cookies, referers, etc. Just agent.get, agent.post() as normal.
 
## Module 2: Scraper 10-k data from yahoo or SEC
