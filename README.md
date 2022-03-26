# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Norman Cattles

Time spent: **7** hours spent in total

Link to project: (https://modern-shiny-horse.glitch.me)

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

Winning Game:
![](http://g.recordit.co/gSlVv7dZPV.gif)  
Losing Game:
![](http://g.recordit.co/3zufI0X4No.gif) 
Stopping Game:
![](http://g.recordit.co/vQ8Z1dC88Z.gif) 
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

[I did not use any outside resources.]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

[A challenge I encountered in creating this submission was trying to understand the small syntax of all the JavaScript. I almost went down a rabbit-hole trying to get an idea of what every single letter did in the code; and that's when I noticed how my approach was not the best. I overcame this confusion by trying to understand the overall function of a piece of code. For example, the playClueSequence function has a lot of technical syntax, but I started with asking myself what the goal of this function is- which is to execute the sequence of the clues with a delay. Then, I looked at how the delay was being defined and how each sequence was being recorded. This is when I noticed that I need to identify the goal first before looking at what tools could help me achieve that goal. This approach to thinking about a problem reminds me of the top-down stepwise refinement for writing pseudocode. The overall function of the program is the beginning of the pseudocode, and with each refinement your pseudocode explicates in a little more detail of how the function will work. Your third and forth refinement will start to look a little more like code that will be able to translate pretty seamlessly from pseudocode to your programming language. I believe that learning about how to write pseudocode has absolutely helped me do the complete opposite, which is reading a programming language that I may not be that familiar with.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

[How do different files within a project have the ability to interact and understand each other? For example, how is it possible that buttons defined in HTML can have their appearance directly edited in CSS? Why is it that variables in JavaScript do not need a type when defining them? Are there any other languages that are crucial to web development besides HTML, CSS and JavaScript? How similar or different are web development and mobile app development?]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

[If I had a few more hours to work on this project, I would have definitely spent time trying to find a way of making the game have no definite end until the user loses. I would also try to add a live leaderboard so that players can compare their highest score with other people. Since the webpage is only the start and stop buttons, incorporating a settings section that would allow the user to customize the tones, the size, the number, and the colors of the buttons would be a really fun idea. Also, a difficulty setting from very easy to impossible that would speed up the sequence depending on the user choice would be a nice addition.]



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright [Norman Cattles]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
