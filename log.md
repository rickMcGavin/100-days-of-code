# 100 Days Of Code - Log

### Day 32: February 5, 2017
- [x] 25 minutes [Javascript Understanding The Weird Parts](https://www.udemy.com/understand-javascript/)
- [x] 100 minutes Javascript30 by Wes Bos
- [x] 50 minutes FCC Simon Game Challenge

**Thoughts**

I am absolutely starting to wish I had started [Javascript Understanding The Weird Parts](https://www.udemy.com/understand-javascript/) sooner. I am only on session 3, and it's just great information delivered in a very understandable way. Today was largely about comparison operators, and what operators take precedence over others, and in which direction they process (left-to-right) or (right-to-left). I definitely reviewed some things I knew regarding the equality operator and strict equality operator, but the instructor does a great job really digging in to how things work. I also didn't realize you could use comparison operators to set variables. The example given was:

name = name || "<your name here>";

I feel somewhat slow for not knowing this yet, but then again, I'm just now taking the course.

I did the Javascript30 day 1 challenge where you build a drum kit. I rather enjoyed this and learned a lot while I was at it. I was able to immediately apply it to my Simon Game by utilizing the same method for playing audio files.

I fixed the issue with my event listeners by just taking them out of a function. I have to get better at recognizing when I'm really frustrated with an issue, and changing gears. It might be best to work on a tutorial type of project or a video course to get my head right again. Also, the solution I'm looking for may pop up.

**Link to work:**

[FreeCodeCamp: Simon Game](https://github.com/rickMcGavin/simon)

### Day 31: February 4, 2017
- 200 minutes FCC Simon Game Projects

**Thoughts**

After my first 4 pomodoros (200 minutes), I can say I'm quite frustrated. I easily solved the issue I'm having right now in jQuery. However, I'm quite dead set in building this with Vanilla JS. I am really struggling though.

I've created a function that will be called numerous times, and each time it's called, I'm setting another event listener, which is inflating my player's array of moves. In jQuery, I did have a similar issue with the tic-tac-toe game, which I easily solved by just adding .unbind("click") before using jQuery's .click() method.

This does not seem nearly as easy in JavaScript. I tried using removeEventListener(), but that requires you to name the function. When I name the function, and move the code inside the named function, and run a named function instead of an anonymous function, I do not get the same results.

After much difficulty with it tonight, I just am not understanding. I guess I will have to battle it another day.

**Link to work:**

[FreeCodeCamp: Simon Game](https://github.com/rickMcGavin/simon)


### Day 30: February 3, 2017
- 25 minutes [Javascript Understanding The Weird Parts](https://www.udemy.com/understand-javascript/)
- 200 minutes FCC Simon Game Projects

**Thoughts**
I'm 25% of the way through JavaScript understanding the weird parts. It has been a welcome refresher that deepened my understanding of the scope chain and how operators work so far.

I figured out the fairly challenging problem I was having with the Simon game, and the elements all lighting up at once. Once, I figured out how to solve that with a recursive function (very cool), I realized I was having trouble with the player's turn. When the player clicked the buttons, nothing happened! I was using getElementById(), and changing it to querySelector seemed to solve all my problems. I can't imagine why though, and I can't find anywhere that says this is a known issue.

**Link to work:**

[FreeCodeCamp: Simon Game](https://github.com/rickMcGavin/simon)

### Day 29: February 2, 2017

**Today's Progress**
- 1 hour [Understanding Flexbox: Everything You Need to know](https://medium.freecodecamp.com/understanding-flexbox-everything-you-need-to-know-b4013d4dc9af#.w26mj27k9) by Ohans Emmanuel
- 50 minutes [Javascript Understanding The Weird Parts](https://www.udemy.com/understand-javascript/)
- 50 minutes FCC Simon Game Projects

Still have to give some credit to the flexbox article above. It's been immensely helpful in helping me better understand flexbox. I practiced by making some nav bars. I love how clean and easy it was to build a nav with flexbox.

After being fairly confused by Kyle Simpson's [YDKJS](https://github.com/getify/You-Dont-Know-JS) book 3, I decided to load up Understanding the Weird Parts. It's been a very helpful video course so far. I think I definitely should have started with this then moved to YDKJS, but either way, I'm learning JavaScript better.

The Simon game was smooth sailing until now. I'm trying to make the the computer move play the button presses, and it's just not working correctly. I don't know why, but setInterval just gets progressively faster every time it's ran. I will figure it out though.

**Link to work:**

[FreeCodeCamp: Simon Game](https://github.com/rickMcGavin/simon)

### Day 28: February 1, 2017

**Today's Progress**
- 1 hour [Understanding Flexbox: Everything You Need to know](https://medium.freecodecamp.com/understanding-flexbox-everything-you-need-to-know-b4013d4dc9af#.w26mj27k9) by Ohans Emmanuel
- 150 minutes FCC Simon Game Projects

**Thoughts**

The flexbox article above on medium is fantastic for making quick sense of flex box. I had a pretty strong understanding before. Although I admittedly mostly used it for vertical alignment and it's flex-wrap ability. I have not completely worked my way through the article (it's very comprehensive), but I have a much stronger sense I can build most of my HTML/CSS layouts utilizing the CSS Flexbox model.

Finished the HTML/CSS portion of the project so far. I added the the basic features of turning the game on/off. I also adjusted the box shadow for the start button when you click the button.

**Link to work:**

[FreeCodeCamp: Simon Game](https://github.com/rickMcGavin/simon)

### Day 27: January 31, 2017
**Today's Progress**
- 200 minutes FCC Simon Game Project

**Thoughts**

I have built the bulk of the user interface. I only need to complete a start button, strict button, & on/off button. I also will need labels for all of them. Then I can move on to the functionality in JS. So far, I am definitely loving this project as much as I thought I would. I can't wait to dig in to the javascript.

**Link to work:**

[FreeCodeCamp: Simon Game](https://github.com/rickMcGavin/simon)

### Day 26: January 30, 2017
**Today's Progress**
- 200 minutes FCC Tic-Tac-Toe Project

**Thoughts**

I finally completed the tic-tac-toe challenge. It's funny how taking some time away can make it a lot easier to just sit down and figure out why it wasn't working before. I added some @media queries to make it responsive and playable on small screens. The JS is definitely not optimal, but it works.

**Link to work:**

[FreeCodeCamp Tic-Tac-Toe: codepen](https://codepen.io/rickMcGavin/full/JEOaVd/)

[FreeCodeCamp Tic-Tac-Toe: github](https://github.com/rickMcGavin/tic-tac-toe)

### Day 25: January 28, 2017
**Today's Progress**
- 100 minutes FCC Tic-Tac-Toe Project

**Thoughts**

I've completed the functionality to run a successful two-player game of tic-tac-toe. At this point in time, I just want to figure out how to code the game to choose random open squares to play against. No fancy unbeatable AI for the time being.

I've managed to make single-player as X work completely. That said, it broke the two-player version. And single-player as O only runs through once. I can't lie here. I was not even remotely interested in this project, and it's been so frustrating that I hate it even more. I'll get through it, but that's a tough combination: disinterest and difficult.

**Link to work:** [FreeCodeCamp Tic-Tac-Toe](https://github.com/rickMcGavin/tic-tac-toe)

### Day 24: January 27, 2017
**Today's Progress**
- 25 minutes React Docs Quick Start
- 25 minutes FCC Tic-Tac-Toe Project

I've been going through the [React Docs](https://facebook.github.io). The documentation here is solid. Might be better than the Lynda video I was taking to learn React.  

I made a little bit of progress with the tic-tac-toe app. Added a modal for the winner, which I should ultimately just turn in to a message modal/overlay of sorts and feed content into it with jQuery. I finished the function to completely check for a winner. Essentially it's complete as a two-player game.

**Link to work:** [FreeCodeCamp Tic-Tac-Toe](https://github.com/rickMcGavin/tic-tac-toe)

### Day 23: January 25, 2017
**Today's Progress**
- 75 minutes FCC Tic-Tac-Toe Project

**Thoughts**
I am moving along nicely with this project now. I'm almost done making this a functional 2-player game. After that, I'll have to make it 1-player, which should be interesting. It shouldn't be too hard if it just chooses randomly, but I'm not sure how to approach coding it in a way that will make it choose the best choices.

**Link to work:** [FreeCodeCamp Tic-Tac-Toe](https://github.com/rickMcGavin/tic-tac-toe)


### Day 22: January, 24 2017
**Today's Progress**
- 100 minutes FCC Tic-Tac-Toe Project

**Thoughts**

I learned how to make modal pop ups in JavaScript. Thankfully it was fairly straight forward. I am struggling to center the content properly though.

Right, now I'm working on basically making it work as a two player game. I have it alternating between X's and O's, but when I make one click, it fires the X and the O back to back, and I'm not quite sure why.

**Link to work:** [FreeCodeCamp Tic-Tac-Toe Challenge](https://github.com/rickMcGavin/tic-tac-toe)

### Day 21: January 23, 2017
**Today's Progress**
- 25 minutes [Lynda.com](http://www.lynda.com)
- 50 minutes FCC Tic-Tac-Toe Project

**Thoughts**

I am picking back up where I left off with the reactjs series. It's definitely just the essentials. React makes some sense to me just to look at it. Although, I honestly don't care for the way it looks as code. It don't find it as aesthetically pleasing, but that's ok.

I started the HTML & CSS portion of the tic-tac-toe challenge. Nothing major so far. It should get significantly harder later.

**Link to work:** [FreeCodeCamp Tic-Tac-Toe Challenge](https://github.com/rickMcGavin/tic-tac-toe)

### Day 20: January 22, 2017
**Today's Progress**
- 50 minutes FreeCodeCamp Advanced Project: Pomodoro Timer

**Thoughts**

I was able to add the underline animation like I desired to the Pomodoro timer. It's not exactly how I wanted it, but ultimately it's a nice touch, and something I wanted to include. I really should write a JS function to handle the repeated use of the same code. I can do that later.

I fixed allowing the user to enter numbers less than one in to the timer.

I did not figure out how to animate the border to fill with the timer, but maybe another day.

**Link to work:** [FreeCodeCamp: Pomodoro Clock](https://github.com/rickMcGavin/Pomodoro-Clock)

### Day 19: January 21, 2017
**Today's Progress**
- 25 minutes [funfunfunction](https://www.youtube.com/watch?v=PIkA60I0dKU&list=PL0zVEGEvSaeHBZFy6Q8731rcwk0Gtuxub&index=2) YouTube video showing examples of *this* and bind in his object creation series.
- 150 minutes FreeCodeCamp Advanced Project: Pomodoro Timer

**Thoughts**

I've always found the funfunfunction YouTube channel helpful at explaining some of the more advanced concepts in JavaScript, so I am going to plug away at his series on object creation.

I don't think I did a good job keeping track of the time I spent working on this timer. It certainly feels like more than 150 minutes. It's fully functional now. It could pass the freecodecamp test as it is, but I fully intend to add just a few animations.

**Link to work:** [FreeCodeCamp: Pomodoro Clock](https://github.com/rickMcGavin/Pomodoro-Clock)


### Day 18: January 20, 2017
**Today's Progress**
- ~100 minutes FreeCodeCamp Advanced Project: Pomodoro Timer

**Thoughts**

I skipped Lynda entirely today. I did watch some youtube videos on Object Creation in Javascript on the [funfunfunction](https://www.youtube.com/playlist?list=PL0zVEGEvSaeHBZFy6Q8731rcwk0Gtuxub) channel. His channel really helped me understand higher-order functions better. Although today, I just watched his first video on Object Creation in JavaScript. What I like about his explanation is that he gives you some of those ideal examples, or what you might see in YDKJS, but he also provided a practical example. Like something you'd come across in a fairly normal project.

My focus has not been as precise. I have not been starting every session with clear goals and the laser focus I usually have. Part of this I believe is a result of the unusually large struggles I've had with this Project Challenge. I was able to code a good portion of the functionality with basically no assistance. I very easily coded the timer to count down from whatever the user desired to 0.

I had written my code without really being object oriented. When it came time to add the pause timer functionality, I simply could not figure out how to call it with the way I had written the code. Again I turned to the blog of [Gorka Hernandez](https://www.gorkahernandez.com/blog/). While I was able to move forward, I'm not fully satisfied, and I still insist that I want to write it my own way. Writing his code out, and playing around with it though was a big help in gaining a deeper understanding.


**Link to work:**  [FreeCodeCamp: Pomodoro Clock](https://github.com/rickMcGavin/Pomodoro-Clock)


### Day 17: January 19, 2017
**Today's Progress**
- 25 minutes [Lynda.com](http://www.lynda.com)
- 50+ minutes FreeCodeCamp Advanced Project: Pomodoro Timer

**Thoughts**

My 25 minutes on Lynda basically doesn't count. I ended up falling asleep during it. I am extremely tired. I'll have to watch it again tomorrow.

I worked for well over 50 minutes on the Pomodoro code. I am trying to make it more object oriented by using a constructor, and well, the struggle is back. When I wasn't writing the code that way, I definitely was able to accomplish a lot, but I don't think it was working out in my favor. I'm definitely missing something. I started to write it differently because I couldn't figure out how to use clearTimeout in my original code that was actually working more. Now, that I'm writing it in a more object-oriented way though, it's like I turned the struggle back up. One thing I know for sure is that I'm too tired and frustrated to figure *this* out tonight.

**Link to work:**  [FreeCodeCamp: Pomodoro Clock](https://github.com/rickMcGavin/Pomodoro-Clock)

### Day 16: January 18, 2017
**Today's Progress**
- 25 minutes [Lynda.com](http://www.lynda.com)
  - Started React.js: The Basics
- ~50 minutes FreeCodeCamp Advanced Project: Pomodoro Timer

**Thoughts**

Due to some potentially pressing desire to find employment. I have decided to skip some courses that would mostly be considered review, and I've started React.js.

I made some actual progress on this timer. I was definitely approaching it the wrong way. I was trying to manipulate the seconds and minutes separately. Instead, it was much easier to just run the timer based on the total seconds, and convert the display.

**Link to work:**  [FreeCodeCamp: Pomodoro Clock](https://github.com/rickMcGavin/Pomodoro-Clock)

### Day 15: January 17, 2017
**Today's Progress**
- 25 minutes [Lynda.com](http://www.lynda.com)
  - Continued HTML Essential Training on Front-End Developer Learning Path
- 75 minutes FreeCodeCamp Advanced Project: Pomodoro Timer

**Thoughts**

Still nothing major learned from the HTML course. Although, I will say it's interesting to learn the difference between when to use the tags &lt;em&gt;, &lt;i&gt;, &lt;strong&gt;, and &lt;b&gt;. I didn't realize they all serve their own purpose. &lt;em&gt; and &lt;strong&gt; are geared more towards a conversational emphasis, and screen readers with inflection capabilities will change the inflection. &lt;i&gt; and &lt;b&gt; are for presentational use of italic and bold.

Now that I have my setup complete with the HTML/SCSS, I am working with the JS. I'm trying to push myself more to use object constructors, and as much Vanilla JS as possible. That said, I'm definitely struggling with this timer. I have no issue, getting that clock to count down from 60 - 0. After that though, I am definitely struggling. It may be possible because of the way I am handling minutes and seconds separately. It likely would be significantly easier to convert the input to all seconds, and then convert it back to minutes and seconds upon updating to the display.

Either way, I didn't get quite enough sleep, and since I'm 2 hours in. I'll call it a night.

**Link to work:**  [FreeCodeCamp: Pomodoro Clock](https://github.com/rickMcGavin/Pomodoro-Clock)

### Day 14: January 16, 2017
**Today's Progress**
- 25 minutes [Lynda.com](http://www.lynda.com)
  - Started HTML Essential Training on Front-End Developer Learning Path
- 125 minutes FreeCodeCamp Advanced Project: Pomodoro Timer

**Thoughts**

The first 25 minutes of the Lynda course were obviously a little boring as I feel I know HTML rather well at this point. However, I definitely want that Front-End Certification from Lynda, so I'll bear with it. I'll be getting in to new territory shortly.

I coded the HTML & SCSS for the Pomodoro Clock. That is complete except for the animations. I started the JavaScript functionality. I figured out how to count from 60 to 0 in 1 second intervals so far. I feel like I am at least on the right path.

**Link to work:** [FreeCodeCamp: Pomodoro Clock](https://github.com/rickMcGavin/Pomodoro-Clock)

### Day 13: January 15, 2017
**Today's Progress**
- 50 minutes [Lynda.com](http://www.lynda.com)
  - Finished CSS: Core Concepts course on Front-End Developer Learning Path
- 50 minutes FreeCodeCamp Advanced Project: Pomodoro Timer

**Thoughts**

Again I'm learning some interesting things about CSS in regards to styling container elements. This course is far more detailed in regards to teaching how to round corners, handling background image properties, and the various ways you can write border properties. I wish I came across this course initially as it is easily the most comprehensive I've come across. It's helping me fill gaps in my learning. Some of the gaps I knew existed. Some I didn't, and those are the worst after all. Not knowing what you don't know can really leave you in the dark.

Put together a design in Sketch App of how I'd like the Pomodoro Clock to look. Calling it an easy day and stopping after 2 hours. It is Sunday after all.

**Link to work:** [FreeCodeCamp: Pomodoro Clock](https://github.com/rickMcGavin/Pomodoro-Clock)

### Day 12: January 14,2017
**Today's Progress**
- Read 25 minutes Eloquent JavaScript
  - Tried reading up on objects from another book for more insight in to my struggles with objects and *this*.
- 75+ minutes FreeCodeCamp Advanced Project: JavaScript Calculator
  - Finished... for now.

**Thoughts**

After reading more and varying sources on *this* and objects and object prototypes. I don't think I have a huge misunderstanding of them. I think I just managed to break my calculator code in a confusing enough way to make me doubt myself more than I should. That said, I still don't have my code working the way I want for the JavaScript calculator.

After taking about 10 minutes to learn how the debugger in Chrome works courtesy of [Ghordon Zhu's YouTube Channel](https://www.youtube.com/user/gordonmzhu/feed), I was able to narrow down where the issue was. It turns out that I am not a total moron who has no concept of how objects work & how *this* works. Instead, I named two classes in my html "number-button" and "operator-button", and then I tried calling them as "number-buttons" and "operator-buttons" in my JavaScript file.

Lessons learned:
- Use debugger often and early.   
- Check those damn variables for pluralization!

Mission accomplished on breaking the code in to smaller functions. I still have some issue where the user can enter multiple decimals though.
Added the ability to operate the calculator with the use of key presses.
The user also cannot enter multiple decimals per number now.

**Link to work on github**
[FreeCodeCamp: JavaScript Calculator](https://github.com/rickMcGavin/JavaScript-Calculator)

**Link to work on codepen**
[FreeCodeCamp: JavaScript Calculator](http://codepen.io/rickMcGavin/pen/oBLNxM)

### Day 11: January 13, 2017
**Today's Progress**
- 25 minutes [Lynda.com](http://www.lynda.com)
  - Continued CSS: Core Concepts course on Front-End Developer Learning Path
- 75+ minutes FreeCodeCamp Advanced Project: JavaScript Calculator
- 25 minutes YDKJS: *this* & Object Prototypes

**Thoughts**

The CSS course today largely covered how to understand the basics of the box model, controlling element spacing, and controlling interior spacing. Many things I knew, but there were some quirks in regards to the way margin is calculated vertically on elements.

I made the calculator a little wider and increased the height some, so as to make it most appealing on mobile devices. I felt it was a little too small when I used it on my iPhone. I like how it works now, but am not sure why I can't make it reach the entire width of the screen.

I added some more border to the top, left, and right of the display to make it look more uniform with the rest of the calculator's styling.

I did not like the way the JavaScript was written in my version. It was mostly one big function. I wanted to be able to make it more functional by using many smaller functions. Since my version is already complete and working, I figured there is no harm in going and finding a better way to write it and possibly learn something while I am at it. I am trying to adapt [JavaScript Calculator Guide](https://www.gorkahernandez.com/blog/fcc-zipline-series-build-javascript-calculator-vanilla/) by [Gorka Hernandez](http://www.gorkahernandez.com/). I am still trying to get this to work without much success, and am not sure what it is I'm missing at this point.

I made a point to read YDKJS today due to my struggles with *this*, objects, constructors. I hear people rave about YDKJS, and it is good. I don't find it that accessible though. I don't care for the examples either. They don't seem to have any practical application. Every example is written to demonstrate only what the author is trying to demonstrate. They are all foo() bar() style. I'm definitely struggling with this.


**Link to work on github**
[FreeCodeCamp: JavaScript Calculator](https://github.com/rickMcGavin/JavaScript-Calculator)

**Link to work on codepen**
[FreeCodeCamp: JavaScript Calculator](http://codepen.io/rickMcGavin/pen/oBLNxM)

### Day 10: January 12, 2017
**Today's Progess**
- 25 minutes [Lynda.com](http://www.lynda.com)
  - Continued CSS: Core Concepts course on Front-End Developer Learning Path
- 75+ minutes FreeCodeCamp Advanced Project: JavaScript Calculator

**Thoughts**

Much of the CSS course today was in regards to text manipulation, which is another topic I knew fairly well.

The JavaScript calculator was somewhat simpler than I was expecting. It will technically pass all FCC user stories as it is, so I submitted it as complete. It still has some quirks I want to work out though. For example, you can input as many decimals in a number as you want, which will eventually break it.

**Link to work on github**
[FreeCodeCamp: JavaScript Calculator](https://github.com/rickMcGavin/JavaScript-Calculator)

**Link to work on codepen**
[FreeCodeCamp: JavaScript Calculator](http://codepen.io/rickMcGavin/pen/oBLNxM)


### Day 9: January 11, 2017
**Today's Progress**
- 25 minutes [Lynda.com](http://www.lynda.com)
  - Continued CSS: Core Concepts course on Front-End Developer Learning Path
- 50+ minutes FreeCodeCamp Advanced Project: JavaScript Calculator

**Thoughts**

I definitely didn't learn anything new from the CSS course today. Not too surprised. It was bound to happen eventually. Thank you for 2x speed videos. Although, I must say I wish I had 3x. This is in no way a negative criticism of the course. It's just largely review.

Finished the majority of the HTML/CSS portion. Looks better than what I sketched up. Added some basic CSS to it. I'm quite pleased with how it looks. Now that it looks like a calculator, I have to make it work like a calculator.

**Link to work:**
[FreeCodeCamp: JavaScript Calculator](https://github.com/rickMcGavin/JavaScript-Calculator)

### Day 8: January 10, 2017
**Today's Progress**
- 25 minutes [Lynda.com](http://www.lynda.com)
  - Continued CSS: Core Concepts course on Front-End Developer Learning Path
- 75 minutes FreeCodeCamp Advanced Project: JavaScript calculator

**Thoughts**

It's funny how I thought I knew CSS rather well, but continue to learn and understand more by the Lynda course. The most appropriate and easy to understand explanation of specificity exists in this course. I understand in general how CSS selectors could be more specific than others. I did not realize that each selector is assigned a value, and the more specific selector is basically the selector with the highest combined value.

I started the JavaScript calculator project by getting a rough idea of what I wanted the project to look like in Sketch, choose a color palette and general design. This took only about 25 - 45 minutes, but it gives me a clear sense of how to approach writing the HTML & CSS. I started the HTML & CSS, using SCSS.

I'm having a little trouble with the buttons laying out how I want them to in the flexbox, but I'll figure it out.   

**Link to work:**
[FreeCodeCamp: JavaScript Calculator](https://github.com/rickMcGavin/JavaScript-Calculator)

### Day 7: January 9, 2017
**Today's Progress**
- 25 minutes [Lynda.com](http://www.lynda.com)
  - Continued CSS: Core Concepts course on Front-End Developer Learning Path
- ~50 minutes on FreeCodeCamp Advanced Algorithm Challenge: pairwise
  - solved

**Thoughts**

I continue to learn more from the CSS course. I did not have a strong grasp on psuedo-element selectors and how they worked. Even though I have used them before, I certainly did not understand them how I do now.

I was able to rather easily solve pairwise. I had thought about how to solve it frequently at work, and my plan worked largely. I ran in to some odd behavior that caused me to fail the challenge on the first few tries. For instance when I set the initial value of the loop inside the reducer to 1. It worked for most problems, but when I set it to the reduce function's index + 1. It worked for all of them. I'm a little unsure why this is still.

Unfortunately, it seems tonight will be another night I don't read YDKJS. I need to figure out how to start earlier in the night, so I can get everything done.

Looking forward to starting the calculator tomorrow.

**Link to work:**
[FreeCodeCamp: Pairwise](https://github.com/rickMcGavin/algorithm-challenges/blob/master/FreeCodeCamp/advanced_algorithms/pairwise.js)


### Day 6: January 8, 2017
**Today's Progress**
- 25 minutes [Lynda.com](http://www.lynda.com)
  - Continued CSS: Core Concepts course on Front-End Developer Learning Path
- 75 minutes on FreeCodeCamp Advanced Algorithm Challenge: Map the Debris
  - solved

**Thoughts**

Since the CSS course is *mostly* review, I prefer to watch it at 1.75x - 2x speed. I will say that even though I've taken an absurd amount of online courses, and I've even read Jon Duckett's HTML/CSS book, I still learn a ton of things about CSS I never knew. In some cases, I was using them, but didn't understand them until this course.

I loved the Map the Debris challenge. I enjoyed it. I found it sufficiently challenging without being confusing, and I learned from it.

**Link to work:**
[FreeCodeCamp: Map the Debris](https://github.com/rickMcGavin/algorithm-challenges/blob/master/FreeCodeCamp/advanced_algorithms/map_the_debris.js)


### Day 5: January 7, 2017
**Today's Progress**
- 25 minutes [Lynda.com](http://www.lynda.com)
  - Continued CSS: Core Concepts course on Front-End Developer Learning Path
- 50+ minutes on FreeCodeCamp Advanced Algorithm Challenge: Friendly Date Ranges
  - solved
- 25 minutes reading YDKJS: this and Object Prototypes
- 25 - 50 minutes on FreeCodeCamp Advanced Algorithm Challenge: Make a Person
  - solved

**Thoughts**

I like a lot of FCC, but this challenge is kind of lousy. The instructions are not clear in my opinion, especially when compared to the test cases.

To make matters worse, they chose to use a date format separated by hyphens. Maybe they didn't realize this, but the hyphens are wildly inconsistent. I had to append .replace("-", "/") on to a couple lines of code to make it work. Not everyone had to do this it seems. For example, Stephen Mayeaux's code from his YouTube channel worked just fine without. Mine was consistently off unless I changed those hyphens to forward slashes.

My final little gripe about this is really only related to timing. The challenge seems to have been designed for 2017, so I had to add a little alteration to make it work as if it wasn't 2017 already. That's just a necessary update they may not have seen coming.

I submitted an issue for the bug above, and found out they already had an open pull request to remove the challenge entirely as it will require an update every year. Interesting.  

I also solved the Make a Person challenge on FCC. Even though I'm reading the YDKJS book on *this*, I'm still struggling with its use.

**Link to work:**
FreeCodeCamp: Friendly Date Ranges](https://github.com/rickMcGavin/algorithm-challenges/blob/master/FreeCodeCamp/advanced_algorithms/friendly_dates_ranges.js)
**Link to work:**
[FreeCodeCamp: Make a Person](https://github.com/rickMcGavin/algorithm-challenges/blob/master/FreeCodeCamp/advanced_algorithms/make_a_person.js)


### Day 4: January 6, 2017
**Today's Progress**
- 25 minutes on [Lynda.com](http://www.lynda.com)
  - Continued CSS: Core Concepts course on Front-End Developer Learning Path.
- 50+ minutes on FreeCodeCamp Advanced Algorithm Challenge: Friendly Date Ranges

**Thoughts**

I finally understand how this Date object works. Also, it seems that since FCC used hyphens in the date format, there is some sort of inconsistency. I thought I just didn't understand how the methods worked, but apparently if you replace the hyphens with forward slashes, the dates work right. Glad I figured that out. That little inconsistency completely hung me up on this challenge. I've been able to move forward on it now, and should be able to have it completed tomorrow.

I could have most likely solved it, but in a rare change, I just really enjoyed playing around with the Date object and seeing how it works... in a productive way.

**Link to work:**
[FreeCodeCamp: Friendly Date Ranges](https://github.com/rickMcGavin/algorithm-challenges/blob/master/FreeCodeCamp/advanced_algorithms/friendly_dates_ranges.js)


### Day 3: January 5, 2017
**Today's Progress**
- 50 minutes on FreeCodeCamp Advanced Algorithm Challenge: Friendly Date Ranges

**Thoughts**

Life definitely happened today. Got a late start on coding, so I only worked on the FCC challenge instead of my usual routine. I didn't get enough sleep, and I definitely struggled with this date challenge as I barely solved any of the problems in the algorithm. Tomorrow will be better.

**Link to work:**
[FreeCodeCamp: Friendly Date Ranges](https://github.com/rickMcGavin/algorithm-challenges/blob/master/FreeCodeCamp/advanced_algorithms/friendly_dates_ranges.js)


### Day 2: January 4, 2017
**Today's Progress**
- 25 minutes on [Lynda.com](http://www.lynda.com)
  - Began course CSS: Core Concepts on Front-End Developer Learning Path.
- 85 minutes on FreeCodeCamp Advanced Algorithm Challenge: No Repeats Please
  - Solved on 4th Pomodoro and finished the remaining...
- 15 minutes on reading YDKJS this & Object Prototypes

**Thoughts**

I spent the majority of my time coding as compared to reading or studying the Front-End Developer Learning Path on Lynda. It certainly felt like the most productive use of my time, and I have another FCC challenge solved to show for it. I just need to knock down 4 more of these algorithm challenges before I can start the projects.

**Link to work:**
[FreeCodeCamp: No Repeats Please Solution](https://github.com/rickMcGavin/algorithm-challenges/blob/master/FreeCodeCamp/advanced_algorithms/no_repeats_please.js)


### Day 1: January 3, 2017
**Today's Progress**
- 25 minutes on [Lynda.com](http://www.lynda.com)
  - Finished course: Up & Running with Git and Github
- 50 minutes coding FreeCodeCamp Advanced Algorithm Challenge: Inventory Update.
  - Challenge solved.
- 25 minutes reading YDKJS: this & Object Prototypes

**Thoughts:**

I work in Pomodoros, so I consider meeting my coding challenge at 50 minutes per day. I typically always try to read or watch course material as well, but not as much as time spent on code.

The biggest thing I learned today was that I struggled with the Inventory Update challenge largely due to a misunderstanding of how nested for loops would iterate through an array.

I consider it a win that I was able to solve the challenge. Tomorrow I have to start figuring out the next FCC Advanced Algorithm Challenge: No Repeats Please.
**Link to work:**
[Inventory Update Solution](https://github.com/rickMcGavin/algorithm-challenges/blob/master/FreeCodeCamp/advanced_algorithms/inventory_updates.js)
