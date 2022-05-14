# Reflection for Outside the Grid #

I have to admit, this assignment left me incredibly frustrated.

There are several issues I could contribute this to. One being my inability to access the help that I needed. Due to a compulsory placement scheduled for another one of my units, I was unable to attend class to learn about static generators with my classmates and receive feedback on my progress. The second main contributor links back to my lack of understanding of the content material. Never have I been in a situation where my lack of experience and limited access to help have left me completely unable to work on an assignment.    

As seen in *figure 1* my inability to interpret the instructions on the *Modules* page meant I spent several hours attempting every combination possible (going beyond the bounds of the screenshot) to start the server for the static website generator so I'd be able to START the assignment. I couldn't even achieve this on my own and attempted to seek assistance from three people (fellow students and my tutor) through four different methods just to get STARTED. 

Eventually, with the help of my tutor, I was able to get the server runnning though at this point I still had no idea what I was doing. I read through the *Modules* page several times and watched countless tutorials to try and help me interpret the information we were provided but nothing seemed to click. It seemed that the very thing our tutor, Ben, had done to make this assignment easier had added a new layer of difficulty for me. There wasn't a signal tutorial that matched the way Ben had set out the static site generator for us which meant I couldn't interpret what information should go where and how I would get it to work the same across six pages (homepage.html, footer.html, head.html, base.html, index.md & styles.css) - alongside others which I had no understanding of - (node_modules, .eleventy.js, .gitignore, package-lock.json & package.json) the way I add with the last assignment across two pages (index.html & styles.css). I was completely stuck.

All I could was design a prototype for my page (see *figure 2*) but I couldn't even do that successfully. Due to my lack of understanding of markdown and its limitations, I designed a webpage that would create even more difficulties for me as I would soon encounter. 

It wasn't until I was able to speak with Ben online that I finally made some progress. Unfortunately, due to lack of time (on both our ends) rather than going through my prototype and making it markdown friendly, as we probably should have, we decided to go ahead with my design which meant overcomplicating the process ten-fold. Rather than using markdown, which was recommeneded for noobs like me, my design would need to be coded in parts across all six pages mentioned earlier. Ben, very kindly, set up the general format so that all I would need to do is add the content and edit the css but unfortunately that added more difficulties as well.

Because I had Ben set out the format, I wasn't able to develop a solid understanding of what effected what and how. This meant spending several more hours trying to decode what Ben had done (in terms of 'div's and using 'flex' css to format content rather than grids like we had in the last assignment) to try and develop some form of understanding of what was happening so I could write effective css. While I figured out most parts, I couldn't figure out everything which has meant that the spacing on my final website in a little weird in some spots. 

If there's one I felt proud of, it was the way I taught myself to use the *Inspect* function on Google Chrome to locate the css effecting certain content. After watching Ben do so during our call, I felt I should learn to do so myself. I don't feel I have mastered this feature yet, however, it has definitely helped being able to check what code is effecting what in a browser without permanently editing the code in VS Code. 

I certainly feel like I have a long way to go before I can say I'm in any way proficient at web design. This assignment has shown me just how little I fully understood from my work with html and css in the first assignment. I now know **of** the code but not know **how** to code. Still, that's a lot more than I knew going into this unit.

Thank you Ben for giving me the extra time and assistance I needed to complete this assignment. Without your help, I wouldn't have been able to submit. 



## Figure 1 ##
![what-am-i-doing-wrong](https://user-images.githubusercontent.com/100389308/168406136-b3f17251-cb7b-4f30-847d-4c29feae5508.JPG)

## Figure 2 ##
![prototype-1](https://user-images.githubusercontent.com/100389308/168406096-4042ba35-d8a1-4f64-bad7-5d5de4538198.jpg)







# 11056-project2

## 11056 Project 2 Starter

This is repo containing everything you need to start Project 2. All you need to do is clone this repository to your computer and start editing...

Make sure you refer to Canvas for more info.

## Install Elventy
From Terminal, navigate to the folder you saved the repository in:

Type `npm create`

or, if that doesn't work: `npm install --save-dev @11ty/eleventy`

## Test your site

Open Terminal and type: `npm start`

This will create a local server to test the website.

Go to: http://localhost:8080 to view your site

## Build the site

Run `npm build`

Open up your site folder and you'll discover a folder within it called `final-website` this is where your actual site files are located. 
