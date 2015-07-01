#Simple-Timerbar
This is a simple timerbar I used in a project.

##CSS That I learned/Reviewed
####animation-name
      -webkit-animation-name: fillbar; /* Chrome, Safari, Opera */
      animation-name: fillbar;

>This gives the name for the @keyframes animation

***
####animation-duration
    -webkit-animation-duration: 60s;
     animation-duration: 60s;
>This gives the duration of animation in seconds
***
####animation-timing
    -webkit-animation-timing-function: linear;
     animation-timing-function: linear;
>This gives it the style in which it will animate
>[W3C List of timing function values](http://www.w3schools.com/cssref/tryit.asp?filename=trycss3_animation-timing-function2)
***
####animation-direction
    -webkit-animation-direction: normal;
    animation-direction: normal;
>This controls the direction of the animation. There various options to choose from.
>[W3C](http://www.w3schools.com/cssref/css3_pr_animation-direction.asp)

***
####linear-gradient
    background-image: linear-gradient(to right, #f00439, #f28d0d); 
>A linear gradient starting from left to right
***
####keyframes
    @-webkit-keyframes fillBar {
      0% {
        width: 100%;
      }
      100% {
        width: 0%;
      }
    }
      @keyframes fillBar {
        0% {
         width: 100%;
         }
        100% {
         width: 0%;
         }
     }

>The @keyframes rule sets the specific animation code.
>[W3C](http://www.w3schools.com/cssref/css3_pr_animation-keyframes.asp)
***
##Other techniques used
    touch readme.md
>This is to create files in the terminal/commandl prompt

    mkdir dirname
>Makes a directory

##Purpose of this project
To get more familiar with git and other coding practices. To show members of BC some basics.