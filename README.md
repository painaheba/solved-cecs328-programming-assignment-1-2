Download Link: https://assignmentchef.com/product/solved-cecs328-programming-assignment-1-2
<br>
Implement <em><u>linearSearch(a,key)</u></em> and <em><u>binarySearch(a,key)</u></em> functions.

<strong><u>Part A.</u></strong> <u>In this part we will calculate the<strong> average-case running time </strong>of each function.</u>

<ol>

 <li>Request the user to enter a positive integer, and call it <strong>n</strong>. (<em><u>n = 10</u><sup>5</sup></em>)</li>

 <li>Generate <strong>n</strong> random integers between <em><u>-1000</u></em> to<em> <u>1000</u></em> and save them in array <strong>a</strong>.</li>

 <li>Sort <strong>a</strong> (you can use any sorting algorithm you want.<em>)</em></li>

 <li>Pick a random number in <strong>a</strong> and save it in variable called <strong>key</strong>.</li>

 <li>Call each function separately to search for the key in the given array.</li>

 <li>To calculate the <strong>average-running time</strong>, you need to have a timer to save the total runtime when repeating step 4 and 5 for <strong>100 </strong></li>

</ol>

(<strong><em><u>Note1</u></em></strong>: Do not forget to divide the runtime by the number of the times you run step 4-5)

(<strong><em><u>Note2</u></em></strong>: Remember to choose a different random number each time you go back to step 4.)

<em> </em>

<strong><u>Part B.</u></strong> <u>In this part we will calculate the<strong> worst-case running time </strong>of each function.</u>

<ol>

 <li>Repeat steps <strong>1 to 3</strong> in part A.</li>

 <li>Now to have the worst-case scenario, set the value of the key to <strong>5000</strong> to make sure it does not exist in the array.</li>

 <li>Run each function <strong><u>ONLY</u></strong><u> <strong><em>once</em></strong></u> to calculate the <strong>worst-case running time </strong>when <strong>n = 10<sup>5</sup></strong>.</li>

 <li>Calculate how much time your machine takes to run <strong>one</strong> single step using your binary search function. (<strong><em><u>Hint</u></em></strong>: look at HW4)</li>

 <li>Now using the <strong>previous</strong> step, <strong>write a code</strong> to calculate the worst-case running time for each algorithm when <strong>n=10<sup>7 </sup>(</strong><strong>You do not use a timer for this step. Just a simple calculation!)</strong>.</li>

</ol>





