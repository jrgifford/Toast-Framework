The Toast Framework
===================

Welcome, young warrior! Let's go over the basics of the framework, shall we?

Page structure
--------------

The structure for Toast is fairly easy to grasp - lets make a typical page with 2 columns:

<div class="row">
	<div class="col_9">
		Content!
	</div>
	<div class="col_3 box">
		Sidebar!
	</div>
</div>

Now we have 2 columns, one spanning nine column values, and one spanning three. In case you didn't notice, there's a class of "box" in that sidebar too. That class adds padding to the <div>, creating a 'real' box that you can apply a background too. Neat huh? And it doesn't break the grid!

Other cool things
-----------------

There are a couple of other classes that will do cool stuff to the page:

 - *smallscreen* - adding this to the container will make it snap to a smaller size, ideal for people who are used to the 960 pixel grid
 - *respond* - adding this to the container will make it responsive, so it scales down to mobile sizes
 - *push_x* and *pull_x* - add this to a column, and it will push or pull it right & left by x columns
 - *prefix_x* and *suffix_x* will create space on the left or right of the column