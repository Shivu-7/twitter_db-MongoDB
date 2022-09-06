# twitter_db-MongoDB

##### Task: using Mongo command line (please do not use MongoDB Compass) to write code to finish the challenge of “querying”. <img width="468" alt="image" src="https://user-images.githubusercontent.com/23645932/188757431-f73134fe-d1c7-41f7-b8c9-cc849c350ccf.png">


##### Task: Create a MongoDB database “twitter_db” that includes a collection called “tweets”. Add the file “tweets.json” (from google) to the collection. You can use MongoDB Compass to do that. It will take some time to upload the data.<img width="468" alt="image" src="https://user-images.githubusercontent.com/23645932/188757519-1449ed17-78c5-4764-b005-8e8134fa96ea.png">



##### Task: Again, use Mongo command line to write code to finish the following queries:
##### a.	Find the number of total tweets created by user.name “sarah”. 

 <img width="403" alt="image" src="https://user-images.githubusercontent.com/23645932/188757607-7b81ea46-e50b-415f-8f08-2b7992b62ff1.png">


##### b.	Retrieve the five latest tweets that were replying to the user with the user.screen_name “globeandmail” . You need to use find(), sort() and limit() to get the results. Your output should include only 4 fields: 1)_id, 2) the.user.screen_name of each replyer, 3) time of the reply, and 4) text of the replies. (the order of them does not matter ). 

<img width="414" alt="image" src="https://user-images.githubusercontent.com/23645932/188757623-15eb818b-0b92-4337-a722-78e9505024e0.png">

                    
##### c.	Retrieve top 5 users that have twitted the most – in your output you should show 1) their use.name, and 2) the total number of tweets posted by each of them. 
<img width="468" alt="image" src="https://user-images.githubusercontent.com/23645932/188757756-b727a88d-9a3f-48bf-80be-49dde65ae8f1.png">


Resulting collection->
<br>
 <img width="463" alt="image" src="https://user-images.githubusercontent.com/23645932/188757649-72be9f35-9216-476d-9398-88e7d16fd284.png">

