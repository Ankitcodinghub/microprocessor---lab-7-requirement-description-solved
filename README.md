# microprocessor---lab-7-requirement-description-solved
**TO GET THIS SOLUTION VISIT:** [Microprocessor – Lab 7: Requirement Description Solved](https://www.ankitcodinghub.com/product/microprocessor-lab-7-requirement-description-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110637&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Microprocessor - Lab 7: Requirement Description Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
● Introduction to Interrupt &amp; Timer

Video(Interrupt): https://youtu.be/VawuidtuOuk Video2(Timer): https://youtu.be/ERbznytxgmo

● Lab requirements:

● Basic (70%):

○ Description: Initially, blink 4 LEDs with the following order: RA0 -&gt; RA2. When clicking RB0 button, the order will become RA1 -&gt; RA3. After clicking RB0 button again, it will go back to the original order. Repeat it ! Every LED should be on for 0.5 seconds.

○ Example:

RA0 -&gt; RA2

-click-&gt; RA1 -&gt; RA3 -click-&gt; RA0-&gt; RA2 ○ Standard of grading:

1. Use ISR to handle the button event.

2. Button: RB0, 4 LEDs: RA0~RA3.

3. Write in Assembly.

● Advanced (30%) :

○ Description: Blink 4 LEDs with the following order: RA0 -&gt; RA1 -&gt; RA2 -&gt; RA3. In the first round, every LED should be on for 0.5 second. In the second round, every LED should be on for 1 seconds. Repeat it ! You must use TIMER2 to create the proper delay interval. You are not allowed to use DELAY macro.

○ Example:

RA0 -&gt; RA1 -&gt; RA2 -&gt; RA3 ( 0.5s )

-&gt; RA0 -&gt; RA1 -&gt; RA2 -&gt; RA3 ( 1s ) -&gt; RA0 -&gt; RA1 -&gt; RA2 -&gt; RA3 ( 0.5s ) ○ Standard of grading:

1. Don’t use DELAY macro int this program.

2. 4 LEDs: RA0~RA3.

3. Write in Assembly.

4. Explain how timer2 can trigger the interrupt every interval.

● Bonus (20%):

○ Description: Initially, blink 4 LEDs with the following order: RA0 -&gt; RA1 -&gt; RA2 -&gt; RA3. Every LED should be on for 1 seconds. When clicking RB0 button, every LED should be on

0.5 seconds. After clicking RB0 again, every LED should be on 0.25 seconds. Then clicking RB0 again, it will go back to 1

second. When clicking RB0 button, change the blinking direction immediately

○ Example:

RA0 -&gt; RA1 -&gt; RA2 ( 1s )

–click-&gt; RA1 -&gt; RA0 -&gt; RA3 -&gt; RA2 -&gt; RA1 ( 0.5s )

–click-&gt; RA2 -&gt; RA3 -&gt; RA0 -&gt; RA1 -&gt; RA2 ( 0.25s ) –click-&gt; RA1 -&gt; RA0 -&gt; RA3 -&gt; RA2 -&gt; RA1 … (1s ) ○ Standard of grading:

1. Use ISR to handle the button event.

2. Button: RB0, 4 LEDs: RA0~RA3.

3. Write in Assembly.
