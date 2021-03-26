# Pre-work - *Memory Game*

L&S Memory Game is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Anish Rajeshkumar

Time spent: 10 hours spent in total

Link to project: https://elated-zigzag-lunge.glitch.me/
(If you hear no sound, try reloading the page and try again)

## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

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

## Video Walkthrough

Here's a walkthrough of implemented user stories:
https://imgur.com/gallery/zNhkU4y
https://imgur.com/gallery/qiUiyhq



## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I did used outside resources such as w3schools.com to further understand 
how elements, attributes, event handlers and selectors work to get a 
basic sense of how Java, css and html all worked

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
A challenge I encountered during this projects was understanding what each of these elements were
and how they all worked. I previously had no experience with html or css so I was pretty confused 
on how they worked alongside javascript but after going through the walkthrough and testing the 
code out for myself, for example exploring how selectors work and how the div element worked and how 
I could manipulate certainchareteristics such as the size, font and color based on the elements 
attributes, really gave me a solid understanding on how I could code using html,javascript and 
css and I gained a solid understanding on how javascript,css and html all talk to each other.Furthermore, 
I was very confused on how the sound functions worked. It seemes as if it was created its own audiocontext
object and I spent quite a bit of time exploring about what that object entailed and the methods that 
the object could invoke such as the creatOscillator method and the createGain method. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
Some questions I have with web development is how can I use hyperlinks in my HTML code? I would like to 
include some hyperlinks that redirect to other links as well as include images that use hyperlinks. 
Furthermore, I am intrigued by the way that the audio functions such as starttone and stoptone work. I 
understand the basics of how it works however I would like to learn more about the audiocontext object 
and further ways I can use it. I would also like to learn more about the general process of strtagizing 
and designing code such as this and deploying this code on the web. Additionally, I would like to see 
if there is a way you can track the users who visited the page and gain data from any feedback they leave. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had additional time with this project I would possibly add images to this project through hyperlinks
in the html code. Furthermore, I would have added a  global variable, a console log display, 
and a function where the user can input how many tries they would like  and have that tracked.Therefore if
the user possibly accidentally made an error such as clicking the wrong button, they have more chances before 
they completely lose the game. Further, I would build on that idea of having multiple tries and track 
how many times the user got it wrong during his tries. From there I would create a function in JS 
that would calcultate the average percentage error and display this on the console log when 
end button pops up. From this information, the user can see his average error percentage and this
could somehow indicate how well or poor his memory is. 



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
