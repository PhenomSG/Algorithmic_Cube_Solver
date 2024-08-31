# Rubiks-Cube-Cracker

A virtual Rubik's Cube with a built-in optimal solver written in Python and rendered with OpenGL.  
The optimal solver can solve any scrambled cube in **20 moves** or fewer using *Korf's algorithm*.  


### Rubik's Cube Notation

The documentation below describes the program and the various algorithms that are implemented.  Standard twist notation is used.
# Twist Notation and Moves

## Faces:
- **U:** Up face
- **L:** Left face
- **F:** Front face
- **R:** Right face
- **B:** Back face
- **D:** Down face

## Twists:

### Clockwise (90 degrees):
- **U:** Twist the up face clockwise.
- **L:** Twist the left face clockwise.
- **F:** Twist the front face clockwise.
- **R:** Twist the right face clockwise.
- **B:** Twist the back face clockwise.
- **D:** Twist the down face clockwise.

### Counter-clockwise (90 degrees):
- **U':** Twist the up face counter-clockwise.
- **L':** Twist the left face counter-clockwise.
- **F':** Twist the front face counter-clockwise.
- **R':** Twist the right face counter-clockwise.
- **B':** Twist the back face counter-clockwise.
- **D':** Twist the down face counter-clockwise.

### 180-degree twist:
- **U2:** Twist the up face 180 degrees.
- **L2:** Twist the left face 180 degrees.
- **F2:** Twist the front face 180 degrees.
- **R2:** Twist the right face 180 degrees.
- **B2:** Twist the back face 180 degrees.
- **D2:** Twist the down face 180 degrees.

## Total Moves:
Since there are 6 faces and each face can have three types of twists (clockwise, counter-clockwise, and 180-degree), there are a total of **18 possible face twists**.

There's more information, here -> [Rubik's Cube Notation](https://ruwix.com/the-rubiks-cube/notation/).

___________________________________________________________________
A Rubik's Cube is made up of cubies (the cubies are the small cubes with
stickers on them).  There are corner cubies, which are the cubies with three
stickers.  Edge cubies are the cubies with two stickers.  And there are center
cubies, which are stationary and cannot be moved with the 18 twists described
above.

### Keys

Twist the faces of the cube using these keys: `U`, `L`, `F`, `R`, `B`, and `D`
for up, left, front, right, back, and down twists, respectively.  
