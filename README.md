# cse406-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CSE406  Assignment 1 Solved](https://www.ankitcodinghub.com/product/cse406-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95165&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE406&nbsp; Assignment 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
Topic:

</div>
</div>
<div class="layoutArea">
<div class="column">
In this assignment you will have to implement the Advanced Encryption Standard (AES) algorithm for 128-bit key. Total marks of this assignment is 30.

Overview of AES:

Advanced Encryption Standard (AES) is a popular and widely adopted symmetric key encryption algorithm.

AES uses repeat cycles or “rounds”. There are 10, 12, or 14 rounds for keys of 128, 192, and 256 bits, respectively.

Each round of Algorithm consists of four steps:

<ol>
<li>subBytes: for each byte in the array, use its value as an index into a fixed 256 – element lookup table, and replace its value in the state by the byte value stored at that location in the table. You can find the table and the inverse table on the web.</li>
<li>shiftRows: Let Ri denote the ith row in state. Shift R0 in the state left 0 bytes (i.e., no change); shift R1 left 1 byte; shift R2 left 2 bytes; shift R3 left 3 bytes. These are circular shifts. They do not affect the individual byte values themselves. Shift left for decryption.</li>
<li>mixColumns: for each column of the state, replace the column by its value multiplied by a fixed 4 x 4 matrix of integers (in a particular Galois Field). This is a relatively complex step, but if you utilize the BitVector library demonstrated in the sessional class it will be simple matrix multiplication. Note that the inverse operation multiplies by a different matrix.</li>
<li>addRoundkey: XOR the state with a 128-bit round key derived from the original key K by a recursive process.</li>
</ol>
The final round is slightly different from the others. Implementation details can be found in the presentation slide shared in the sessional class.

</div>
</div>
<div class="layoutArea">
<div class="column">
Page 1 of 5

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Figure: Block Diagram of AES

</div>
</div>
<div class="layoutArea">
<div class="column">
Page 2 of 5

</div>
</div>
<div class="layoutArea">
<div class="column">
28-Feb -2021

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Mark Distribution and Task Breakdown

Task Marks

17 2 12 35 44

Proper Submission 2

Total 30

Bonus (Task 5) 3

Task 1: Key Scheduling (7 Marks)

The key will be provided by the user as ASCII string. If the string length is less than 16 (16×8 = 128 bit), pad it with ‘0’ and if the length is greater than 16 ignore extra characters.

Implement the key scheduling algorithm in this step and generate keys for all the rounds. Link of the algorithm: https://en.wikipedia.org/wiki/AES_key_schedule

Task 2: Encryption (12 Marks)

The encryption method will encrypt a block of text (128 bit/16 characters) with the keys generated in 1. You have to divide the input plain text into blocks of 16 characters and encrypt one block at a time. Pad the input string with spaces if its length is not multiple of 16.

Task 3: Decryption (5 Marks)

Decrypt the encrypted text blocks and observe if they match with the original text. Also report the execution time. A sample output is shown below.

Plain Text:

Key:

</div>
</div>
<div class="layoutArea">
<div class="column">
BUET CSE16 Batch [In ASCII]

</div>
</div>
<div class="layoutArea">
<div class="column">
42554554204353453136204261746368 [In HEX]

</div>
</div>
<div class="layoutArea">
<div class="column">
WillGraduateSoon [In ASCII]

</div>
</div>
<div class="layoutArea">
<div class="column">
57696c6c4772616475617465536f6f6e [In HEX]

</div>
</div>
<div class="layoutArea">
<div class="column">
Cipher Text:

</div>
</div>
<div class="layoutArea">
<div class="column">
54b0f718f62f03c0a455ed78007c6386 [In HEX]

</div>
</div>
<div class="layoutArea">
<div class="column">
T°÷ö/ À¤Uíx�|c† [In ASCII]

</div>
</div>
<div class="layoutArea">
<div class="column">
Page 3 of 5

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Deciphered Text:

</div>
</div>
<div class="layoutArea">
<div class="column">
57696c6c4772616475617465536f6f6e [In HEX]

</div>
</div>
<div class="layoutArea">
<div class="column">
WillGraduateSoon [In ASCII]

</div>
</div>
<div class="layoutArea">
<div class="column">
Execution Time

</div>
</div>
<div class="layoutArea">
<div class="column">
Key Scheduling: 0.01599264144897461 seconds Encryption Time: 0.2241218090057373 seconds

</div>
</div>
<div class="layoutArea">
<div class="column">
Decryption Time: 0.3562753200531006 seconds

</div>
</div>
<div class="layoutArea">
<div class="column">
Task 4: Additional Functionalities (4 Marks)

<ol>
<li>Modify your program so that you can encrypt and decrypt not only text but also other objects (e.g., pdf, image etc.)</li>
<li>Generate the S-Box and the Inverse S-Box tables instead of using hardcoded values. Note that you may use the gf_MI()function of the BitVector module for calculating multiplicative inverse.

Ref: https://en.wikipedia.org/wiki/Rijndael_S-box</li>
</ol>
Task 5: Bonus (3 Marks)

Generalize your program to accommodate key lengths of 128-bit, 192-bit and 256-bit. Compare and report the execution speed in console.

Task 6: [Optional]

Cipher: 182e0afe67094cb70f2a7dc74f7e0076 552456c820d6029f9519a7f8a020a6dc 6707ec0f7e1eb439f3ea0db53ee60c95 8d67693151bba8ec61dacbd83e99c6ef 9daa26069685e2284ba264a9b7ad9a56 d6203cc8ab315c34de944af524b12d65 85ccfb0c6fab4b7006266d66280ad44e a44dbe21d269f3e030129f49851711a6 dd7b9f55dfd4c5dcee355973fc2ce648 6d7df8de352e73d434ee9932477226e4 2012d10b974dfa66366f9830b0fb62e6 9dfde63105ae1d2eccb316e4f57ceb55 eef9677d5dc267f8ece3d2fa30d2c06c

</div>
</div>
<table>
<tbody>
<tr>
<td colspan="2" rowspan="1">
<div class="layoutArea">
<div class="column">
Key:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
44656372797074205461736b20536978

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
</div>
