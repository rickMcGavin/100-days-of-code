# 100 Days Of Code - Log

### Day 15: January 17, 2017
**Today's Progress**
- 25 minutes [Lynda.com](http://www.lynda.com)
  - Continued HTML Essential Training on Front-End Developer Learning Path
- 75 minutes FreeCodeCamp Advanced Project: Pomodoro Timer

**Thoughts**
Still nothing major learned from the HTML course. Although, I will say it's interesting to learn the difference between when to use the tags &lt;em&gt;, &lt;i&gt;, &lt;strong&gt;, and &lt;b&gt;. I didn't realize they all serve their own purpose. &lt;em&gt; and &lt;strong&gt; are geared more towards a conversational emphasis, and screen readers with inflection capabilities will change the inflection. &lt;i&gt; and &lt;b&gt; are for presentational use of italic and bold.

Now that I have my setup complete with the HTML/SCSS, I am working with the JS. I'm trying to push myself more to use object constructors, and as much Vanilla JS as possible. That said, I'm definitely struggling with this timer. I have no issue, getting that clock to count down from 60 - 0. After that though, I am definitely struggling. It may be possible because of the way I am handling minutes and seconds separately. It likely would be significantly easier to convert the input to all seconds, and then convert it back to minutes and seconds upon updating to the display.

Either way, I didn't get quite enough sleep, and since I'm 2 hours in. I'll call it a night.

**Link to work**[FreeCodeCamp: Pomodoro Clock](https://github.com/rickMcGavin/Pomodoro-Clock)

### Day 14: January 16, 2017
**Today's Progress**
- 25 minutes [Lynda.com](http://www.lynda.com)
  - Started HTML Essential Training on Front-End Developer Learning Path
- 125 minutes FreeCodeCamp Advanced Project: Pomodoro Timer

**Thoughts**
The first 25 minutes of the Lynda course were obviously a little boring as I feel I know HTML rather well at this point. However, I definitely want that Front-End Certification from Lynda, so I'll bear with it. I'll be getting in to new territory shortly.

I coded the HTML & SCSS for the Pomodoro Clock. That is complete except for the animations. I started the JavaScript functionality. I figured out how to count from 60 to 0 in 1 second intervals so far. I feel like I am at least on the right path.

**Link to work** [FreeCodeCamp: Pomodoro Clock](https://github.com/rickMcGavin/Pomodoro-Clock)

### Day 13: January 15, 2017
**Today's Progress**
- 50 minutes [Lynda.com](http://www.lynda.com)
  - Finished CSS: Core Concepts course on Front-End Developer Learning Path
- 50 minutes FreeCodeCamp Advanced Project: Pomodoro Timer

**Thoughts**
Again I'm learning some interesting things about CSS in regards to styling container elements. This course is far more detailed in regards to teaching how to round corners, handling background image properties, and the various ways you can write border properties. I wish I came across this course initially as it is easily the most comprehensive I've come across. It's helping me fill gaps in my learning. Some of the gaps I knew existed. Some I didn't, and those are the worst after all. Not knowing what you don't know can really leave you in the dark.

Put together a design in Sketch App of how I'd like the Pomodoro Clock to look. Calling it an easy day and stopping after 2 hours. It is Sunday after all.

**Link to work** [FreeCodeCamp: Pomodoro Clock](https://github.com/rickMcGavin/Pomodoro-Clock)

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

**Link to work**
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

**Link to work**
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

**Link to Work**
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

**Link to work**
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

**Link to work**
FreeCodeCamp: Friendly Date Ranges](https://github.com/rickMcGavin/algorithm-challenges/blob/master/FreeCodeCamp/advanced_algorithms/friendly_dates_ranges.js)
**Link to work**
[FreeCodeCamp: Make a Person](https://github.com/rickMcGavin/algorithm-challenges/blob/master/FreeCodeCamp/advanced_algorithms/make_a_person.js)


### Day 4: January 6, 2017
**Today's Progress**
- 25 minutes on [Lynda.com](http://www.lynda.com)
  - Continued CSS: Core Concepts course on Front-End Developer Learning Path.
- 50+ minutes on FreeCodeCamp Advanced Algorithm Challenge: Friendly Date Ranges

**Thoughts**

I finally understand how this Date object works. Also, it seems that since FCC used hyphens in the date format, there is some sort of inconsistency. I thought I just didn't understand how the methods worked, but apparently if you replace the hyphens with forward slashes, the dates work right. Glad I figured that out. That little inconsistency completely hung me up on this challenge. I've been able to move forward on it now, and should be able to have it completed tomorrow.

I could have most likely solved it, but in a rare change, I just really enjoyed playing around with the Date object and seeing how it works... in a productive way.

**Link to work**
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
