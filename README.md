# Mission_To_Mars.

### Overview

This project consisted of a Python script to scrape text and images from various websites discussing Mission to Mars. Then, I created a Flask web application with a rendered HTML template designed using Bootstrap to display all the data in a central location without gathering it manually. The data scraped and displayed was stored in a non-relational Mongo database. Additionally, I connected the scraping script so that the scraping occurred again, the database got updated,  new data. This button only works under the condition that these web pages don't change the HTML components I used for scraping.



<img width="895" alt="MARS 1 1" src="https://user-images.githubusercontent.com/81654454/126915464-e93d1cdc-89ae-4926-97ef-f6d77e973e72.PNG">



#### Code From Iphone


<img width="439" alt="Code_from_Iphone" src="https://user-images.githubusercontent.com/81654454/126915502-1e93feeb-b625-49ec-9ae5-0f7e68086b09.PNG">




The scrape included a news_title with its brief explanation, a featured_image, a table HTML component stored in facts, and four picture thumbnails, with their titles, of the different Mars' hemispheres held in hemispheres.






The database will be updated, and each time new data is scraped, it will be saved with a "last_modified" date to know when was the last time, as represented at the bottom of the query results.



<img width="589" alt="Mars_From_Iphone 1" src="https://user-images.githubusercontent.com/81654454/126915610-5d63d677-186d-4c62-aba2-9a6e81b41185.PNG">


<img width="843" alt="From_Mars_ 2" src="https://user-images.githubusercontent.com/81654454/126915650-578da191-cb7d-4104-851b-8056b65c4248.PNG">
