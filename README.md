Download Link: https://assignmentchef.com/product/solved-csc21100-project-5
<br>
<span class="kksr-muted">Rate this product</span>

In this project, students are expected to use the Xilinx ISE Design Suite (Webpack edition) 14.7 to complete the following tasks.

Please read the instructions carefully. Failing to follow the instructions would lead to significant point deductions.

Finite State Machine (FSM)

Write a VHDL program to implement a “combination lock” state machine that activates and “unlock” output when a certain binary input sequence is received.

Requirements: Similar to the example in the lecture, the FSM has one input X and two outputs

UNLK and HINT;

1|Page

<ul>

 <li>  The UNLK output should be 1 if and only if X is 1 and the sequence of inputs received on X at the preceding three clock ticks was “101”, and the FSM returns to the INIT state;</li>

 <li>  HINT output should be 1 if and only if the current value of X is the correct one to move the machine closer to being in the “unlocked” state (with UNLK=1);</li>

 <li>  Whenever a wrong input is detected, the FSM returns to the INIT state and HINT=0;</li>

 <li>  For the state memory, only two D flip-flops are allowed;Please make sure you use the entity declaration provided below. No points wouldbe given if failed to follow it.In this task, use the FD component (essentially a D flip-flop) defined in the UNISIM library. In order to use the FD component, please make sure you have the following lines in your VHDL program to include the UNISIM library.Then you will need to declare the component in the VDHL architecture definition. For example:Then you can use it like this:</li>

</ul>

Write a test-bench program and run simulations to validate your design. Use the given test cases in your test-bench program. Pay attention to the signal names, signal values, and the time.

Requirement(s):

(1) You must follow the structural design method. (2) You must use the FD component.(3) You must follow the submission guidelines.

Note: no points will be given if any of the requirements are not satisfied.

3|Page

<table>

 <tbody>

  <tr>

   <td></td>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

<table>

 <tbody>

  <tr>

   <td></td>

   <td></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

Deliverables: Report

1.1

Draw a circuit diagram of the module to show the design. (2 point)

1.2

Include your VHDL entity declaration(s), architecture definition(s) and the testbench program. (1 point)

1.3

Show simulation results (e.g. the waveforms). Describe the outcome of each testcase with screenshots. Explain why the simulation result is correct. (4 point)

Deliverables: Source Code

1.4

Can compile without any errors. (1 point)

1.5

Can run simulations without any errors. (1 point)