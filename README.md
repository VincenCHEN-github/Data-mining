# Data-mining

**AIDM7390 Data Mining and Knowledge Discovery for Digital Media Group Project****   ****Twitter Data Analysis**

**NBA social media strategy**

**1. Introduction**

In the 2015-2016 season, the NBA achieved a clear breakthrough: Basketball Twitter strategy (Basketball Twitter). The NBA became the first league to have over 1 billion likes and fans on social media among all leagues, teams, and player accounts. In the 2014-2015 season, the NBA achieved a revenue record of approximately $4.8 billion. In addition to being affected by the TV broadcast agreement, this is also inseparable from the credit of the expensive sponsorship agreement. According to reports, the rising prices of broadcast agreements and sponsorship agreements are inseparable from the increased exposure and audience level brought by the alliance&#39;s social media strategy. The NBA&#39;s social media strategy has changed the way sports marketing and fans watch games. By building a platform, fans, teams, players, and leagues all have a say. On Twitter, the personalities of the players and the team complemented their athletic performance, attracting a large number of fans to join the discussion and gain a sense of belonging to the basketball community. The NBA&#39;s social media strategy has changed the way sports marketing and fans watch games.

We select the content of Twitter data for analysis from three perspectives. First, from the perspective of the stars, we selected James&#39; Twitter for data crawling, mainly personal dynamics and information. On the other hand, we get the tweets in the #NBA tag topic. Special content analysis text, mainly event information, game discussion, etc. Finally, we obtained official NBA accounts from 9 different countries to observe the discussion content and timeline.

**2. Procedures**

First, apply for a new Twitter account and apply for an API, and then use Rstudio programming language to start data crawling. We load the required package, and then enter the API information

![](RackMultipart20210510-4-nd3jdu_html_2ca6aee70c940667.jpg)

Since we also need to obtain the Twitter content of a specific account and the data content of a specific tag, we choose different crawling languages. When researching specific users, such as James, we choose the &quot;get\_timelines&quot;statement:

![](RackMultipart20210510-4-nd3jdu_html_91ef777909f89447.jpg)

When fetching tweets tagged #NBA, we use the search statement:

![](RackMultipart20210510-4-nd3jdu_html_22a41ee2fd91863d.jpg)

When obtaining the content of multiple accounts, we also select gettimeline to select multiple specific users at the same time.

![](RackMultipart20210510-4-nd3jdu_html_67df2588bed4768d.jpg)

**3. Results**

I**. ![](RackMultipart20210510-4-nd3jdu_html_9f287fb524015cb3.jpg) ![](RackMultipart20210510-4-nd3jdu_html_89a40b479601d799.jpg) James personal Twitter account content**

It can be clearly seen from the figure that the number of average annual tweets of James is generally on the rise. It will reach its peak in 2019 and 2020. It shows that it is paying more and more attention to the role of Twitter as a social media channel, and to the role of Twitter in expanding its influence.

It can be seen from the frequency of words appearing in James&#39; Twitter text in the picture that there are more texts related to personal image, occupation and competition in his Twitter, such as &quot;striveforgreatness&quot;, &quot;game&quot; and occupation, &quot;love&quot; Words related to emotions such as &quot;proud&quot;, &quot;proud&quot;, and &quot;happy&quot;, and terms such as &quot;guys&quot;, &quot;bro&quot;, and &quot;brother&quot; are related to appellation. It can be seen that most of James&#39; tweets discuss or express professional-related topics Or emotions, not just personal social media, the connotations of these texts are consistent with James&#39; personal image and performance on the court.

![image](https://github.com/VincenCHEN-github/Data-mining/blob/main/results/%E5%9C%96%E7%89%87%201.png) 

![image](https://github.com/VincenCHEN-github/Data-mining/blob/main/results/%E5%9C%96%E7%89%87%202.png)


II **.NBA hashtag twitter content**

On the other hand, from the discussion under the NBA hashtag, it can be seen that most of the text is related to the game, such as team information, season, basketball, etc. Compared with James&#39; personal Twitter account, it focuses more on career The discussion of the game, rather than the expression of emotion, contains less subjective words. Observed from the word cloud, the text content of Twitter involves James to a large extent, such as mentioning &quot;KingJames&quot;, &quot;lebron&quot;, etc., which overlap with the Twitter in James&#39; account.

![](RackMultipart20210510-4-nd3jdu_html_bd5266b83259362b.jpg) ![](RackMultipart20210510-4-nd3jdu_html_cdd3e16e1485365b.png)

Comparison of NBA tags and James&#39; Twitter account

T ![](RackMultipart20210510-4-nd3jdu_html_e0c2aaa98f069655.jpg) ![](RackMultipart20210510-4-nd3jdu_html_a8a201d4c417bb87.jpg) he first is the nature of the push. It can be seen that James&#39; personal tweets and NBA topics account for most of the organic content. There are more replies in the NBA tab.

O ![](RackMultipart20210510-4-nd3jdu_html_5a3e4b06fd681d61.jpg) ![](RackMultipart20210510-4-nd3jdu_html_bc72f79aa2769b88.jpg) n the other hand, from the comparison of sentiment analysis, it can be seen that the sentiment of personal Twitter and topic discussions are similar in general, while the number of &quot;joy&quot; in James&#39; personal account is more than that of &quot;fare&quot;, while in discussions the opposite is true.

![image](https://github.com/VincenCHEN-github/Data-mining/blob/main/results/%E5%9C%96%E7%89%87%203.png)
![https://github.com/VincenCHEN-github/Data-mining/blob/main/results/%E5%9C%96%E7%89%87%2014.png)
![image](https://github.com/VincenCHEN-github/Data-mining/blob/main/results/5.png)
![image](https://github.com/VincenCHEN-github/Data-mining/blob/main/results/6.png)
![image](https://github.com/VincenCHEN-github/Data-mining/blob/main/results/7.png)
![image](https://github.com/VincenCHEN-github/Data-mining/blob/main/results/8.png)


III **.Twitter content of NBA official accounts in different countries**

On the basis of obtaining official Twitter accounts in different countries, we selected accounts from America, Europe, Asia, and Oceania and compared them at the same time. It can be seen that the number and frequency of account tweets in various countries are generally increasing. The increase in the number of tweets from the main account is even more pronounced.

![](RackMultipart20210510-4-nd3jdu_html_271bd3dbc374447a.jpg)

![image](https://github.com/VincenCHEN-github/Data-mining/blob/main/results/9.png)



**4. Conclusion**

First of all, NBA social media marketing consists of a combination of personal accounts and official accounts. Both the star personal accounts and the NBA official accounts have increased significantly. In the past few decades, the NBA has accumulated a more diversified fan base, changed the league&#39;s traditional game viewing mode, and began to move from live games and live TV to digital media channels, the most prominent of which is Twitter. Twitter has become the center of basketball fans.

The star&#39;s Twitter account focuses on information related to personal image, while the content of the official account is mostly to provide a discussion platform, which is conducive to content aggregation and expansion of influence. It is also more emotionally diverse, with no obvious emotional bias. It is like a central nervous system on which people from every corner of the world are sharing data analysis, highlights, jokes, condemnation and crazy talk. The NBA Twitter ecosystem includes professional gamblers, math geniuses, journalists, decision-making experts, die-hard fans, team public relations, rappers, government officials, many sportswear brands, cable news hosts, and current hot players.

And various organic and reply content to promote the interaction of fans can allow viewers to participate in sports events through social media in addition to watching football matches through Twitter, and other social media tools. And this NBA social media strategy is precisely the perfect business strategy.

The data we involved in this study are relatively scattered, and the variables studied are not very comprehensive. In future research, you can focus on the content of several Twitter accounts, compare them with the same variables and indicators, and use more intuitive visual images to divide and compare, and draw useful conclusions.
