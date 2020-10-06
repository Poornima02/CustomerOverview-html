# CustomerOverview
<!DOCTYPE html>
<html>
<head>
<meta charset="ISO-8859-1">
<title>Customer Overview</title>
<style>
table, th, td {
	border: 1px solid white;
	border-collapse: collapse;
}

h2 {
	text-align: center;
}

#delete-button {
	position: fixed;
	bottom: 30px;
	left: 0px;
}

#fixed-button {
	position: fixed;
	bottom: 30px;
	right: 0px;
	}
.center {
  text-align: center;
}
.pagination a {
  color: white;
  float: center;
  padding: 8px 16px;
  text-decoration: none;
}
</style>
</head>
<body style="background: black; color: blanchedalmond;">
	<div class="top-nav"
		style="padding-topdown: 4px; background-color: #e9e9e9; color: black">
		<h2>Customer Overview</h2>
	</div>
	</br>
	<div style="float: right;">
		<label for="search">Search by</label> <select id="search"
			name="search">
			<option>Cust Name</option>
		</select> <input type="text" id="searchbytext" name="searchbytext"
			value="Search text here.."> </br> </br>
	</div>

	<table style="width: 100%;">
		<tr
			style="padding: 1px; background-color: blanchedalmond; color: black;">
			<th><input type="checkbox"></th>
			<th>Cust Code</th>
			<th>Customer Name</th>
			<th>Address</th>
			<th>City</th>
			<th>Country</th>
			<th>Email</th>
			<th>Status</th>
			<th>Contact</th>
			<th>Payment Terms</th>
			<th>Credit Limit</th>
			<th>Created By</th>
			<th>Created Dt</th>
		</tr>
		<tr>
			<td><input type="checkbox"></td>
			<td>A0304</td>
			<td>Anglo-Eastern Ship Management Ltd.</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td>Active</td>
			<td></td>
			<td>0</td>
			<td>0.00</td>
			<td>Admin</td>
			<td>23/08/2020</td>
		</tr>
		<tr>
			<td><input type="checkbox" value="selected"></td>
			<td>A1001</td>
			<td>AL AREEN INT L.GRP</td>
			<td>P.O BOX 55050</td>
			<td>DUBAI</td>
			<td>UNITED ARAB EMIRATES</td>
			<td></td>
			<td>Active</td>
			<td></td>
			<td>0</td>
			<td>0.00</td>
			<td>Admin</td>
			<td></td>
		</tr>
		<tr>
			<td><input type="checkbox" value="selected"></td>
			<td>A1002</td>
			<td>AHAMED SHIPPING,JADAF</td>
			<td>rertr</td>
			<td>DUBAI</td>
			<td>UAE</td>
			<td></td>
			<td>Active</td>
			<td></td>
			<td>5</td>
			<td>52.00</td>
			<td>MANGAL</td>
			<td></td>
		</tr>
		<tr>
			<td><input type="checkbox" value="selected"></td>
			<td>A1003</td>
			<td>AHAMED MARINE MAINTANANCE</td>
			<td>P.O BOX 8618</td>
			<td>DUBAI</td>
			<td>UAE</td>
			<td></td>
			<td>Active</td>
			<td></td>
			<td>5</td>
			<td>50000.00</td>
			<td>Admin</td>
			<td></td>
		</tr>
		<tr>
			<td><input type="checkbox" value="selected"></td>
			<td>A1004</td>
			<td>ALPHA SHIP MANAGERS PTE LTD.,</td>
			<td>33,UBI AVENUE 3,</td>
			<td></td>
			<td>SINGAPORE</td>
			<td>admin@alphaship.ae</td>
			<td>Active</td>
			<td></td>
			<td>0</td>
			<td>0.00</td>
			<td>Admin</td>
			<td>21/04/2010</td>
		</tr>
		<tr>
			<td><input type="checkbox" value="selected"></td>
			<td>A1005</td>
			<td>ABDULLA BIN HAMID TRADING</td>
			<td>P.O BOX 30495</td>
			<td>DUBAI</td>
			<td>UAE</td>
			<td>riazs@eim.ae</td>
			<td>Active</td>
			<td></td>
			<td>0</td>
			<td>0.00</td>
			<td>Mangal</td>
			<td></td>
		</tr>
		<tr>
			<td><input type="checkbox" value="selected"></td>
			<td>A1006</td>
			<td>ACELINE SHIPMANAGEMENT PTE LTD</td>
			<td>101 CECIL STREET #09-03/05</td>
			<td></td>
			<td>SINGAPORE</td>
			<td>aceline@aceline</td>
			<td>Active</td>
			<td></td>
			<td>0</td>
			<td>0.00</td>
			<td>Admin</td>
			<td></td>
		</tr>
		<tr>
			<td><input type="checkbox" value="selected"></td>
			<td>A1007</td>
			<td>ADAM SHIP REPAIRS,DUBAI</td>
			<td>P.O BOX 6849</td>
			<td>DUBAI</td>
			<td>UAE</td>
			<td></td>
			<td>Active</td>
			<td></td>
			<td>0</td>
			<td>0.00</td>
			<td>Admin</td>
			<td></td>
		</tr>
		<tr>
			<td><input type="checkbox" value="selected"></td>
			<td>A1008</td>
			<td>ALABDEEN MARINE CO.LLC</td>
			<td>P.O BOX 21513</td>
			<td>SHARJAH</td>
			<td>UAE</td>
			<td></td>
			<td>Active</td>
			<td></td>
			<td>0</td>
			<td>0.00</td>
			<td>Admin</td>
			<td></td>
		</tr>
		<tr>
			<td><input type="checkbox" value="selected"></td>
			<td>A1009</td>
			<td>ARESCO TRADING EST.</td>
			<td>P.O BOX 2,DUBAI</td>
			<td>DUBAI</td>
			<td>UAE</td>
			<td></td>
			<td>Active</td>
			<td></td>
			<td>0</td>
			<td>0.00</td>
			<td>Admin</td>
			<td>21/04/2020</td>
		</tr>
		<tr>
			<td><input type="checkbox" value="selected"></td>
			<td>A1010</td>
			<td>A.M.TRADING CO.(L.L.C.),DUBAI</td>
			<td>DUBAI</td>
			<td>DUBAI</td>
			<td>United Arab Emirates</td>
			<td></td>
			<td>Active</td>
			<td></td>
			<td>10</td>
			<td>3000</td>
			<td>Mangal</td>
			<td></td>
		</tr>
		<tr>
			<td><input type="checkbox" value="selected"></td>
			<td>A1011</td>
			<td>DUBAI</td>
			<td>DUBAI</td>
			<td>UAE</td>
			<td></td>
			<td></td>
			<td>Active</td>
			<td></td>
			<td>10</td>
			<td>3000.00</td>
			<td>MANGAL</td>
			<td></td>
		</tr>
	</table></br></br>
	<div id="delete-button">
		<button type="button">Delete</button>
	</div>
	<div class="center">
	<div class="pagination">
  <a href="#">&laquo;</a>
  <a href="#">1</a>
  <a href="#">2</a>
  <a href="#">3</a>
  <a href="#">4</a>
  <a href="#">5</a>
  <a href="#">6</a>
  <a href="#">7</a>
  <a href="#">8</a>
  <a href="#">9</a>
  <a href="#">10</a>
  <a href="#">11</a>
  <a href="#">&raquo;</a>
</div>
</div>
	<div id="fixed-button">
		<button type="button">Generic validation</button>
		<button type="button">Edit</button>
		<button type="button">ADD</button>
	</div>
</body>
</html>
