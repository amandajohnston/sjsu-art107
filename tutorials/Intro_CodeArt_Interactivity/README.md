# **INTRO TO P5 & CODING- VARIABLES & INTERACTIVITY!**

### **++[SJSU Art 107 Fall 2019](https://carriehott.github.io/sjsu-art107/)++**

[<Back to Tutorials](https://carriehott.github.io/sjsu-art107/tutorials)

#### **Related Pages:**
* [Interactive Art Lecture](https://carriehott.github.io/sjsu-art107/tutorials/Interactive_Art)
* [p5 Drawing Basics Tutorial](https://carriehott.github.io/sjsu-art107/tutorials/Intro_CodeArt/)
* [p5- Complex Shapes and Color](https://carriehott.github.io/sjsu-art107/tutorials/Intro_CodeArt_Color)
* [p5- Adding Images](https://carriehott.github.io/sjsu-art107/tutorials/Intro_CodeArt_Images)
* [p5- Put on GitHub](https://carriehott.github.io/sjsu-art107/tutorials/Intro_CodeArt_GitHub)

#### **Other Resources:**
* [p5js.org](https://p5js.org/)
* [p5js.org Code Reference Library](https://p5js.org/reference)
* [Coding Train YouTube Channel- p5](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA)
<br>

#### **On this page:**
1. [What's a Variable?](#what-is-a-variable)
2. [mouseX and mouseY](#mouseX-and-mouseY)
3. [mousePressed](#mousePressed)
4. [Make Your Own Variable](#make-your-own-variable)
5. [Adding Math](#adding-math)
6. [Variable Scope](#variable-scope)
7. [Conditional Statements](#conditional-statements)
8. [Keyboard Input](#keyboard-input)
9. [Logical Operators](#logical-operators)
10. [Width, Height, and Bounce!](#width-height-and-bounce)
11. [Create Your Own](#create-your-own)

# What Is a Variable

![Intro p5](images/p5_Variables.008.jpeg)

![Intro p5](images/p5_Variables.009.jpeg)

![Intro p5](images/p5_Variables.010.jpeg)

![Intro p5](images/p5_Variables.011.jpeg)

![Intro p5](images/p5_Variables.012.jpeg)

# mouseX and mouseY

![Intro p5](images/p5_Variables.013.jpeg)

![Intro p5](images/p5_Variables.014.jpeg)

![Intro p5](images/p5_Variables.015.jpeg)

![Intro p5](images/p5_Variables.016.jpeg)

![Intro p5](images/p5_Variables.017.jpeg)

# mousePressed

![Intro p5](images/p5_Variables.018.jpeg)

# Make Your Own Variable

![Intro p5](images/p5_Variables.019.jpeg)

![Intro p5](images/p5_Variables.020.jpeg)

![Intro p5](images/p5_Variables.021.jpeg)

![Intro p5](images/p5_Variables.022.jpeg)

![Intro p5](images/p5_Variables.023.jpeg)

# Adding Math

![Intro p5](images/p5_Variables.024.jpeg)

![Intro p5](images/p5_Variables.025.jpeg)

![Intro p5](images/p5_Variables.026.jpeg)

![Intro p5](images/p5_Variables.027.jpeg)

![Intro p5](images/p5_Variables.028.jpeg)

![Intro p5](images/p5_Variables.029.jpeg)

![Intro p5](images/p5_Variables.030.jpeg)

![Intro p5](images/p5_Variables.031.jpeg)

![Intro p5](images/p5_Variables.032.jpeg)

# Variable Scope

![Intro p5](images/p5_Variables.033.jpeg)

![Intro p5](images/p5_Variables.034.jpeg)

# Conditional Statements

![Intro p5](images/p5_Variables.035.jpeg)

![Intro p5](images/p5_Variables.036.jpeg)

![Intro p5](images/p5_Variables.037.jpeg)

![Intro p5](images/p5_Variables.038.jpeg)

# Keyboard Input

![Intro p5](images/p5_Variables.039.jpeg)

![Intro p5](images/p5_Variables.040.jpeg)

![Intro p5](images/p5_Variables.041.jpeg)

![Intro p5](images/p5_Variables.042.jpeg)

![Intro p5](images/p5_Variables.043.jpeg)

# Logical Operators

![Intro p5](images/p5_Variables.044.jpeg)

![Intro p5](images/p5_Variables.045.jpeg)

![Intro p5](images/p5_Variables.046.jpeg)

##### Code to copy to the editor:

    function setup() {
      createCanvas(500, 500);
      background(200, 10, 100);
      strokeWeight(3);
    }

    function draw() {
      if (mouseX > 400) {
        //yellow
        fill(255, 255, 0);
      } else if (mouseX > 300) {
        //violet
        fill(101, 22, 232);
      } else if (mouseX > 200) {
        //green
        fill(101, 250, 182);
      } else if (mouseX > 100) {
        //pink
        fill(255, 142, 182);
      } else {
        //orange
        fill(255, 142, 0);
      }
  	  triangle(50, 400, 150, 400, 100, 480);
      quad(30, 100, 300, 450, 350, 150, 200, 50);
      }

<br>
<br>

![Intro p5](images/p5_Variables.047.jpeg)

##### Code to copy to the editor:

    function setup() {
      createCanvas(500, 500);
    }

    function draw() {
      background(200, 100, 100);
      noStroke();
      if (mouseX > 400 && mouseY > 400) {
      triangle(100, 100, 200, 100, 250, 200);
      text("Here it is", 150, 125);
    }
    }

<br>
<br>


# Width Height and Bounce

![Intro p5](images/Code_Bounce.001.jpeg)

![Intro p5](images/Code_Bounce.002.jpeg)

![Intro p5](images/Code_Bounce.003.jpeg)

![Intro p5](images/Code_Bounce.004.jpeg)

![Intro p5](images/Code_Bounce.005.jpeg)

![Intro p5](images/Code_Bounce.006.jpeg)

![Intro p5](images/Code_Bounce.007.jpeg)

## More Resources:
## [Watch the Coding Train video on the Bouncing Ball](https://www.youtube.com/watch?v=LO3Awjn_gyU&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=13)

## [Check out the p5 Bounce Examples](https://p5js.org/examples/motion-bounce.html)

# Create Your Own

## [Go to the p5 Learn page on Interactivity](https://p5js.org/learn/interactivity.html)
