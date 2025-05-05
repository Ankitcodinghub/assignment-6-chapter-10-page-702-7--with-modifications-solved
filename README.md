# assignment-6-chapter-10-page-702-7--with-modifications-solved
**TO GET THIS SOLUTION VISIT:** [Assignment # 6 (Chapter 10, Page 702, #7 -with modifications) Solved](https://www.ankitcodinghub.com/product/assignment-6-chapter-10-page-702-7-with-modifications-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;7162&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Assignment # 6 (Chapter 10, Page 702, #7  -with modifications) Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
&nbsp;

Introduction

The purpose of this assignment is to provide you with experience in working with pointers and dynamic memory allocation. The problem description is as follows. Additional specifications are shown in blue text.

<strong>This assignment is not implemented using classes. It is written in a single program</strong>

&nbsp;

<table width="696">
<tbody>
<tr>
<td width="696"><strong>7. Movie Statistics</strong>

Write a program that can be used to gather statistical data about the number of movies college students see in a month. The program should ask the user how many students were surveyed and dynamically allocate an array of that size. The program should then allow the user to enter the number of movies each student has seen. The program should then calculate the average of the values entered.

&nbsp;

Create the following functions:

●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>printArray</strong>. This function should take in the dynamically created array (i.e. pointer to dynamically created array) and the size of the array as parameters. It should print out the contents of the array.

●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>getAverage</strong>. This function should take in the dynamically created array (i.e. pointer to dynamically created array) and the size of the array as parameters.&nbsp; It should return the average as a double value.

●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>sortArray</strong>. This function should take in the dynamically created array (i.e. pointer to dynamically created array) and the size of the array as parameters. It sorts the array sent into it and returns nothing.

●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>getMaximum</strong>. This function should take in the dynamically created array (i.e. pointer to dynamically created array) and the size of the array as parameters. It should return the maximum value within the array as an int value.

&nbsp;

Make sure that user enters positive numbers for # of students and number of movies seen by each student
</td>
</tr>
</tbody>
</table>
&nbsp;

Note that you only have to calculate average, not median and mode of the values entered.

<strong>This assignment does not require you to create classes. Code the assignment in a single cpp file.</strong>

<strong>&nbsp;</strong>

<h2>Approach 1 – Use “regular” pointers</h2>
In this approach, an integer pointer variable is declared. An array (sized at the number entered by the user) is created and the memory address of this array is placed in the pointer variable. With this approach, <strong>remember to deallocate the dynamically created array.</strong>

&nbsp;

<h2>Approach 2 – use Smart Pointers</h2>
You may use unique_ptr to declare a smart pointer to hold the address of the dynamically created array. The syntax to declare such a pointer and to set it to point to an array is as follows:

<table width="345">
<tbody>
<tr>
<td width="23">1

2</td>
<td width="322">unique_ptr&lt;int[]&gt; dynamic_array;

dynamic_array = make_unique&lt;int[]&gt;(5);</td>
</tr>
</tbody>
</table>
The statements shown above create a 5 element array dynamically and place the address of this array in the dynamic pointer. In this assignment, a variable is used instead of the numeric literal “5”.

&nbsp;

When using smart pointer, remember the following 2, very important, issues:

<ul>
<li>Smart points MUST be passed into function by reference</li>
<li>Dynamic arrays managed by unique pointer do not have to be “deleted”.</li>
</ul>
&nbsp;

<h2>Sample output from my version of Assignment 5</h2>
User input is shown in bold, blue, highlighted text.

&nbsp;

&nbsp;

The <strong>main </strong>function’s pseudocode is as follows:

&nbsp;

<table width="648">
<tbody>
<tr>
<td width="648">In int main

●&nbsp;&nbsp;&nbsp; ask user for number of student to be surveyed

●&nbsp;&nbsp;&nbsp; ensure that the number is &gt; 0&nbsp; (Do not check for non-numeric input, test with numbers)

●&nbsp;&nbsp;&nbsp; Setup dynamic array

●&nbsp;&nbsp;&nbsp; ask user to enter movies seen by each of the students

●&nbsp;&nbsp;&nbsp; ensure that number of movies seen by each student is &gt; 0 (Do not check for non-numeric input, test with numbers)

&nbsp;

●&nbsp;&nbsp;&nbsp; Invoke these functions:

●&nbsp;&nbsp;&nbsp; printArray function, passing in the appropriate arguments

●&nbsp;&nbsp;&nbsp; sortArray function, passing in the appropriate arguments

●&nbsp;&nbsp;&nbsp; printArray functions after the sortArray function has been invoked

●&nbsp;&nbsp;&nbsp; getAverage function, passing in the appropriate arguments, and print out the value returned by this function

●&nbsp;&nbsp;&nbsp; getMaximum function, passing in the appropriate arguments, and print out the value returned by this function
</td>
</tr>
</tbody>
</table>
&nbsp;
