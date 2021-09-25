Challenge Name:  Global

Category: Web Security
Level:  medium 


Challenge Description

I think we have mutual things.

Link:
http://ec2-35-158-236-11.eu-central-1.compute.amazonaws.com/global/

Answer:

so we will open the link and we will find the page look like this :

![index](https://user-images.githubusercontent.com/56412281/134765797-037176fb-c854-4fa2-984f-53b7319f5015.png)

and if we look to the source code we will find that;

![source](https://user-images.githubusercontent.com/56412281/134765814-1e7767be-e5c3-42a7-bf04-77c39353b4a9.png)

we will not find any thing there except the link to nothing 

so after some search its apper to be a rfi remote file include

and here some link about the subject
https://www.imperva.com/learn/application-security/rfi-remote-file-inclusion/

so we will use some tool the first one in ngrok and its simply make a url for your own localhost that you can use
and here a link to download and read the doc about it 

https://ngrok.com/download

and the seconed one is simple http server with python to run a local server  and here a link about the subject

https://www.pythonforbeginners.com/modules-in-python/how-to-use-simplehttpserver

so we will use the ngrok to open the tunnel 

![ngrok](https://user-images.githubusercontent.com/56412281/134765803-cdf8c653-d2fa-4446-92e2-c5a5a9b8a759.png)

and we will use the python on the same port 

![pyhto](https://user-images.githubusercontent.com/56412281/134765808-3c38e8d8-260c-4294-8018-2ff355d74ad0.png)

and after that we will create a file in the same dir call phpinfo.php

![inf](https://user-images.githubusercontent.com/56412281/134765802-431dac72-5502-4047-a8b6-3e30b5074992.png)

and cahange the pramert in the global page to the new link from ngrok follow by the file we create

![index2](https://user-images.githubusercontent.com/56412281/134765799-de4c4a33-3313-4550-871a-4b32b3528102.png)

so the url will be like ?page='the ngrok link'/phpinfo.php

and the result will be


![a](https://user-images.githubusercontent.com/56412281/134765837-0107d73b-dd2c-46cf-8fa1-7b5a67be3a93.png)

and here we catch all the info so we need to get the flag we will try to see the source code of the main page

by create anthor file call show look like this 

![show](https://user-images.githubusercontent.com/56412281/134765809-1cd78276-bbc6-4fb3-b37d-71d501c71940.png)

and we will use the same method and here the flag 

![flag](https://user-images.githubusercontent.com/56412281/134765792-4e8d8814-fd56-4de1-9b58-002fb18a6b05.png)

this was a good one until the next one have agood day (:

