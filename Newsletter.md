
Challenge Name:  Newsletter


Category: Web Security
Level: easy 

Challenge Description :
the administrator put the backup file in the same root folder as the application,
help us download this backup by retrieving the backup file name

Answer: hgdr64.backup.tar.gz

Solution:
first we will open the link for the challenge we will see simple form use post method look like this

![inde](https://user-images.githubusercontent.com/56412281/134555263-a1f6225f-111f-48da-8b0e-d8ead37a2d24.png)

we will look to the source page but we will not find somthing interesting there

so we will fill the form and the the response we will see something like this :

![index2](https://user-images.githubusercontent.com/56412281/134555269-3dcfd4fb-b299-4879-8c92-fd3023cd38ce.png)

and now we will use burpsuiet to see what is gooing on so we will see 

![burp](https://user-images.githubusercontent.com/56412281/134555281-d8401fd8-e013-4683-a1c1-24b10dcf7790.png)


then we will send this to the repeter to test it over there

![res](https://user-images.githubusercontent.com/56412281/134555288-16d62d1a-fbac-47d2-b94f-1b389134ffeb.png)


and here we will find the response we recive back from the server and now we will try to modify our payload

we will get 

![res2](https://user-images.githubusercontent.com/56412281/134555326-2fba057d-67ab-497e-a771-5297f201419a.png)


so its apper to be Command Injection and here an extra link to know about the issue 
https://owasp.org/www-community/attacks/Command_Injection
so try again to modify it again and see we will find the flag as simple as that

![flag](https://user-images.githubusercontent.com/56412281/134555351-fe7380f6-c678-4f77-959e-c58f3c98dc17.png)

so have a good one untile the next one (: 


