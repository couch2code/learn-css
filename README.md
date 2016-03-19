# Learn CSS

---

### Teachers

* Mr Tom
* Ms Alex
* Mr Lucas

---

### Rules

* Be Cool
* Raise your hand when you want to speak or need help.
* If you are stuck in a challenge, ask your neighbor, ask google, ask the teacher

---

### Lesson Format

Each lesson will last about an hour, and the format will go as follows:

* Introduce something new to learn.
* Watch me apply the topic on the projector.
* Exercises to practice the concept.

---

! http://i.giphy.com/e4PkUJXi88n1C.gif

---

# Finish the Maze together

---

! http://i.giphy.com/AGGz7y0rCYxdS.gif

---

# CSS

---

! http://i.giphy.com/yoJC2ppnSOPIhe0FWg.gif

---

Cascading Style Sheets give you the ability to format your content using colors, fonts, and animations, 

---

```
<style>
  body {
    background: yellow;
  }
</style>
```

---

The structure of a CSS Statement is the following:

```
element {
  command : value ;
}
```

---

# Demo 

---

# Exercises

---

### Exercise 1

Open up your `index.html` file and add the `<style>` element to your `<head>` section:
then inside the style element, add the background color to your body element.

---

### Exercise 2

Lets change the color of your h1 element using the color command:

```
color : blue ;
```

---

### Exercise 3

Using the background and color command change other elements on your index.html page.

---

! http://i.giphy.com/3o85xunRezGKPOkcG4.gif

---

# Layout

---

Using css you can manipulate the elements to control the position and layout of each
element to create a more rich view than just one column.

---

```
.container {
  width: 960px;
  margin: 0 auto;
}
.column {
  width: 480px;
}
.left {
  float: left;
}
.right {
  float: right;
}
.clear {
  clear: both;
}
```

---

Using the class attribute and the div command we can apply these styles to any html page:

```
<div class="container">
  <div class="left column">
    Left Column
  </div>
  <div class="right column">
    Right Column
  </div>
  <div class="clear"></div>
</div>
```


---

# Demo

---

# Exercise 1

Lets create our own two column layout: Lets put our avatar image on the left and the super powers list on the right.

---

# BREAK 

---

# Position

---

The default position of each element is 'relative', but sometimes you want to be absolute where 
you want to put elements, using the position command with the value 'absolute' enables the exact
placement of an element.

---

```
  .right_corner {
    position: absolute;
    right: 10px;
    top: 10px;
  }
```

---

# Demo

---

# BREAK

---

# Exercises

---

# Buttons

---

```
button {
	position: relative;
	padding: .3em .5em;
	background: #58a;
	border-radius: 50%;
	border: 1px solid rgba(0,0,0,.3);
	box-shadow:  0 .1em .2em -.05em rgba(0,0,0,.5);
	color: white;
	font: bold 150%/1 sans-serif;
	cursor: pointer;
}

button:before {
	content: '';
	position: absolute;
	top: -10px; right: -10px;
	bottom: -10px; left: -10px;
}
```

---

# Demo

---

# Exercises

---

# BREAK

---

# Bootstrap

---

Using a css framework can make implementing css much less time consuming and consistent.

Lets look at one of the most popular frameworks.  Bootstrap

http://getbootstrap.com

---

Adding bootstrap to your html file is easy:

```
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
```

---

# Demo

---

# Exercise

---

Lets apply bootstrap to our index html file.

---

# BREAK

---

# Animation

---

https://daneden.github.io/animate.css/

---

Animate CSS makes animation easy. 

```
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.5.1/animate.css">
```

---

# Demo

---

# Exercise

---

# BREAK

---

# Roll your own css 

---

Using .css files in your project, you can write your own css in one location and
share it to many files.

---

# Demo

---

# Exercises
