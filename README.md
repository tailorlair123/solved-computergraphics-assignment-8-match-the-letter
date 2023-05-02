Download Link: https://assignmentchef.com/product/solved-computergraphics-assignment-8-match-the-letter
<br>
5/5 - (1 vote)

Match the letter

The application allows the user to turn around a shape in any angle. Evert direction resembles a different letter. Pressing space, the letter on the right changes: the purpose of the game is rotating the object on the left to match the one on the right. The current version works, but in a very ugly way: some transitions are extremely hard and not intuitive to obtain.

You have to correct the application to make it more usable.

The game is contained in index.html, and the procedure for computing and update the world matrix for is contained in file Rotation.js. To improve the application the rotation, should be always relative to the screen: the horizontal movement should always be horizontal, the vertical rotation should always be vertical, and the roll should always perform a circle with respect to the view.

The procedure receives as input three values rvx, rvy, rvz, that are either positive, negative or zero depending on the rotation direction being requested by the user. You will also need to add one or more global variables to remember the previous ship angle, so to update it according to the values contained in rvx, rvy, rvz.

In order to perform correct rotations with respect to the view, you need to use quaternions. You can write quaternion operations yourself, or use a library available on the web. For your convenience, the page already includes library quaternion.js:

https://www.npmjs.com/package/quaternion