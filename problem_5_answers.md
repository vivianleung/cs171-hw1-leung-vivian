<h1>Problem 5 Answers</h1>
<ol>

	<li><!-- What's missing? Is this bar chart usable in its current form? -->
		Axis, bar labels, chart title and optionally numerical values for bars are missing from the data. Color scale (for continuously distributed data), gaps between bars, and highlights/emphasis of labels for hovered bars would be helpful as well. In its current for, it's not really useful or usable.
	</li>
	<li><!-- Complete the implementation section below. Is there any consequence if you add the text elements before or after the rect elements? Why?-->
		If the text elements are added before the rect elements, then the former appear behind the latter. This is because later elements are added on a higher layer (on top of previous ones, like a painter's model) unless otherwise specified by moving the element forward or backward.
		
	</li>
	<li><!-- What is the role of each of the three nested levels of g elements? (keep in mind you'll be adding a title to the chart)-->
		The first g transforms the g components together, in this case, translates them along x and y. The second g groups together individual g's according to their data set; it is appended as the set of data parsed by d3.tsv(). The third g's are the individual bars themselves.

	</li>

</ol>