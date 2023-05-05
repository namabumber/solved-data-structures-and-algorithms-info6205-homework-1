Download Link: https://assignmentchef.com/product/solved-data-structures-and-algorithms-info6205-homework-1
<br>
Put all your java, compiled class files and documentation files into a zip file named Homework1.zip and submit it via the drop box on the blackboard before the END of due date. Put your name on all .java files. There will be a short quiz on this homework.




<ol>

 <li>Estimate the running time (or memory) as a function of input size <em>N</em>. Explain as to why the results are for the following three examples.</li>

</ol>




⅙ <em>N </em><sup>3   </sup>+  20 <em>N</em><sup>  </sup> +  16                                ~   ⅙ <em>N </em><sup>3</sup>

⅙ <em>N </em><sup>3   </sup>+  100 <em>N </em><sup>4/3 </sup> +  56                           ~   ⅙ <em>N </em><sup>3</sup>

⅙ <em>N </em><sup>3   </sup>–  ½ <em>N</em><sup>  2</sup><em> </em><sup> </sup><em> </em>+  ⅓  <em>N                           </em>~   ⅙ <em>N </em><sup>3</sup>




<ol start="2">

 <li>Write the code samples with running time of: (constant 1, logN, N, NlogN, N^2, N^3, 2^N). Mathematically, what do you describe each one of these examples?</li>

</ol>
















<ol start="3">

 <li>Write the code that results to following running time. Describe the math.</li>

</ol>



















<ol start="4">

 <li>The 3-Sum Triple loop has the following running time estimate. Explain.</li>

</ol>

Note: I do not want to prove the math. I want only the description of the math, what it

represents and why the result is 1/6 N^3




<ol start="5">

 <li>What are all Stack operations, explain.</li>

</ol>




<ol start="6">

 <li>Consider String “It was the best of time”. Start with the first word, design a Stack such that when you read back the words, the order of string does not change. Provide code for all necessary operations of Stack. Compile and run the code.</li>

</ol>




<ol start="7">

 <li>Consider the following Node data structure, build a Stack linkedList with the following data: {31, “Name1”}, {24, “Name2”}, {10, “Name3”}, {44, “Name4”}, {81, “Name5”}.</li>

 <li>a) Provide java implementation for all necessary Stack operations including stack pointers.</li>

 <li>b) Compile and run your program.</li>

 <li>c) What is Stack linkedList time and space complexity?</li>

</ol>




class Node {

int Age;

String Name;

Node next;

}




<ol start="8">

 <li>Consider data: {31, “Name1”}, {24, “Name2”}, {10, “Name3”}, {44, “Name4”}, {81, “Name5”}.</li>

</ol>




<ol>

 <li>a) Provide Array implementation of Stack.</li>

 <li>b) Compile and run the code.</li>

 <li>c) What is Stack Array implementation time and space complexity?</li>

</ol>




<ol start="9">

 <li>Suppose in problem-8 the array size was: a) too large, or b) too small. How would you manage resizing the array for (a) and (b). Write the code, compile and test the program. Also discuss the running time/space complexity of your approach.</li>

</ol>




<ol start="10">

 <li>Human use Infix expression and computers use Postfix expression. You are to write a simple Calculator. There are three steps: a) Read Infix expression, b) Convert Infix expression to Postfix, and c) Evaluate Postfix expression. Write Java code, compile and run with five Infix expression examples.</li>

</ol>

(1 + 2 * (20 / 5 ))

(1 + 2 – 3)

(1 + 3 + ( ( 4 / 2 ) * ( 8 * 4 ) ))

(300+23)*(43-21)/(84+7)

(4+8)*(6-5)/((3-2)*(2+2))

References:

<a href="http://www.cs.nthu.edu.tw/~wkhon/ds/ds10/tutorial/tutorial2.pdf">http://www.cs.nthu.edu.tw/~wkhon/ds/ds10/tutorial/tutorial2.pdf</a>

<a href="https://www.includehelp.com/c/infix-to-postfix-conversion-using-stack-with-c-program.aspx">https://www.includehelp.com/c/infix-to-postfix-conversion-using-stack-with-c-program.aspx</a>

<a href="http://ice-web.cc.gatech.edu/ce21/1/static/audio/static/pythonds/BasicDS/InfixPrefixandPostfixExpressions.html">http://ice-web.cc.gatech.edu/ce21/1/static/audio/static/pythonds/BasicDS/InfixPrefixandPostfixExpressions.html</a>





