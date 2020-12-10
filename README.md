1)Demonstrate the use of Table, Un-order and Order list using both HTML & CSS.

ANS:
//USING CSS;

table, th, td {
  border: 2px solid black;
  border-collapse: collapse;
  margin-left: auto;
  margin-right: auto;
}

h1, h2{
	text-align: center;
}

ol li{
	text-align: center;
	font-size: 20px;
}

ul li{
	text-align: center;
	font-size: 20px;
}

.square li{
	list-style: square;
}



//USING HTML;


<!DOCTYPE html>
<html>
<head>
	<title>1) Demonstrate the use of Table, Un-order and Order list using both HTML & CSS.</title>
	<link rel="stylesheet" type="text/css" href="assignment1.css">
</head>
<body>
<h1>This is a table</h1>
<table>
	<tr>
		<th>Roll Num</th>
		<th>Name</th>
		<th>Address</th>
	</tr>

	<tr>
		<td>29</td>
		<td>Safal</td>
		<td>Pokhara</td>
	</tr>

	<tr>
		<td>40</td>
		<td>sid</td>
		<td>kanchanpur</td>
	</tr>

	<tr>
		<td>41</td>
		<td>sujit</td>
		<td>dolpa</td>
	</tr>
</table>

<h1>Things you need to make tea shown using ordered list. </h1>
	<ol>
		<li>Tealeaves</li>
		<li>Sugar</li>
		<li>Milk</li>
		<li>Water</li>
	</ol>

<h2>Counting started from 10 instead of 1</h2>
	<ol start="10">
		<li>Tealeaves</li>
		<li>Sugar</li>
		<li>Milk</li>
	</ol>

<h1>Things you need to make tea shown using un-ordered list. </h1>
	<ul>
		<li>Tealeaves</li>
		<li>Sugar</li>
		<li>Milk</li>
		<li>Water</li>
	</ul>

<h2>List style changed from circle to square</h2>
	<ul class="square">
		<li>Tealeaves</li>
		<li>Sugar</li>
		<li>Milk</li>
		<li>Water</li>
	</ul>

</body>
</html>




