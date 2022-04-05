# SMU-IS434 Social Analytics G2T3 with 191 Labs

Business Problem
1) What are the trends in the second hand luxury market?
2) What are the popular online second hand luxury goods markets?
3) What do social media conversation reveal about the market?

Dataset used
Second hand luxury shop
1) lovelotsluxury 
2) Madam milan

Luxury Brand forum
1) Bagaholic

Tools used
PhantomBuster - To scrape data such as 1st degree followers, post and comments data from the 3 instagrams 
SEOTool Excel - download images from excel after scrapping from phantom buster
AWS Rekognition - To extract demographic details of the instagram profile pictures  
Beautiful soup - Scrape data from the website such as the products, pricing, and whether it is available or has been sold
Python Library- we used VADER to perform sentiment analysis on the comments in bagaholic posts
Keyhole - To track profile and posts lotsloveluxury and madam milan instagram in interactive charts 
Gephi -  Identify common hubs and key opinion leaders / influencers that is known in the luxurious market 
TIBCO- To perform data visualization





Project Directory Structure

Note: Only the most critical files to our application are explicitly show. 

📦IS434_SOCIALANALYTICS_G2T3
 ┣ 📂Bagaholic
 ┃ ┣ 📂comments
 ┃ ┃ ┗ 📜Analysis on Forum.pynb
 ┃ ┃ ┗ 📜bag_comment_extractor.csv
 ┃ ┃ ┗ 📜bag_post.csv
 ┃ ┃ ┗ 📜comment_edited.csv
 ┃ ┃ ┗ 📜comment_sentiment_final.csv
 ┃ ┃ ┗ 📜comment_sentiment.csv
 ┃ ┃ ┗ 📜original_post_edited.csv
 ┃ ┃ ┗ 📜Sentimental Analysis - By Brand
 ┃ ┣ 📂Wordcloud
 ┃ ┃ ┗ 📜chanel.csv
 ┃ ┃ ┗ 📜Chanel.png
 ┃ ┃ ┗ 📜dior.csv
 ┃ ┃ ┗ 📜Dior.png
 ┃ ┃ ┗ 📜gucci.csv
 ┃ ┃ ┗ 📜Gucci.png
 ┃ ┃ ┗ 📜hermes.csv
 ┃ ┃ ┗ 📜Hermes.png
 ┃ ┃ ┗ 📜lv.csv
 ┃ ┃ ┗ 📜LV.png
 ┣ 📂LoveLotLuxury Dataset
 ┃ ┣ 📂Followers (Instagram)
 ┃ ┃ ┗ 📜result.csv
 ┃ ┃ ┗ 📜result.json
 ┃ ┣ 📂Json
 ┃ ┃ ┗ 📜text.txt
 ┃ ┣ 📂ProFile Picture
 ┃ ┣ 📂Website
 ┃ ┃ ┗ 📜LotsLoveWeb.csv
 ┃ ┃ ┗ 📜LovelotsLuxury Website Scraping.pynb
 ┣ 📂Madam Milan Dataset
 ┃ ┣ 📂Followers (Instagram)
 ┃ ┃ ┗ 📜text.txt
 ┃ ┣ 📂Json
 ┃ ┃ ┗ 📜text.txt
 ┃ ┣ 📂ProFile Picture
 ┃ ┣ 📂Website
 ┃ ┃ ┗ 📜MadamMilan Website Scraping.pynd
 ┃ ┃ ┗ 📜MdmMilanWeb.csv
 ┣ 📂Tibco
 ┃ ┣ 📜Tibco Analysis1.pdf
 ┃ ┣ 📜Tibco Analysis2.pdf
 ┣ 📜README.md



Authors
Teo Jia Cheng           : jcteo.2019@scis.smu.edu.sg
Lim Weilun              : weilun.lim.2019@scis.smu.edu.sg
ian Leong               : ian.leong.2019@scis.smu.edu.sg
Cheryl Chee Xue Qi      : xueqi.chee.2019@scis.smu.edu.sg
Wong Shi Ting           : stwong.2019.2019@sis.smu.edu.sg


