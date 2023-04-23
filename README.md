Download Link: https://assignmentchef.com/product/solved-50-004-homework-set1
<br>



Note: In this homework set, log denotes the natural logarithm<a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a>, i.e. the logarithm in base <em>e</em>.

<strong>Question 1. </strong>For each function pair of <em>f<sub>row</sub></em>(<em>n</em>) and <em>f<sub>column</sub></em>(<em>n</em>) in the following table, determine<a href="#_ftn2" name="_ftnref2"><sup>[2]</sup></a>the smallest <strong>positive integer </strong><em>n </em>≥ 2 that makes <em>f<sub>row</sub></em>(<em>n</em>) ≥ <em>f<sub>column</sub></em>(<em>n</em>). [5 points]

√

<table width="555">

 <tbody>

  <tr>

   <td width="99"> </td>

   <td width="99">1000000log<em>n</em></td>

   <td width="80">100000 <em>n</em></td>

   <td width="61">10000<em>n</em></td>

   <td width="86">1000<em>n</em>log<em>n</em></td>

   <td width="53">100<em>n</em><sup>2</sup></td>

   <td width="46">10<em>n</em><sup>3</sup></td>

   <td width="31">2<em>n</em></td>

  </tr>

  <tr>

   <td width="99">1000000log<em>n</em>√</td>

   <td width="99">–</td>

   <td width="80">–</td>

   <td width="61">–</td>

   <td width="86">–</td>

   <td width="53">–</td>

   <td width="46">–</td>

   <td width="31">–</td>

  </tr>

  <tr>

   <td width="99">100000 <em>n</em></td>

   <td width="99"> </td>

   <td width="80">–</td>

   <td width="61">–</td>

   <td width="86">–</td>

   <td width="53">–</td>

   <td width="46">–</td>

   <td width="31">–</td>

  </tr>

  <tr>

   <td width="99">10000<em>n</em></td>

   <td width="99"> </td>

   <td width="80"> </td>

   <td width="61">–</td>

   <td width="86">–</td>

   <td width="53">–</td>

   <td width="46">–</td>

   <td width="31">–</td>

  </tr>

  <tr>

   <td width="99">1000<em>n</em>log<em>n</em></td>

   <td width="99"> </td>

   <td width="80"> </td>

   <td width="61"> </td>

   <td width="86">–</td>

   <td width="53">–</td>

   <td width="46">–</td>

   <td width="31">–</td>

  </tr>

  <tr>

   <td width="99">100<em>n</em><sup>2</sup></td>

   <td width="99"> </td>

   <td width="80"> </td>

   <td width="61"> </td>

   <td width="86"> </td>

   <td width="53">–</td>

   <td width="46">–</td>

   <td width="31">–</td>

  </tr>

  <tr>

   <td width="99">10<em>n</em><sup>3</sup></td>

   <td width="99"> </td>

   <td width="80"> </td>

   <td width="61"> </td>

   <td width="86"> </td>

   <td width="53"> </td>

   <td width="46">–</td>

   <td width="31">–</td>

  </tr>

  <tr>

   <td width="99">2<em>n</em></td>

   <td width="99"> </td>

   <td width="80"> </td>

   <td width="61"> </td>

   <td width="86"> </td>

   <td width="53"> </td>

   <td width="46"> </td>

   <td width="31">–</td>

  </tr>

 </tbody>

</table>

<strong>Question 2. </strong>For each function <em>f</em>(<em>n</em>) and time <em>t </em>in the following table, determine the largest input size <em>n </em>of a problem that can be solved in time <em>t</em>, assuming that the algorithm takes <em>f</em>(<em>n</em>) microseconds to solve the problem. Each input size <em>n </em>must be a <strong>positive number</strong>. (Note: 1 microsecond equals 10<sup>−6 </sup>second. For convenience, you may express <em>n </em>in the scientific notation, rounded to three decimal places, e.g. 1<em>.</em>234 × 10<sup>8</sup>.) [5 points]

<table width="297">

 <tbody>

  <tr>

   <td width="57"> </td>

   <td width="80">1 second</td>

   <td width="77">1 hour</td>

   <td width="84">1 year</td>

  </tr>

  <tr>

   <td width="57"> </td>

   <td width="80"> </td>

   <td width="77"></td>

   <td width="84"> </td>

  </tr>

 </tbody>

</table>

1

<strong>Question 3. </strong>Please explain the following statements:

<ul>

 <li>Explain why the statement, “The running time of algorithm A is at least <em>O</em>(<em>n</em><sup>2</sup>)”, does not make sense. Your explanation should include a detailed example. [2 points]</li>

 <li>We are given that an algorithm has complexity <em>O</em>(log<em>n</em>) in the given input size n. Explain why the complexity for this algorithm is also <em>O</em>(log<em><sub>b </sub>n</em>), regardless of the choice of any base <em>b &gt; </em>1 for the logarithm appearing in the expression. [3 points]</li>

</ul>

<strong>Question 4. </strong>In every row of the table below, there are two functions <em>f</em>(<em>n</em>) and <em>g</em>(<em>n</em>) given.

Determine whether each of the three statements “<em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>))”, “<em>f</em>(<em>n</em>) = Ω(<em>g</em>(<em>n</em>))”, “<em>f</em>(<em>n</em>) = Θ(<em>g</em>(<em>n</em>))” is true or false for the given functions. You may indicate your answer as T/F in the

blanks provided in the table.                                                                                                                          [5 points]

<table width="572">

 <tbody>

  <tr>

   <td width="173"><em>f</em><strong>(</strong><em>n</em><strong>)</strong></td>

   <td width="57"><em>g</em><strong>(</strong><em>n</em><strong>)</strong></td>

   <td width="114"><em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>))</td>

   <td width="113"><em>f</em>(<em>n</em>) = Ω(<em>g</em>(<em>n</em>))</td>

   <td width="114"><em>f</em>(<em>n</em>) = Θ(<em>g</em>(<em>n</em>))</td>

  </tr>

  <tr>

   <td width="173"><em>n</em>1<em>.</em>01</td>

   <td width="57"><em>n</em>log<em>n</em></td>

   <td width="114"> </td>

   <td width="113"> </td>

   <td width="114"> </td>

  </tr>

  <tr>

   <td width="173"><em>n</em>log<em>n</em></td>

   <td width="57">log<em>n</em>!</td>

   <td width="114"> </td>

   <td width="113"> </td>

   <td width="114"> </td>

  </tr>

  <tr>

   <td width="173">1 + 1<em>/</em>2 + 1<em>/</em>3 + <em>… </em>+ 1<em>/n</em></td>

   <td width="57">log<em>n</em></td>

   <td width="114"> </td>

   <td width="113"> </td>

   <td width="114"> </td>

  </tr>

  <tr>

   <td width="173"><em>n</em>2<em><sup>n</sup></em></td>

   <td width="57">3<em>n</em></td>

   <td width="114"> </td>

   <td width="113"> </td>

   <td width="114"> </td>

  </tr>

  <tr>

   <td width="173"><em>n</em><em>π</em></td>

   <td width="57"><em>e</em><em>n</em></td>

   <td width="114"> </td>

   <td width="113"> </td>

   <td width="114"> </td>

  </tr>

 </tbody>

</table>

<strong>Question 5. </strong>Suppose <em>f</em>(<em>n</em>) and <em>g</em>(<em>n</em>) are real-valued functions in the single variable <em>n</em>, where <em>n </em>represents input size (assumed to be a positive integer). Are the following statements true or false? Please justify your answers with details.

(i) For any real constants <em>a </em>and <em>b </em>such that <em>b &gt; </em>0, we must have (<em>n </em>+ <em>a</em>)<em><sup>b </sup></em>= Θ(<em>n<sup>b</sup></em>). [3 points] (ii) <em>f</em>(<em>n</em>) + <em>g</em>(<em>n</em>) = Θ(min(<em>f</em>(<em>n</em>)<em>,g</em>(<em>n</em>))). [1 point]

(iii) <em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>)) implies <em>g</em>(<em>n</em>) = Ω(<em>f</em>(<em>n</em>)). [1 point]

<a href="#_ftnref1" name="_ftn1">[1]</a> The logarithm notation is not consistently used throughout various academic disciplines, so what “log” (with no subscript) means would depend on the context. For example, in mathematics (especially in functional analysis and analysis-related areas), log by default is natural logarithm. In information theory, log is commonly used to denote base 2 logarithm. In some engineering areas (e.g. communication theory), log is sometimes in base 10, but sometimes in base 2. More theoretical engineering papers would use log to mean natural logarithm. The common good practice in research papers is to specify which base is being used in logarithms, since there is actually no “universally accepted convention”.

<a href="#_ftnref2" name="_ftn2">[2]</a> You may find WolframAlpha (<a href="https://www.wolframalpha.com/input/?i=sqrt%28x%29+%3E10+*+log%28x%29">https://www.wolframalpha.com/input/?i=sqrt%28x%29+%3E10+*+log%28x% </a><a href="https://www.wolframalpha.com/input/?i=sqrt%28x%29+%3E10+*+log%28x%29">29</a><a href="https://www.wolframalpha.com/input/?i=sqrt%28x%29+%3E10+*+log%28x%29">)</a> useful to solve Question 1 and Question 2.