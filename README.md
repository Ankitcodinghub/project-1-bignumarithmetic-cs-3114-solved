# project-1-bignumarithmetic-cs-3114-solved
**TO GET THIS SOLUTION VISIT:** [Project 1: BigNumArithmetic CS 3114 Solved](https://www.ankitcodinghub.com/product/project-1-bignumarithmetic-cs-3114-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;52951&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Project 1: BigNumArithmetic  CS 3114 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
<h1>Overview</h1>
In most programming languages, integer values are of a fixed size, e.g., 32 bits in C++, 64 bits in Java. 32 bits will allow integers of approximately 10 decimal digits. For most purposes this is sufficient, but when it is not, infinite precision integer arithmetic can be implemented in software. For this project you will implement a “BigNumArithmetic” or infinite precision arithmetic package for non-negative integers.

<h1>Input &amp; Output</h1>
The input to this program should be read from the provided input file and the output should be printed to standard output (i.e., using <sub>System.out.println</sub>). The name of your driver class (the one containing the <sub>main </sub>method) should be <sub>BigNumArithmetic</sub>. The input file will consist of a series of arithmetic expressions. To simplify the project, all expressions will be in <em><sub>Reverse Polish Notation </sub></em>(RPN). In RPN, the operands come before the operator. For example, you normally see multiplication written <sub>(a * b)</sub>. In RPN, this expression would appear as <sub>(a b *)</sub>. For expressions with more than one operator, each time an operator is encountered, it operates on the two immediately preceding sub-expressions. For example, <sub>(a + b * c) </sub>would be <sub>(a b c * +) </sub>in RPN. This means that <sub>b </sub>and <sub>c </sub>are multiplied, then the results of the multiplication are added to <sub>a </sub>(this follows the normal rules of arithmetic precedence in which <sub>* </sub>operations take precedence over <sub>+ </sub>operations). In RPN, there is no operator precedence; operators are evaluated left to right, making things substantially simpler to implement. Thus, the expression <sub>((a + b) * c) </sub>is written (a b + c *) in RPN.

Input operands consist of a string of digits, and may be of any length. You should trim off any excess zeros at the beginning of an operand. Expressions may also be of any length. Spaces may appear within the expression arbitrarily, with the rule that a space terminates an operand, and a line break terminates an expression. The operations to be supported are addition (<sub>+</sub>), multiplication (<sub>*</sub>), and exponentiation (<sub>ˆ</sub>). Your program should not break if the number of operators and operands don’t match correctly, i.e., if there are no operands left for an operator, or if the expression ends without providing sufficient operators. When an error is detected, processing should stop on the current expression, and your program should proceed to the next expression.

Use the following output format. For each expression, echo the input as it is read, followed by the result of the operation, or blank space for an error, as appropriate. If you are given the expression <sub>2 8 + 2 </sub><sub>ˆ</sub>, you should print the expression, followed by an equals sign (<sub>=</sub>) and the answer. That is:

2 8 + 2 ˆ = 100

If an error is detected, e.g., if you get an expression like <sub>2 8 + 2 </sub>that doesn’t have enough operators, print:

2 8 + 2 =

You will be provided with an example input and corresponding output file in Canvas.

<h1>Implementation</h1>
RPN simplifies the project since it can be easily implemented using a stack. As the expression is read in, operands are placed on the stack. Whenever an operator is read, the top two operands are removed from the stack, the operation is performed, and the result is placed back onto the stack. You may assume that the stack will never hold more than 100 operands. Example. Suppose you see the expression <sub>(a b c * +)</sub>. As you read the expression, place <sub>a</sub>, <sub>b</sub>, and <sub>c </sub>on the stack. Then you come across the multiplication operator (<sub>*</sub>). Pop the top two operands off the stack (<sub>b </sub>and <sub>c</sub>), and multiply them. Place the result back on the stack. Next, you see the addition operator (<sub>+</sub>). Pop the top two operands off the stack (now, these are the result (<sub>b * c</sub>) and <sub>a</sub>), and add them. Place the result back on the stack. You have reached the end of the expression—pop off the remaining item and return it as the result.

The main problem in this project is implementation of infinite precision integers and calculation of the arithmetic operations <sub>+</sub>, <sub>*</sub>, and<sub>ˆ</sub>.

Integers are to be represented in your program by a linked list of digits, one digit per list node. You must maintain a linked list of nodes as discussed in class, and allocate new link nodes with the new operator as needed. Each digit may be represented as a character, or as an integer, as you prefer. You will likely find that operations are easier to perform if the list of digits is stored backwards (low order to high order).

Example. The integer 436 (four hundred and thirty six) may be represented in a linked list as: <sub>6 </sub>→ <sub>3 </sub>→ <sub>4</sub>. Note that results should be returned with digits in the correct order, so be sure to convert between this representation and a ”normal” representation as appropriate.

<em>Addition </em>is easily performed by starting low order digits of the two integers, and add each pair of digits as you move to the high order digits. Don’t forget to carry over when the sum of two digits is 10 or greater!

<em>Multiplication </em>is performed just as you probably learned in elementary school when you multiplied two multi-digit numbers. The low order digit of the second operand is multiplied against the entire first operand. Then the next digit of the second operand is multiplied against the first number, with a “0” placed at the end. This partial result is added to the partial result obtained from multiplying the previous digit. The process of multiplying by the next digit and adding to the previous partial result is repeated until the full multiplication has been completed.

<em>Exponentiation </em>will need to be performed in a very specific way. The obvious way to exponentiate is to multiply the first operand to itself the appropriate number of times, decrementing the exponent once each time until done. This is extremely inefficient, and becomes untenably slow for even moderately large exponents. Instead, you will follow the <em><sub>exponentiation by squaring </sub></em>algorithm, which takes advantage of observation that, for a positive integer <em><sub>n</sub></em>,

<sup>( </sup>is odd&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (1)

<em>,&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </em>if <em><sub>n </sub></em>is even

This drastically reduces the number of multiplications that need to be performed, and can be used to deal with larger values of <em><sub>x </sub></em>or <em><sub>n</sub></em>.

Addition, multiplication, and exponentiation may be implemented iteratively (using loops) or recursively, as you prefer.

<h1>Submission &amp; Grading</h1>
<ul>
<li>You will implement your project using Eclipse, and you will submit your project using the Eclipse plugin to WebCAT. Links to the WebCAT client are posted at the class website.</li>
<li>If you make multiple submissions, only your last submission will be evaluated. There is no limit to the number of submissions that you may make.</li>
<li>You should write tests for your program as you go, from the beginning. You are required to submit your own test cases with your program, and part of your grade will be determined by how well your test cases test your program, as defined by Web-CAT’s evaluation of code coverage. The names of your test files should include the word “Test”, so that Web-CAT knows what they are. Of course, your program must pass your own test cases.</li>
<li>Part of your grade will also be determined by test cases that are provided by the graders. WebCAT will report to you which tests have passed correctly, and which have not. Note that you will not be given a copy of these test files, only a brief description of what each accomplished in order to guide your own testing process in case you did not pass one of our tests.</li>
</ul>
When structuring the source files of your project, use a flat directory structure; that is, your source files will all be contained in the project <sub>src </sub>directory. Any subdirectories in the project will be ignored. You are permitted to work with a partner on this project. When you work with a partner, then only one member of the pair will make a submission. Be sure both names are included in the documentation. Whatever is the final submission from either of the pair members is what we will grade unless you arrange otherwise with the TA.

<h1>Programming Standards</h1>
You must conform to good programming/documentation standards. Web-CAT will provide feedback on its evaluation of your coding style, and be used for style grading. Beyond meeting Web-CAT’s checkstyle requirements, here are some additional requirements regarding programming standards:

<ul>
<li>You should include a comment explaining the purpose of every instance variable or named constant you use in your program.</li>
<li>You should use meaningful identifier names that suggest the meaning or purpose of the constant, variable, function, etc. Use a consistent convention for how identifier names appear, such as “camelCasing”.</li>
<li>Always use named constants or enumerated types instead of literal constants in the code.</li>
<li>Source files should be under 600 lines.</li>
<li>There should be a single class in each source file. You can make an exception for small inner classes (less than 100 lines including comments) if the total file length is less than 600 lines.</li>
</ul>
We can’t help you with your code unless we can understand it. Therefore, you should not bring your code to the TAs or the instructors for debugging help unless it is properly documented and exhibits good programming style. Be sure to begin your internal documentation right from the start.

You may only use code you have written, either specifically for this project or for earlier programs, or code provided by the instructor (this includes code from OpenDSA). Note that the OpenDSA code is not designed for the specific purpose of this assignment, and is therefore likely to require modification. It may, however, provide a useful starting point.

<em>Good luck!</em>
