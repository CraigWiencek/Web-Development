# Web-Development
Written in HTML5 and CSS3
<!DOCTYPE html>

<!--Programmer: Craig Wiencek
*Class ID: cwienc5421*
Lab #3: Portable Layouts and Presentation*
CIS 3900: Business Web Architecture*Fall 2016*
Due date: 11/17/16
Date completed: 11/16/16 
**************************************
Program Explanation: 


*************************************-->

<html lang="en">
<head>
<title>Welcome to Buoy Boy&#33;</title>
<link href="WebCSScwienc5421.css" rel="stylesheet">
<meta charset="utf-8">
</head>
<body>
<div id="container">
	<header role="banner">
	<img src="Images/buoy_logo.png" alt="Buoy_Boy_logo">
		<span><a href="#content">Jump to chart</a></span>
		<h1>Buoy Boy</h1>
	</header>
	<nav role="navigation">
	<ul>	
		<li><a href="Lab3cwienc5421.html">Home</a></li>
		<li><a href="#">How It Works</a></li>
		<li><a href="#">Contact</a></li>
	</ul>
	</nav>
	<aside role="complementary">
		<h3>News</h3>
		<p class="news">Oct&#46; 12 &#45; Buoy Boy One<br> hits <a href="http://www.nasdaq.com/">market</a> shelves<br>February 1&#44; 2017&#46;</p>
		<p class="news">Oct&#46; 12 &#45; Buoy Boy files <br> for their first patent&#46;</p>
		<p class="news">Oct&#46; 7 &#45; Buoy Boy recieves<br> its first capital <br>investment&#46;</p>	
	</aside>
<main>
<h2>The Problem We Face</h2>
<p>As society progresses we are demanded to do more, whether it is at work or school, and we just don&#39;t have the 
same time to do chores we have to do at home. But that does not mean we should have to sacrifice our luxuries 
like our in-ground pools at home.</p>

<p>The complex chemistry of a pool makes them high maintenance and time consuming, they are like maintaining an ecosystem: 
maintain a certain temperature, manage fluxes in chemical levels, cleanses and cycle. There is an extensive list of duties
 that need to be under taken to maintain a proper pool and if left neglected a pool&#39;s walls deteriorate, algae builds up,
  pool water becomes green and cloudy which lead to extensive repairs down the road.</p>

<p>That is why I have come up with the next home improvement system that will enable home owners to achieve a new level of
 inter-connectivity with their at home pool and spa. </p>
 
 <table border="1" id="informative_chart">
 <caption>Chemical Balance Chart</caption>
<thead> 
 <tr>
 	<th id="chemical">CHEMICAL</th>
 	<th id="ideal_range">IDEAL RANGE</th>
 	<th id="test_schedule">TEST SCHEDULE</th>
 	<th id="effects_of_low_levels">EFFECTS OF LOW LEVELS</th>
 	<th id="corrective_action">CORRECTIVE ACTIONS</th>
 </tr>
</thead> 
<tbody>
 <tr>
 <td headers="chemical">Chlorine</td>
 <td headers="ideal_range">1 to 3 ppm</td>
 <td headers="test_schedule">Daily</td>
 <td headers="effects_of_low_levels">Not enough residual chlorine to safely sanitize pool water</td>
 <td headers="corrective_action">Add granular chlorine as necessary and adjust chlorinator release valve to maintain 1&#45;3
 ppm chlorine reading</td>
 </tr>
 <tr>
 <td headers="chemical">pH</td>
 <td headers="ideal_range">7.2 to 7.8 ppm</td>
 <td headers="test_schedule">Daily</td>
 <td headers="effects_of_low_levels">Equipment and pool wall corrosion, eye and skin irritation, plaster etching, and
 rapid chlorine consumption</td>
 <td headers="corrective_action">add sodium carbonate</td>
 </tr>
 <tr>
 <td headers="chemical">Alkalinity</td>
 <td headers="ideal_range">80 to 100 ppm</td>
 <td headers="test_schedule">Daily</td>
 <td headers="effects_of_low_levels">Eye irritation, pH fluctuation's, stained plaster and metal 
 corrosion</td>
 <td headers="corrective_action">Add sodium bicarbonate</td> 
 </tr>
 <tr>
 <td headers="chemical">Calcium Hardness</td>
 <td headers="ideal_range">200 to 400 ppm</td>
 <td headers="test_schedule">Weekly</td>
 <td headers="effects_of_low_levels">Etching of plaster and equipment corrosion</td>
 <td headers="corrective_action">Add calcium chloride flakes</td>
 </tr>
 <tr>
 <td headers="chemical">Cyanuric Acid</td>
 <td headers="ideal_range">60 to 80 ppm</td> 
 <td headers="test_schedule">Weekly</td>
 <td headers="effects_of_low_levels">Destruction of chlorine by UV rays from sun</td>
 <td headers="corrective_action">Add cyanuric acid(1 lb&#47;500 gallons increases CYA 25 ppm)</td>
 </tr>
</tbody>
<tfoot>
<tr>
 <td colspan="5"><strong>*NOTE: CYA not needed for indor or bromine pool. CYA can be reduced to 30 to 50 ppm
 for colder climate regions.</strong></td>
</tr>
</tfoot>
 </table>
 

<h2> The Solution: Buoy Boy! </h2>
<p>Buoy Boy is a buoy that remains in the pool and/or spa that takes routine readings of the water and reports readings
 and reports of the pool to the home owner&#39;s cell phone via our smart phone application. </p>
 <img src="Images/water_buoty_sensor2.jpg" alt="Sensor_Buoy">
<p>Through our app the home owner will have full access and control of the pools heater, cholorinator/brominator release
 valve, skimmer and main drain valves located on pool pump, pool lights and jets.</p>

<p>We have provided a chart below that you can print out and log the different chemical levels in your pool for a week. 
You can see how levels fluctuate and see just how demanding it is to stay insync with your pools chemistry with out Buoy Boy.</p> 

<table border="1" class="log_chart">
	<caption>My Personal Pool Readings</caption>
	<thead>
	<tr>
	<th id="home_chemical"></th>
	<th id="monday">Monday</th>
	<th id="tuesday">Tuesday</th>
	<th id="wednesday">Wednesday</th>
	<th id="thursday">Thursday</th>
	<th id="friday">Friday</th>	
	</tr>
	</thead>
 <tbody>
<tr>	
 <td headers="home_chemical">Free Chlorine</td>
 <td headers="monday"></td>
 <td headers="tuesday"></td>
 <td headers="wednesday"></td>
 <td headers="thursday"></td>
 <td headers="friday"></td>
</tr>
<tr>	
 <td headers="home_chemical">pH</td>
 <td headers="monday"></td>
 <td headers="tuesday"></td>
 <td headers="wednesday"></td>
 <td headers="thursday"></td>
 <td headers="friday"></td>
</tr><tr>	
 <td headers="home_chemical">Total Alkalinity</td>
 <td headers="monday"></td>
 <td headers="tuesday"></td>
 <td headers="wednesday"></td>
 <td headers="thursday"></td>
 <td headers="friday"></td>
</tr><tr>	
 <td headers="home_chemical">Calcium Hardness</td>
 <td headers="monday"></td>
 <td headers="tuesday"></td>
 <td headers="wednesday"></td>
 <td headers="thursday"></td>
 <td headers="friday"></td>
</tr><tr>	
 <td headers="home_chemical">Cyanuric Acid</td>
 <td headers="monday"></td>
 <td headers="tuesday"></td>
 <td headers="wednesday"></td>
 <td headers="thursday"></td>
 <td headers="friday"></td>
</tr>
</tbody>
<tfoot>
<tr>
<td colspan="6"><strong>*NOTE: Each measurement/reading should be recorded in parts per million</strong> (ppm)</td>
</tr>
</tfoot>
</table>


<footer role="contentinfo">
<small><i>Copyright &copy; 2016 Craig Wiencek </i></small><br>
 	<!--Here I made my email address active and available under my copyright. href= refers to hyperlink reference which i set to
 	"mailto:" so it knows it will be an email address i am hyperlinking and entered my own email. -->
 	<a href="mailto:craig.m.wiencek@wmich.edu">craig.m.wiencek@wmich.edu</a>
</footer>
</main> 	
</div>
</body>
</html>
