EASYBINGO

A quick and easy way to make a randomized, custom printable bingo card from whatever data set you'd like to provide. Uses randomseed.js to allow verification of cards through consistent custom random seeds, if you really want to take bingo that seriously. 

IMPORTANT NOTE

The Quintus game engine, or at least, the site hosting it, has a faulty SSL certificate at the moment. That means EasyBingo won't work over https: connections because it won't be able to load the Quintus engine. Sorry, people who like security. You could probably host the entire engine yourself of course.

HOW TO USE

Edit /scripts/bingoData.js to add whatever data you want. I'd recommend at least 30 distinct phrases, but more is always better. Any less than 25 and the script will get stuck in an endless loop, however.

Change index.html however you like, at your own risk. Optimize my JavaScript if you want, this was literally my first time using it.

logobg.png is displayed behind the bingo card to give a tiny amount of visual substance. It's going to get obscured by the squares but it really ties the page together, y'know?

I'd appreciate it if you kept my name at the bottom but if it bugs you that much you can remove it.
