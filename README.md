Download Link: https://assignmentchef.com/product/solved-quantum-homework-14
<br>
<ol>

 <li>Let G be a finite Abelian group such that</li>

</ol>

by the Fundamental Theorem of Finitely Generated Abelian Groups. Regard elements <em>g </em>∈ <em>G </em>as tuples <em>g </em>= (<em>g<sub>i</sub></em>) ∈ <sup>Q</sup>Z<em>/m<sub>i</sub></em>Z. Recall that the Quantum Fourier Transform for G was

defined where

<em>k µ</em>(<em>g,h</em>) := <sup>Y</sup><em>ω<sub>m</sub><sup>g</sup></em><em><sup>i</sup></em><em><sub>i</sub><sup>h</sup></em><em><sup>i</sup>,    ω<sub>m</sub></em><em><sub>i </sub></em>:= exp(2<em>πi/m<sub>i</sub></em>)<em>.</em>

<em>i</em>=1

<em>k</em>

Show that FG = OFZ<em>/m</em><em>i</em>Z.

<em>i</em>=1

<ol start="2">

 <li>Recall that the Kronecker product of <em>matrices A </em>and <em>B </em>is defined</li>

</ol>

   <em>a</em>11<em>B            </em>···            <em>a</em>1<em>n</em><em>B</em>

<em>A </em>∗ <em>B </em>:= <sup></sup><sub>    </sub><sup>.</sup>..                       <sup>.</sup>..    <sup></sup><sub></sub><em>,                             A </em>= (<em>a<sub>ij</sub></em>)<em>,</em>

   <em>a</em><em>m</em>1<em>B           </em>···            <em>a</em><em>mnB</em>

and that given a <em>linear operator C </em>: T → U, we denote the matrix of <em>C </em>relative to some specified ordered bases for T and U as [<em>C</em>].

Let V<em>,</em>W<em>,</em>X<em>,</em>Y be vector spaces with respective ordered bases

<em>,</em>

<em>,</em>

Define linear operators <em>D </em>: V → W and <em>E </em>: X → Y by

<ul>

 <li>|<em>v</em><sub>1</sub>i = |<em>w</em><sub>1</sub>i + |<em>w</em><sub>2</sub>i + |<em>w</em><sub>3</sub>i<em>, E </em>|<em>x</em><sub>1</sub>i = |<em>y</em><sub>1</sub>i − |<em>y</em><sub>2</sub>i<em>,</em></li>

</ul>

<em>D</em>|<em>v</em><sub>2</sub>i = 2|<em>w</em><sub>2</sub>i − |<em>w</em><sub>3</sub>i<em>,                                            E </em>|<em>x</em><sub>2</sub>i = 2|<em>y</em><sub>2</sub>i<em>,</em>

<ul>

 <li>|<em>x</em><sub>3</sub>i = |<em>y</em><sub>1</sub>i + |<em>y</em><sub>2</sub>i<em>.</em></li>

</ul>

Show that [<em>D</em>] ∗ [<em>E</em>] = [<em>D </em>⊗ <em>E</em>], where the bases for V ⊗ X and W ⊗ Y are the usual lexicographically ordered bases. You may do this by direct calculation if you wish.

<ol start="3">

 <li>Given a group G, recall that the discrete logarithm problem takes as input elements <em>a,b </em>∈ <em>G </em>such that <em>b<sup>s </sup></em>= <em>a</em>, and outputs the number <em>s</em>. Recall that the quantum solution to the discrete logarithm problem involves running the eigenvalue estimation circuit in series using the operators <em>U<sub>b </sub></em>and <em>U<sub>a</sub></em><sup>†</sup>.

  <ul>

   <li>Show that the state in the circuit before passing through the two inverse Quantum</li>

  </ul></li>

</ol>

Fourier Transform blocks is proportional to

<em>.</em>

<ul>

 <li>Carefully show that the state after passing through the two inverse Quantum Fourier Transform blocks but before measurement is proportional to</li>

</ul>

<em> ,</em>

where <em>m </em>is the period/order of <em>b </em>in G. [<em>Hint: use b<sup>s </sup></em>= <em>a</em>.]

<ul>

 <li>Conclude that measuring the top two registers of the circuit produces pairs |<em>u,v</em>i such that <em>b<sup>u</sup>a</em><sup>−<em>v </em></sup>= 1. Explain how to use such pairs to find <em>s</em>.</li>

</ul>