# tipCalculator2017

**tipCalculator2017** is a tip calculator application for iOS.

Submitted by: **Yang Chen**

Time spent: **3.5** hours spent in total

## User Stories

The following **required** functionality is complete:

* [ ] User can enter a bill amount, choose a tip percentage, and see the tip and total values.
* [ ] Awesome color scheme for the tip calculator

The following **optional** features are implemented:

* [ ] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

<img src='http://boostshore.com/index_files/tipCalculator2017.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />


## Project Analysis

As part of your pre-work submission, please reflect on the app and answer the following questions below:

**Question 1**: "What are your reactions to the iOS app development platform so far? How would you describe outlets and actions to another developer? Bonus: any idea how they are being implemented under the hood? (It might give you some ideas if you right-click on the Storyboard and click Open As->Source Code")

**Answer:** iOS app development is relative new development compare with Java or C. It is using a new language swift/Obj-C. outlets is a way to handle events. it allows you to write event functions for you UI Component, then use outlet to link them together. Actions is the result performed after you link your method with certain outlet. For under the hood, if you right click on the storyboard or UI Component, it lists all the possible events able to performed by that storyboard or UI then display on the outlet. when you link your method to the outlet. it add your method under the existing event method. 
<!--
Question 2: "Swift uses [Automatic Reference Counting](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/AutomaticReferenceCounting.html#//apple_ref/doc/uid/TP40014097-CH20-ID49) (ARC), which is not a garbage collector, to manage memory. Can you explain how you can get a strong reference cycle for closures? (There's a section explaining this concept in the link, how would you summarize as simply as possible?)"

**Answer:** [Enter your answer here in a paragraph or two].
-->

## License

    Copyright [2017] [YANG CHEN]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
