# Balloon Pop Maths #
[Balloon Pop Maths Live Site](https://richardhenyash.github.io/balloon-pop-maths/)  

<img src="./assets/testing/responsive/balloon-pop-maths-responsive.png" width="100%" style="margin: 15px;">

## Contents ##
- [Background](#background)
- [Project Goals](#project-goals)
- [Site Owner Goals](#site-owner-goals)
- [User Goals](#user-goals)
- [UX](#ux)
    - [Project Strategy](#project-strategy)
        - [Opportunities Matrix](#opportunities-matrix)
        - [Initial Development Phase](#initial-development-phase)
    - [Project Scope](#project-scope)
        - [User Demographics](#user-demographics)
        - [User Requirements](#user-requirements)
        - [User Stories](#user-stories)
        - [Contraints](#constraints)
        - [Functional Requirements](#functional-requirements)
        - [Business Rules](#business-rules)
        - [Key Features](#key-features)
    - [Site Map](#site-map)
    - [Wireframes](#wireframes)
    - [Design Choices](#design-choices)
        - [Fonts](#fonts)
        - [Colours](#colours)
- [Technologies](#technologies)
    - [Languages](#languages)
    - [Frameworks Libraries and Tools](#frameworks-libraries-and-tools)
- [Game Logic](#game-logic)

## Background ##
During the Covid pandemic, many parents have been required to facilitate education for their children at home. Often, parents have found
themselves juggling full time jobs and home education responsibilities. School work, especially for younger children, requires a 
high degree of facilitation and help from busy parents. Interative web based maths games can give children an engaging way of 
learning new maths skills and reinforcing existing maths knowledge independently.

## Project Goals ##
To provide a simple and engaging maths game that young children are able to play independently to learn new maths skills and to
reinforce existing maths knowledge.

## Site Owner Goals ##
Developing the site will serve as a learning experience for the developer. The finished website will act as a showcase for the
developer's new skills and will also help to raise the developer's profile. The developer also hopes that his 7 year old
son will become a keen user of the site!

## User Goals ##
To play the maths game for fun, to learn new maths skills and to reinforce existing maths knowledge.

## UX ##

### Project Strategy ###

#### Opportunities Matrix ####
The following opportunities were identified and ranked using a score of 1 - 5 for importance and viability:

Opportunity | Importance |Viability
------------| -----------|---------
Balloon Pop Multiplication game|5|4
Balloon Pop Division game|3|4
Balloon Pop Addition game|3|4
Balloon Pop Subtraction game|3|4
Contact Form to contact developer|3|5
Link to developer [GitHub](https://github.com/richardhenyash) page|4|5
Subscribe Option|1|2

<img src="/assets/wireframes/initial-strategy.png" style="margin: 15px; width: 400px;">

#### Initial Development Phase ####
The opportunities matrix was used to help decide which items should be included for the initial development phase (phase 1):
Item|Development Phase
----|-----------------
Balloon Pop Multiplication game|1
Contact Form to contact developer|1
Link to developer [GitHub](https://github.com/richardhenyash) page|1
Balloon Pop Division game|1
Balloon Pop Addition game|1
Balloon Pop Subtraction game|1
Subscribe Option|2

### Project Scope ###
#### User Demographics ####
* The primary users of the site will be Key Stage 1 and 2 school pupils from ages 5 to 10.
* A simple, bright, colorful and engaging design would fit this demographic.

#### User Requirements ####
* Visually engaging.
* Easy to navigate.
* Easy to update game settings.
* Responsive design is required as users may be viewing the site on Mobile, Tablet or Desktop.

#### User Stories ####
* ***As a user, I am playing the game for fun and enjoyment.***
* ***As a user, I am playing the game to learn new maths skills.***
* ***As a user, I am playing the game to reinforce existing maths knowledge.***
* ***As a user or parent, I would like to to provide feedback to the developer about the game.***

#### Constraints #####
* Developer skill set - the developer is currently learning JavaScript.
* Developer's available time - the developer is working full time whilst studying.
This coupled with the developer's current skills constraints may impact on whether
all four maths games can be incorporated into the site in the initial development phase.

#### Functional Requirements ####
* The user would like to be able to select different maths games to play.
* The user would like to be able to select different options within each maths game - e.g. 2x, 5x and 10x tables
within the multiplication game, or addition of numbers up to 20 in the addition game.
* The user would like to be able to set the difficulty level of the maths games -  this will give the games a wider age appeal.
* The user needs to be able to initiate the game from the menu, and return to the main menu if they want to abort the current game.
* The user would like to see their current score, and their previous top score. This will mean that the user is more likely to play
another game or return to the site in the future to better their previous score.
* The user would like to be able to contact the developer.

#### Business Rules ####
* It is not envisaged that the game will be sold for profit. However, the game should be as much fun as possible to play, in order to 
maximise the learning opportunities for users, increase the game's following and therefore increase the profile of the developer.

#### Key Features ####
The following key features have been identified and scored from 1 - 5 for importance and difficulty. The proposed development phase has also been indicated:
Feature|Importance|Difficulty|Development Phase
-------|----------|----------|-----------------
Balloon Pop Multiplication game| 5 | 3 | 1 |
Contact Form to contact developer | 4 | 2 | 1
Link to developer [GitHub](https://github.com/richardhenyash) page | 3 | 1 | 1
Balloon Pop Division game| 3 | 3 | 1
Balloon Pop Addition game| 3 | 3 | 1
Balloon Pop Subtraction game| 3 | 3 | 1
Subscribe Option| 1 | 3 | 2

### Site Map ###
An initial [Site Map](/assets/wireframes/site-map.png) was produced, and is shown below:  
<img src="./assets/wireframes/site-map.png" width="400px" style="margin: 15px;">

### Wireframes ###
[Hand Sketches](/assets/wireframes/rev0) were drafted showing the home page and times table game:  

<img src="./assets/wireframes/rev0/home-sketch.jpg" width="600px" style="margin: 15px;">
<img src="./assets/wireframes/rev0/game-sketch.jpg" width="600px" style="margin: 15px;">

[Initial Wireframes](/assets/wireframes/rev1) were then produced showing the [Home](/assets/wireframes/rev1/home-multiplication.png)
page layout for each game mode: [Multiplication](/assets/wireframes/rev1/home-multiplication.png), 
[Division](/assets/wireframes/rev1/home-division.png), [Addition](/assets/wireframes/rev1/home-addition.png) 
and [Subtraction](/assets/wireframes/rev1/home-subtraction.png).  The  home page [Multiplication](/assets/wireframes/rev1/home-multiplication.png)
layout is also shown below:  

<img src="./assets/wireframes/rev1/home-multiplication.png" width="600px" style="margin: 15px;"> 

[Initial Wireframes](/assets/wireframes/rev1) were also produced showing the [Game](/assets/wireframes/rev1/game-multiplication.png) 
page layout for each game mode: [Multiplication](/assets/wireframes/rev1/game-multiplication.png), 
[Division](/assets/wireframes/rev1/game-division.png), [Addition](/assets/wireframes/rev1/game-addition.png) 
and [Subtraction](/assets/wireframes/rev1/game-subtraction.png).  The game page [Multiplication](/assets/wireframes/rev1/game-multiplication.png)
layout is also shown below:  

<img src="./assets/wireframes/rev1/game-multiplication.png" width="600px" style="margin: 15px;"> 

[Responsive design wireframes](/assets/wireframes/rev2) were then produced showing the [Home](/assets/wireframes/rev1/home-multiplication.png)
and [Game](/assets/wireframes/rev1/game-multiplication.png) page layouts on [Tablet](/assets/wireframes/rev2/home-multiplication-tablet.png) and
[Phone](/assets/wireframes/rev2/home-multiplication-phone.png). The [Responsive design wireframes](/assets/wireframes/rev2) are also shown below:  

<img src="./assets/wireframes/rev2/home-multiplication-tablet.png" width="300px" align="left" style="margin: 15px;">
<img src="./assets/wireframes/rev2/game-multiplication-tablet.png" width="300px" style="margin: 15px;">
<img src="./assets/wireframes/rev2/home-multiplication-phone.png" width="300px" align="left" style="margin: 15px;">
<img src="./assets/wireframes/rev2/game-multiplication-phone.png" width="300px" style="margin: 15px;">  


### Design Choices ###

#### Fonts ####
[Whale I Tried](https://mistifonts.com/whale-i-tried/) has been chosen as the title font, and is used for the main **Balloon Pop Maths** [heading](./assets/testing/features/title.png). 
[Whale I Tried](https://mistifonts.com/whale-i-tried/) is a custom outlined cartoon font available from [Misti's Fonts](https://mistifonts.com/), 
and is free for personal and non-profit use. This font was chosen as it has a balloon like look and a soft, playful feel.
* font-family: "Whale I Tried", sans-serif;

[Nunito](https://fonts.google.com/specimen/Nunito?preview.text_type=custom) has been chosen as the main body font for text content. 
[Nunito](https://fonts.google.com/specimen/Nunito?preview.text_type=custom) is a clean, rounded and modern sans-serif font 
which works well with the maths game theme and complements the [Whale I Tried](https://mistifonts.com/whale-i-tried/) title font. 
[Nunito](https://fonts.google.com/specimen/Nunito?preview.text_type=custom) is available from [Google Fonts](https://fonts.google.com/) 
and is licensed under the [Open Font License](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL).
* font-family: 'Nunito', sans-serif;

#### Colours ####
The "sky" background colour is a 3 colour gradient generated using [ColorSpace](https://mycolor.space/gradient3). 
The three colours used (#7CC0FF, #6FD1F4, #9EFBF5) and the colour gradient generated are shown below:  

<img src="./assets/wireframes/colour-gradient.png" width="800px" style="margin: 15px;"> 

The colour palette was chosen to tie-in with the first colour in the 3 colour gradient (#7CC0FF). 
Colour ideas were generated using the [ColorSpace](https://mycolor.space/) colour palette generator. 
The final colour palette selected is shown below:  

<img src="./assets/wireframes/colour-palette.png" width="800px" style="margin: 15px;">  

* #908CD9 - "Blue Bell" - used for buttons, question area, score and high score outlines.
* #9C70BD - "Purple Mountain Majesty" - Used for button highlighting, footer and information area links and audio controls.
* #A2529A - "Purpureus" - Used for modal dialog text, high score text, score text, information text and highlighting.
* #3E8BC6 - "Green Blue Crayola" - Used for button and question area borders, 
* #EEFBFF - "Azure X 11 Web Color" - Used for title, button text, question text, balloon answer text and modal dialog background.
* #DC7774 - "Candy Pink" - Used for "Health" bar.
* #A9A9A9 - "Silver Chalice" - Used for text shadow on balloon answer text.

## Technologies ##
### Languages ###
* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://www.w3.org/Style/CSS/Overview.en.html)
* [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

### Frameworks Libraries and Tools ###
* [Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
* [jQuery](https://jquery.com/)
* [Font Awesome](https://fontawesome.com/)
* [Google Fonts](https://fonts.google.com/)
* [Email JS](https://www.emailjs.com/)
* [Jasmine](https://jasmine.github.io/) 


## Game Logic ##
The game logic was developed using [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript).  

When the user hits the [Play](./assets/testing/features/play.png) button, the heading, options and information
sections of the [index](index.html) page are hidden and the game section is shown. 
The selected options are gathered using functions in the [JavaScript Display Interaction Functions Library](./assets/js/display.js) 
and are stored in global variables. All global variables are initialised in the 
[JavaScript Initialisation Library](./assets/js/initialisation.js) and are prefixed with "bpm".  

The user is presented with a [maths question](./assets/testing/features/game-question.png). The question type depends on the selected 
[Game Mode](./assets/testing/features/game-mode.png). 
6 potential answers are presented in the [answer balloons](./assets/js/game-balloons.js), 1 correct answer and 5 wrong answers. 
Random maths questions and correct and incorrect answers are generated using functions in the 
[JavaScript Maths Function Library](./assets/js/maths.js).

If the game is played on "Easy" difficulty level (selected in options), [health](./assets/testing/features/game-health.png) is set to 5 hearts.
If the game is played on "Medium" difficulty level (selected in options), [health](./assets/testing/features/game-health.png) is set to 3 hearts.
If the game is played on "Hard" difficulty level (selected in options), [health](./assets/testing/features/game-health.png) is set to 1 heart.  

If the user selects the correct answer, the balloon "popping" animation and sound is played using functions in the 
[JavaScript Animation Function Library](./assets/js/animation.js), and the score increments by 1. 
If the user selects the wrong answer, the "deflate" sound is played, the selected balloon and answer text fades out and 
[health](./assets/testing/features/game-health.png) is depleted by 1 heart. The game continues until the user has either answered 
all of the questions or their [health](./assets/testing/features/game-health.png) has been fully depleted.  
