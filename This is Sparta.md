Category: Web Security 

Level: easy

Challenge Description: 

Morning has broken today they're fighting in the shade when arrows blocked the sun they fell tonight they dine in hell

Answer : {J4V4_Scr1Pt_1S_Aw3s0me}

Solution:

first we will open the challenge link we will see a normal login page looks like that:

![index](https://user-images.githubusercontent.com/56412281/133991237-f4e21d1a-a1aa-4e94-941f-361625a2f5e7.png)

and there is a big hint button when we hit it we see: 

![hint](https://user-images.githubusercontent.com/56412281/133991332-dfc04641-cbdb-4267-b21a-848cf43c2311.png)


so first thing we have to do is open the source code to what there and we will see :



![script](https://user-images.githubusercontent.com/56412281/133991455-c0b0ecc7-1463-4a94-a504-a9d3567ddec0.png)

and there is function check something but we don't know what it say :

![function](https://user-images.githubusercontent.com/56412281/133991410-fc14c04e-6a2f-4ae5-9c95-c33c10e08726.png)

so we will open the developer tool to see the first script because we can exploit it 

![inspect](https://user-images.githubusercontent.com/56412281/133991544-284eadea-41a3-4fa5-87ee-8f1d487dc2aa.png)

we will try to change the event handler to make it execute the code we want so we will test it first by change
the hint() function and add the alert(1) and see  

![execut](https://user-images.githubusercontent.com/56412281/133991557-4a8baa80-88bc-4f65-a185-e5dc561f8c7b.png)

and its done we can use this bug to bass the login 
we remeber that there is a function we don't know what it have but we will try to know that by alert(the array element)

![wrong](https://user-images.githubusercontent.com/56412281/133991586-a546ac81-c71c-4677-8c29-45947035ec69.png)

and its look like it use this function to check the credential so try again we will see

![cong](https://user-images.githubusercontent.com/56412281/133991603-57c5fab1-514f-42d6-ae60-4c35588c5c25.png)

so not yet try again 

![cred](https://user-images.githubusercontent.com/56412281/133991618-e802eeec-f27d-4dba-a992-5b507d22e193.png)

so now we have the credential to log so when we do that we will have the 

![flag](https://user-images.githubusercontent.com/56412281/133991644-0824a4b9-4da9-4ad7-8aa1-4d88d64233e8.png)


and here is the falg so until the next one have a good one (:
