# WhatsApp Chat/Text Analysis
## About this project:
- The main goal of this project is to analyze the WhatsApp chat and represents it through charts and visuals.
- Project is live now and deployed on Heroku. visit
- This project can be used for individual as well as group chats.
​
## Idea:
1. Created a function that converts WhatsApp chat text file into data frame with columns name(['date', 'year', 'month', 'day', 'hour', 'minute', 'month_name', 'day_name', 'user', 'message', 'message_chars'])
​
2. Which Data you will get in this analysis
1. Sum
    - Chat starting date, the first entry in chat
    - Chat Ending Date, last entry in chat
    - Total Members in chat, only those who had sent at least one message
    - Total Messages, including messages, missed calls, media, links
    - Total Words of Messages, 
    - Total Media File Shared
    - Total Links Shared
    - Total Missed Calls
2. Bar chart of no messages sent by members
3. Bar chart of no messages sent by members with a mean line
4. Pie chart with no if messages sent in %
5. Pie chat of Who started and ended the chat most of the time
6. WordMap of most 75 words used in chat with stopwords and without stopwords
7. Box Plot of who sent the longest messages
8. Pie chart of most used emoji
9. Sunburt chart of members and their weekly messages(and yearly, monthly, weekly)
10. Line chart of Daily chat activity(same monthly, yearly) for all and individuals
11. Heatmap represents which has occurred more on given features
12. Table of 5 longest messages in the entire chat
13. Table of 5 Longest messages of highest chat happened on a single day
14. Table of all shared links in chat
    
## Charts used to represent data:
    - Bar, Line, Box, WordMap, Sunburst Heatmap
    
## Library used
   - **streamlit** : for web application
   - **matplotlib**: for charts 
   - **plotly** : interactive charts
   - **pandas**: for creation of dataframe
   - **PIL**: opening image file 
   - **re** : regular expression
   - **urlextract**: for extracting URLs from chat
   - **collections**: for counting each words
   - **word cloud**: creating word map
   - **emoji**: extracting emoji from chat
   - **warnings**: ignore warnings
​
# Code is written in sublime in three files
- **app.py** : main file
- **dataset.py**: for generating dataset
- **functions.py**: user-defined functions as required
​
#### Project Files link: https://github.com/Vibe30/WhatsappTextAnalyze/
​
# How to use:
1. To use this web app first you WhatsApp chat text file.
    - You can try your Whatsapp or any individual or group chat this is 100% SAFE and SECURE, I don't have access to this web app. So, feel free to use it.
    - To export your chat: follow the steps given below:
        - Open your WhatsApp on mobile only
        - Open any chat
        - Click on three vertical dots (upper right corner)
        - Click on More
        - Click on Export Chat, proceed with Without Media
        - Now save this file anywhere you want.
        
2. Now, visit at 
3. To see details of how it works click on the plus icon '+', and click again '-' to close
4. Browse your file or drag and drop it in the file box.
5. Once your file has been uploaded all members' names will be visible in the dropdown menu, By default select All, if you want to analyze for an individual member then select that member and click on 'Show Analysis'.


# Some Snapshots:
![164450540-f0700c3e-c0bb-47a7-af01-2b23b71e2782](https://user-images.githubusercontent.com/19228512/207432701-538bf0f1-e8d7-4467-998b-5c8215b5ebb5.jpg)


![164450748-aeb5c4ae-4030-48bb-a3a8-c63b6e0fde77](https://user-images.githubusercontent.com/19228512/207432769-5dfa185e-9a15-422e-bdd7-b58b30bf9968.jpg)

![what4](https://user-images.githubusercontent.com/40932902/164450755-c8215423-6c23-47bd-a70c-7369b1533237.png)


![what5](https://user-images.githubusercontent.com/40932902/164450758-3a3b8a72-4651-467d-8b95-d3008c07c519.png)


![what6](https://user-images.githubusercontent.com/40932902/164450759-08a12997-5d06-4f50-9e29-fc272dd28523.png)


![what7](https://user-images.githubusercontent.com/40932902/164450765-38aac503-87e4-4097-a1f2-6cdc89cdac81.png)


![what8](https://user-images.githubusercontent.com/40932902/164450768-d6712ba7-5ecb-4f7b-8d3d-9ebb2c1bc2cf.png)


![what9](https://user-images.githubusercontent.com/40932902/164450771-5ba10e9c-ab57-472a-b8bf-f783271c9056.png)


