# amazon
header: Represents a container for introductory content or a group of navigational elements typically found at the top of a webpage.

nav: Defines a section of navigation links, often used to create menus or lists of links for navigating within the webpage or to other pages.

div: A generic container element used to group and style content together for layout and styling purposes.

i: Typically used to italicize text, but in modern HTML, it's often used for icons or other visual elements.

span: An inline container used to apply styles or scripting to a specific section of text or inline content.

p: Represents a paragraph of text, providing structure and spacing for blocks of textual content.

option: Used within a select element to define individual selectable options within a dropdown list.

select: Creates a dropdown list or selection box, allowing users to choose from a list of predefined options.

button: Generates a clickable button element, often used to trigger actions or submit forms.

ul: Stands for "unordered list" and is used to create a bulleted list of items.

li: Represents a list item within an ordered (ol) or unordered (ul) list, creating individual entries in the list.
In this article, we will learn about the CSS Margin & Padding properties of the Box Model & understand their implementation through the example. 
box-sizing: Determines how the width and height of an element are calculated, accounting for padding and borders if set to border-box.

scroll-behavior: Defines the scrolling behavior when navigating to anchor links, allowing smooth scrolling to the target.

overflow: Controls what happens when the content of an element overflows its dimensions.

margin: Sets the spacing outside an element's border, creating space between elements.

border: Sets the properties of an element's border, including width, style, and color.

border-radius: Defines the curvature of the corners of an element, creating rounded corners.

flex-direction: Specifies the direction of flexible items in a flex container.

font-weight: Determines the thickness or boldness of the font characters.

font-size: Sets the size of the font characters.

background-color: Sets the background color of an element.

height: Defines the height of an element.

width: Sets the width of an element.

padding: Specifies the spacing between an element's content and its border.

justify-content: Aligns flex items along the main axis of a flex container.

max-width: Sets the maximum width an element can have.

gap: Sets the spacing between rows and columns in a grid or flex layout.

align-items: Aligns flex items along the cross axis of a flex container.

display: Specifies how an element should be displayed (e.g., block, inline, flex).

list-style: Sets the style of the list marker for list items.

text-decoration: Sets the decoration applied to text (e.g., underline, line-through).

hover: Refers to the state when a user's cursor is over an element.

cursor: Sets the appearance of the cursor when it's over an element.

color: Sets the color of the text content.

CSS Margins: CSS margins are used to create space around the element. We can set the different sizes of margins for individual sides(top, right, bottom, left).

Margin properties can have the following values:

    Length in cm, px, pt, etc.
    Width % of the element.
    Margin calculated by the browser: auto.

Syntax: 

body {
    margin: value;
}

The margin property is a shorthand property having the following individual margin properties:

    margin-top: It is used to set the top margin of an element.
    margin-right: It is used to set the right margin of an element.
    margin-bottom: It is used to specify the amount of margin to be used on the bottom of an element.
    margin-left: It is used to set the width of the margin on the left of the desired element.

Note: The margin property allows negative values.

We will discuss all 4 properties sequentially.

If the margin property has 4 values: 

margin: 40px 100px 120px 80px;

    top = 40px
    right = 100px
    bottom = 120px
    left = 80px

Example:  This example describes the margin property by specifying the four values.

<!DOCTYPE html>
<html>
 
<head>
    <style>
        p {
            margin: 80px 100px 50px 80px;
        }
    </style>
</head>
 
<body>
    <h1>
        GeeksforGeeks
    </h1>
    <p> Margin properties </p>
</body>
 
</html>

Output:

If the margin property has 3 values: 

margin: 40px 100px 120px; 

    top = 40px
    right and left = 100px
    bottom = 120px

Example: This example describes the margin property by specifying the three values.

<!DOCTYPE html>
<html>
 
<head>
    <style>
        p {
            margin: 80px 50px 100px;
        }
    </style>
</head>
 
<body>
    <h1>
        GeeksforGeeks
    </h1>
    <p>
        Margin properties
    </p>
</body>
 
</html>

Output:

If the margin property has 2 values:

margin: 40px 100px; 

    top and bottom = 40px;
    left and right = 100px;

Example:  This example describes the margin property by specifying the double value.

<!DOCTYPE html>
<html>
 
<head>
    <style>
        p {
            margin: 100px 150px;
        }
    </style>
</head>
 
<body>
    <h1>
        GeeksforGeeks
    </h1>
    <p>
        Margin properties
    </p>
</body>
 
</html>

Output:

If the margin property has 1 value: 

margin: 40px; 

    top, right, bottom and left = 40px

Example: This example describes the margin property by specifying the single value.

<!DOCTYPE html>
<html>
 
<head>
    <style>
        p {
            margin: 100px 150px;
        }
    </style>
</head>
 
<body>
    <h1>
        GeeksforGeeks
    </h1>
    <p>
        Margin properties
    </p>
</body>
 
</html>
CSS border properties allow us to set the style, color, and width of the border. 

Note: Different properties can be set for all the different borders i.e.top border, right border, bottom border, and left border. 

Properties of CSS Borders:  

1. Border Style

    CSS border-top style Property
    border-right-style Property
    border-bottom-style Property
    border-left-style Property

2. Border Width

    border-top-width Property
    border-right-width Property
    border-bottom-width Property
    border-left-width Property

3. Border Color

    border-top-color Property
    border-right-color Property
    border-bottom-color Property
    border-left-color Property

4. Border individual sides

5. Border radius property

1. Border Style: The border-style property specifies the type of border. None of the other border properties will work without setting the border style. 

Following are the types of borders:

    dotted – It describes a dotted border
    dashed – It describes a dashed border
    solid – It describes a solid border
    double – It describes a double border
    groove – It describes a 3D grooved border.
    ridge – It describes a 3D ridged border.
    inset – It describes a 3D inset border.
    outset – It describes a 3D outset border.
    none – It describes no border
    hidden – It describes the hidden border

Example: 

<!DOCTYPE html>
<html>
 
<head>
    <style>
        p.dotted {
            border-style: dotted;
        }
 
        p.dashed {
            border-style: dashed;
        }
 
        p.solid {
            border-style: solid;
        }
 
        p.double {
            border-style: double;
        }
    </style>
</head>
 
<body>
    <h2>The border-style Property</h2>
 
    <p>Geeksforgeeks</p>
 
 
    <p class="dotted">A dotted border.</p>
 
    <p class="dashed">A dashed border.</p>
 
    <p class="solid">A solid border.</p>
 
    <p class="double">A double border.</p>
 
</body>
 
</html>

Output: 

2. Border Width: Border width sets the width of the border. The width of the border can be in px, pt, cm or thin, medium, and thick.

Example: 

<!DOCTYPE html>
<html>
 
<head>
    <style>
        p {
            border-style: solid;
            border-width: 8px;
        }
    </style>
</head>
 
<body>
    <p>
        Geeksforgeeks
    </p>
    <p>
        Border properties
    </p>
</body>
 
</html>

Output: 

3. Border Color: This property is used to set the color of the border. Color can be set using the color name, hex value, or RGB value. If the color is not specified border inherits the color of the element itself.

Example: 

<!DOCTYPE html>
<html>
 
<head>
    <style>
        p {
            border-style: solid;
            border-color: red
        }
    </style>
</head>
 
<body>
    <p>
        Geeksforgeeks
    </p>
    <p>
        Border properties:color
    </p>
</body>
 
</html>

Output: 

4. Border individual sides: Using border property, we can provide width, style, and color to all the borders separately for that we have to give some values to all sides of the border.

Syntax: 

border-top-style : dotted;
border-bottom-width: thick;
border-right-color: green;
etc.

Example: In this example, we set border-top-style as dotted in h2.

<!DOCTYPE html>
<html>
 
<head>
    <style>
        h2 {
            border-top-style: dotted;
        }
    </style>
</head>
 
<body>
    <h2>Welcome to GeeksforGeeks</h2>
</body>
 
</html>

Output:

More Examples on CSS Border:

Example: In this example, we use border style, and border style property on the p tag.

<!DOCTYPE html>
<html>
 
<head>
    <style>
        p {
            border-style: solid dashed dotted double;
            border-color: red;
        }
    </style>
</head>
 
<body>
 
    <p>
      Geeksforgeeks
    </p>
    <p>
        Border properties:color
    </p>
 
</body>
 
</html>

Output: 

Syntax: If border properties have 3 values then:

border-style: solid dotted double
Solid:top border
Dotted: Left and right border
Double: bottom border

Example: 

<!DOCTYPE html>
<html>
 
<head>
    <style>
        p {
            border-style: solid dashed dotted;
            border-color: blue;
        }
    </style>
</head>
 
<body>
 
    <p>
        Geeksforgeeks
    </p>
    <p>
        Border properties:color
    </p>
 
</body>
 
</html>

Output: 

Syntax: If border properties have 2 values

border-style:solid dotted
Solid:top and bottom border
Dotted: right and left border

Example:

<!DOCTYPE html>
<html>
 
<head>
    <style>
        p {
            border-style: solid dashed;
            border-color: blue;
        }
    </style>
</head>
 
<body>
 
    <p>Geeksforgeeks</p>
    <p>
        Border properties:color
    </p>
 
</body>
 
</html>

Output: 

Syntax: If border properties have 1 value

border-style:dotted
Dotted:top, bottom, left and right border

Example:

<!DOCTYPE html>
<html>
 
<head>
    <style>
        p {
            border-style: solid;
            border-color: green;
        }
    </style>
</head>
 
<body>
 
    <p>
        Geeksforgeeks
    </p>
    <p>
        Border properties:color
    </p>
 
</body>
 
</html>

Output: 

5. Border radius property: It is used to round the corner of the border that looks more attractive.

Example:

<!DOCTYPE html>
<html>
 
<head>
    <style>
        h1 {
            border-style: solid;
            text-align: center;
            background: green;
            border-radius: 20px;
        }
    </style>
</head>
 
<body>
    <h1>GeeksforGeeks</h1>
</body>
 
</html>
The flexbox or flexible box model in CSS is a one-dimensional layout model that has flexible and efficient layouts with distributed spaces among items to control their alignment structure ie., it is a layout model that provides an easy and clean way to arrange items within a container. Flexbox can be useful for creating small-scale layouts & is responsive and mobile-friendly.

Features of flexbox:

    A lot of flexibility is given.
    Arrangement & alignment of items.
    Proper spacing
    Order & Sequencing of items.
    Bootstrap 4 is built on top of the flex layout.

Before the flexbox model, we had 4 layout modes:

    Block: It is used to make sections in web pages.
    Inline: It is used for text.
    Table: It is used for two-dimensional table data.
    Positioned: It is used for the explicit position of an element.

There are 2 main components of the Flexbox:

    Flex Container: The parent “div” which contains various divisions is called a flex container.
    Flex Items: The items inside the container “div” are flex items.

For creating the flexbox, we need to create a flex container along with setting the display property to flex.

<!DOCTYPE html>
<html>
 
<head>
    <title>Flexbox Tutorial</title>
    <style>
    .flex-container {
        display: flex;
        background-color: #32a852;
    }
     
    .flex-container div {
        background-color: #c9d1cb;
        margin: 10px;
        padding: 10px;
    }
    </style>
</head>
 
<body>
    <h2>GeeksforGeeks</h2>
    <h4> Flexbox</h4>
    <div class="flex-container">
        <div>Item1</div>
        <div>Item2</div>
        <div>Item3</div>
    </div>
</body>
 
</html>

Output:

Flexbox Axes: While working with Flexbox, we deal with 2 axes:

    Main Axis
    Cross Axis

Main Axis:

    By default, the main axis runs from left to right.
    Main Start: The start of the main axis is called Main Start.
    Main Size: The length between Main Start and Main End is called Main Size.
    Main End: The endpoint is called Main End.
    Main And Cross Axis

left to right:

flex-direction: row;

right to left:

flex-direction: row-reverse;

top to bottom:

flex-direction: column;

bottom to top:

flex-direction: column-reverse;

Cross Axis: The cross axis will be perpendicular to the main axis.

    By default, Cross Axis runs perpendicular to the Main Axis i.e. from top to bottom.
    Cross Start: The start of the Cross axis is called Cross Start.
    Cross Size: The length between Cross Start and Cross End is called Cross Size.
    Cross End: The endpoint is called Cross End.
Transitions in CSS allow us to control the way in which transition takes place between the two states of the element. For example, when hovering your mouse over a button, you can change the background color of the element with help of CSS selector and pseudo-class. We can change any other or combination of properties, though. The transition allows us to determine how the change in color takes place. We can use the transitions to animate the changes and make the changes visually appealing to the user and hence, giving a better user experience and interactivity. In this article, we will show you how to animate the transition between the CSS properties. There are four CSS properties that you should use, all or in part (at least two, transition-property and transition-duration, is a must), to animate the transition. All these properties must be placed along with other CSS properties of the initial state of the element:

1. transition-property: This property allows you to select the CSS properties which you want to animate during the transition(change). 

Syntax:

transition-property: none | all | property | property1,
property2, ..., propertyN;

    Values:
        none is used to specify that no property should be selected.
        all is used to specify all the properties to be selected, though not all properties are animate-able, only the properties which are animate-able will be influenced.
        We can specify a single property or a set of comma-separated properties property1, property2, …, propertyN.

2. transition-duration: This property allows you to determine how long it will take to complete the transition from one CSS property to the other. 

Syntax:

transition-duration: time;

    Here, time can be in seconds(s) or milliseconds(ms), you should use ‘s’ or ‘ms’ after the number (without quotes).

3. transition-timing-function: This property allows you to determine the speed of change and the manner of change, during the transition. Like, the change should be fast at the beginning and slow at the end, etc. 

Syntax:

transition-timing-function: ease|ease-in|ease-out|ease-in-out|linear|
step-start|step-end;

    Note, there are other values that this transition-timing-function can take, only the most frequent and simple are mentioned here.

4. transition-delay: This property allows you to determine the amount of time to wait before the transition actually starts to take place. 

Syntax:

transition-delay: time;

    Here, again, time can be in seconds(s) or milliseconds(ms), and you should use ‘s’ or ‘ms’ after the number (without quotes).

The Shorthand Property You can combine all the four transition properties mentioned above, into one single shorthand property, according to the syntax given below. This saves us from writing long codes and prevents from getting messy. Note the ordering of property, it has significance. 

Syntax:

transition: (property name) | (duration) | (timing function) | (delay);

The value is taken by are same as mentioned above. This property must be placed with other CSS properties, if any, of the initial state. You should use at least, property name and duration to get any animate-able effect. Also, the ordering of the values matters. The first value is of the property name, second for the duration and so on, as listed above. So, if only one number is mentioned, it will be taken up as duration, and not as a delay. 

Example: Changing property without using transitions. 

<!DOCTYPE html>
<html>
<head>
    <title>CSS Transition</title>
 
    <style>
        h1 {
            color: green;
            text-align: center;
        }
 
        div.one {
            height: 150px;
            width: 150px;
            border: 1px dashed black;
            margin: 0 auto;
            background: #FFEBEE;
        }
 
        div.one:hover {
            height: 300px;
            width: 300px;
            background: #BBDEFB;
        }
    </style>
 
</head>
 
<body>
    <h1>Geeksetr</h1>
 
    <div class="one">
    </div>
 
</body>
</html>

CSS Animation: CSS Animations is a technique to change the appearance and behavior of various elements in web pages. It is used to control the elements by changing their motions or display. It has two parts, one contains the CSS properties which describe the animation of the elements and the other contains certain keyframes which indicate the animation properties of the element and the specific time intervals at which those have to occur. 
What is a Keyframe?

Keyframes are the foundations with the help of which CSS Animations work. They define the display of the animation at the respective stages of its whole duration. For example: In the first example code, the paragraph changes its color with time. At 0% completion, it is red, at 50% completion it is of orange color and at full completion i.e. at 100%, it is brown. 
Syntax:

/*property-name*/: /*value*/;

Animation Properties:

There are certain animation properties given below:

    animation-name: It is used to specify the name of the @keyframes describing the animation.
    animation-duration: It is used to specify the time duration it takes animation to complete one cycle.
    animation-timing-function: It specifies how animations make transitions through keyframes. There are several presets available in CSS which are used as the value for the animation-timing-function like linear, ease,ease-in,ease-out, and ease-in-out. 
    animation-delay: It specifies the delay of the start of an animation.
    animation-iteration-count: This specifies the number of times the animation will be repeated.
    animation-direction: It defines the direction of the animation. animation direction can be normal, reverse, alternate, and alternate-reverse.
    animation-fill-mode: It defines how styles are applied before and after animation. The animation fill mode can be none, forwards, backwards, or both.
    animation-play-state: This property specifies whether the animation is running or paused.

Example 1: This example describes the CSS Animation using the @keyframe rule.

<!DOCTYPE html>
<html>
<head>
    <style>
        #gfg {
            animation-name: color;
            animation-duration: 25s;
            padding-top: 30px;
            padding-bottom: 30px;
            font-family: Times New Roman;
        }
 
        #geeks {
            font-size: 40px;
            text-align: center;
            font-weight: bold;
            color: #090;
            padding-bottom: 5px;
        }
 
        #geeks1 {
            font-size: 17px;
            font-weight: bold;
            text-align: center;
        }
 
        @keyframes color {
            0% {
                background-color: red;
            }
 
            50% {
                background-color: orange;
            }
 
            100% {
                background-color: brown;
            }
        }
    </style>
</head>
 
<body>
    <div id="gfg">
        <div id="geeks">GeeksforGeeks</div>
        <div id="geeks1">A computer science portal for geeks</div>
    </div>
</body>
</html>
