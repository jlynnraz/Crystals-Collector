## Crystals Collector
The Crystals Collector will assign you 4 crystals with randomly generated values. Click the crystals and hit the target amount without going over!

## Motivation
Crystals Collector was designed to test my skills in jQuery. jQuery is used for a series of onClicks which contain the calculations to determine whether the user has won or lost.
  
## Sneak Peak
![Crystals](https://user-images.githubusercontent.com/53287044/74378972-204b4300-4da4-11ea-8eb8-c61613af18bd.jpg)

## Installation
* Fork It
* Clone It
* Open in your default browser, or view live demo [HERE](https://jlynnraz.github.io/Crystals-Collector/) 

## Technologies
* JavaScript 
* jQuery 
* HTML 
* CSS 

## Behind the Scenes
An if/else if is used to determine whether or not the user has hit the target number. If they hit the target number, an alert will be sent out that "You win!". If they go over the target number, it will alert "You lose!".
~~~
 if (counter === targetNumber) {

                // If the numbers match we'll celebrate the user's win.
                alert("You win!");
                wins++;
                $("#wins").text(wins);
                gameRestart();
            } else if (counter > targetNumber) {

                // Then they are alerted with a loss.
                alert("You lose!!");
                losses++;
                $("#losses").text(losses);
                gameRestart();
            }
        })
~~~

## Contact
Please contact me directly with any comments of questions!
* jlynnraz@gmail.com
* [LinkedIn](https://www.linkedin.com/in/jaimee-razee/)
* [Portfolio](https://jlynnraz.github.io/Portfolio2/)

