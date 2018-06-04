# faceme
A website application that lets a user find out statistics based on their news feed and information. 

*Notice: currently our application is still in development mode because making it public requires Facebook to review over it over an extended duration of time. Hence, this application only works for the developers, I and MJ Kim.

Two ways:

Short way

Go to our personal website (https://snfaceme.heroku.com)
If you try to login, it will not work because only developers have access. Hence, if you would like to try it on your facebook account, we will add you to the developers list and it will work the next time you login.
Long way (Recommended)

Download Mamp and our source code (HTML:JS)
Change the port value of apache to 8888 on MAMP.
Put all the files in HTML:JS to the htdocs folder found in "MAMP" folder.
Then, go to https://developers.facebook.com/ and create your own app. Select web.
Enter http://localhost:8888/ as your application website link.
Go to htdocs folder and open index.html (in code).
Replace the current app ID in the code with yours.
Should work. :)
