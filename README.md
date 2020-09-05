# CYBR8470: Secure Web Application Development
Professor: Dr. Hale  
Student:   Robert Ernewein

## Lab 1: RESTFul APIs
Twitter Application: CYBR8470-F20-Lab1
![](./images/Step3-1.png)

Keys:     Twitter API Keys.txt  
Browser:  Google Chrome (v85.0.4183.83)  
Software: Postman (v7.31.1)

## Screenshots & Findings

### Step 4: GET Requests

4.1: Creating GET request for Twitter Trends
![](./images/Step4-1.png)

4.2: Getting new Access Token
![](./images/Step4-2.png)

4.3: Set Authentication Type: OAuth 2.0
![](./images/Step4-3.png)

4.4: Set Location ID: 2465512 (Omaha, NE)
![](./images/Step4-4.png)

Note: I had some issues with Postman requiring manual input/configuration of the GET request.
![](./images/Step4-4a.png)
![](./images/Step4-4b.png)

4.5: Local Trending Data 
![](./images/Step4-5.png)

### Step 5: Addtional GET Requests

Searching recent Tweets via
https://api.twitter.com/search/tweets.json

5.1: Omaha City Council
![](./images/Step5-1.png)

5.2: High School Football
![](./images/Step5-2.png)


### Step 6: Post Request

Can't POST using App Key. No access to the user.
![](./images/Step6-1.png)

I was not able to POST under a user context after resetting the Authorization to Oauth 1. Based on the writeup, I assumed that the Token Secret was the same as the Consumer Secret. I also tried multiple combinations of the user ID & Access Token for the Token Secret without success.
![](./images/Step6-2.png)

Note: The inteface in the current version of Postman differs greatly from the writeup. Fields and settings don't matchup well.
