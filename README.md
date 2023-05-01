Download Link: https://assignmentchef.com/product/solved-bintodec-dectobin-and-parityparty-python
<br>
5/5 - (10 votes)

<strong>ParityParty</strong>

Write a Python function ParityParty() that takes in a nonnegative integer dd and returns a list:

<ul>

 <li>the first element of the output list is a 0 if the number dd is even, and 1 if dd is odd,</li>

 <li>the second element of the output list is d/2d/2 if dd is even, and (d−1)/2(d−1)/2 if dd is odd.</li>

</ul>

A potentially useful reminder: When you divide or multiply an integer by a floating point number in Python, the result will be a floating point number. If the test cases require an integer as output for d/2d/2 or (d−1)/2(d−1)/2, you may need to account for this…

For example:

<table>

 <thead>

  <tr>

   <th scope="col">Test</th>

   <th scope="col">Result</th>

  </tr>

 </thead>

 <tbody>

  <tr>

   <td><pre>print(ParityParty(0))</pre></td>

   <td><pre>[0, 0]</pre></td>

  </tr>

  <tr>

   <td><pre>print(ParityParty(10))</pre></td>

   <td><pre>[0, 5]</pre></td>

  </tr>

  <tr>

   <td><pre>print(ParityParty(33))</pre></td>

   <td><pre>[1, 16]</pre></td>

  </tr>

 </tbody>

</table>

<strong>BinToDec</strong>

Suppose you were working on some Python code to convert numbers from binary to decimal form. Suppose your mischievous cat walked across your keyboard while you were getting a cup of coffee, and as a result several important pieces of code have gone missing. For each missing piece of code, select the answer that will enable the function BinToDecBinToDec to convert positive integers from binary to decimal form, without modifying any of the other pieces of code.

<strong>DecToBin</strong>

Write a Python function DecToBin() that takes in a nonnegative integer dd and returns a Python list of 00’s and 11’s corresponding to the binary representation of dd.

For example:

<table>

 <thead>

  <tr>

   <th scope="col">Test</th>

   <th scope="col">Result</th>

  </tr>

 </thead>

 <tbody>

  <tr>

   <td><pre>print(DecToBin(0))</pre></td>

   <td><pre>[0]</pre></td>

  </tr>

  <tr>

   <td><pre>print(DecToBin(10))</pre></td>

   <td><pre>[1, 0, 1, 0]</pre></td>

  </tr>

  <tr>

   <td><pre>print(DecToBin(241))</pre></td>

   <td><pre>[1, 1, 1, 1, 0, 0, 0, 1]</pre></td>

  </tr>

 </tbody>

</table>

<strong>Note</strong>: binary_inbinary_in is a Python list, representing the number in binary form.

<strong>Example</strong>: The number 1010 in binary would be input as [1, 0, 1, 0].

def BinToDec(binary_in):def BinToDec(binary_in):

# initialize# initializedecimal_out = 0decimal_out = 0

# add up the binary expression of the decimal number# add up the binary expression of the decimal numberfor position in for position in Choose…range(0, len(binary_in))range(1, len(binary_in))range(0, len(binary_in)-1)range(1, len(binary_in)+1) :

decimal_out = decimal_out + binary_in[len(binary_in)-position-1]*(2**decimal_out = decimal_out + binary_in[len(binary_in)-position-1]*(2**Choose…positionposition-1position+1 ))