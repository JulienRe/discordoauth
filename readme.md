# Discord Oauth Script - [Login With Discord, PHP]

 # How To use it?
It's very simple! Just add this line of code in your file :
```include 'discord.php`;```
That's it! You've successfully added the oauth script to your code!
TO Make it easier, I've added a demo working of the whole script. Open it and adjust it to your needs.

 # How do I integrate it into my website
To use it, you will need a quick overview on how this script works. This is not a library, its more like a code snippet. Basically, once you include the file in your login file, you just have to call some predefined functions. This makes oauth for discord a breeze.
Like I mentioned, I've now added a demo - just fill in the details and you'll have a basic understanding of how it works.

# How does Oauth work?
After the user authorizes the application, a code is sent by discord to the Rediect URI. This script which is in your Reirect URI folder will grab the code sent by discord through a GET request and will POST it to the Oauth API along with your data to get an authorizaion token. This authorization token is again sent to the send to the Discord API (which depends on your required scope) to get the user data, which is then utilized by you, that is you make SESSIONS with the data you receieved.

Too confusing? Just use the demo!

# I have more doubts as on how to use it and I want to request more functions!
Join my server and DM me - Markis™#0227 your questions and I will sort them. Feel free to request for more functions :)

Server Link : https://discord.gg/GeTuFyN


