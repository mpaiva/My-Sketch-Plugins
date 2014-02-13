# Getting Started with Sketch

##Overview

The [Sketch App](http://www.bohemiancoding.com/sketch/) by Bohemian Coding is a professional vector graphics app with a beautiful interface and powerful tools. 

As any newborn, it will take some time to get to a maturity level that we all expect it to get as a professional design application.

One of the great advantages of Sketch, like [Sublime Text](http://www.sublimetext.com/), it has the ability to install open-source plugins written by great people that advocates posting their code on GitHub. 


##The goal here is..
1. To get you started with Sketch by leading you to some quick tutorials, 
2. Most importantly, setup a quick workflow where you will be able to install plugins in Sketch by - simply - clicking on the **Clone in Desktop** button on Github.

I'm aiming this article on designers that are not so familiar with GitHub's workflow. Hopefully we can find ways to get designers using GitHub in a collaboratively manner. 

##Quick Requirements
**Mac Only** - First off. Windows users, at this point, the [Sketch App](http://www.bohemiancoding.com/sketch/)  is only available for Mac.

**Get a GitHub Account** - Other than having the Sketch app installed, you will need to have a [github account](https://github.com/join) if you don't already have one.

**GitHub App for Mac** - Download the [GitHub app for Mac](http://mac.github.com/) and make sure you move it to your Applications folder. We will use it to create the plugin repository in your machine.

##Learning Sketch
I have have watched way too many tutorial videos about this app and - by far - here's [the most comprehensive walkthrough video](http://youtu.be/wIodpWdvqaU) about the Sketch app by JawnMercenary - quick and effective.

Other resources to get you using Sketch like a pro:

* [Sketch Tips & Tricks Blog](http://sketchtips.tumblr.com/) by Bohemian Coding.
* [Sketch App Sources](http://www.sketchappsources.com) - Cool place for resources and tutorials.
* [Sketch Commands](https://github.com/bomberstudios/sketch-commands) - A collection of script commands.
* [Sketch Templates](https://github.com/search?q=%40nvk+sketch) by Rodolfo Novak.
* [Sketch Gems](http://www.sketchgems.com/category/free-gems/) - Free templates by SketchGems
* [Brilliant Sketch](http://brilliantsketch.com/) - by Indonesian designer [@kuswanto](https://twitter.com/kuswanto) 
* [Hey, Designer!](http://heydesigner.com/sketchapp/) - SketchApp category

##Installing Plugins
###The conventional  way is:

1. to find the plugin folder for the Sketch app;
2. then copy the downloaded plugin folder into it.

This involves downloading a zip file, exploding this file, moving the folder to a hidden Library folder in your Mac - each time you need to install a plugin - which for some folks may be complicated.

###The quickest way:

1. Click on the "Clone in Desktop" button on GitHub - and voilá!

You will need get a few things setup once and you will be good to go anytime you need to install a new plugin in the future.


###Step 1 - Finding Sketch's Plugins folder

#####Go to Folder...
Open Finder, the navigate to `Go > Go to Folder...`

![Got to Folder](http://cl.ly/image/3z2L3q251h3w/Image%202014-02-12%20at%202.28.44%20PM.png)

#####Populate folder field
Enter the following path and hit the `Go` button

	~/Library/Containers/com.bohemiancoding.sketch/Data/Library/Application Support/sketch/Plugins

#####Create new folder
Create a new folder - inside `Plugins` - called `My Sketch Plugins`, as follows:

![Create new folder](http://cl.ly/image/2D0r1b0t051t/Image%202014-02-12%20at%202.53.28%20PM.png)

#####Create a Favorites shortcut
Drag this new folder onto the Favorites section of your Sidebar. This will help you creating the repository in the GitHub app:

![Creating a shortcut](http://cl.ly/image/0G191W0b3w3P/dragToFavorites.gif)

####From this point on, I'm assuming that:

1. **You have already installed the GitHub app** 
2. AND have signed into your GitHub account under **Preferences** <kbd>Cmd + ,</kbd>

###Step 2 - Create a New Repository
Hit <kbd>Cmd + N</kbd> or go to `File > New Repository...` to create a **New Repository**

![Create New Repository](http://cl.ly/image/1N2o0W271R22/Image%202014-02-12%20at%202.05.19%20PM.png)

The following dialog will popup, add the `Name`, `Description` as follows.

![Choose path](http://cl.ly/image/2n2E2R2D1t13/Image%202014-02-12%20at%203.28.57%20PM.png)

##### Important step ahead
For the `Local Path` you will need to select the path carefully: 

1. Go to your Favorite path "My Sketch Plugins"  
2. **Then choose its *PARENT FOLDER* `Plugins`**.  

![Choose the parent folder PLUGIN](http://cl.ly/image/2x162O1q110g/Image%202014-02-12%20at%204.32.11%20PM.png)

#####Push to GitHub option
Make sure to **check** the `Push to GitHub` option, this indicates that you will have a backup on GitHub.

#####Create Repository button
Then hit the `Create Repository` button. 

#####Repository already exists?
Since we had already created a folder with the same name, GH app will need to confirm that you want to use the same folder. Hit the `Add` button and go on.

![Repository already exists](http://cl.ly/image/2j1p1y2C0t1x/Image%202014-02-12%20at%204.34.23%20PM.png) 

##### Repository created
You should see an empty state screen for your new repository on GitHub.

If you go into your [GitHub](http://github.com) account you will see the new repository under the **Repositories** tab

![New repo on github.com](http://cl.ly/image/11402j0R053a/Image%202014-02-12%20at%203.37.10%20PM.png)

###Step 3 - Find some cool plugins
Since plugins for Sketch are written in JavaScript, you will find plugins anywhere on the web, but most likely, the large majority will be on GitHub. One particular resource on GitHub is [bomberstudios](https://gist.github.com/bomberstudios). They have compiled a great list of Sketch plugins into the following Gist:

####[https://gist.github.com/bomberstudios/7694497](https://gist.github.com/bomberstudios/7694497)

Thanks to the folks at Bomber Studios!
 
###Step 4 - Cloning a plugin into your repository
#####Lorem Ipsum plugin
As a simple example, I will install the [Lorem Ipsum Plugin for Sketch](https://github.com/brandonbeecroft/Lorem-Ipsum-Plugin-for-Sketch) by [brandonbeecroft](https://github.com/brandonbeecroft)

#####Clone in Desktop button
Once in the plugin's main repository page, simply click on the `Clone in Desktop` button. 

This will **launch the GitHub Desktop** App, you may be alerted by your browser that the link is trying to launch your desktop application, you may accept it. 

![Click on the Clone in Desktop button](http://cl.ly/image/142M042i2w2L/CloneInDesktop.png)


<<<<<<< HEAD:GettingStartedWithSketch.md




=======
>>>>>>> e90c5b724a412f885a25e4e54238991a5d3f83fb:README.md
###Step 5 - Select your Favorite shortcut

The GitHub application will prompt you to select a location to place your cloned folder. 

#####Choose the "**My Sketch Plugins**" folder from your favorite sidebar

as follows then hit the `Clone` button.

![Select Clone location](http://cl.ly/image/2D1u2g2j2a2B/Image%202014-02-12%20at%204.13.35%20PM.png)


---

###Step 6 - Test the Plugin

#####Let's test the installed plugin on Sketch...
Go to your Sketch app, select the Text tool set the text frame area on the artboard, then check out the Plugin menu, as illustrated below.

![LoremIpsumTest](http://cl.ly/image/1Q1h0O2S0E35/testingLoremIpsum.gif)

---

###Step 7 - Push your changes to GitHub
<<<<<<< HEAD:GettingStartedWithSketch.md
After all this work, you will appreciate the power of code sharing a bit more. I'd recommend you commiting your changes to GitHub for a couple of reasons:
=======
After all this work, you will appreciate the power of code sharing a bit more. I'd recommend you committing your changes to GitHub for a couple of reasons:
>>>>>>> e90c5b724a412f885a25e4e54238991a5d3f83fb:README.md

1. You will have a backup of your plugins;
2. If by any chance you install the Sketch app in a new machine, you can always download all your plugin collection very quickly;
3. You collaborate your plugins with your team members;  

#####Go to your GitHub Desktop application

Once you go to your repositories, you will see the plugins you have installed on your main list of repositories. 

<<<<<<< HEAD:GettingStartedWithSketch.md
#####Select the My SKetch Plugins repository
=======
#####Select the My Sketch Plugins repository
>>>>>>> e90c5b724a412f885a25e4e54238991a5d3f83fb:README.md
All of the plugins you have installed is located inside in your **My Sketch Plugins** repository.

#####Select the Changes tab
The `Changes` tab on the left side will display all the changes that have occurred within this repo.  

![](http://cl.ly/image/2p0q0s2y1w1a/Image%202014-02-12%20at%205.44.33%20PM.png)

1. Enable the `Commit & Sync` option if it's grey ![](http://cl.ly/image/3E321e1k3z1t/Image%202014-02-12%20at%205.47.18%20PM.png) - this should be green.
2. Enter a `Summary` and `Description`
3. Check the `Select All` checkbox
4. then hit the `Commit & Sync` button to push your changes to the GitHub server;

#####Cheers!
Your team members should now be able to see the great plugins you have installed.


#Conclusion
I know I could have created a single-level plugins folder, but I simply didn't want to either mess with the application's plugins folder permissions for obvious reasons nor have a repository on my Github called "Plugins"

With this structure, you should be able to keep things organized in a way that you can share your plugin repository with others.


Please drop me a line or do a pull-request if you would like to expand this forward.

<<<<<<< HEAD:GettingStartedWithSketch.md
-end
=======
-end
>>>>>>> e90c5b724a412f885a25e4e54238991a5d3f83fb:README.md
