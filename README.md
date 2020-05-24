# Match The Spartans
Milestone Project #2 : Interactive Frontend Development  - Code Institute 

## Demo
[Live demo](https://nikolaspolychronidis.github.io/Match-The-Spartans/) is available here.

I have built a small card matching game. The game's theme is based on ancient Greek history. The player is supposed to match every pair of cards within 200 seconds.
The back of the cards carries a red black Lamda, the first letter of the word Lacedemonians, the name Spartans and surrounding settlements called themselves. 
The front of the cards carries pairs of different soldier icons.

## UX

The purpose of this project is to create a fun and aesthetically pleasing matching game. 

**In order to achieve and fun and aesthetically pleasing game I did the following:**

- When the game is launched a start screen pops up with a message. The player is told to prepare and click to play.

![](![](assets/images/start-game.jpg "Full picture on the Start screen.")


- The back of the cards carries a red black Lamda, the first letter of the word Lacedemonians, the name Spartans and surrounding settlements called themselves.

![](assets/images/gameplay-1.jpg "Full picture gameplay")

- The front of the cards carries pairs of different soldier icons. The player is supposed to match them in pairs. When Cards are matched they remain as they are with the soldiers display.

![](assets/images/gameplay-3.jpg "Full picture gameplay")

- If the cards do not match they are flipped and the player sees the Lamda again.

![](assets/images/gameplay-2.jpg "Full picture gameplay")

- If the time runs out before the player has managed to match all the card then a failure screen is displayed.

![](assets/images/failed.jpg "Full picture of the failure screen")

- If the player matches all the cards before time runs out, then a victory message is displayed.

![](assets/images/victory.jpg "Full picture of the victory screen")



>I did my best to keep the colors as of the website as consistent as possible, in order to ensure a possitive user experience.
 
 ### Wireframe Mockups
 
 These can be found at the following links below:
- [Single page wireframe](assets/images/wireframe.jpg)
 

## Technologies
1. HTML
2. CSS
3. JavaScript

## Testing
This site was physically tested for display as well as gameplay across multiple browsers  (Chrome, Safari, FireFox, Opera) and on multiple mobile devices using Google developer tool(iPad, iPad Pro, iPhone X, iPhone 6/7/8 (Plus), iPhone 5/SE, Pixel 2 (XL), Galaxy S5). The site is compatible and responsive in all of the above.

## Development
- I used Gitpod for a developer tool (IDE) in this project.

## Deployment
This site is deployed directly from the master branch. I deployed it by going to my repository -> settings -> Github pages -> and in the dropdown I clicked Master Branch which hosts the website on GitHub Pages.

## Validation
Html, Css and Javascript code was validated and checked for errors at:
- https://validator.w3.org/
- https://jigsaw.w3.org/css-validator/
- https://jshint.com/

- No errors were found in the css and HTML. The JavaScript had a few warning due to the arrow function syntax (=>) that is only available in ES6 (use 'esversion: 6').
- What I did to move past that was going to 
File -> Preferences -> Settings
Default User Settings -> JSHint configuration
Looked for "jshint.options": {},
Changed it to "jshint.options": {"esversion": 6}, by clicking on Edit on the left side.

#### Lamda image on back of cards 
Cropped by the Creative Assembly's PC game "Rome 2 Total War". 

I do not own the rights to any of the above images. All rights are reserved to Creative Assembly. This project was created for educational purposes only and falls under the "Fair use" policies.

#### Soldier Icon Images on front of cards
Cropped by the Creative Assembly's PC game "Rome 2 Total War". 

I do not own the rights to any of the above images. All rights are reserved to Creative Assembly. This project was created for educational purposes only and falls under the "Fair use" policies.

#### I do not own the rights to any of the above images.  This project was created for educational purposes only and falls under the "Fair use" policies.


### Acknowledgements
- [Code Institute](https://www.codeinstitute.net/) 
- [W3schools.com](https://www.w3schools.com/bootstrap/bootstrap_theme_band.asp) - I have used w3schools to learn how to create the bio section of my project including the body, heading and images as well as hover effects and round effect. I did creat the box and the opaque background myself.
- [Bootstrap](https://getbootstrap.com/) - The navbar as well as all buttons were taken from bootstrap documentation page and were modified/edited (sizes, colors, hovers, text-alignment, etc).


