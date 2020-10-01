# Keeping Glitch Projects Online 24/7 ( ᵔ ᴥ ᵔ )

Recently, [Glitch](https://glitch.com) stopped accepting requests from [UptimeRobot](https://uptimerobot.com) to keep projects online. They're now only holding 24/7 projects with the $10/month premium plan. With that type of price, you could pay for a real VPS and not need to use Glitch.

-------------------------

### Method 1 (Transfer from Glitch to Repl.it)
    
  To transfer your project from [Glitch](https://glitch.com) to [Replit](https://repl.it), create a free Replit account and then go to the [Glitch Import Page](https://repl.it/glitch). You will have to use Repl.it as your IDE now.
  
  1) Make sure your Glitch project is public (so repl.it can copy it) and paste the `glitch.com/edit/#!/project-name` link into the box. 
  
  2) The language automatically defaults to Linux Bash. [Change the program language](https://i.imgur.com/KSlWcnh.png) to Node.js.
  
  3) When everything is set up, you can enable UptimeRobot for your Repl (using [this domain](https://i.imgur.com/ew5swCR.png)) since they don't block it. And, that's it! Your project will now be online 24/7.

-------------------------

### Method 2 (Using Repl.it as a Pinging Service)
This method will let you continue using Glitch as an IDE, but **it's against Glitch terms of service** so I'm not responsible if you get in trouble for using it.

1) Go to the [Github Import Page](https://repl.it/github) and put `github.com/whasonyt/glitch247` in the box. [Change the program language](https://i.imgur.com/KSlWcnh.png) to Node.js.

2) Find [this part](https://i.imgur.com/wZBHu0O.png) of the code and add your own sites in. If you're using this for Glitch projects, enter the `project-name.glitch.me` domain.

 3) When everything is set up, you can enable UptimeRobot for your Repl (using [this domain](https://i.imgur.com/ew5swCR.png)) since they don't block it. And, that's it! Your project will now be online 24/7 by using Repl.it as the middle-man.
 [![Run on Repl.it](https://repl.it/badge/github/whasonyt/glitch247)](https://repl.it/github/whasonyt/glitch247)