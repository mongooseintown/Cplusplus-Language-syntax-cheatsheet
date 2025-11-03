<h1><u>🔢Bitwise Operator🔢</u></h1>
<p>Integer Data type -> Data -> Bit Representation -> Bit level operation -> Bitwise Operation.</p>
<p>Bitwise operation -> operator -> Bitwise Operator.</p>
<p>Bitwise Operator -> direct Manipulates bits.</p>
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
