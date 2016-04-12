---
title: Adina, David, and Courtney's Makey Makey Project
layout: post
---

**The Makey Makey Project**

**Some Resources:**

[Original Makey Makey KickStarter campaign](https://www.kickstarter.com/projects/joylabz/makey-makey-an-invention-kit-for-everyone/description),
[Assistive Technology: What It Is and How It Works](https://www.understood.org/en/school-learning/assistive-technology/assistive-technologies-basics/assistive-technology-what-it-is-and-how-it-works),
[This Is the Easiest Way to Build Accessibility Tech for Kids with Disabilities](http://makezine.com/2016/02/19/this-is-the-easiest-way-build-accessibility-tech-kids-disabilities/)

**Assistive Technology Makey Makey**

1. We decided to focus on only one disability in particular.  For this we have selected cerebral palsy.  
2. Question: Can we use the Makey Makey to break an interface in such a way that a person who does not have cerebral palsy can attain some understanding of how traditional user interfaces are unusable for people lacking certain motor skills?
3. Inspiration: a ["typewriter" artist,](https://www.youtube.com/watch?v=svzPm8lT36o) Paul Smith (since deceased) had cerebral palsy.  [Here is another website on him and his work](http://www.cerebralpalsy.org/inspiration/artists/paul-smith).
4. Finally, can we create an application (something very simple in P5) that would act as a kind of artistic typewriter whose interface and controls facilitated by Makey Makey would be usable by people lacking certain motor skills.

**Goals:**

**1. Use the Makey Makey to create an interface to allow users with cerebral palsy (referred to as UserA) to create art using technology in a more accessible way than is currently available.**

While using the Makey Makey, we want UserA to engage with the technology in its limited format. The limited format of this technology enhances UserA’s ability to engage with the technology itself. We want UserA to be able to feel a sense of accomplishment and a discovery of new possibilities to engage with technology in a way that they were unable to previously. Finally, we want UserA to recognize that technology is more adaptable and capable of meeting their needs than the market that is producing them would have us believe. Through the example of the Makey Makey, we want to show users that there is technology already available that is inexpensive, easy to use, and highly adaptable.  We want to show users this inexpensive technology can be used to create assistive technology that is adaptable to numerous users with a variety of disorders across the spectrum.  We want UserA to create art using the interface (Addendum A) and to realize technology can be accessible for them.  

**2. We want a user who does not have cerebral palsy (referred to as UserB) to use a broken interface to attain some understanding of how traditional user interfaces are unusable for people lacking certain motor skills.**

We want UserB to engage with a “broken” interface (Addendum B) with the intent of creating a simple image on the screen (for our demo, we want them to create an arrow).  Through this, we want UserB to be able to feel the same frustration that a person with cerebral palsy might experience while attempting to create the same image using current mass produced interfaces.  The “broken” interface gives UserB added challenges that moves the mouse to a random part of the screen at a random moment.  This causes a “jerking” motion, which simulates what one might feel when they have cerebral palsy.  We want to raise awareness, and to have UserB think about the need for assistive technologies as well as solutions that meet that need.  We want UserB to understand how traditional user interfaces are not as easily accessible to everyone, and the frustrations that come with that.  

**3. To get all users to see the lack of availability in assistive technology as a problem in today’s market and to further promote imaginative designs to solve the issue.**  

We want all users to become aware of the issue of limited assistive technologies, and we want users to promote awareness among others.  We want users to expect the creators of new technologies to not be limited in the mass production of the same product that only addresses one specific demographic, but expect them to develop similar technologies that are usable by those with various disabilities across all spectrums. We want the users to actively think about solutions to the limitations of technology and the need for them.  We also want to raise awareness to not only the “one size fits all” assistive technology rationale, but also the “profit” aspect of it, because a lot of assistive technology is expensive and not easily adaptable.  We want users to understand the current model of assistive technology is not as effective as it could be, and that there are other solutions out there.  

**Specifications:**

1. Obtain Makey Makey

2. Obtain Play-Doh

3. Arrange Play-Doh to have these five controls:

4. Attach the USB cord from the Makey Makey to your laptop and the Makey Makey itself

5. Grab a conductive bracelet, or make it conductive by wrapping it in aluminum foil

6. Attach an alligator clip to the bracelet and the other end of the alligator clip to Earth on the Makey Makey

7. Take 4 connector wires and add one end of each to W,A,S, and D on the back of the Makey Makey

8. Using four alligator clips, clip them to the end of the four connector wires

9. Take the W connector wire and attach the alligator clip to the up Play-Doh arrow

10. Take the A connector wire and attach the alligator clip to the left Play-Doh arrow

11. Take the S connector wire and attach the alligator clip to the down Play-Doh arrow

12. Take the D connector wire and attach the alligator clip to the right Play-Doh arrow

13. Take a new alligator clip and clip it to the “Click” holes on the back of the Makey Makey and attach the other end of the clip to the center Play-Doh button

14. Open p5 and paste the attached code (see Addendum A) into the p5 editor

15. Put on the bracelet and move the keyed up ball around the screen

16. Move to the starting point and create an image of an arrow one click at a time across the canvas.

17. Open a new p5 document and paste the attached code from Addendum B into the p5 editor and attempt to create another image of an arrow

**Rationale:** 

This [Ted Talk](http://makezine.com/2016/02/19/this-is-the-easiest-way-build-accessibility-tech-kids-disabilities/) inspired us to raise awareness involving the limitations of technology for individuals with disabilities. A user without these disabilities would not face these limitations and therefore not realize the need for such solutions. Because we are addressing two different types of users (UserA and UserB) we created two different experiences using the same interface. The specific disability we are raising awareness of is Cerebral Palsy, and this due to the artist Paul Smith—who creates works of art only using 9 keys of a typewriter. For more on Paul see [A Tribute to the typewriter artist]( http://www.cerebralpalsy.org/inspiration/artists/paul-smith) and [Typewriter Artist](https://www.youtube.com/watch?v=svzPm8lT36o). Using these videos we brainstormed and came up with the experiences we want users to have.  

The first, which we will call code 1, asks users create a basic image using the mouse. Each click places a yellow dot on the screen. For our demonstration, the user is asked to move the target ball around the canvas to create the image of an arrow. What the user is not told is that after a random interval between 3 and 7 seconds, the target ball will move to a random location on the canvas. This forces the user to move the mouse towards the target ball’s new location in order to regain control over it, and then move it back to the original desired position to continue the task of drawing an arrow. The user would have been easily able to do this without this added challenge. We added this challenge because we want the user to understand and feel the frustration that a user with cerebral palsy might experience using the same interface due to their lack of fine motor coordination.

Once that task is complete the user starts their second experience by opening code 2. In this experience, the target ball is controlled not by the mouse but rather by the W, A, S, D keys, and the target ball does not move to a new location randomly. We hooked up these 5 action keys on our laptop to the Makey Makey (the WASD and “click”), wiring Makey Makey to Play-Doh controls described under the Specifications section. The user should be able to move the target ball around and is once again asked to create a simple drawing. This second experience is meant to demonstrate to all users how alternative solutions to the previously frustrating scenario are necessary for people with disabilities and not only possible, but can be made far less expensively than what is currently available. Instead of being mass produced with the “one size fits all” mentality, tools can be made more simply and flexibly in order to cater to disabled individuals whose disabilities vary along a wide spectrum. 

The readings contributing to our understanding of a humanistic approach to technology include Donna Haraway’s “A Cyborg Manifesto”, Marshall McLuhan’s The Language of New Media, and Anthony Dunne and Fiona Raby’s Speculative Everything: Design, Fiction, and Social Dreaming. The big concepts we draw on is McLuhan’s concept that technology is an extension of our humanity and his belief that there is a reciprocal relationship between technology and humans: we create and influence each other. As it might relate to assistive technologies, “extensions of ourselves, in sickness or in health, are attempts to maintain equilibrium” (42).  Much of the current available technology, however, is not able to be used as extensions for people with disabilities but rather is presented yet another limitation they are faced with. Even when assistive technology exists, it isn’t always a reciprocal relationship. This is because it is not adaptable, more a one size fits all concept, ignoring the fact that disabilities fall along a spectrum. Individual with cerebral palsy cannot adapt one piece of technology for their needs when it is created for someone somewhere else along the spectrum. Another issue with assistive technology is the high cost, which is a limiting factor for its use by many individual users for whom it’s intended. This brings us to Dunne and Raby’s book which addresses the issue of technology being created by the government and industries, instead of by consumers. To these industries it is just another market to exploit that doesn’t keep what is best for the consumer in mind. Dunne and Raby explain that we have power as consumers; we just need to voice our concerns and “Sometimes we can have more effect as citizens than as designers” (37). We can express what we want to buy, and we can use the technology we buy in an effective manner. Being “Critical shoppers” (37) gives us the power to allow things to succeed or fail. We need to follow the advice of Dunne and Ruby and choose what we consume, “The most threatening act of protest for a capitalist system would be for its citizens to refuse to consume” (37). Rather than refusing to consume, we can force change.  

Haraway expresses a similar challenge faced by the limitations we put on ourselves and technology because of our lack of imagination. “The political struggle is to see from both perspectives at once because each reveals both dominations and possibilities unimaginable from the other vantage point.  Single vision produces worse illusions than double vision or many-headed monsters” (295). Instead of having one experience for the users to interact with in which they are challenged, we wanted to create two experiences so that they can see from both perspectives simultaneously. This, in turn, ignites their imagination to think of possibilities and solutions to address the issue of limited assistive technology.  

While creating this project, we experienced everything we wanted our users to experience in our goals. We did this not only through interacting with our own code, but also in the making of it and our rationale for the need of it. During the demonstration our volunteer was able to experience the “jerking” motion one might experience when they have cerebral palsy. The volunteer and audience realized the frustration in creating the arrow with the “broken” interface (code 1), thereby helping them understand the issues with accessibility for users with cerebral palsy. In the modern world, where technology has become such an essential part of our lives, where man and machine have become extensions of each other, we need make an effort to make this important aspect of our modern society accessible to everyone. The only ones holding back our imaginations is ourselves. And, if the big companies will not take the time to address these concerns, then we as consumers need to make them feel the pressure to see that it is not only wanted by us, but an expectation we hold them to meet. We chose the writings of McLuhan, Dunne and Ruby, and Haraway because we thought that together they best expressed one of the themes from our course, as well as that which our project is designed to demonstrate: there should be a more humanistic approach to technology, especially when it comes to making it accessible to all individuals. The lack of availability and access to assistive technology is an issue that needs to be addressed, and we are happy to at least inform our class about it.   

**Addendum A:**

**index.html:**

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Untitled</title>

    <!-- import base p5 library -->
    <script src="libraries/p5.js" type="text/javascript"></script>

    <!-- import additional p5 libraries -->
    <script src="libraries/p5.dom.js" type="text/javascript"></script>
    <script src="libraries/p5.sound.js" type="text/javascript"></script>

    <!-- import project files -->
    <script src="KeyListener.js" type="text/javascript"></script>
    <script src="KeyedUpBall.js" type="text/javascript"></script>
    <script src="ArtDraw.js" type="text/javascript"></script>
    <script src="DrawingMark.js" type="text/javascript"></script>
    <script src="DrawingMarks.js" type="text/javascript"></script>

    <!-- import sketch file -->
    <script src="sketch.js" type="text/javascript"></script>

    <style> body {padding: 0; margin: 0;} canvas {vertical-align: top;} </style>
  </head>
  <body>
  </body>
</html>
```

**Sketch.js:**

```
var myDrawing = new ArtDraw();

setup = function () {
  myDrawing.initialize();
};

draw = function() {
  myDrawing.update();
  myDrawing.display();
};

mouseClicked = function () {
  myDrawing.createSpot();
};
```

**ArtDraw.js:**

```
// constructor function
var ArtDraw = function () {
};

ArtDraw.prototype = {
  initialize: function () {
    createCanvas(windowWidth, windowHeight);

    this.drawBall =  new KeyedUpBall(width / 2, height / 2);
    this.drawBall.initialize();

    this.marks = new DrawingMarks();
  },

  createSpot: function () {
    var drawLocation = this.drawBall.getPosition();
    this.marks.create(drawLocation.x, drawLocation.y);
  },

  update: function () {
    this.drawBall.update();
  },

  display: function () {
    background('#00BFFF');

    this.marks.display();
    this.drawBall.display();
  }
};
```

**DrawingMark.js:**

```
var DrawingMark = function(x, y) {
  this.position = new p5.Vector(x, y);
};

DrawingMark.prototype = {

  radius: 10,

  initialize: function(x, y) {},

  update: function() {},

  // display() draws a circle
  display: function() {
    noStroke();
    fill('#FFFF00');
    ellipse(this.position.x, this.position.y, this.radius * 2, this.radius * 2);
  }

};
```

**DrawingMarks.js:**

'''
var DrawingMarks = function () {
  this.marks = [];
};

DrawingMarks.prototype = {
  initialize: function () {},

  update: function() {},

  display: function() {
    for (var index = 0; index < this.marks.length; index++) {
      this.marks[index].display();
    };
  },

  create: function(x, y) {
    this.marks.push(new DrawingMark(x, y));
  },

  delete: function(index) {
    this.marks.splice(index, 1);
  },

};
```

**KeyUpBall.js:**

```
// constructor: takes a starting x and y position.
var KeyedUpBall = function(x, y) {
  this.position = new p5.Vector(x, y);
  this.direction = new p5.Vector(0, 0);
};

KeyedUpBall.prototype = {

  speed: 3, // speed is the speed at which the ball moves in a given direction in a given frame
  radius: 24, // instead of size, radius (this makes our math simpler)
  listeners: [], // this holds our listeners

  // below are the key mappings; these variables are defined on the prototype, but can easily be overwritten on a given instance
  keyUp: 'W', // describes the key to move the ball up
  keyLeft: 'A', // describes the key to move left
  keyDown: 'S', // decribes the key to move down
  keyRight: 'D', // describes the key to move right

  // initialize() sets up the KeyListeners on the movement keys
  initialize: function() {
    this.listeners.push(new KeyListener(this.keyUp, this.moveUp, this));
    this.listeners.push(new KeyListener(this.keyLeft, this.moveLeft, this));
    this.listeners.push(new KeyListener(this.keyDown, this.moveDown, this));
    this.listeners.push(new KeyListener(this.keyRight, this.moveRight, this));
  },

  // display() draws the InteractiveBall
  display: function() {
    noStroke();
    fill(131, 126, 126, 100);
    ellipse(this.position.x, this.position.y, this.radius * 2, this.radius * 2);

    stroke(0);
    line(this.position.x -5, this.position.y, this.position.x -75, this.position.y);
    line(this.position.x +5, this.position.y, this.position.x +75, this.position.y);
    line(this.position.x, this.position.y -5, this.position.x, this.position.y - 75);
    line(this.position.x, this.position.y +5, this.position.x, this.position.y + 75);
  },

  // update() resets the direction of the ball to zero, so it can be changed by user interaction, then moves the ball
  update: function() {
    this.resetDirection();
    this.listen();
    this.move();
  },

  getPosition: function() {
    return new p5.Vector(this.position.x, this.position.y);
  },

  // listen() simply tells all listeners to listen
  listen: function() {
    this.listeners.forEach(function listen(listener) {
      listener.listen();
    });
  },

  // resetDirection() sets the direction vector to [0, 0]
  // this is called every update(); key presses work by modifying a baseline of [0, 0]
  resetDirection: function() {
    this.direction.x = 0;
    this.direction.y = 0;
  },

  // move()s the ball by adding the direction vector, constraining the ball's to the canvas
  move: function() {
    if (this.direction.mag() > 0) this.normalizeSpeed(); // if the vector has any magnitued, normalize it
    this.position.x = constrain(this.position.x + this.direction.x, this.radius, width - this.radius);
    this.position.y = constrain(this.position.y + this.direction.y, this.radius, height - this.radius);
  },

  // normalize() takes the direction vector and scales it so that its magnitude is always equivalent to speed
  // this is necessary so that diagonal movement isn't faster than horizontal or vertical movement
  normalizeSpeed: function() {
    this.direction.normalize(); // changes the vector so that it keeps its direction, but sets is magnitude to 1
    this.direction.mult(this.speed); // mutliplies by speed
  },

  // the various move functions modify a baseline direction vector of [0, 0]
  // they do so by adding and subtracting, so that opposite key presses cancel each other out
  moveUp: function() {
    this.direction.y -= 1;
  },

  moveLeft: function() {
    this.direction.x -= 1;
  },

  moveRight: function() {
    this.direction.x += 1;
  },

  moveDown: function() {
    this.direction.y += 1;
  },

  // detectCollision() should returns true if this ball intersects with another ball
  // for this to work, the other ball must have its position represented by a position object that has an x and y, as well as a radius, as our BouncyBall does
  detectCollision: function(otherBall) {
    var distance = dist(this.position.x, this.position.y, otherBall.position.x, otherBall.position.y);
    var radiiSum = this.radius + otherBall.radius;
    return distance < radiiSum ? true : false;
  }

};
```

**KeyListener.js:**

```
var KeyListener = function(key, _function, listenOn) {
  this.keyToListen = key.charCodeAt(0);
  console.log("Created listener on " + key + ", code: " + this.keyToListen);
  this.functionToCall = _function;
  this.listenOn = listenOn;
};

KeyListener.prototype = {

  // KeyListener.listen() should be called in draw(), or in something that is invoked by draw().
  // If the function call throws an error, it's reported out to the console, but it doesn't interrupt the program or the object.
  // The most likely source of error here is failing to specify the listenOn object when it's necessary.
  listen: function() {
    if (keyIsDown(this.keyToListen)) {
      console.log("Key pressed: " + String.fromCharCode(this.keyToListen) + ": " + this.keyToListen); // sends the keypress to the console; comment this out if you wish.
      try {
        this.functionToCall.call(this.listenOn);
      } catch (e) {
        console.log("Function call failed. Most likely, you need an object to listen on.");
        console.error(e);
      }
    }

  }

};

/*
  Special variables for special keys.

  For keys that don't easily have a string attached to them (arrow keys, enter, etc.) use this special object and its special properties. p5 has related variables, but for reasons of scope, these have to be defined here. This is not an exhaustive list. Please note that p5 is a bit idiosyncratic in how it handles key mapping.
*/
var keyListenerMap = {

  leftArrow: String.fromCharCode(37),

  upArrow: String.fromCharCode(38),

  rightArrow: String.fromCharCode(39),

  downArrow: String.fromCharCode(40),

  enter: String.fromCharCode(13),

  backspace: String.fromCharCode(8),

};
```

**Addendum B:** 

In creating the “broken” version of the ArtDraw application we introduced a Timer mechanism and modified only the KeyedUpBall.js functionality, which handles the random movement of the pointer and the coordination of the mouse back to the pointer.

**KeyedUpBall.js:**

```
// constructor: takes a starting x and y position.
var KeyedUpBall = function(x, y) {
  this.position = new p5.Vector(x, y);
  this.direction = new p5.Vector(0, 0);
  this.randomTimer = new Timer();
};

KeyedUpBall.prototype = {

  speed: 3, // speed is the speed at which the ball moves in a given direction in a given frame
  radius: 24, // instead of size, radius (this makes our math simpler)
  listeners: [], // this holds our listeners
  trackMouse: 0,

  // below are the key mappings; these variables are defined on the prototype, but can easily be overwritten on a given instance
  keyUp: 'W', // describes the key to move the ball up
  keyLeft: 'A', // describes the key to move left
  keyDown: 'S', // decribes the key to move down
  keyRight: 'D', // describes the key to move right

  // initialize() sets up the KeyListeners on the movement keys
  initialize: function() {
    this.listeners.push(new KeyListener(this.keyUp, this.moveUp, this));
    this.listeners.push(new KeyListener(this.keyLeft, this.moveLeft, this));
    this.listeners.push(new KeyListener(this.keyDown, this.moveDown, this));
    this.listeners.push(new KeyListener(this.keyRight, this.moveRight, this));
    this.startRandomTimer();
  },

  // display() draws the InteractiveBall
  display: function() {
    noStroke();
    fill(131, 126, 126, 100);
    ellipse(this.position.x, this.position.y, this.radius * 2, this.radius * 2);

    stroke(0);
    line(this.position.x -5, this.position.y, this.position.x -75, this.position.y);
    line(this.position.x +5, this.position.y, this.position.x +75, this.position.y);
    line(this.position.x, this.position.y -5, this.position.x, this.position.y - 75);
    line(this.position.x, this.position.y +5, this.position.x, this.position.y + 75);
  },

  startRandomTimer: function() {
    this.randomTimer.restart();
    this.randomDuration = random(3, 7);
    this.trackMouse = 1;
    noCursor();
  },

  randomMovement: function() {
    this.position.x = random(0, windowWidth);
    this.position.y = random(0, windowHeight);
    //this.display();
  },

  mouseMove: function() {
      if (this.trackMouse == 0 && !this.detectMouseCatchUp()) return;

      if (this.trackMouse == 0) this.startRandomTimer();

      this.position.x = mouseX;
      this.position.y = mouseY;
  },

  // update() resets the direction of the ball to zero, so it can be changed by user interaction, then moves the ball
  update: function() {
    this.resetDirection();
    this.listen();
    this.move();
    this.mouseMove();

    if (this.randomTimer.secondsElapsed() > this.randomDuration) {
      this.randomMovement();
      this.randomTimer.restart();
      this.randomTimer.pause();
      cursor(ARROW);
      this.trackMouse = 0;
    }
  },

  getPosition: function() {
    return new p5.Vector(this.position.x, this.position.y);
  },

  // listen() simply tells all listeners to listen
  listen: function() {
    this.listeners.forEach(function listen(listener) {
      listener.listen();
    });
  },

  // resetDirection() sets the direction vector to [0, 0]
  // this is called every update(); key presses work by modifying a baseline of [0, 0]
  resetDirection: function() {
    this.direction.x = 0;
    this.direction.y = 0;
  },

  // move()s the ball by adding the direction vector, constraining the ball's to the canvas
  move: function() {
    if (this.direction.mag() > 0) this.normalizeSpeed(); // if the vector has any magnitued, normalize it
    this.position.x = constrain(this.position.x + this.direction.x, this.radius, width - this.radius);
    this.position.y = constrain(this.position.y + this.direction.y, this.radius, height - this.radius);
  },

  // normalize() takes the direction vector and scales it so that its magnitude is always equivalent to speed
  // this is necessary so that diagonal movement isn't faster than horizontal or vertical movement
  normalizeSpeed: function() {
    this.direction.normalize(); // changes the vector so that it keeps its direction, but sets is magnitude to 1
    this.direction.mult(this.speed); // mutliplies by speed
  },

  // the various move functions modify a baseline direction vector of [0, 0]
  // they do so by adding and subtracting, so that opposite key presses cancel each other out
  moveUp: function() {
    this.direction.y -= 1;
  },

  moveLeft: function() {
    this.direction.x -= 1;
  },

  moveRight: function() {
    this.direction.x += 1;
  },

  moveDown: function() {
    this.direction.y += 1;
  },

  // detectCollision() should returns true if this ball intersects with another ball
  // for this to work, the other ball must have its position represented by a position object that has an x and y, as well as a radius, as our BouncyBall does
  detectCollision: function(otherBall) {
    var distance = dist(this.position.x, this.position.y, otherBall.position.x, otherBall.position.y);
    var radiiSum = this.radius + otherBall.radius;
    return distance < radiiSum ? true : false;
  },

  // detectCollision() should returns true if this ball intersects with another ball
  // for this to work, the other ball must have its position represented by a position object that has an x and y, as well as a radius, as our BouncyBall does
  detectMouseCatchUp: function(otherBall) {
    var distance = dist(this.position.x, this.position.y, mouseX, mouseY);
    return distance < 50 ? true : false;
  }

};
```

**Timer.js:**

```
var Timer = function () {
  this.initialize();
};

Timer.prototype = {

  // initialize() starts the counter running; this need only be used internally
  initialize: function() {
    this.init = Date.now();
    this.now = Date.now();
  },

  // I removed the code to start the timer from the initialize function and created
  // a start fnction that must be invoked by the calling applicaiton.  I did this
  // so that the timer can be instantiated without starting the timer itself.
  start: function() {
    this.running = true;
  },

  // restart() restarts the counter from zero
  restart: function() {
    this.initialize();
    this.running = true;
  },

  // pause() stops the timer at the current value
  pause: function() {

'''
