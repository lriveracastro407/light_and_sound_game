# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Leonel Rivera-Castro

Time spent: 6 Hours total | 3 hours on main, 2 hours fixing game logic & audio, 1 hour on additional features 

Link to project: https://crawling-north-play.glitch.me

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
* [ ] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [X] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [X] Added a Cheat Sheet so Users can see the randomized pattern

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![X]https://cdn.glitch.com/191c9496-328d-415c-abc5-32317b87aa15%2Fezgif.com-gif-maker.gif?v=1616633710988
^I couldn't win the game because I'm not good enough and I was running out of time!


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
https://stackoverflow.com/questions/48757933/audiocontext-issue-on-safari
I had issues with playing Audio and so I figured out that it was a Safari problem so I had to switch to Google Chrome
http://shtooka.net/index.php
I used this website to get the sounds for my game (In assets, but not used)
https://www.w3schools.com/jsref/jsref_push.asp
https://www.w3schools.com/cssref/pr_background-image.asp


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
One challenge that I encountered when creating the submission was that my Game Logic was not correct. Even after I copied and pasted the given answer it still didn't work and I realized it was because my "guessCounter"
wasn't resetting after each round of guessing and I spent over an hour diagnosing and fixing the problem using console log. Another challenge was that my Audio wasn't working and I had to research and I found out it was
because I was on Safari so I switched to Chrome. My audio still doesn't work perfectly, one must press the refresh button on the Glitch window for the sound to work. The last challenge was adding in my additional features.
I had to research CSS backgrounds so I would be able to make my game into the "Animal Edition". I also wanted to include a voice over where it would say the name of the animal instead of a frequency. I researched both the audio
tag on HTML and audio.play on JavaScript, but I couldn't get the sounds to work as I wanted. The sounds worked when you pressed on the button, but it wouldn't work in game so I removed it all together. I probably could've solved
the problem given more time, but in fairness to other applicants I didn't want to go too much over time. 


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I have a lot more questions about web development now and I am excited to learn more! I didn't know how JavaScript worked, but now I know it is like a "regular" coding language! The biggest question I have is how to get my own
sounds to play during the game, which was something I could not answer in the time alloted. Another question is how would you use code from Java and Python put it onto a Web Page. I created a few games in the past for a class
project and now I am curious on how I could move everything onto a website so I could share it with others and not have to play it locally everytime. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
I have a few ideas on things I would work on. One would be to add more "Game" elements. For example, I'd like to create different difficulties for the game. If a User wanted an "easier" game they could choose an "easy" setting and
the length of the pattern would be 4, a "medium" difficulty game would be a length 8 pattern and a "hard" difficulty would be length 12. Additionally, I would've loved to implement different sounds as I explained earlier. Another idea
that I have would be to create a small easter egg. It would be a small dot on the screen and if the User clicked on it it would send them to the original PreWork specifications website.

Thank you so much for this opportunity! I had a lot of fun creating and remixing the project!



## License

    Copyright Leonel Rivera-Castro

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.