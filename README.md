# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Jennifer Prince**

Time spent: **3.5** hours spent in total

Link to project: https://glitch.com/edit/#!/thememorygame

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [x] Buttons use a pitch (frequency) other than the ones in the tutorial
- [x] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [x] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
<img src="http://g.recordit.co/OyEzGvQQ3S.gif" width=400px> <br>

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

Getting a random integer between two values: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

One challenge I faced was wrapping my head around the game logic flowchart when handling guesses. I don’t usually use a diagram such as this when coding, so it was taking me some time to translate the flow of logic into code. I took a step back and decided to tackle the problem of handling guesses on my own, from scratch, and then compare what I got with the solution. My thought process was to write out a conditional for every scenario, rather than using a nested structure, because I thought it would be easier to keep track of at first. However, it soon got pretty complicated with too many cases, and my code was perpetually filled with bugs. But, it did make me learn how important using a nested structure is, so I looked back at the flowchart and things made more sense. Knowing what not to do somehow gave me a clearer idea of what to do when I came back to tackle the problem. Eventually, I came up with something similar to the given solution, separating every step in the flowchart and grouping certain steps under certain conditions. With time and a willingness to try my ideas even if they turned out to be wrong the first time allowed me to eventually come to and understand the correct solution. And, I now see how useful using a flowchart is to create logic in code, so I will definitely consider using it the next time I face a roadblock while coding.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

What other tools do people use to make web development faster? Glitch was a really cool tool and I would love to learn more about it and other tools the industry uses to develop projects.
How is web development done collaboratively? How do things get resolved when people working on different parts of a web project end up interfering or interacting with each other? 


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)

If I had a few more hours to work on the project, I might have attempted to restructure to code to make it more organized and object-oriented. I ended up with a large list of functions, and I should definitely add more comments to the code to document the purpose of everything in more detail. I also would want to give the player many more options on the gameplay, such as how long the sequence should be, what octave the sounds should play in, what difficulty they want, and so on. It would really help to have a structure in the code that can just take in attributes such as difficulty and sequence length while still running the game on the same basic engine we coded for this project. 

## License

    Copyright Jennifer Prince

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
