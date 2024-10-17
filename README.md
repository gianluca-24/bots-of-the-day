# Bots of the day
Me and a colleague created these 3 bots that make daily post about three topics:
- Facts of the day: x.com/factsfromtoday;   
- Births of the day: x.com/birthsfromtoday;
- Deaths of the day: x.com/deathsfromtoday;

## Technologies

- X API: Through the X API we've been able to post content on X (f.k.a. Twitter) through a Python script;
- BeautifulSoup: Essential to perform daily scraping on https://www.onthisday.com as a source for our posts;
- wikipedia API: A shortcut that makes easier for us to retrieve an image relative to the event we are trying to post;   
- AWS: In order to keep our bots up and running we took advantage of the AWS cloud resources. The scraping and posting is handled through an AWS Lambda function. Such function is being triggered by an EventBridge - a clock that every day at the same hour will trigger the function and post on X.   




