<h1>Some explanations</h1>
<h2>SCSS and Matrices</h2>
<p>To create a matrix in scss, create a list inside another list, always ended with comma</p>
<pre><p><small>// 1x3</small>
$matrix: (
  ( 1, 2, 3<mark><strong>,</strong></mark> )<mark><strong>,</strong></mark>
);</p><hr/><p><small>// 3x3</small>
$matrix: (
  (1, 2, 3<mark><strong>,</strong></mark> )<mark><strong>,</strong></mark>
  (4, 5, 6<mark><strong>,</strong></mark> )<mark><strong>,</strong></mark>
  (7, 8, 9<mark><strong>,</strong></mark> )<mark><strong>,</strong></mark>
);</p></pre>
