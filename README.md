# social_score
This repository contains the source code for the research  paper titled "Calculate the score of a social media profile and posts on twitter and other social media sites on the internet".

#### Authors: Pooja Chaudhary, [Ravin Kumar](https://mr-ravin.github.io)

### Working Demonstration
```python
import social_score
### pass username , and degree_score along with the login credentials for twitter app.
res=social_score.social_score(consumer_key,consumer_secret,access_token,access_token_secret,username,degree_score) 
###res contains the social score value.
```

#### Note: This scoring is recently developed, and does not convey any bias against anyone. Thats just pure mathematics, although the mathematical formulae can be improved to have better performance. 
