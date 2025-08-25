# WEB102 Prework - Sea Monster Crowdfunding

Submitted by: Kaylen Teves

Sea Monster Crowdfunding is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: 8 hours spent in total

## Required Features

The following **required** functionality is completed:

* [X] The introduction section explains the background of the company and how many games remain unfunded.
* [X] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [X] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [X] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [X] The header doubles as a navigation bar, allowing users to jump to specific sections of the page.
* [X] The Our Games section also includes a search bar where users can enter a specific game.
* [X] When you hover over a game card, it slightly scales up to draw attention and enhance interactivity.
* [X] Added hover effects to the buttons for better visual feedback and interactivity.
* [X] Slightly increased text size for headers and body to improve readability.


## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='https://imgur.com/a/MstblTA' title='WEB102 - Prework Video Walkthrough' width='' alt='WEB102 - Prework Video Walkthrough' />
GIF created with CloudConvert (https://cloudconvert.com/mp4-to-gif)

In case the GIF does not work, I've also provided a YouTube link below:
https://youtu.be/m9X8Y60H1wU

## Notes

Challenges encountered:

* During the second challenge, I ran into some confusion regarding the instruction to adding a CSS rule for the "stats-container" s.
  At first, I misinterpreted this as referring to an s element inside .stats-container. However, after checking the MDN documentation and
  getting clarification from ChatGPT, I realized that <s> is an HTML tag used to apply strikethroughs. The instruction was actually asking me
  to apply Flexbox styling and align the items within the .stats-container class.

* During the third challenge, after completing the addGamesToPage function and calling it, I noticed that my game cards were not displaying
  as expected. After reviewing my code and verifying the logic, I discovered that I have forgotten to declare the i variable in the for-loop,
  which caused the issue. Once I corrected that, the game cards appeared as intended.

* While working on the customization portion, I attempted to implement a fade-in animation for each game card so they would appear one by one
  as they loaded. However, this conflicted with the scaling animation I had already implemented for hover interactions. After some experimentation,
  I realized that putting both animations was causing the scaling effect to stop working properly. In the end, I decided to scrap the fade-in
  animation idea and keep the scaling animation since it provided better interactivity and visual feedback.

## License

    Copyright 2025 Kaylen Teves

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
