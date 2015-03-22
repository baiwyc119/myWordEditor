# myWordEditor

A simple silo-free blogging tool that creates beautiful essay pages. 

#### Demo app

Here's the <a href="http://myword.io/editor/">demo app</a> for this project, MyWord Editor.

You can set up your own blogging environment and use it to host your writing and for other people, your friends, colleagues, members of a club, whatever you like.

#### It's radical software

My name is Dave Winer. I blog at <a href="http://scripting.com/">Scripting News</a>. I wrote some of the earliest blogging, RSS and podcasting software. 

These days blogging tools try to lock you into their business model, and lock other developers out. I have the freedom to do what I want, so I decided to take the exact opposite approach. I don't  want to operate a free public blogging tool and lock users in and make them dependent on me. Instead, I want to learn from thinkers and writers and developers. I want to engage with other minds. Making money, at this stage of my career, is not so interesting to me. I'd much rather make ideas, and new working relationships, and friends. 

So MyWord Editor is radically <a href="http://scripting.com/2015/03/19/mywordEditorWillBeSilofreeFromTheStart.html">silo-free</a>. 

#### How to clone this

This app runs on the user's computer, in a browser. It's a JavaScript app. It communicates via a simple API, with a <a href="https://github.com/scripting/nodeStorage">nodeStorage</a> server, that uses Twitter for identity and Amazon S3 for storage. That server, like the app, is open source. The first part of creating your own blogging system is to set up a nodeStorage server. 

Once you've done that, download the contents of the myWordEditor repository, and put it in a folder that's publicly accessible over the web. I like using S3 buckets, but you could put it in a folder on an Apache or nginx server. 

Edit the config.json file so that the <i>urlTwitterServer</i> string is the URL of your nodeStorage server. 

You can also change the default image for your users' blog posts, or you can leave it as-is, with a nice picture from Wikipedia of the Grateful Dead. 

Test the installation by logging on. Follow the <a href="http://myword.smallpict.com/2015/03/06/welcomeToMywordEditor.html">instructions</a> on the MyWord Editor blog.

