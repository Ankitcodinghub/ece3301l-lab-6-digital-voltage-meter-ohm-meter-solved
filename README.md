# ece3301l-lab-6-digital-voltage-meter-ohm-meter-solved
**TO GET THIS SOLUTION VISIT:** [ECE3301L LAB 6-Digital Voltage Meter / Ohm Meter Solved](https://www.ankitcodinghub.com/product/ece3301l-lab-6-digital-voltage-meter-ohm-meter-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91478&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE3301L LAB 6-Digital Voltage Meter \/ Ohm Meter Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
LAB 6: Digital Voltage Meter / Ohm Meter

Using the provided schematics, you will need to design the following meters:

A) Voltage Meter:

Connect AN0 (RA0 @pin 2) directly to the wiper pin of a potentiometer (see schematics). Write a program that will measure the voltage input VL0 at AN0 (RA0) and display its value on the two 7-segment displays with the upper digit in Volt and the lower digit representing the 1/10V unit. Turn on the Decimal Point (connected to pin RD7) of the leftmost digit (Upper digit) to show the decimal point. In addition, your team will need to show the same result on the TeraTerm software by doing the output through the use of ‘printf’.

Hint: Copy the function ‘get_full_ADC(void)’ used in the previous lab to measure the value of the input voltage. Make sure that on the register ADCON0 you select AN0 (pin RA0) as the voltage source. Don’t forget to use the function ‘void Select_ADC_Channel( char channel)’

Also, you must make sure that the register ADCON1 has the proper value to force the pin AN0 as an analog input. In addition, don’t forget to program that same register so that the external voltage VREF = 4.096V as the VREF+ reference voltage for the A/D while using GND as the source for VREF-. Do visit the datasheet of the PIC18F4620 at the A/D chapter and look for ADCON1’s definitions.

Make 4 measurements from 0.5 to 4V in increments of 1.0V (do not go past 4.0V). For each measurement, take only the data shown on the output of TeraTerm (not the display) and then measure the same voltage using a DVM. Show the percentage error between the value from the DVM and the one shown on TeraTerm for each measurement.

</div>
</div>
<div class="layoutArea">
<div class="column">
V(DVM) V(TeraTerm)

</div>
<div class="column">
% difference

</div>
</div>
<div class="layoutArea">
<div class="column">
0.5V 1.5V 2.5V 3.5V 4.0V

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
B) Ohm Meter:

You will need to acquire the following resistors:

* 1 100 ohm with 1% precision * 1 1 Kohm with 1% precision * 1 10 Kohm with 1% precision

Note: Use the unit of Kohm instead of ohm because for the purpose of this lab it would prevent overflow in the computations.

In addition to the above resistors, you also need to get the following resistors to be used as unknown resistors RL:

* 1 22 ohm

* 1 220 ohm * 1 470 ohm * 1 1Kohm

* 1 2.2Kohm * 1 10Kohm * 1 22Kohm * 3 33Kohm * 1 47Kohm * 1 100Kohm

Before doing the lab, measure each resistor using the DVM and record its value and put them on a spreadsheet.

You don’t have to get the exact value of the resistors listed above but something close to those resistors. However, there should be a resistor with the value up close to 100K ohms.

Part B1)

Referring to the schematics for this lab, connect the 100 ohm 1% precision resistor at Rref1 and an unknown resistor at RL. The junction of Rref1 and RL is called VL1 and it must be connected to AN1 (pin RA1). Modify the program for the Voltage meter above that measures the input voltage at RA1 and uses that value in conjunction of the KVL and KCL laws to derive the value of the unknown RL based on the fact that Vref is 4.096V.

The measured value of the unknown resistor must be shown on the two 7- segment displays. If the unknown resistor is less than 10K, show the decimal point on the upper digit so that we will see the values on the both 7-segment

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
displays will show values from 0.0 to 9.9K. If the resistor is greater than 10K, then turn off the decimal point to only show the integer portion of that value indicating it is from 10 to 99.

In addition, you need to use the serial port to display the same result on the TeraTerm. Use the ‘printf’ function to display the floating point result.

Once again, make sure that the proper bits are set on the ADCON0 register to you select AN1 now as the voltage source.

Make 10 measurements using the different values that I have asked you to obtain and tabulate them along with the values measured of each unknown resistor using a DVM. Show the percentage error between the value shown on TeraTerm (not the value from the display) and the measured value for each measurement (the one that you have measured at the start of the experiment). Sort the results in ascending order of the resistors RL.

</div>
</div>
<div class="layoutArea">
<div class="column">
Resistor (in Kohms) 0.022 0.220

… 100

</div>
<div class="column">
RL(DVM) RL(TeraTerm)

</div>
<div class="column">
% difference

</div>
</div>
<div class="layoutArea">
<div class="column">
After a value of resistance is measured, do the following additional tasks:

a) Set the color of the RGB LED D1 to reflect the range of value of the unknown resistor. Use the following color table:

</div>
</div>
<div class="layoutArea">
<div class="column">
Resistance Range Below 10K

10K-19 K 20K-29 K 30K-39 K 40K-49K 50K-59 K 60K-69K Above 70K

</div>
<div class="column">
D1’s color Off

Red Green Y ellow Blue Purple Cyan White

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol start="2">
<li>b) &nbsp;Check if the value of the resistor is less than 20 ohm (0.020 Kohm). If it is, turn on the RGB LED D2 to be BLUE else force it to be off.</li>
<li>c) &nbsp;At the same time, when that unknown resistor is below 20 ohms turn on the buzzer circuit by calling the routine Activate_Buzzer() below:</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
void Activate_Buzzer() {

PR2 = 0b11111001 ; T2CON = 0b00000101 ; CCPR2L = 0b01001010 ; CCP2CON = 0b00111100 ;

}

The buzzer will use the pin from PORTB bit 3. However, that bit on the PIC18F4620 has a dual function. To enable for the use to work with the buzzer, insert the following line at the beginning of the program close to the other ‘#pragma config’ lines:

#pragma config CCP2MX = PORTBE

When the unknown resistance is higher than 20 ohms, turn off D2 and shut off the buzzer by calling the routine Deactivate_Buzzer();

void Deactivate_Buzzer() {

CCP2CON = 0x0; PORTBbits.RB3 = 0;

}

Part B2)

This part will use the alternate circuit built with the resistor Rref2 and RL to measure an unknown resistor. Rref2 is 1Kohm 1% instead of the 100ohm 1% used as Rref1. The voltage VL2 is connected to AN2 (or RA2). Change the program in Part B1) to determine the value of RL. Use the same set on unknown resistors used in Part B1) and repeat the same measurements. Make another table to show all the measurements. Don’t forget to change ADCON0 accordingly. The RGB LEDs D1 and D2 and the buzzer should have the same implementation as in part B1.

Part B3)

This part will use the alternate circuit built with the resistor Rref3 and RL to measure an unknown resistor. Rref3 is 10Kohm 1% instead of the 1K ohm 1% used as Rref2. The voltage VL3 is connected to AN4 (or RA5). Change the program to determine the value of RL. Use the same set on unknown resistors used in part 1 and repeat the same measurements. Make another table to show all the measurements. Don’t forget to change ADCON0 accordingly.

When all the three parts of this ohmmeter section are completed and after the three spreadsheets are filled with the %error calculated, study the columns for the

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
errors in each case to come up with the explanations of the use for each of the reference resistance.

</div>
</div>
</div>
