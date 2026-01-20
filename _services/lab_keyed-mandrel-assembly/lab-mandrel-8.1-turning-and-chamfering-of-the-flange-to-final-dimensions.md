---
title: "Turning and Chamfering of the Flange to Final Dimensions"
weight: 2
layout: content
prevcontenturl: ../lab-mandrel-7.1-drilling-boring-and-facing-of-the-flange
nextcontenturl: ../lab-mandrel-9.1-keyway-cutting-on-the-flange
---

# Objective
This activity introduces students to center-to-center turning operations involving a flange assembly. The task requires the student to mount the previously machined flanges onto the shaft (first workpiece) and secure them using a nut. The goal is to perform accurate <strong>turning to dimension</strong> followed by <strong>chamfering</strong> using the <strong>compound rest set to a calculated angle</strong>. The exercise emphasizes geometric computation, workholding alignment, and sequential machining techniques.

# Materials and Equipment
The following materials and tools are essential for successfully completing this activity. Ensure they are available, complete, and in proper working condition before starting.
- Shaft with Threaded End (from previous activity)
- Two Finished Flanges (from previous activity)
- Hex Nut to clamp flanges
- HSS or Carbide Turning Tool
- Protractor
- Lathe Machine
- Drive Plate
- Lathe Dog
- $60\degg$ Dead Center
- $60\degg$ Live Center
- Vernier Caliper
- Safety Goggles

# Procedure
## Flange Assembly and Mounting
<ol>
	<li>Mount both <strong>flanges</strong> onto the <strong>threaded shaft</strong>, placing one flange on each side.</li>
	<li>Secure the flanges tightly using a <strong>hex nut</strong> to ensure both are clamped firmly against the shaft (see Figure 8.1).</li>
	<li>Mount the assembly <strong>center to center</strong> using a <strong>lathe dog</strong> and a live center in the tailstock.</li>
	<li>Rotate the workpiece manually to confirm that it spins freely and is properly aligned.</li>
</ol>


{% include images.html 
    url= "lab-mandrel/lab-mandrel-8.1.jpg" 
    caption= "Figure 8.1: Mounting the flange assembly onto the threaded shaft and securing it with a hex nut."
    size= "500px"
%}


## Turning to Dimension
<ol start="5">
	<li>Use the <strong>HSS or carbide turning tool</strong> to reduce the <strong>outer diameter</strong> of both flanges according to the design specifications.</li>
	<li>Ensure the cutting is even across both flanges and that the surfaces remain parallel.</li>
	<li>Continue turning until the desired outer diameter is achieved.</li>
</ol>

## Computing the Chamfer Angle
<ol start="8">
	<li>Based on the desired <strong>chamfer length, $L$</strong> and <strong>chamfer depth, $t$</strong>, compute the required compound rest angle using the tangent function:</li>
	
	{% include tcolorbox.html 
		details= "
			\theta = \tan^{-1}\left(\frac{L}{t}\right)
			"
	%}

	<li>Refer to Table 8.2 (in the Laboratory Worksheet) to compute the chamfer angle using your dimensions.</li>
	<li>Rotate the compound rest to the calculated angle relative to the workpiece axis.</li>
	<li>Lock the compound rest securely to prevent any movement during the chamfering operation.</li>
</ol>

{% include images.html 
    url= "lab-mandrel/lab-mandrel-8.2.jpg" 
    caption= "Figure 8.2: Visual representation of chamfer angle computed from chamfer length and depth. This angle determines the compound rest setting."
    size= "200px"
%}


## Chamfering the First Flange
<ol start="12">
	<li>Using the adjusted compound rest, feed the tool manually along the set angle to chamfer the edge of the first flange.</li>
	<li>Visually inspect the chamfer and verify its dimensions using a <strong>protractor</strong> and vernier caliper.</li>
	<li>Continue cutting until the chamfer matches the dimensions specified in your plan.</li>
</ol>


{% include images.html 
    url= "lab-mandrel/lab-mandrel-8.3.jpg" 
    caption= "Figure 8.3: Chamfering the edge of the first flange using the adjusted compound rest angle."
    size= "500px"
%}


## Chamfering the Second Flange
<ol start="15">
	<li>Loosen the hex nut and remove both flanges from the shaft.</li>
	<li>Rotate or flip the flange assembly to expose the second flange edge for chamfering.</li>
	<li>Remount the assembly in the same center-to-center configuration, ensuring proper alignment.</li>
	<li>Chamfer the second flange using the same compound rest angle and technique as the first.</li>
</ol>


{% include images.html 
    url= "lab-mandrel/lab-mandrel-8.4.jpg" 
    caption= "Figure 8.4: Repositioning the assembly to chamfer the opposite flange using the same compound rest angle."
    size= "500px"
%}



## Final Measurements
<ol start="19">
	<li>Use a <strong>vernier caliper</strong> to measure and verify the final dimensions of each machined flange.</li>
	<li>Record your measurements and <strong>compare them with the design specifications</strong> in Table 8.1 (in the Laboratory Worksheet).</li>
</ol>