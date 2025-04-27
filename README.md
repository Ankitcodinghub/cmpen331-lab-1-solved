# cmpen331-lab-1-solved
**TO GET THIS SOLUTION VISIT:** [CMPEN331 Lab 1 Solved](https://www.ankitcodinghub.com/product/cmpen331-solved-3/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;123628&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMPEN331 Lab 1  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Lab 1

In this lab, you will obtain experience with sequential logic design, and study digital design using the Xilinx design package for FPGAs. It is assumed that the students are familiar with the operation of the Xilinx design package for Field Programmable Gate Arrays (FPGAs) through the Xilinix tutorial available in the class website.

1. A finite state machine is a way of modeling system in which the system’s output will depend on not only the current inputs but also the past history of inputs. It defines a finite set of states and behaviors, and how the system transits from one state to another when certain conditions are true. The module of output function is a combinational circuit that generates the outputs based on the current state (Moore model) or the combination of the current state and the current inputs (Mealy model).

2. Suppose we design a radix of six up/down counters as shown in Figure 1. The state of the counter changes on the positive (rising) edge of the clock. If the input u is a 1, the counter value will change in the sequence 0, 1, 2, 3, 4, 5, 0, 1, 2, … . If u is a 0, the counter value will change in the sequence 0, 5, 4, 3, 2, 1, 0, 5, 4, … . There are seven output signals, with each connecting to a segment of LED. A segment of the LED will be on if its control signal is a 0 (active-low).

3. There are six states, the circuit of the counter is shown in Figure 2. The module of dff3 contains three DFFs. The other module is a combinational circuit that generates signals of the next state (ns[2:0]) and LED control signals (a, b, c, d, e, f, and g). The current state (the outputs of dff3) is denoted with q[2:0].

5. Table 1 is the truth table for the next state.

6. For students who took this class as an (honor option). Figure 4 shows the Karnaugh maps for each of the next state signals. From the Karnaugh maps, you can get the expressions of the next state signals. Figure 5 shows the truth table and Karnaugh maps of the output signals. You can get the expressions of the output signals from the Karnaugh maps.

Figure 1 A counter with a seven-segment LED

Figure 2 Block diagram of a counter with a seven segment LED

Figure 3 State transition diagram of the counter

Table 1 State transition table

Figure 4 Karnaugh map for next state of the counter

Figure 5 Karnaugh map for the output function of the counter

Figure 6 Test wave form

7. Write a behavioral Verilog code description using the states shown in Figure 1, 2, 3 and Table 1.

Compile and simulate your code using the test sequence shown in Figure 6.

8. Write a report that contains the following:

a. Your Verilog design code. Use:

i. Device: XC7Z010- -1CLG400C

b. Your Verilog® Test Bench design code (use the test sequence shown in Figure 6). Add “`timescale 1ns/1ps” as the first line of your test bench file.

c. The waveforms resulting from the verification of your design with ModelSim showing all the outputs of the following signals (q, a, b, c, d, e, f, g).

d. The design schematics from the Xilinx synthesis of your design. Do not use any area constraints.

e. Snapshot of the I/O Planning and

f. Snapshot of the floor planning

9. REPORT FORMAT: Free form, but it must be:

a. One report per student.

b. Have a cover sheet with identification: Title, Class, Your Name, etc.

c. Using Microsoft word and it should be uploaded in word format not PDF. If you know LaTex, you should upload the Tex file in addition to the PDF file.

d. Double spaced

10. You have to upload the whole project design file zipped with the word file.

11. For students who took this class as an (honor option).

In addition to all of the above requirements, you need to get the expressions of the next state and the output signals from Karnaugh maps. Compare the results that you get from Karnaugh map and the results you got from the behavioral model of the Verilog code.
