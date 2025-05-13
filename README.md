# cse220-homework-1-solved
**TO GET THIS SOLUTION VISIT:** [CSE220 Homework 1  Solved](https://www.ankitcodinghub.com/product/cse220-homework-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93841&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE220 Homework 1 &nbsp;Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

Part 1: Validate the First Command-line Argument and the Number of Command-line Arguments

For this assignment you will be implementing several operations that perform computations and do data manipulation.

In hwkl .asm, begin writing your program immediately after the label called start coding here.

_

You may declare more items in the .data section after the provided code. Any code that has already been provided must appear exactly as defined in the given file. Do not delete or rename these labels, as doing so will negatively impact grading.

The number of arguments is stored in memory at the label num args by code already provided for you. You will need to use various system calls to print values that your code generates. For example, to orint a strina in MIPS. vou need to use svstem call 4. You can find a listina of all the official MARS

&nbsp;

The number of arguments is stored in memory at the label num args by code already provided for

supported system calls within MARS itself. Click the blue question mark in the right-hand end of the tool bar to open it.

Later in the document is a list of the operations that your program will execute. Each operation is identified by a single character. The character is given by the first command-line argument (whose address is addr_arg0). The parameter(s) to each argument are given as the remaining

4

command-line arguments (located at addresses addr_argl, addr_arg2, etc.). In this first part of the assignment your program must make sure that each operation is valid and has been given the correct number of parameters. Perform the validations in the following order:

<ul>
<li>The first command-line argument must be a string of length one that consists of one of the following characters: 1, 2, S, F, R or P. If the argument is a letter, it must be given in uppercase. If the argument is not one of these strings or if the argument contains more than one character, print the string found at label invalid operation error and exit the program (via system call 10). This string contains a newline character at the end, so you do not need to provide your own.</li>
<li>The 1, 2 and S operations expect two additional arguments. If the total number of command-line arguments for these commands is not three, print the string found at label and exit the program (via system call 10). This string contains a newline character at the end, so you do not need to provide your own.</li>
<li>The F operation expects one additional argument. If the total number of command-line arguments for this command is not two, print the string found at label and exit the program (via system call 10). This string contains a newline character at the end, so you do not need to provide your own.</li>
</ul>
arguments for this command is not two, print the string found at label invalid_args error and exit the program (via system call 10). This string contains a newline character at the end, so you do not need to provide your own.

Important: You must use the provided invalid operation error and invalid args error strings when printing error messages. Do not create your own labels for printing output to the screen. If your output is marked as incorrect by the grading scripts because of typos, then it is your fault for not using the provided strings, and you will lose all credit for those test cases.

Be sure to initialize all of your values (e.g., registers) within your functions. Never assume registers or memory will hold any particular values (e.g., zero). MARS initializes all of the registers and bytes of main memory to zeroes. The grading scripts for later assignments will fill the registers and/or main memory with random values before executing your code.

Later sections will explain how to validate the arguments for each operation.

<h1>Examples of Invalid Input</h1>
5

See the later sections of the documents for explanation of what arguments are valid for each operation.

<table width="321">
<tbody>
<tr>
<td width="111">Command-line Arguments</td>
<td width="112">Label for String to Print</td>
<td width="98">Expected Output</td>
</tr>
<tr>
<td width="111">&nbsp;</td>
<td width="112">&nbsp;</td>
<td width="98">&nbsp;</td>
</tr>
<tr>
<td width="111">Command-line Arguments</td>
<td width="112">Label for String to Print</td>
<td width="98">Expected Output</td>
</tr>
<tr>
<td width="111">Signed OOOE 32</td>
<td width="112">invalid operation error</td>
<td width="98">INVALID OPERATION</td>
</tr>
<tr>
<td width="111">p HIJKL</td>
<td width="112">invalid operation error</td>
<td width="98">INVALID OPERATION</td>
</tr>
<tr>
<td width="111">F XYZ ABC</td>
<td width="112">invalid args</td>
<td width="98">INVALID ARGS</td>
</tr>
</tbody>
</table>
<h1>Character Strings in MIPS Assembly</h1>
In assembly, a string is a one-dimensional array of unsigned bytes. Therefore, to read each character of the string we typically need to use a loop. Suppose that $so contains the base address of the string (that is, the address of the first character of the string). We could use the instruction Ibu $tO, O ($sO) to copy the first character of the string into $tO. To get the next character of the string, we have two options: (i) add I to the contents of $sO and then execute Ibu $tO, O ($sO) again, or (ii) leave the contents of $so alone and execute Ibu $to, 1 ($s0) . Generally speaking, the first approach is easier and simpler to use, but the other approach works perfectly fine if the string is short in length and is always the same length. Note that syntax like Ibu $tO, $tl ($sO) is not valid; an immediate value (a constant) must be given outside the parentheses.

<h1>Next: Process the Input</h1>
<table>
<tbody>
<tr>
<td width="16"></td>
</tr>
<tr>
<td></td>
<td></td>
</tr>
</tbody>
</table>
If the program determines that the first command-line argument is a valid operation and that it has been given a correct number of additional arguments, the program continues by executing the appropriate operation as specified below. Note that you are permitted to add code to the .data section as necessary to implement these operations.

<h1>Part 2: Process a String of Four Hexadecimal Digits that Represents a Signed Integer</h1>
The I, 2 and S operations treat the second command-line argument as a string of hexadecimal digit characters (‘0’ — ‘9’, ‘A’ — ‘F’) that represent a signed one’s complement number, two’s complement number or sign/magnitude number, respectively. The leftmost character represents the most significant nibble (4 bits) of the integer. The operation converts the string into a 32-bit signed integer in two’s complement, storing it in a single register. The code then prints the N rightmost bits of that register, where N is given by the third argument. In other words, the integer is printed as an N-bit, two’s complement value. Finally, the code prints a newline character ( ‘ &nbsp;&nbsp; ). The number of bits to print given by the third argument should be at least 16. Helpful hint: you can give an ASCII character

register, where N is given by the third argument. In other words, the integer is printed as an N-bit, two’s complement value. Finally, the code prints a newline character print given by the third argument should be at least 16. Helpful hint: you can give an ASCII character as a literal in MIPS (e.g., li $aO, ‘\n’).

There are different algorithms you can devise to implement this operation. To get started, think of how you would convert characters like ‘7’ and ‘D’ from the binary ASCII values 00110111 and

6

01000100, respectively, to the binary values 0111 and 1101, respectively. Also explore how you can extract individual bits from a register using bitwise operators.

<ul>
<li></li>
</ul>
<table>
<tbody>
<tr>
<td width="17"></td>
</tr>
<tr>
<td></td>
<td></td>
</tr>
</tbody>
</table>
<ul>
<li>
First command-line argument: the character 1, 2 or S</li>
<li>Second command-line argument: exactly four characters that represent hexadecimal digits</li>
<li>Third command-line argument: a number of bits 2 16 and 32</li>
</ul>
Input Validation

The second command-line argument must consist only of characters that represent hexadecimal digits. All letters must be provided in uppercase. An input containing any lowercase letters is considered invalid; in such cases, print the string invalid args error and terminate the program via system call 10. If the argument contains any other invalid characters, print the string found at label invalid args_error and terminate the program. You may assume that the second command-line argument contains exactly four characters.

The third command-line argument must consist only of two characters that represent decimal digits.You may assume that the third command-line argument contains exactly two digit characters, but that those digits might represent a number in the range 0 through 99, inclusive. If the number is outside the range 16 through 32, print the string invalid args_error and terminate the program. When the third araument is a valid number, vou mav assume that the inout value mav be exoressed

&nbsp;

complement representation of that value using 25 bits.

integer -14 in one’s complement representation, which is represented in 25-bit two’s complement as

Examples

<table width="269">
<tbody>
<tr>
<td width="106">Command-line Arguments</td>
<td width="163">Expected Output</td>
</tr>
<tr>
<td width="106">2 FFFF 20</td>
<td width="163"></td>
</tr>
<tr>
<td width="106">2 0011 25</td>
<td width="163">0000000000000000000010001</td>
</tr>
<tr>
<td width="106">2 7EA2 19</td>
<td width="163"></td>
</tr>
</tbody>
</table>
7

<table width="269">
<tbody>
<tr>
<td width="139">&nbsp;</td>
<td width="13">1</td>
<td width="22">FFFE</td>
<td colspan="3" width="71">20</td>
<td colspan="2" width="163"></td>
<td width="36">&nbsp;</td>
</tr>
<tr>
<td width="139">&nbsp;</td>
<td width="13">1</td>
<td width="22">FFFI</td>
<td colspan="3" width="71">25</td>
<td colspan="2" width="163"></td>
<td width="36">&nbsp;</td>
</tr>
<tr>
<td width="139">&nbsp;</td>
<td width="13">1</td>
<td width="22">4190</td>
<td colspan="3" width="71">32</td>
<td colspan="2" width="163">00000000000000000100000110010000</td>
<td width="36">&nbsp;</td>
</tr>
<tr>
<td width="139">&nbsp;</td>
<td width="13">s</td>
<td width="22">OOOE</td>
<td colspan="3" width="71">22</td>
<td colspan="2" width="163">0000000000000000001110</td>
<td width="36">&nbsp;</td>
</tr>
<tr>
<td width="139">&nbsp;</td>
<td width="13">s</td>
<td width="22">800A</td>
<td colspan="3" width="71">20</td>
<td colspan="2" width="163"></td>
<td width="36">&nbsp;</td>
</tr>
<tr>
<td width="139">&nbsp;</td>
<td width="13">s</td>
<td width="22">OOFF</td>
<td colspan="3" width="71">19</td>
<td colspan="2" width="163"></td>
<td width="36">&nbsp;</td>
</tr>
<tr>
<td colspan="3" rowspan="4" width="174">&nbsp;</td>
<td width="12">s</td>
<td width="23">OOFF</td>
<td colspan="2" width="71">19</td>
<td colspan="2" width="163"></td>
</tr>
<tr>
<td width="12">2</td>
<td width="23">faCE</td>
<td colspan="2" width="71">19</td>
<td colspan="2" width="163">INVALID ARGS</td>
</tr>
<tr>
<td width="12">1</td>
<td width="23">WOLF</td>
<td colspan="2" width="71">28</td>
<td colspan="2" width="163">INVALID ARG S</td>
</tr>
<tr>
<td width="12">s</td>
<td width="23">OIFI</td>
<td colspan="2" width="71">05</td>
<td colspan="2" width="163">INVALID ARG S</td>
</tr>
<tr>
<td width="18"></td>
<td width="15"></td>
<td width="27"></td>
<td width="16"></td>
<td width="25"></td>
<td width="5"></td>
<td width="35"></td>
<td width="123"></td>
<td width="5"></td>
</tr>
</tbody>
</table>
Part 3: Print a Decimal Fixed-point Number as a Binary Fixed-point Number

The F operation takes a string of nine characters that represent a positive decimal real number and, using only integer arithmetic, converts the decimal value to binary and prints it to the screen. The whole number part of the output must not contain any leading zeros except in the case where the whole number part is zero. In this case, only a single zero may be printed. Finally, the code prints a newline character ( ).

The fractional part of the input number will always represent a value that can be computed by adding some combination of the values 0.5, 0.25, 0.125, 0.0625 and 0.03125 (that is, 2-1 , 2-2, 2-3 , 2<sup>4 </sup>and 2 -5). (This accommodation makes it possible to convert the fractional decimal value to binary using only integer arithmetic.) The output value must always contain exactly five bits to the right of the radix point.

<ul>
<li></li>
</ul>
<table>
<tbody>
<tr>
<td width="27"></td>
<td width="39"></td>
<td width="92"></td>
<td width="65"></td>
<td width="122"></td>
<td width="23"></td>
<td width="126"></td>
<td width="58"></td>
</tr>
<tr>
<td></td>
<td rowspan="4"></td>
<td></td>
<td rowspan="2"></td>
<td></td>
<td></td>
<td></td>
<td rowspan="3"></td>
</tr>
<tr>
<td></td>
</tr>
<tr>
<td></td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<ul>
<li>
First command-line argument: the character F</li>
<li>Second command-line argument: exactly three decimal digits characters, followed by a</li>
</ul>
period, followed by exactly five decimal digit characters

Input Validation

You may assume that the input is always valid.

Examples

<table width="195">
<tbody>
<tr>
<td width="106">Command-line Arguments</td>
<td width="90">Expected Output</td>
</tr>
</tbody>
</table>
8

File Edit View Tools Help

Part 4: Encode Six Numerical Fields as an R-Type MIPS Instruction

<table>
<tbody>
<tr>
<td width="17"></td>
</tr>
<tr>
<td></td>
<td></td>
</tr>
</tbody>
</table>
The R operation takes six decimal values, treats them as the six fields of a MIPS R-type instruction, and, using shifting and masking operations, combines the four values into a single 32-bit integer that represents an R-type instruction. The program then prints this value in hexadecimal using syscall 34. Finally, the code prints a newline character ( ‘ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ). An example will help to clarify this process.

<ul>
<li>First command-line argument: the character R</li>
<li>Second command-line argument: the string “00”</li>
<li>Third command-line argument: a string that encodes a positive, two-digit decimal integer in the range [0, 31] (the rs field). A leading zero is provided if needed.</li>
<li>Fourth command-line argument: a string that encodes a positive, two-digit decimal integer in the range [O, 31] (the rt field). A leading zero is provided if needed.</li>
<li>Fifth command-line argument: a string that encodes a positive, two-digit decimal integer in the range [O, 31] (the rd field). A leading zero is provided if needed.</li>
<li>Sixth command-line argument: a string that encodes a positive, two-digit decimal integer in the range [O, 31] (the shamt field). A leading zero is provided if needed.</li>
<li>Seventh command-line argument: a string that encodes a positive, two-digit decimal integer in the range [0, 63] (the funct field). A leading zero is provided if needed.</li>
</ul>
&nbsp;

<table width="222">
<tbody>
<tr>
<td width="42">Field</td>
<td width="40">opcode</td>
<td width="25">rs</td>
<td width="24">rt</td>
<td width="24">rd</td>
<td width="32">shamt</td>
<td width="34">funct</td>
</tr>
<tr>
<td width="42"># of bits</td>
<td width="40">6</td>
<td width="25">5</td>
<td width="24">5</td>
<td width="24">5</td>
<td width="32">5</td>
<td width="34">6</td>
</tr>
</tbody>
</table>
9

Suppose the command-line arguments were the strings

R 00 15 17 03 14 29

The program must process each numerical argument in turn, converting each of the six strings into an integer. Remember that all data in a computer is stored in binary, so, after conversion, these values will be stored as the 32-bit values given below:

00000000000000000000000000000000

00000000000000000000000000010001

00000000000000000000000000000011

00000000000000000000000000001110

00000000000000000000000000011101

We treat these six values as the opcode, rs, rt, rd, shamt and funct fields, respectively. Next, using bitwise operations, we need to concatenate the six rightmost bits of the opcode, five rightmost bits of the rs, rt, rd and shamt fields, and 6 rightmost bits of the funct field:

When printed in hexadecimal, the output value (produced by syscall 34) will be Ox01 fl 1b9d.

characters that encode a positive integer. However, you may not assume that the values are in the legal ranges specified above. If any of the third, fourth, fifth, six and seventh command-line arguments is outside its legal range, print the string found at label invalid args_error and exit the program (via system call 10).

Note that the shamt field is applicable only when performing a shift instruction. You do not need to check whether a non-zero shamt amount is given when a non-shifting instruction is provided. Simply have your code convert the shamt argument to a 5-bit binary value, regardless of what the funct field is, and incorporate that 5-bit value in the final 32-bit value computed by your code.

Examples

<table width="190">
<tbody>
<tr>
<td colspan="2" width="112">Command-line Arguments</td>
<td width="78">Expected Output</td>
</tr>
<tr>
<td width="67">R 00 15 17 03</td>
<td width="44">14 29</td>
<td width="78">Ox01f11b9d</td>
</tr>
<tr>
<td width="67">R 00 02 31 24</td>
<td width="44">05 42</td>
<td width="78">Ox005fc16a</td>
</tr>
<tr>
<td width="67">R 00 22 25 31</td>
<td width="44">00 61</td>
<td width="78">Ox02d9f83d</td>
</tr>
</tbody>
</table>
10

<table width="540">
<tbody>
<tr>
<td width="327">&nbsp;

<table width="190">
<tbody>
<tr>
<td width="112">R 00 17 41 22 30 08</td>
<td width="78">INVALID ARGS</td>
</tr>
</tbody>
</table>
</td>
<td width="213"></td>
</tr>
</tbody>
</table>
Part 5: Identify Non-standard, Five-card Poker Hands

The P operation treats the second command-line argument as a string of exactly five characters that encode a <u>non-standard five-card hand</u> from draw poker.

The P operation treats the second command-line argument as a string of exactly five characters that encode a <u>non-standard five-card hand</u> from draw poker.

The program must be able to identify some of the non-standard hands of five-card draw poker and print a message indicating which one it found. If the hand can be matched with two or more hands, the hand of highest rank is printed. If none of these five ranked hands is identified, the program prints HIGH CARD. You may assume that when the P operation has been provided, the second argument always contains exactly 5 characters. For the purposes of this assignment, an Ace is always treated as a low card (i.e., less than 2), never as a high card (i.e., higher than King).

The hand ranks from highest-to-lowest, along with the relevant MIPS string to print, are:

<table width="335">
<tbody>
<tr>
<td width="27">Rank</td>
<td width="115">Hand Name</td>
<td width="96">Label for String to Print</td>
<td width="97">Output on Screen</td>
</tr>
<tr>
<td width="27">1</td>
<td width="115">Big bobtail</td>
<td width="96">big bobtail str</td>
<td width="97">BIG BOBTAIL</td>
</tr>
<tr>
<td width="27">2</td>
<td width="115">Full house</td>
<td width="96">full house str</td>
<td width="97">FULL HOUSE</td>
</tr>
<tr>
<td width="27">3</td>
<td width="115">Five and dime</td>
<td width="96">five and dime str</td>
<td width="97">FIVE AND DIME</td>
</tr>
<tr>
<td width="27">4</td>
<td width="115">Skeet</td>
<td width="96">skeet str</td>
<td width="97">SKEET</td>
</tr>
<tr>
<td width="27">5</td>
<td width="115">Blaze</td>
<td width="96">blaze str</td>
<td width="97">BLAZE</td>
</tr>
<tr>
<td width="27">6</td>
<td width="115">Everything else (i.e., High card)</td>
<td width="96">high card_str</td>
<td width="97">HIGH CARD</td>
</tr>
</tbody>
</table>
From Wikipedia:

I . Big bobtail: A four-card straight flush (four cards of the same suit in consecutive order). 2. Full house: three cards of one rank and two cards of another rank (example: 3-3-3-J-J).

<ol start="3">
<li>Five and dime: 5-low, 10-high, with no pair (example: 5-6-7-8-10).</li>
<li>Skeet: A hand with a 2, a 5, and a 9, plus two other un-paired cards lower than 9 (example:</li>
</ol>
24-5-6-9).

<ol start="5">
<li>Blaze: All cards are Jacks, Queens, and/or Kings.</li>
<li>High card: None of the above.</li>
</ol>
A single card is encoded as an ASCII character. Specifically, the ASCII code ranges employed are:

<ul>
<li>Ox41 – Ox4D represent the A through K of Clubs</li>
</ul>
&nbsp;

For example, Ox63 represents the 3 of Diamonds and corresponds with the ASCII character ‘c’. Likewise, Ox4B represents the Jack of Clubs and corresponds with the ASCII character

An example of a valid hand would be the string “vX[qd”, which have ASCII codes:

= 6 of Hearts

— 8 of Spades

<ul>
<li>Ox5B = Jack of Spades</li>
<li>ox71 = Ace of Hearts</li>
</ul>
– 4 of Diamonds

Input Validation

You may assume that the second command-line argument always consists of exactly five characters that encode valid cards. You may also assume that no card appears more than once in the input.

Examples

<table width="257">
<tbody>
<tr>
<td colspan="2" width="99">Command-line Arguments</td>
<td width="79">Meaning of Input</td>
<td width="79">Expected Output</td>
</tr>
<tr>
<td width="13">P</td>
<td width="86">BVTUS</td>
<td width="79">64445434</td>
<td width="79">BIG BOBTAIL</td>
</tr>
<tr>
<td width="13">P</td>
<td width="86">BDCEG</td>
<td width="79"></td>
<td width="79">BIG BOBTAIL</td>
</tr>
<tr>
<td width="13">P</td>
<td width="86">RTtbB</td>
<td width="79">24444’2+2*</td>
<td width="79">FULL HOUSE</td>
</tr>
<tr>
<td width="13">P</td>
<td width="86">WUxj 1</td>
<td width="79"></td>
<td width="79">FIVE AND DIME</td>
</tr>
<tr>
<td width="13">P</td>
<td width="86">WRuiF</td>
<td width="79">74245’9+6*</td>
<td width="79">SKEET</td>
</tr>
<tr>
<td width="13">P</td>
<td width="86">TRSYU</td>
<td width="79">442434945*</td>
<td width="79">BIG BOBTAIL</td>
</tr>
<tr>
<td width="13">P</td>
<td width="86">[L}mK</td>
<td width="79">J4Q4K’K+J*</td>
<td width="79">BLAZE</td>
</tr>
<tr>
<td width="13">P</td>
<td width="86">GIDuF</td>
<td width="79"></td>
<td width="79">HIGH CARD</td>
</tr>
</tbody>
</table>
&nbsp;
