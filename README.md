# The-Price-is-right-

Have you ever wanted to know if you had a bid just a little off?
What about an Ask thats just a little to high?

Well look no further, all you need to do is run this bad boy and tell it

Your nation name this is used for the useragent
What mode do you want to use? Ask/bid Ask mode will check for any bids with in a set range of your ask.  Bid mode will do the same but search for asks
How close would you like to search? You can search anywhere from .01 away to 100 away
Would you like live out put? Yes/no  This is great for people who have way to many sitting asks and bids as it will print out links as it finds them.  The one down side is during the live output it will not delete the duplicates.  If you have this on or off it will still make the txt file at the end and deletes dupicates. 



This does use the API so please do not run it with other NS based programs running, you can browse NS while this is running and will not run into any issues. 


To install you will need to install a few dependicies.  To do that make sure you have pip installed and then type 
pip install beatifulsoup4 
and
pip install lxml
