# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's Futureforce Program. 

Submitted by: Fanny Li

Time spent: **5** hours spent in total

Link to project: https://glitch.com/edit/#!/guiltless-instinctive-honeycup?path=index.html%3A43%3A2

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

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [X] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [X] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!


## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
 

![](https://i.imgur.com/SS3ZeHr.gif)

![](https://i.imgur.com/lVxHF40.gif)




## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

    1. https://tutorial.eyehunts.com/js/change-text-in-p-tag-javascript-easy-html-example-code/
    2. http://www.java2s.com/example/html-css/css-form/put-the-value-of-an-input-button-next-to-the-button-via-css.html
    3. https://www.w3schools.com/cssref/pr_background-image.asp
    4. https://www.w3schools.com/colors/colors_picker.asp?colorhex=E6E6FA

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

    A challenge that I encountered in creating this submission was understanding how the Javascript functions were executed. Prior to the pre-work, I had little experience with Javascript. I completed tutorials on front-end design before, mainly focusing on HTML and CSS. I understood the styling of the website, especially how the selector tags worked. My understanding also included creating the buttons, divisions, and text elements. However, I had to spend a little more time understanding how the functions worked. For example, I was a little confused about how the sound functions were implemented. To overcome this confusion, I researched the AudioContext API and read about the methods that were used in each of the playSound functions. 

    Another challenge that I encountered was when the buttons were not lighting up. I had followed all the directions leading up to the step where we were to add the .lit class to each button's styling. I was not entirely sure where I went wrong. I looked back at my code files and tried to figure out if it was the functions that I did not write properly. I found out at the end that it was because I failed to separate the selectors in the styling sheet. This was another example of proving that your methods and logic could all be correct, but the syntax is important. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

    After finishing the submission, I wonder how I can make certain aspects of web development appear more smooth. For example, changing between the start and stop button is not entirely clear. I would like to learn more about CSS styling techniques and how to create animations with Javascript. In addition, Glitch is able to optimize the screen for different sizes. The objects on the screen change to fit the screen size that the user specifies. I wonder what is going on in the background. I want to know how to do this from scratch, for example, using media-queries in CSS. Another question I have about web development is the background structure of how information is being sent and received. What are the steps in this process? How do servers respond to data and send it back to the host domain? 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

     I was able to implement a few of the optional features during the time that I had to work on this project. If I had a few more hours, I would try to recreate the project over again without looking at the code samples. This would be beneficial because I would apply what I have learned and know for sure that I can implement these features from scratch. I would also try to implement a feature where when a player wins or loses, it would change to another page that shows the text in large letters. I would style this page with the same theme colors as the buttons and give an option to play the game again. Finally, I would try to read more on the setInterval API and add the ticking time clock onto the page. The clock would give the user about 3 seconds to choose each button and there would be a countdown that includes the milliseconds. If the user doesn't choose within 3 seconds of the correct button, it would take off one life and the timer would reset. 





## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/8fd459d2edfc47f38d53a1023f75b56d)


## License

    Copyright Fanny Li

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
