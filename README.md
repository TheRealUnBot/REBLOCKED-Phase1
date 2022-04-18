# REBLOCKED Phase One
## What is REBLOCKED?
REBLOCKED is a small but popular and open source website that acts as a way to help stop boredom at school. It has around 25 games that work with just the website (located in the REBLOCKED folder) and another 25 games that work with the modified Alloy proxy (located in the Alloy folder) that allows for multiplayer, and unlimited online access.
## How do I run it?
Note: These commands are for linux but to run on windows is pretty straight forward anyways.
1. Install Mono and NodeJs
~~~
sudo apt install nodejs
~~~
[Go here to learn how to install Mono](https://linuxize.com/post/how-to-install-mono-on-ubuntu-18-04/)

3. Unzip both directories
~~~
tar -xvf reblocked-main.tar.gz
tar -xvf alloy-reblocked.tar.gz
~~~

5. Go into the REBLOCKED directory, edit js/index.js to match the url of Alloy you are going to run next and run Main.exe using Mono.
~~~
cd reblocked-main
mono Main.exe
~~~

7. Exit the REBLOCKED directory, go into the Alloy directory, and edit Config.json to set firewall, port number (from last step), and proxy directory name.
~~~
cd ..
cd alloy-reblocked
sudo nano config.json
~~~

9. Run index.js using NodeJs
~~~
node index.js
~~~

11. Go to localhost to see REBLOCKED

## But what if I wanted to edit the files?
You can edit Main.cs all you want and then you just have to run the command below to compile: 
~~~
csc Main.cs
~~~

You can also edit index.js all you want, just make sure to stop all instances and then rerun the command:
~~~
node index.js
~~~

You may also edit the webpage files, which should update as soon as you save and reload.

Note: Remember to still give credit to the creators in your edited REBLOCKED!

## What's Next?
Well Phase 2 is on its way with better blocking and posiiblly free Wifi but it requires and Raspberry Pi 4 or 3 to use!
## Credits

###### Creator and Main Programmer: 
+ Unknown Bot
###### Secondary Programmers and Design: 
+ Mongoose
+ Unnamed
