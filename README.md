# youtube-recommender
Create a simple YouTube channel recommender system.

## Background
Every YouTube channel lists other channels that users may be interested based off the channel they are currently viewing.

## Task
Write a python script that takes in a YouTube channel as an input and displays multiple channels that users may also like.
Channels display similar channels on their home pages, so pulling HTML data would be a good place to start. 
Some specifics to include:
1. You should display the number of subscribers for every channel displayed.
2. Utilize the pprint library to display information in an organized manner. 
3. The number of recommended channels is up to your discretion.

## Extras
Get Creative! 
* To make your recommnder system more accurate, you could get all the similar channels from a specific channel, then check each of those channels' "recommended" lists to see if there are any matches with the original set. Channels that appear more often are likely to be more popular!
* Add an option for the user to input more than one channel, then check to see if those channels share any recommended channels. The more data, the better.
* Most popular channles list their social media links (Twitter, Facebook, etc.). Scrape these from their "About" sections and display them.
* Add an option for the user to input a genre to specify results. Many channels have a lot of content. For example, Vsauce has many science-oreinted videos, but suppose the user is only interested in videos relating to mathematics. Add genre functionality!
* Add anything you think is valuable lol.
