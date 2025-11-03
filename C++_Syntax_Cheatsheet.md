<h1><u>🔢Bitwise Operator🔢</u></h1>
<p>Integer Data type 👉 Data 👉 Bit Representation 👉 Bit level operation 👉 Bitwise Operation.</p>
<p>Bitwise operation 👉 operator 👉 Bitwise Operator.</p>
<p>Bitwise Operator 👉 direct Manipulates bits.</p>
<b>List of C++ Bitwise operators</b>
<table>
  <thead>
    <tr>
      <th>Operator</th>
      <th>Description</th>
      <th>Example</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>&amp;</td>
      <td>Binary AND Operator copies a bit to the result if it exists in both operands.</td>
      <td>(A &amp; B) will give 12 which is 0000 1100</td>
    </tr>
    <tr>
      <td>|</td>
      <td>Binary OR Operator copies a bit if it exists in either operand.</td>
      <td>(A | B) will give 61 which is 0011 1101</td>
    </tr>
    <tr>
      <td>^</td>
      <td>Binary XOR Operator copies the bit if it is set in one operand but not both.</td>
      <td>(A ^ B) will give 49 which is 0011 0001</td>
    </tr>
    <tr>
      <td>~</td>
      <td>Binary Ones Complement Operator is unary and has the effect of 'flipping' bits.</td>
      <td>(~A ) will give -61 which is 1100 0011 in 2's complement form due to a signed binary number.</td>
    </tr>
    <tr>
      <td>&lt;&lt;</td>
      <td>Binary Left Shift Operator. The left operands value is moved left by the number of bits specified by the right operand.</td>
      <td>A &lt;&lt; 2 will give 240 which is 1111 0000</td>
    </tr>
    <tr>
      <td>&gt;&gt;</td>
      <td>Binary Right Shift Operator. The left operands value is moved right by the number of bits specified by the right operand.</td>
      <td>A &gt;&gt; 2 will give 15 which is 0000 1111</td>
    </tr>
  </tbody>
</table>
Example
<pre><code>
#include &lt;iostream&gt;
using namespace std;

int main() {
   unsigned int a = 60;    // 60 = 0011 1100  
   unsigned int b = 13;    // 13 = 0000 1101
   int c = 0;             

   c = a &amp; b;              // 12 = 0000 1100
   cout &lt;&lt; "Line 1 - Value of c is : " &lt;&lt; c &lt;&lt; endl ;

   c = a | b;              // 61 = 0011 1101
   cout &lt;&lt; "Line 2 - Value of c is: " &lt;&lt; c &lt;&lt; endl ;

   c = a ^ b;              // 49 = 0011 0001
   cout &lt;&lt; "Line 3 - Value of c is: " &lt;&lt; c &lt;&lt; endl ;

   c = ~a;                 // -61 = 1100 0011
   cout &lt;&lt; "Line 4 - Value of c is: " &lt;&lt; c &lt;&lt; endl ;

   c = a &lt;&lt; 2;             // 240 = 1111 0000
   cout &lt;&lt; "Line 5 - Value of c is: " &lt;&lt; c &lt;&lt; endl ;

   c = a &gt;&gt; 2;             // 15 = 0000 1111
   cout &lt;&lt; "Line 6 - Value of c is: " &lt;&lt; c &lt;&lt; endl ;

   return 0;
}
  </code></pre>
