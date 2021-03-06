# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Maya Zheng**

Time spent: **6** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com/edit/#!/knowledgeable-grizzled-abacus?path=README.md%3A1%3A0)

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [X] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [X] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [X] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

Start, stop buttons. Winning the game. 

![](http://g.recordit.co/sLxStsqzNE.gif) 

Losing after 3 strikes

![](http://g.recordit.co/tsYNiv246x.gif)

Computer picks a different pattern each time the game is played

![](http://g.recordit.co/1xPA3XwzqC.gif)

Losing beacuse time ran out

![](http://g.recordit.co/Bdc5W50uIK.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

Images for Optional Tasks sourced from
- <a href="https://www.flaticon.com/free-stickers/hamster" title="hamster stickers">Hamster stickers created by Stickers - Flaticon</a>
- <a href="https://www.flaticon.com/free-stickers/nature" title="nature stickers">Nature stickers created by Stickers - Flaticon</a>
- <a href="https://www.flaticon.com/free-stickers/cat" title="cat stickers">Cat stickers created by Stickers - Flaticon</a>
- <a href="https://www.flaticon.com/free-stickers/turtle" title="turtle stickers">Turtle stickers created by Stickers - Flaticon</a>
- <a href="https://www.flaticon.com/free-stickers/nature" title="nature stickers">Nature stickers created by Stickers - Flaticon</a>
- <a href="https://www.flaticon.com/free-stickers/animals" title="animals stickers">Animals stickers created by Stickers - Flaticon</a>
- <a href="https://www.flaticon.com/free-icons/disco-ball" title="disco ball stickers">Disco ball stickers created by smashingstocks - Flaticon</a>

Understanding how to use setInterval and clearInterval
- https://www.w3schools.com/jsref/met_win_clearinterval.asp
- https://www.w3schools.com/jsref/met_win_setinterval.asp
- https://tousu.in/?qa=492949/" title = "timer clarifications

Understanding text in CSS
- https://www.w3schools.com/css/css_text_align.asp
- https://www.w3schools.com/css//css_font_websafe.asp

CSS colors
- https://www.rapidtables.com/web/css/css-color.html#cyan

Images in html
- https://www.w3schools.com/tags/tag_img.asp


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

During this submission, I struggled the most with the optional task of building a timer. As I have never used html before, I started out very confused about how to add a rectangle into the interface to contain the time. This was a problem that I managed to overcome easily by searching online. However, I struggled to figure out how to use setInterval() and clearInterval() to represent time. Luckily, I managed to find code online of a timer, and using that as a reference, I created the timer that counted down from 18 seconds. What followed was a struggle to figure out where to put the timer and how to reset it after the player makes a correct guess. At first, I just tried to add it according to where I thought it would fit, however, it just resulted in the timer counting down very quickly and continuing from where it stopped in the previous guess. I soon realized that clearInterval() did not restart the timer but instead paused it, which was why I had to search online on how to reset the time. Furthermore, there was also the problem of the timer running after the game had ended. To solve this problem, I decided to draw a flow chart, similar to the one provided in the task guidelines, and figured out where to add the startTime() function. This made my understanding of the flow of the code much better and I also managed to find a bug where I called the startTime() function twice in a row, which was a reason for why it would sometimes count down much faster than at 1 second intervals. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

When we approach web development, is it usually better to plan out the layout beforehand in other tools like Figma? If so, how can we effectively transfer what we visualize into reality?
Other than Javascript, CSS, HTML, what are other programming languages that web developers should understand well to complete web development. 
In terms of frontend web development, how does one design an effective User interface? Since for this project we mainly did buttons, and headings with basic colors, how should we improve on the design to make the game more visually appealing to capture user attention, and more easy and enjoyable to play?


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

Firstly, I will try to add a different audio for each button since that was one of the optional tasks that I did not have time to complete.
Secondly, I would add a few symbols to represent the number of lives the player has. I realized while playing the game that right now the player has to remember how many mistakes they have made so far. Three symbols that represent the lives could disappear one by one with every mistake that the player makes. 
I would also try to shorten the times taken for the player to make their decision to increase the difficulty as the game progresses. To make the interface more engaging, when the time is running out, I would make the timer flash to increase the intensity of the game. 




## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/7593a40e19e5451d9d360962e8541762)


## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
