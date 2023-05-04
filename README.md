Download Link: https://assignmentchef.com/product/solved-cs4373_5473-homework1
<br>
Notice: <em>Given the nature of on-line course, we will require you to practice using Words, Markdown, or HTML to write and format your homework solutions (no scanned smeared image please). It will prepare you for taking the on-line exams, where only a Words style editor (with HTML support) is available.</em>

<ol>

 <li>(Data Statistics) Write basic Python functions to obtain the following statistics and apply these functions to columns C, D, E, and F in the table.

  <ul>

   <li>The mean and the midrange.</li>

   <li>The mode and the modality (i.e., bimodal, trimodal, etc.).</li>

   <li>The five-number summary.</li>

   <li>Compare to the corresponding functions provided by DataFrame</li>

  </ul></li>

 <li> (Similarity and Distance) Prompt the user for a tuple, say <em>p </em>= (<em>a</em>1<em>,b</em>2<em>,</em>515<em>,</em>−0<em>.</em>876<em>,</em>6<em>.</em>4253<em>,</em>45), and perform the following tasks.

  <ul>

   <li>Print the row in the DataFrame that is the least dissimilar to <em>p</em>, where the dissimilarity is measured by different types of distances, including the Euclidean distance, Manhattan distance, supremum distance, and cosine similarity, using the set of columns C, D, E, and F.</li>

   <li>Normalize the data points by making the norm of each data point (under columns C,D, E, and F) equal to 1. That is, scale the values in columns C, D, E, and F, so that,</li>

  </ul></li>

</ol>

for each row (c, d, e, f) we have <sup>p</sup><em>c</em><sup>2 </sup>+ <em>d</em><sup>2 </sup>+ <em>e</em><sup>2 </sup>+ <em>f</em><sup>2 </sup>= 1. Then, print the row in the DataFrame that has the shortest Euclidean distances from the normalized point <em>p</em>.

<ol start="3">

 <li> (Normalization) Write functions to normalize the data in a given column using the following methods. Apply these functions on column C.</li>

</ol>

<ul>

 <li>Min-max normalization that transforms the values onto a given range, for example,[−1<em>.</em>0<em>,</em>1<em>.</em>0].</li>

 <li>Z-score normalization.</li>

</ul>

Decimal scaling normalization