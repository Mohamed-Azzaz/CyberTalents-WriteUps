Challenge Name:  who am i?

Category:  Web Security
Level:  easy 

Challenge Description: 

Do not Start a fight you can not stop it

Solution:

when we open the challenge link we will find that

![index](https://user-images.githubusercontent.com/56412281/134576761-09af00d1-5589-45de-8e69-a9f1f33f57ac.png)

so we will take a look at the source code we will find 

![source](https://user-images.githubusercontent.com/56412281/134576818-fc60ce9a-d8de-4353-9173-544755179123.png)

after we have the user and the password we use it and have this 

![index2](https://user-images.githubusercontent.com/56412281/134576766-effb365c-dbf7-4811-b765-49c169140dac.png)

if we take a deep look we will find there is a cookie call authentication with some code in it 

so its look like url encoding (( this will come with practice )) so with any online decode for the url we will find
it have a base64 code in it so will use any online base64 decode we will find it is have 

![url](https://user-images.githubusercontent.com/56412281/134576858-8490575d-a9d6-46fb-aea4-4de0c39ffa26.png)


![base](https://user-images.githubusercontent.com/56412281/134576874-b7417936-a9af-4c04-b915-5c3208841cd8.png)


and we will use the same way use it to login=admin and encoded it with base64 and after that we will use url encoded

and change the cookie and save it and resend it and we will have the flag 

![flag](https://user-images.githubusercontent.com/56412281/134576885-ac38ebc8-c392-44d5-97e7-a16851f1f74d.png)

so untile the next one have a good one (:
