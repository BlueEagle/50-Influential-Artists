# Sprint Challenge: Advanced CSS and Intro to JavaScript - Influential Artists

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored Advanced CSS and JavaScript fundamentals. During this Sprint, you studied studied preprocessing, variable declaration, conditionals, loops, functions, arrays, and objects. In your challenge this week, you will demonstrate proficiency by creating a website for artisits with data from a `JSON` object.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your TL if you need direction. Your work reflects your proficiency in Preprocessing, and JavaScript Basics.

> You have **three hours** to complete this challenge. Plan your time accordingly.

## Introduction

In this challenge, you will use a data set of influential artists to build a "influential artists" webpage. This data comes from a set of "50 influential artists" on [kaggle](https://www.kaggle.com/ikarus777/best-artworks-of-all-time). We have reduced the data to just 20 artists to make it slightly easier to work with. You can work with the full dataset as a stretch goal.

### Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your team lead.

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. How would you describe preprocessing to someone new to CSS?

Preprocessing is a using extra, third party language features, where additional software compiles it to work with the platform.
In CSS, an example of this is nesting selectors inside other selectors for specificity and organization.

2. What is your favorite concept in preprocessing? What is the concept that gives you the most trouble?

My favorite concept of preprocessing as it relates to CSS is parametric mixins, being able to pass arguments into mixins is the closest thing CSS has to programming in my mind.

3. How would you explain the concept of a variable to someone new to programming?

A variable is an object which represents a value, which in most cases stands in place of a value which can be used in many places and may be changed.

4. What is the purpose of using functions in code?

Functions allow code to be containerized. It helps keep our code DRY by reducing how often we repeat instruction. It also helps to minimize clutter in the namespace.

5. What is a JSON data?

Javascript Object Notation(JSON) is a beautiful stardard of representing data in a structured form that also makes sense according to the object format used in Javascript. It has therefore become massively popular for it's simplicity and readability. It is the standard for most operations done in Javascript.


You may need to look up an answer but, you are expected to be able to answer all these questions. Your responses contribute to your Sprint Challenge grade. Skipping this section *will* prevent you from passing this challenge.

## Instructions

### Task 1: Project and Pre-processer Set Up

Follow these steps to set up your project:

#### Git Set up

- [x] Create a forked copy of this project.
- [x] Add your Team Lead as collaborator on Github.
- [x] Clone your OWN version of the repository (Not Lambda's by mistake!).
- [x] Create a new branch: git checkout -b `<firstName-lastName>`.

#### Preprocessor Set up

* [x] Verify that you have LESS installed correctly by running `lessc -v` in your terminal, if you don't get a version message back, reach out to your project manager for help.
* [x] In your project's root folder, run the following command `less-watch-compiler less css index.less`
* [x] Verify your compiler is working correctly by changing the `background-color` on the `body` selector to `red` in your `index.less` file.
* [x] Once you see the red screen, you can delete that style and you're ready to start on the next task

### Task 2a:  Minimum Viable Product - PreProcessing

#### Import LESS Files

* [x] Navigate to your `index.less` file. Notice the file is blank. You have been asked to use a certain import order. That order is as follows:

```markdown
1.variables.less
2.mixins.less
3.reset.less
4.general.less
5.navigation.less
6.main.less
7.cta.less
```

_You will know everything is working properly when you see the styles enabled for the provided content._  

#### Home Page - Desktop HTML & LESS

* [x] Take 10 minutes to review the code that has already been provided for you. Take time to see how the home page was built.
* [x] Add a viewport meta tag to the head of your index.html page.
* [x] [Review the provided design files](design/). You have been provided all content necessary in the [index.html file](index.html).
* [x] Navigation Styles: Use the `navigation.less` file for styling.
* [x] Main Content Styles: Use the `main.less` file for styling.
* [x] LESS Mixins: Create and use 2 different mixins to aid your styling. Use the `mixins.less` file for your mixins.
* [x] LESS Parametric Mixin: create a parametric mixin that is used to create the `contact us` button styles.
* [x] Use at least 2 parameters to create your button.
* [x] Add responsive breakpoints to your code for 500px such that your styles match the mobile design file.

### Task 2b: Minimum Viable Product - JavaScript

Navigate to `index.js` and complete the MVP challenges. Note that you need to scroll past data (or collapse data in VScode) to find the challenges.

### Task 3: Stretch Problems

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals, also listed in `index.js`, where applicable:

* [ ] Use JavaScript to programmatically create HTML elements in the console and copy them to display all 20 artists on the page
* [ ] Create a function called `randomize` that takes a data array as an argument and returns a the same array in a randomized order.
* [ ] Use advanced array methods (.map, .reduce, .filer) to refactor your MVP code (create an array of all artists born in the 1900s with .filter, for example)
* [ ] Add responsive breakpoints to your code by using media queries
* [ ] Add CSS animations

## Resources

📚[Best Practices for Responsive Design](https://www.browserstack.com/guide/responsive-design-breakpoints)

🤝[W3 Schools - Responsive Design](https://www.w3schools.com/html/html_responsive.asp)

👀 [Styling with HTML and CSS](https://www.w3schools.com/html/html_css.asp)

## Submission format

Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo). **Please don't merge your own pull request**
- [ ] Add your team lead as a reviewer on the pull-request
- [ ] Your team lead will count the project as complete by merging the branch back into master
