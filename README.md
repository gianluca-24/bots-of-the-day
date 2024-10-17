# Bots of the day
Me and a colleague created these 3 bots that make daily post about three topics:
- [Facts of the day](https://x.com/factsfromtoday)   
- [Births of the day](https://x.com/birthsfromtoday)
- [Deaths of the day](https://x.com/deathsfromtoday)

## Idea
It was a random evening and we were spending an evening with friends. While talking, we ended up discussing what had happened in history on that particular day, hence the idea: why not create a page ourselves that would publish the events of that day on a daily basis? Once we had found our source of events, we decided to expand this project by also adding who was born and who died on that day. This is not a university project, but a simple project in which I wanted to get involved with a friend, applying the knowledge I had learnt in my final years at university.

## Technologies

- X API: Through the X API we've been able to post content on X (f.k.a. Twitter) through a Python script;
- BeautifulSoup: Essential to perform daily scraping on https://www.onthisday.com as a source for our posts;
- wikipedia API: A shortcut that makes easier for us to retrieve an image relative to the event we are trying to post;   
- AWS: In order to keep our bots up and running we took advantage of the AWS cloud resources. The scraping and posting is handled through an AWS Lambda function. Such function is being triggered by an EventBridge - a clock that every day at the same hour will trigger the function and post on X.   




