# ShinyApp
Using Shiny and Slidify

You will find the presentation slides in the ShinyApp Folder.
If you click on the index.md the slides will appear, however, not as a presentation.  They will show as one page, however, if you are familiar with slidify (I am not) you will notice I have the code in there for 5 slides. I failed to push the slides using git in the command window.  It would not accept my password.  I apologize for the inconvience.


<!DOCTYPE html>
<html>
<head>
	<meta charset='utf-8'>
	<title>Finding Anomalies with K-means</title>
	<meta name="description" content="Finding Anomalies with K-means">
	<meta name="author" content="Kyle">
	<meta name="generator" content="slidify" />
	
	<!-- LOAD STYLE SHEETS -->
	<link rel="stylesheet" href="libraries/frameworks/html5slides/default/styles.css">
	<link rel="stylesheet" href="libraries/highlighters/highlight.js/css/tomorrow.css" />  <link rel="stylesheet" href = "assets/css/ribbons.css">
  
</head>
<body style='display: none'>
	<section class='slides layout-regular template-regular'>
     <article class="" id="slide-1" style="background:;">
  <h3>Anomaly Detection</h3>
  <ul>
<li>At work I anaylize software system data</li>
<li>Most of it isn&#39;t interesting, but occasionally something abnormal happens</li>
<li>My goal is to find out when that happens and why</li>
<li>To do this I look for anomalies</li>
</ul>

<p><img src="figure/unnamed-chunk-1-1.png" title="plot of chunk unnamed-chunk-1" alt="plot of chunk unnamed-chunk-1" style="display: block; margin: auto;" /></p>

</article>

<article class="class" id="1" style="background:;">
  <h3>How to find Anomalies in Data</h3>
  <ul>
<li>There are a couple ways to find them</li>
<li>Density</li>
<li>Distance</li>
<li>Statistical Properties</li>
</ul>

<table><thead>
<tr>
<th>Density</th>
<th>Distance</th>
<th>Statistical</th>
</tr>
</thead><tbody>
<tr>
<td>LOF</td>
<td>Kmeans</td>
<td>Parametric Models</td>
</tr>
<tr>
<td>CBOF</td>
<td>Knn</td>
<td>Mean, Var, Stdev</td>
</tr>
<tr>
<td>DENLCUE</td>
<td>LDOF</td>
<td>Distribution Assumptions</td>
</tr>
</tbody></table>

</article>

<article class="class" id="2" style="background:;">
  <h3>Don&#39;t Fear!</h3>
  <ul>
<li>Building some of the models mentioned is difficult</li>
<li>Luckily R has many models already made</li>
<li>Kmeans is an example</li>
<li>Caret also has a ton of built in functions for ML and Anomaly Detection</li>
</ul>

</article>

<article class="class" id="3" style="background:;">
  <h3>I&#39;ll help you get started</h3>
  <ul>
<li><a href="https://kgartrell.shinyapps.io/Finding_Anomalies/">https://kgartrell.shinyapps.io/Finding_Anomalies/</a></li>
<li>That link goes to a shiny app that highlights Anomalies using Kmeans</li>
</ul>

</article>

<article class="class" id="4" style="background:;">
  <h3>Hopefully You Found This Interesting!</h3>
  <ul>
<li>Good luck coming up with your own algorithms</li>
</ul>

<pre><code class="r">2+2
</code></pre>

<pre><code>## [1] 4
</code></pre>

<h3>Kindest Regards,</h3>

<h3>Kyle</h3>

</article>

<article class="class" id="5" style="background:;">
  <h3>NA</h3>
  
</article>

  </section>
</body>
  <!-- LOAD JAVASCRIPTS  -->
	<script src='libraries/frameworks/html5slides/default/slides.js'></script>
	<!-- LOAD HIGHLIGHTER JS FILES -->
	<script src="libraries/highlighters/highlight.js/highlight.pack.js"></script>
	<script>hljs.initHighlightingOnLoad();</script>
	<!-- DONE LOADING HIGHLIGHTER JS FILES -->
	 
	</html>
