# WEB102 Prework - *Sea Monster Crowdfunding*

Submitted by: **Lily Shiomitsu**

**Sea Monster Website** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **2.5** hours spent in total

## Required Features

The following **required** functionality is completed:

* [x] The introduction section explains the background of the company and how many games remain unfunded.
* [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [x] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [x] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [x] Changed the CSS for the buttons so that the cursor is a pointer upon hovering. 

## Video Walkthrough

Here's a walkthrough of implemented features:

![gif](https://github.com/user-attachments/assets/b1fb2e33-2701-4689-91be-8ed42f8ef112)

<!-- Replace this with whatever GIF tool you used! -->
GIF created with `ezgif.com`
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

One challenge that I faced was figuring out how to format the text in the stats section. I thought 
that the format was "Example text ${variable}". However, what worked for me was using "Example text " + variable.
Another thing that was confusing for me was the use of `console.log` to call the `toLocaleString` function. It turns out
that this was not needed and I just called the `toLocaleString` function directly.

## License

    Copyright [2024] [Lily Shiomitsu]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
