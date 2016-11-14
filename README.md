Requirements & Behavior

Reference: Checkout the setInterval and clearInterval functions in JavaScript
Create a Plant function.
Create a Tree function.
Plant should be the prototype of Tree.
Plant should have a property of height.
The Plant prototype should have two methods on it: increaseHeight and decreaseHeight. Each method should accept an integer value as input.

Plant.prototype.increaseHeight = function (growth) {

}
increaseHeight should increase the value of the height property by the amount passed in as an argument.
decreaseHeight should decrease the value of the height property by the amount passed in as an argument.
Tree should have a property of branches.
The Tree prototype should have two methods on it: grow and trim.
The grow method should accept an integer value as input.

Tree.prototype.grow = function (amount) {

}
The grow method should increase the height of the tree.
The trim method should accept an integer value as input.
The trim method should decrease the height of the tree.
When the trim method is called, the number of branches should decrease by one.
Each time the height of a tree increases by 10, the value of branch should increase by one.
Create a PearTree instance of Tree. var PearTree = new Tree();
Create an OakTree instance of Tree.
Every second, increase the height the pear tree by some integer value and increase the height the oak tree by some integer value that is larger than what you used for the pear tree.
Also output the current height of each tree and how many branches it has to the DOM.

Pear tree is now 23cm tall and has 2 branches

Oak tree is now 57cm tall and has 4 branches
Every tenth time the trees are grown, invoke the trim method. Pass one value to the method for the pear tree, and a larger value to the method on the oak tree.

Stop growing the trees after they have grown 30 times.
Orchard Simulation