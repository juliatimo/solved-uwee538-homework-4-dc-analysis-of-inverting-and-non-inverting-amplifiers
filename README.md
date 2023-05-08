Download Link: https://assignmentchef.com/product/solved-uwee538-homework-4-dc-analysis-of-inverting-and-non-inverting-amplifiers
<br>
For the two amplifiers shown above, the opamp has open-loop DC gain <em>A<sub>0</sub></em>, input resistance <em>R<sub>in</sub></em>, and output resistance <em>R<sub>out</sub></em>. For the Ltspice parts, use the UniversalOpamp2 (SpiceModel level.1), with <em>R<sub>1</sub></em> = 1k and <em>R<sub>2</sub></em> = 10k. The default open-loop output resistance for the opamp model is 0.1. You can use the ‘DC Transfer’ analysis.

<ol>

 <li>For the inverting and non-inverting amplifiers shown in Fig 1a and 1b, determine <em>expressions</em> for each of the following assuming <em>A<sub>0 </sub></em>→  (infinite open-loop gain). Provide comments on how each closed-loop parameter compares to its open-loop counterpart.

  <ol>

   <li>Closed-loop gain (<em>V<sub>out</sub></em>/<em>V<sub>in</sub></em>).</li>

   <li>Closed-loop output resistance.</li>

   <li>Closed-loop input resistance.</li>

  </ol></li>

 <li> Repeat Part a assuming <em>A<sub>0</sub></em> is finite. Try to develop some intuition regarding how each parameter depends on <em>A<sub>0</sub></em> and the feedback factor . Check your answer by setting <em>A<sub>0 </sub></em>→  and comparing to your answer in Part a.</li>

 <li> Assuming the opamp has a voltage offset <em>v<sub>OS</sub></em>, what is the resulting output offset for each structure? Assume <em>A<sub>0 </sub></em>→ <em>.</em> Check your answer in Ltspice.</li>

 <li> Assuming the opamp has input bias current <em>I<sub>B</sub></em>, what is the resulting output offset for each structure? Assume <em>A<sub>0 </sub></em>→ <em>.</em></li>

</ol>

<strong>             </strong>

<h1>Problem 2: Opamp circuit transient response</h1>

<h1>             Figure 2a. Current-input integrator                                      Figure 2b. Input current pulse</h1>




For the following, assume ideal opamp behavior.

<ol start="2">

 <li>( Determine an expression for the transfer function <em>v<sub>out</sub></em>/<em>i<sub>in</sub>.</em></li>

 <li> Determine an expression for the transient response of the circuit. What is the value of <em>v<sub>out</sub></em> (in terms of <em>R</em>, <em>C</em>, <em>i<sub>max</sub></em>, and <em>t<sub>on</sub></em>) at time <em>t</em> = <em>t<sub>on</sub></em>?</li>

</ol>

<em>Bonus ):</em> Design the circuit (i.e. determine R and C) to function as an integrator, such that             <em>v<sub>out</sub></em>(<em>t<sub>on</sub></em>) = <em>i<sub>max</sub></em>/<em>C </em>with less than 0.1% error<em>.</em> Use <em>i<sub>max</sub></em> = 10µA and ensure <em>v<sub>out</sub></em> doesn’t exceed a bipolar supply voltage of 2.5V. Verify your design in Ltspice.

<strong>                </strong>

<h1>Problem 3. Difference amplifier</h1>

<strong>Figure 3. Difference amplifier </strong>

For the following, the opamp has a DC gain (<em>A<sub>0</sub></em>) of 100 dB and a unity-gain bandwidth (<em>f<sub>T</sub></em>) of 10MHz but is otherwise ideal (<em>R<sub>in</sub></em> =  and <em>R<sub>out</sub></em> = 0). <em>R<sub>1</sub></em> = <em>R<sub>2</sub></em> = <em>R<sub>3</sub></em> = <em>R<sub>4</sub></em> = 10k.

<ol start="2">

 <li> Sketch the Bode magnitude and use the graph to approximate the 3dB bandwidth. Sketch the Bode phase plot.</li>

 <li>Calculate the DC gain and 3dB bandwidth of the closed-loop transfer function <em>v<sub>out</sub></em>/(<em>v<sub>ip</sub></em> – <em>v<sub>im</sub></em>). Sketch the Bode magnitude and phase of the closed-loop transfer function.</li>

 <li> What is the resistance “looking into” each input (<em>v<sub>im</sub></em> and <em>v<sub>ip</sub></em>)?</li>

 <li> Check your answers to Parts b and c in Ltspice using the Analog Devices opamp model for the AD8691.</li>

</ol>





