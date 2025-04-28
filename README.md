# comp3220-homework-5--racket-interpreter-solved
**TO GET THIS SOLUTION VISIT:** [COMP3220 Homework 5- Racket Interpreter Solved](https://www.ankitcodinghub.com/product/comp3220-racket-interpreter-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118111&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP3220 Homework 5- Racket Interpreter Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Homework Summary

For this part of the homework assignment, we will be creating an interpreter for our TINY programming language in scheme. Our program should be able to take an AST (created by our parser) written in a list format, and “execute” those instructions in racket.

Details

I have given you a mostly completed racket file that you will need to complete to finish the interpreter. Our program defines an “interpreter” that accepts a “program” (an AST from the previous homework assignment that has been formatted as a list) and executes it. Note that the format of the AST does NOT include the token names (as they did in the assignment).

Should you wish to modify your program so that yours produces the same output, you could then use this to produce more test cases than the ones that I will provide to you. You simply need to modify the toStringList method.

I have included several “programs” at the bottom that you can give your interpreter to execute without having to run your previous assignment to generate programs.

Referencing Environment

When we start our interpreter, one of the first things it will do is create an empty reference environment. It should pass this environment along with a single “statement” (recall we built our AST tree so that a program is a series of statements, where each statement is another child of program). Each time our interpreter encounters an assignment statement, it should add the new variable (and it’s value) to the reference environment. Each time a statement is processed, the interpreter should decide whether it’s looking at a variable, and if it is, it should search for the value of that variable in the reference environment (that it was passed).

I have provided several of the functions for you:

• empty-env: creates an “empty reference environment”

• extend-env: accepts a reference environment, a variable, and it’s value and adds the variable and it’s value to the reference environment

• apply-env: accepts a reference environment and a variable and returns its value (or an error message if it cannot find that variable in the reference environment) Extra Credit (5 Points)

Add the ability for your interpreter to handle at least the following Boolean expressions:

&lt;, &gt;, and

Hint: in scheme the symbols for the boolean operators above are what is written above (&lt;, &gt;, and) Racket Interpreter

(15 Points)

Add the ability for your interpreter to handle while loops.

Grading:

(20 points each)

5 test programs similar to [a-e]prog

Some will have errors.

(5 points extra credit)

1 test program to see if your interpreter can handle the following boolean operators: &gt;, &lt;, and

(15 points extra credit)

1 test program to see if your interpreter can handle while loops
