# 10.2.1-Von-Neumann-Architecture

# von Neumann  Architecture
Information can be found here https://www.bbc.co.uk/bitesize/guides/zbfny4j/revision/1  

The primitive model of a computer-code architecture is credited to a mathematician named John von Neumann (1903 – 1957). John von Neumann created the Von Neumann machine! (How creative, right?) 

For this next assignment, please create an interactive program to explain the nature, evolution, and  of a Von Neumann machine. 

Purpose: to understand why the von Neumann Machine was created and how it was used to bridge code with hardware.


## Your presentation must include (10 pts)
1. A block diagram of a stereotypical von Neumann machine
2. A rollover label for each block
    - naming the part
    - describing what it does in your own words
    - a picture of the component
3. A typical device associated with each block in your block diagram
4. The flow of data through the computer under the direction of a program


```
  let descriptX = 100 // sets xfor where definition shows up
  let descriptY = 10 // sets y for where definition shows up


function setup() {
  createCanvas(800, 800);

  // rectMode(CENTER)
  textAlign(CENTER)
}

function draw() {

  background(255);

  // block 1 copy this code, edit the numbers to make other blocks
  rect(50, 50, 100, 100); //input box
  
  if (mouseX < 150 && mouseX > 50 && mouseY < 150 *& mouseY > 50 ) {
    text("input device", mouseX, mouseY) //name of the block
    text("information provided by user", descriptX, descriptY) // definition of 
  }//end if

// start your next block here. 


  
  }// end draw 


// if you click this it will tell you where your mouse is
function mousePressed(){
  print(`X:${mouseX}`) 
  print("y:"+ mouseY)
}
```

## Rubric for Von Neumann Architecture Interactive Program:

1. **Accuracy of Block Diagram:**
   - The block diagram should accurately represent the components of a typical Von Neumann machine.
   - Components include CPU, ALU, Control Unit, Memory, Input/Output.

2. **Clarity of Rollover Labels, Explanation:**
   - Each block in the diagram should have rollover labels.
   - Labels should name the part and describe its function in simple and understandable language.
   - Clear demonstration of how data flows through the computer under the direction of a program.
   - A clear and concise definition explaining what each component does needs to appear when the mouse rolls over. 

3. **Inclusion of Component Pictures:**
   - Each component described in the rollover labels should be accompanied by a picture to enhance visualization.
   - Each block in the diagram should be associated with a typical device or hardware component found in a computer system.
       - For example, CPU can be associated with a microprocessor, Memory with RAM, Input/Output with keyboard/mouse, etc.

