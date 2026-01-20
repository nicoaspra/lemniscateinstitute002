---
title: "Testing of Thread with the Three-Wire Method"
weight: 2
layout: content
prevcontenturl: ../lab-mandrel-5.1-external-thread-cutting
nextcontenturl: ../lab-mandrel-7.1-drilling-boring-and-facing-of-the-flange
---



# Objective
This activity introduces students to the three-wire method, a precise technique used to approximate the dimensions of external threads. With the aid of calibrated wires and a micrometer, students will determine the pitch diameter of their threaded workpiece and evaluate the accuracy of their threading operation.

# Materials and Equipment
The following materials and tools are essential for successfully completing this activity. Ensure they are available, complete, and in proper working condition before starting.
- Threaded Workpiece (from previous activity)
- Three Calibrated Wires (appropriately sized for the thread pitch)
- Micrometer
- Thread Pitch Gauge
- Calculator



# Procedure
<ol>
	<li>Based on your design, take note of the number of <strong>threads per inch</strong>, $n$, of your workpiece.</li>
	<li>Using this value, compute the pitch using the equation:</li>

	{% include tcolorbox.html 
		details= "
			P = \frac{1}{n}
			"
	%}

	<li>Determine the proper wire diameter for the three-wire method using:</li>

	{% include tcolorbox.html 
		details= "
			W = 0.5P \sec(30^\circ) \approx 0.57735P
			"
	%}

	<li>Select three identical wires that closely match the calculated diameter $W$.</li>
	<li>Carefully place two wires on opposite flanks of the thread, and the third wire on the other side of the thread, directly between the two.</li>
	<li>Using a <strong>micrometer</strong> measure over the wires. Ensure that the micrometer anvils contact the wires gently and evenly without displacing them.</li>
	<li>Record the micrometer reading, $M$, which represents the <strong>measurement over wires</strong>.</li>
	<li>Repeat the measurement several times and record the average value.</li>
	<li>Compute the <strong>theoretical measurement over wires</strong>, $M_t$, using:</li>
	
	{% include tcolorbox.html 
		details= "
			M_t = D_o + 3W - 1.5155P
			"
	%}

	<li>Compare your actual measurement $M$ with the computed value $M_t$.</li>
	<li>Evaluate whether the deviation is within acceptable limits and provide an assessment of the <strong>accuracy of the thread cutting operation</strong>.</li>
</ol>



{% include images.html 
    url= "lab-mandrel/lab-mandrel-6.1.jpg" 
    caption= "Figure 6.1: Measuring the external thread using the three-wire method and a micrometer. In this activity, the measurement over wires is used to verify if the thread was cut to the correct outer diameter, based on the theoretical formula involving pitch and wire diameter."
    size= "400px"
%}

