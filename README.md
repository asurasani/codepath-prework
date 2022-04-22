# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Aneesh Surasani**

Time spent: **6** hours spent in total

Link to project: (https://glitch.com/edit/#!/excessive-lucky-salmon)
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

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

For the random pattern array, no consecutive numbers elements in the array would not be the same

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://i.imgur.com/Jnwhmkf.gif)

![](https://i.imgur.com/rYXCrXD.gif)



## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[YOUR ANSWER HERE]
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random
https://www.onlinegdb.com/online_javascript_rhino_interpreter
https://www.w3schools.com/js/



2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

One challenge I encountered when creating this submission was not being able to debug my program easily. When an issue occurred with my code, Glitch does 
not tell you where the error is and Glitch does not have its own debug feature so it was hard to spot errors in my code. Also, Glitch only gave me error  
notifications when I did not close parentheses or brackets, so syntax errors were not shown. In my programming classes, where we use other IDE’s such as 
VScode, the debug feature allows me to run my projects step by step. For example, one error that I had was generating the random pattern for the buttons. 
When I implemented the function and started the game, the game would display that I had lost. I overcame this challenge by using online javascript 
compilers from other websites to test individual segments of code. This was beneficial because in the event something were to go wrong in the online 
compilers, the error would be easier to spot because I was working with less lines of code and I can use more display commands. Then, once the code was 
working in the online compiler, I would copy and paste the code into glitch and the website would work. 


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

To make advanced websites, there are many languages involved and there are different purposes each language plays, such as Backend development, DevOps, 
or Databases. Basic Frontend web development is commonly done using three different languages, HTML, CSS, and Javascript. My question is why is it not 
possible to merge these three languages into one universal language. Most people already use these languages to build websites, so why not use one 
language which can save time to focus on other parts of the website which take longer to do. Each language has its own format that developers must be 
accustomed to, and can make it tedious. Also, this will make it easier to learn to build websites because there is less syntax to learn. 


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had more time to work on this project, I would use it to add additional features to make it more difficult for the user to win the game. For example,
I would have implemented a countdown timer at the top of the page for each turn. Also, I would have wanted to display the pattern faster on each turn. I
would have wanted to refactor my random function to make it more efficient because it is a nested loop. The purpose of the nested loop is to have no two 
consecutive numbers in the pattern array the same. Since nested loops take more time to process, I would have wanted to redo that function into a better 
time complexity.




## Interview Recording URL Link

[My 5-minute Interview Recording](https://youtu.be/MV6sd3Nd4rw)


## License

    Copyright [Aneesh Surasani]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
