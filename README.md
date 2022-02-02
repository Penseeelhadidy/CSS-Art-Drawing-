# CSS-Art-Drawing-

Hi there, this is a tutorial of a CSS Art drawing that I found from code and dream. 
In this project, I was inspired and curious to learn how to draw CSS vanilla art. I have never used vanilla art before, but I was intrigued by it!
I learned to either sketch or find an image to replicate.
Then to plan out the layers in which we will begin to get the overall structure of the CSS art drawing. In this case, it was an animated catcus in a pot!
I liked how, in code and dream, she has used colorhunt.co to help and aid your color scheme design to flow well. 
So, I started with an html.index file and a styles.css file.
In the very first step, i have followed and outlined all the css color schemes from colorhunt.co, to be used in a commentary for my reference. 
This is for the purpose to reference back the css styling numbers to draw the cactus as well as for the background layers. 

Some of the css properties I have learned were:
The box-shadow property attaches one or more shadows to an element.
notes to self: vmin and vh:vmin is the minimum between the viewport's height or width in percentage depending on which is smaller
vmax is the maximum between the viewport's height or width in percentage depending on which is bigger.
The ::before and ::after pseudo-elements in CSS allows you to insert content onto a page without it needing to be in the HTML. 
The ::after content is also “after” in source-order, so it will position on top of ::before if stacked on top of each other naturally.

Another interesting feature I learned from code and dream, was
@keyframes blink {
    0% {transform:scale(1, 0.1);}
    100% {transform: scale(1, 1);}
}

According to Web3docs:https://www.w3docs.com/snippets/css/how-to-create-a-blinking-effect-with-css3-animations.html
"the CSS3 allows creating animation without any Javascript code. 
To have a blinking text effect, you also need the @keyframes rule. We use CSS animation by defining some keyframes for our blinking text animation and set the visibility to "hidden". 
In our example below, we also add the -webkit- extension to the animation property for more browser compatibility"

Example of creating a blinking text effect with CSS3 animations:

<!DOCTYPE html>
<html>
  <head>
    <title>Title of the document</title>
    <style>
      .blink {
        animation: blink-animation 1s steps(5, start) infinite;
        -webkit-animation: blink-animation 1s steps(5, start) infinite;
      }
      @keyframes blink-animation {
        to {
          visibility: hidden;
        }
      }
      @-webkit-keyframes blink-animation {
        to {
          visibility: hidden;
        }
      }
    </style>
  </head>
  <body>
    Here is a <span class="blink">blinking</span> text.
  </body>
</html>

Overall, this was a great project that I have learned so much from code and dream.
And first time using vanilla css and animation! Hope you enjoyed reading this readme.doc
