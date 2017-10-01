this file is to show all the optmization and changing in the original file to make the speed changed from 27 to 95 out of 100
===================================================================================

Getting start:-
to open the website from github:

1- open this link https://github.com/iaialm/frontend-nanodegree-mobile-portfolio

2- go to Settings > scroll down to GitHub Pages > copy the link 

3- open https://developers.google.com/speed/pagespeed/insights/

4- paste the git hub link in the URL box > press analize 

then you can see scors for both Mobile & Desktob 


you can do the same steps to check the Pizza Website by this link https://iaialm.github.io/frontend-nanodegree-mobile-portfolio/views/pizza.html


==============================================================================================

To open the website in local host :

1- go to https://www.python.org/downloads/ and download python and install it

2-go to https://ngrok.com/download and place the downloaded file in your project folder

3-open command line and and  
type in this command to start a live server for your project :

# On Mac and Linux
python -m SimpleHTTPServer 8080

# On Windows
python -m http.server 8080

4- now if you open localhost:8080 you should see your website

5-open the ngrok file after placing it in the project directory and type in the following:
ngrok http 8080

6- It will then give you a live link that you can use and paste in pagespeed insights to checkout how your optimization is working

===========================================================================================================================

the OPTMIZATION process:

1/ index.html
I optimised pizzaria image and resized it 
I moved the JS link the end of the page 
I use in line CSS for style.css instead of having it in different file to make the website faster .

<link href="css/print.css"rel="stylesheet" media="print">
==============================================================================================
2- views/js/main.js

I minify the JS 
==============================================================================================
pizza.html

I optimized the 2 images and resized them 
I moved the JS link the end of the page 
I use in line CSS instead of having it in different file to make the website faster .
===============================================================================================

By: Amira Almurayshid
