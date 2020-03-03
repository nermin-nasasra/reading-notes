**psychological safety**
Yet many of today’s most valuable firms have come to realize that analyzing and improving individual workers ­— a practice known as ‘‘employee performance optimization’’ — isn’t enough. 
Five years ago, Google — one of the most public proselytizers of how studying workers can transform productivity — became focused on building the perfect team. In the last decade, the tech giant has spent untold millions of dollars measuring nearly every aspect of its employees’ lives. 
**project Aristotle’s researchers**
began by reviewing a half-century of academic studies looking at how teams worked.No matter how researchers arranged the data, though, it was almost impossible to find patterns — or any evidence that the composition of a team made any difference.
**the technology industry**
s not just one of the fastest growing parts of our economy; it is also increasingly the world’s dominant commercial culture. And at the core of Silicon Valley are certain self-mythologies and dictums: Everything is different now, data reigns supreme, today’s winners deserve to triumph because they are cleareyed enough to discard yesterday’s conventional wisdoms and search out the disruptive and the new.

### CSS
*Transforms*
div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}

CSS transforms allow you to move, rotate, scale, and skew elements.
**2D Rotate**
transform: rotate(20deg);
The transform property accepts a handful of different values. The rotate value provides the ability to rotate an element from 0 to 360 degrees. 
**2D Scale**
transform: scale(.75);
Using the scale value within the transform property allows you to change the appeared size of an element. 
**2D Translate**
transform: translateX(-10px);
The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document.
**2D Skew**
transform: skew(5deg, -20deg);
The last transform value in the group, skew, is used to distort elements on the horizontal axis, vertical axis, or both.

*Transitions*
As mentioned, for a transition to take place, an element must have a change in state, and different styles must be identified for each state. 
.box {
  background: #2db34a;
  transition-property: background;
  transition-duration: 1s;
  transition-timing-function: linear;
}

*Rotate elements*
CSS transforms have a number of different uses, and one of the best is transforming the rotation of an element. Give your div the class “rotate” and add the following to your CSS:
.rotate:hover
{
        -webkit-transform: rotateZ(-30deg);
        -ms-transform: rotateZ(-30deg);
        transform: rotateZ(-30deg);
}

*Square to circle*
A really popular effect at the moment is transitioning a square element into a round one, and vice versa. With CSS, it’s a simple effect to achieve, we just transition the border-radius property.
.circle:hover
{
        border-radius:50%;
}

*3D shadow*
This effect is achieved by adding a box shadow.
threed:hover
{
        box-shadow:
                1px 1px #53a7ea,
                2px 2px #53a7ea,
                3px 3px #53a7ea;
        -webkit-transform: translateX(-3px);
        transform: translateX(-3px);
}

*Inset border*
.border:hover
{
        box-shadow: inset 0 0 0 25px #53a7ea;
}

