# Price-Tracker
This is a simple price tracker app using python that regularly compares the prices of your favorite stuff on amazon and sends you a customized notification email to tell you if the prices fell down. This uses python and implements beautiful soup, smtplib, time and requests modules and libraries.

# How to run it on your local machine?
To begin with,you have to save the priceTracker.py code in your pc and then make few changes in them. If you want to track prices of a different product other than mentioned here, then simply change the amazon link with that of your product. (Note this would only work for products available in amazon as in this code we are scraping the data of amazon page, for any other site you have to make few changes in the scraping part and then it should work fine).

Secondly, replace sender@gmail.com with the mail id you want to send the mail with and receiver@gmail.com with the mail you want to receive the mail in. For the password of the sender part, you first have to complete the 2 step verification process and then generate a Desktop password for the mail and paste it in the Password section Ref. And Voila it's done!
