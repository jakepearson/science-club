# Program a Computer

Below are a couple of `programs` to get you started. We are using the following `functions`:

* `background`- sets the background color of the scene
* `fill` - sets the background color of the next shapes
* `rect` - draws a rectangle
* `triangle` - draws a triangle
* `ellipse` - draws an ellipse

Each function takes several arguments (the editor will help tell what each one means). Make sure each `function` has a left and right parenthesis and a semi-colon at the end.

## Let's Build A House
```javascript
//Sky
background(0, 187, 255);

//House
fill(112, 84, 84);
rect(100, 200, 200, 200);
triangle(100, 200, 300, 200, 200, 100);

//Door
fill(0, 0, 0);
rect(190, 350, 30, 50);
```

## Let's Build a Snowman
```javascript
//Body
ellipse(142, 299, 185, 180);
ellipse(144, 199, 139, 147);
ellipse(148, 112, 100, 100);

//Nose
fill(255, 162, 0);
triangle(142, 112, 182, 114, 143, 124);

//Eyes
fill(0, 0, 0);
ellipse(129, 95, 20, 20);
ellipse(161, 95, 20, 20);
```
